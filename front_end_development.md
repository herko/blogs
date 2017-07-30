# Front-End development
Porovnaniu svetov Front-End a Back-End vývoja sme sa venovali pred pár mesiacmi. Dnes  sa budeme hrabať v nástrojoch Front-End programátorov - čo všetko musíš zmáknuť, ak sa ním chceš stať (okrem našich kurzov).

V tomto texte nebudeme polemizovať, či je lepší _React_, _Angular_ alebo _Vue.js_. Či treba používať _SASS_ alebo _LESS_, alebo.. ..či je lepší Mac, alebo PC. Prečítaš si o najpoužívanejších front-end technológiách, skúsime Ťa nasmerovať ako s front-endom začať a tiež (ak to myslíš naozaj vážne) kam sa obrátiť s otázkami a koho sledovať na sociálnych sieťach, aby ti nič z Front-Endu neušlo. Pome!

##Predný koniec webu - technológie

Stačí otvoriť niektorú webovú (alebo dnes už aj desktopovú, ajPadovú, ajFonovú, aj androidovú) appku a pozeráme sa na prácu Front-End vývojárov. To oni nakódili tie buttony a textové polia, s citom premysleli  efektné animácie, menu a rozhýbali statický dizajn svojho kamaráta - grafika.

V našom ***webovom svete*** pracujú Front-End vývojári primárne s _HTML_, _CSS_ a _JavaScript_-om. Pre tieto technológie však existuje milión nástrojov a frameworkov, ktoré nám prácu uľahčujú, sme vďaka nim produktívnejší a dokážeme ľahšie tvoriť zložitejšie aplikácie. K takýmto - pokročilejším - nástrojom sa však dostaneš neskôr. Začať s React-om alebo AngularJS ako svojou prvou skúsenosťou s front-endom by bol asi masochizmus.

##Level 1: Kde začať?
Niektorí z nás statické HTML stránky s využitím CSS štýlov zvládli už na strednej (alebo aj základnej) škole. Neskutočná nuda a ani sme netušili, že to môže byť pre nás neskôr užitočné. Niečo podobné, ako keď vás rodičia nútia chodiť do hudobnej školy a vedomosti zúžitkujete až o 10 rokov neskôr, keď s kamošmi vymyslíte kapelu.

