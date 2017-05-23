#Front-End vs Back-End

Vo februári 1997 bolo na sieti Internet prístupných **milión webov**. To bolo pred dvadsiatimi rokmi *(tiež som si práve uvedomil aký som starý)*. Dnes by sme ich rátali v stovkách miliónov. Od tej doby prešiel vývoj webov neskutočnými zmenami. Z jednoduchých prezenčných stránok nakreslených v skicári a oživených HTML, CSS a JavaScript kódom sa stali zložité CMS, LMS, CRM a WTF systémy postavené  na niektorých z desiatok back-end technológií. Dáta môžeme ukladať do SQL alebo NoSQL databázy a súbory už nenahrávame jednoducho na server cez FTP, ale používame zložité build systémy, ktoré náš kód najprv otestujú a až potom posunú do produkcie. Aplikácie otvárame na tabletoch, smartfónoch, laptopoch, chladničkách, … – preto je dobré ak majú responzívny dizajn. Aby tej terminológie nebolo málo.

Jednému programátorovi to množstvo technológií, s ktorými sa denne stretáva, začína prerastať cez hlavu. Preto sa web vývojári začínajú špecializovať. Dve najvýraznejšie skupiny sú front-end a back-end vývojári. Ďalší by boli *full-stack* vývojári, *DevOps*.. Tento text Ti pomôže pochopiť, čo je úlohou front-end a back-end vývojára a s akými technológiami najčastejšie tieto dve skupiny vývojárov pracujú.

##Polopatisticky
Ak chce programátor postaviť dom, najprv zavolá back-end tím: murára a tesára. Back-end murár mu vybetónuje základy, postaví steny, vymuruje otvory na dvere a okná. Neskôr mu pomôže back-end tesár. Ten postaví strechu. V takomto dome by sa však bývalo ťažko - preto príde front-end tím: maliar a bytový dizajnér. Front-end tím zútulní tehlové steny a zariadi dom – aby všetko vyzeralo parádne, spolu ladilo a hlavne ***plnilo svoj účel***.

Ak to premeníme na web-development svet, tak **back-end** je základom pre našu aplikáciu. Je to skrytá časť aplikácie (používateľ ju nevidí), ktorá úzko spolupracuje so serverom, databázou. Úlohou back-end programátora je tvoriť kód, ktorý je efektívny, zbytočne nezaťažuje server, databázu - napr. aby používateľ nečakal príliž dlho na potrebné dáta. Už dve sekundy sú nekonečno. **Front-end** je zase tá časť aplikácie, ktorú vidí a pracuje s ňou používateľ. Často je označovaná pojmom *User Interface* (UI). Úlohou front-end programátora je, aby sa aplikácia zobrazovala každému používateľovi správne a aby mu čo najviac uľahčila prácu s aplikáciou. Front-end programátor vie z tvojho jednoduchého kliku na tlačidlo vyrobiť parádnu animáciu, ktorá Ti napr. odkryje ďalšie možnosti práce s aplikáciou.

##Jazyky, nástroje 
Vývojári pracujú s mnnožstvom technológií, ktoré sa niekedy menia od projektu k projektu.

Diagramy zobrazujú len najpoužívanejšie technológie. Dôležité je rozumieť, že nie všetky technológie z diagramu musí vývojár ovládať - je však dobré o väčšine z nich aspoň niečo vedieť - pri veľkých projektoch môže mať niektorá technológia výhody, iná nevýhody. To je ale na dlhú debatu a mal by to riešiť vývojársky tím interne, najlepšie face-to-face. V žiadnom prípade neodporúčam pýtať sa na sociálnych sieťach, či je lepší React, alebo Vue JS. Nikam to nevedie :)

![img](http://i.imgur.com/GKCU5wB.png)
![img](http://i.imgur.com/VaxZtwe.png)

Samostatnú kapitolu by mohli tvoriť webové frameworky ako Ruby on Rails Laravel alebo ExpressJS. Tie nám uľahčujú postaviť celú aplikáciu - front-end aj back-end časť. 

##Technológie v Learn2Code

Každá webová aplikácia má iné nároky a výber technológií často súvisí aj so skúsenosťami a preferenciami tímu riadeného skúseným CTO. Takýto koktejl technológií sme namiešali v Learn2Code pre naše projekty:

Pracujeme s frameworkom **Ruby on Rails**. S front-end časťou aplikácie nám v Rails pomáha **SASS** preprocesor, vďaka ktorému máme CSS štýly organizované v komponentoch a veľmi jednoducho sa v nich orientuje. Na niektoré časti aplikácie learn2code.sk sme nasadili **React** - prezeranie videí, fórum. Začíname ale experimentovať aj s **Vue.js**. React a všetky jeho závislosti spravuje **WebPack**, ktorý nakoniec vypľuje jeden veľký `bundle.js` súbor.

Keďže používame Rails, back-end je písaný v skriptovacom jazyku **Ruby**. Na testovanie používame **RSpec**, **Mocha**. Aplikácie nám bežia na serveroch **Heroku**. Používame relačnú databázu **PostgreSQL**, kde máme uložené všetky dáta. Obrázky skladujeme na **Amazon S3**. Video obsah je uložený na serveroch **Vimeo**, s ktorými komunikuje React prostredníctvom **REST API**. Kód všetkých projektov skladujeme v privátnych repozitároch na **GitHub**. Na nekvalitný kód nás neustále upozorňuje **RuboCop**. Nasadenie nových funkcií do hlavnej aplikácie je riadené s pomocou **Continuous Integration** - CodeShip.com.

Niektoré z technológií možno poznáš. Niektoré z nich Ťa dokonca vieme naučiť aj u nás v Learn2Code. 