![Level 1: Základy front-end programovania](http://i.imgur.com/tMZWJew.png)

Všetky weby, webové aplikácie však využívajú HTML a CSS naplno a preto je potrebné ich zvládnuť úplne na začiatku – spoznať svoje možnosti. Aby sme si mohli povedať, že sme zvládli základy HTML, CSS a JavaScript-u mali by sme poznať funkcie ***elementov*** a ***atribútov*** z prvého grafu. Tiež by sme mali bez problémov vedieť používať základné ***CSS pravidlá*** a ***jednotky***. No a mali by sme vedieť, na čo slúži ***jQuery*** a ako nám môže pomôcť. Všetky informácie a oveľa viac nájdeš v Yablkovom kurze: _Webrebel 1: HTML, CSS & Javascript_.

##Level 2: Ako pokračovať?
Určite postupom času prejdeš z jednoduchých webstránok na zložitejšie weby. Tvoj CSS súbor bude mať 1000 riadkov a každá ďalšia zmena Ti zaberie 3 minúty strachu, 1 minútu roboty a 25 minút testovania a fixovania, ak sa niečo pokazilo. Je čas na lepšiu organizáciu svojich CSS štýlov.

![Level 2: CSS nástroje a responzívny dizajn](http://i.imgur.com/v2YAW3m.png)

###CSS
Použi SASS - parádny preprocessor CSS štýlov, ktorý Ti umožní organizovať štýly prehľadne do priečinkov/súborov. Tiež môžeš zadefinovať premenné, ktoré obsahujú definície farieb, ktoré často používaš, alebo okraje - aby vyzerali všade rovnako. Ak ich potrebuješ zmeniť na viacerých miestach, prepíšeš hodnotu jednej premennej a máš to vyriešené. SASS vie pracovať aj s jednoduchými funkciami. Často používanými sú napr. `lighten()` a `darken()`, ktoré dokážu danú farbu zosvetliť alebo stmaviť. SASS má tých funkcií a možností samozrejme ďaleko viac.

Ďalšími alternatívami k SASS môže byť LESS, Stylus, PostCSS a ďalšie. My v Learn2Code sme si obľúbili SASS.

###Responzívny dizajn
Responzívny dizajn rieši problém so zobrazovaním Tvojho webu na rôznych zariadeniach. Pre front-end programátora je neodmysliteľnou súčasťou jeho skills. Mobilných zariadení je viac ako obyvateľov na svete - musíme optimalizovať aj pre malé obrazovky.

Samotné HTML a CSS3 má v sebe nástroje, ktoré nám pri takejto optimalizácii môžu pomôcť. Napríklad veľmi dôležitý HTML meta tag je `viewport`, ktorý prispôsobí veľkosť písma pre malé obrazovky tak, aby nebolo príliž malé:
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
Pomocou CSS tiež dokážeme ošetriť responzivitu tak, že na šírku elementov budeme používať percentuálne hodnoty a pravidlo `box-sizing: border-box;`. Takto môžeme zadefinovať vlastný grid, kde tieto pravidlá použijeme.

CSS3 nám veľmi pomáha pri responzívnom dizajne s `@media` query. Pomocou `@media` dokážeme oddeliť CSS, ktoré bude platiť napríklad pri rozlíšeniach menších ako 1000px od pravidiel, ktoré budú platiť pre rozlíšenia vyššie ako 1000px. Výborná vec. Responzívnemu dizajnu venoval Yablko tiež kopec videí v kurze Webrebel 1.

###Front-end Framework
Šikovníkov z Twitteru napadlo, že by bolo fajn mať po ruke sadu _komponentov_, ktoré veľmi často používajú vo svojich projektoch. Takýmito komponentami sú napríklad tlačidlá, rôzne typy menu, textové polia s validáciami alebo rôzne nadpisy. Dôležitá bola tiež responzivita. Aby nemuseli začínať vždy od nuly, vytvorili ***Bootstrap*** - framework, ktorý si okamžite získal vývojárov po celom svete. Bootstrap je obrovský urýchľovač času a čas sú predsa peniaze.

Ak si Bootstrap obľúbiš a spoznáš ho poriadne, začneš experimentovať s upravovaním jeho vzhľadu a pridávaním nových funkcií napríklad cez JavaScript. Na internete nájdeš kopec pluginov, ktoré rozširujú jeho možnosti.

Alternatívami k Bootstrapu môžu byť: Foundation framework, Materialize CSS, Semantic UI a rôzne iné.

##Level 3: JavaScript
Dostávame sa do posledného levelu front-end programátora, tak vysúkajme rukávy a poďme na to :) JavaScript je jedným z najpopulárnejších jazykov.

![Level 3: JavaScript nástroje, knižnice a frameworky](http://i.imgur.com/gES0Mvz.png)

Príchodom _Single Page Applications_ (SPA) sa jeho popularita _zmnohonásobila_. SPA rapidne zlepšili rýchlosť webových aplikácií. Podstatou SPA je, že celá stránka sa načíta len raz - na začiatku. Každá ďalšia zmena sa deje na pozadí a zmení sa len časť stránky s novým obsahom.

Najlepšími príkladmi single-page aplikácií sú Facebook, YouTube, Twitter a mnohé iné populárne weby. Ani si nevieme predstaviť to množstvo JavaScript-u, ktoré tieto aplikácie obsahujú, pretože podstatná časť celej aplikácie je naprogramovaná práve v JavaScript-e.

Veľa .js súborov na jednom webe môže spôsobovať nemalé problémy. Najmä, ak sú jednotlivé súbory na sebe závislé. Veľmi jednoduchý príklad: ak napíšeme vlastný JS plugin na zobrazenie foto galérie, ktorý je závislý na jQuery. Keď prehliadač stiahne a spustí náš plugin, už musí mať k dispozícii knižnicu jQuery. Je úlohou front-end programátora, aby takéto problémy vyriešil.

JavaScript našťastie obsahuje obrovské množstvo nástrojov, ktoré nám pomáhajú riešiť podobné problémy. Tu sú niektoré situácie a ich riešenia:

- ***Správa závislostí*** – ak je knižnica závislá na ďalších knižniciach, pomôžu nám `npm` alebo `yarn`
- ***Automatizácia činností*** – veľkou pomocou je napríklad automatický refresh prehliadača pri každej zmene kódu. Takéto a podobné _tasky_ môžeme riešiť cez `gulp`, `grunt` alebo `npm`
- ***Správa modulov*** - nainštalované závislosti je potrebné poskytnúť prehliadaču vo forme výsledného .js súboru. Tu nám môžu pomôcť `webpack`, `rollup`, `RequireJS`, `browserify`
- ***Automatizované testovanie*** - aby sme pri každej zmene nemuseli celú aplikáciu testovať ručne, pomôžu nám `jest`, `mocha` alebo `jasmine`
- ***Syntax*** - aby sme neprodukovali JS špagety kód, vznikajú nové štandardy, ktoré sprehľadňujú syntax JavaScriptu - `ES5`, `ES6` alebo `ES7`. `Babel` pomôže prehliadaču túto novú syntax pochopiť.

###JavaScript frameworky a knižnice
Podobne ako nám Bootstrap pomohol s responzivitou a niektorými často používanými komponentami, existujú aj JavaScript frameworky, ktoré dopĺňajú svet front-end programátora a celý vývoj komplikovanej SPA urýchľujú. Opísať každý framework nie je úlohou tohoto článku, ak však niektorý z nich preferuješ, napíš nám do komentárov ktorý a prečo. Tu sú najpoužívanejšie:

- ***React*** - Facebook vytvoril react ako riešenie pre svoje komplikované používateľske prostredie. Hlavnou ideou je vytvorenie komponentov, ktoré sa dajú použiť na viacerých miestach v aplikácii. Ak užívateľ vykoná nejakú akciu a zmení sa obsah stránky - prehliadač prekreslí len konkrétny komponent.
- ***Vue.JS*** - Alternatívnou knižnicou k Reactu je Vue.JS, ktorá sa teší čoraz väčšej popularite. Výhodou je prehľadnejší a ľahší syntax, kde sa nemieša HTML kód s JavaScriptom - čo niektorým vývojárom nevyhovovalo
- ***AngularJS*** - Vytvorený firmou Google je na rozdiel od React a VueJS plnohodnotným frameworkom - obsahuje aj nástroje na komunikáciu s databázou.

Ďalšie alternatívy k najpoužívanejším frameworkom/knižniciam: EmberJS, Preact, Inferno a mnohé iné.

##Level 4:
Áno, existuje aj level 4. Sú to prídavné vedomosti naskillovaného front-end programátora. Napríklad bezpečnosť - prevencia pred CSRF, XSS, DNS pinning alebo clickjacking útokmi. Tiež poznanie psychológie používateľa je obrovskou výhodou - priorizovať použiteľnosť a prístupnosť aplikácie pred odvážnym dizajnom. Marketing, SEO, ... a mohli by sme ísť ďalej.

Dôležité je nikdy sa neprestať vzdelávať, získať čo najväčší rozhľad v technológiách a v neposlednom rade nepodľahnúť popularite niektorého z nástrojov, ale zvoliť nástroj tak, aby splnil svoj účel.
