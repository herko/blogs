# Ako sa nepredávkovať návodmi

[img]: ./tutorials-never-ending-story/intro.jpg

Tak. Rozhodol si sa naučiť programovať (na learn2code si správne!). Je jedno, či chceš byť Web Developer ([FrontEnd](https://www.learn2code.sk/kurzy/webrebel-1-html-css-javascript), [BackEnd](https://www.learn2code.sk/kurzy/zaklady-programovania-a-oop)), chceš sa vzdelávať v konkrétnom jazyku ([PHP](https://www.learn2code.sk/kurzy/webrebel-2-php), [JavaScript](https://www.learn2code.sk/kurzy/online-kurz-javascript-es6), [Java](https://www.learn2code.sk/kurzy/java-pre-zaciatocnikov), [C#](https://www.learn2code.sk/kurzy/uvod-do-programovania-v-jazyku-csharp)), alebo si sa ešte nerozhodol, a chceš sa len [naučiť programovať](https://www.learn2code.sk/kurzy/online/programovanie).

Aj keď kniha má svoje čaro, môžeš ju čítať aj elektronicky, s videom to však ide najrýchlejšie. Tvoji rodičia si pri pohľade na Teba možno myslia, že mrháš časom, Ty však vieš, že investuješ do seba. Správne!

Nad kurzami môžeš stráviť dlhé hodiny. Niektoré z nich majú aj viac modulov. Každý má však aj svoj koniec. Zámer autora kurzu predsa nebol získať sledovanosť pre jeho videá, ale chcel ťa niečo naučiť.

Možno si sa už ocitol v tom začarovanom kruhu, kedy po ukončení jedného kurzu hľadáš hneď ďalší, ktorý ťa posunie na vyššiu úroveň. A potom ďalší a ďalší.. Na vyššiu úroveň však už tutoriály a prepisovanie kódu z obrazovky nestačí. Ani jednoduché zadania lektorov z videokurzov nie sú postačujúce. Na vyššiu úroveň treba prax, treba tvoriť, pracovať na projektoch, *vytvárať portfólio*.

## Portfólio programátora

[img]: ./tutorials-never-ending-story/portfolio.jpg

V zaujímavom CV nemusí byť veľa projektov. Ten, kto ho bude čítať vie, či Tvoje portfólio obsahuje zaujímavé projekty, kde si sa stretol s nejakými výzvami. Pri absolvovaní kurzov si možno vytvoril jednoduchú aplikáciu na správu poznámok v Markdown formáte. Alebo sociálnu sieť, Twitter podľa tvojej chuti. 

Všetko sú to však projekty, ktoré každý pozná a vie, že nájdeš kopec zdrojov ako takúto aplikáciu napísať a  tvorba takéhoto projektu bola len akýmsi light fitness pre tvoju hlavu.

Najdôležitejšie na tom však je, že tie projekty nie sú tvoje. Tvoj projekt predsa začína prázdnym priečinkom, možno vytvorením `index.html` súboru, pokračuje nekonečným google hľadaním riešení tvojich front-end alebo back-end problémov, implementáciami tvojich vylepšení, tvojich riešení, testov a refactoringu tvojho kódu. V repozitári vidieť, ako dlho si na projekte pracoval a ako sa projekt vyvíjal.

## Na čom teda začať makať?

[img]: ./tutorials-never-ending-story/coding.jpg

Každý programátor si dobré nápady na aplikácie chráni. Návšteva programátorského fóra s otázkou typu "Nemáte náhodou nápad na nejaký zaujímavý projekt?" bude skôr cieľom posmechu ako zdrojom nápadov pre tvoje projekty. Nezúfaj, mám pre Teba niekoľko rád ako svoj mozog nenechať oddychovať príliž dlho.

Projekty som nevymyslel sám, väčšinou sú to projekty inšpirované existujúcimi aplikáciami, alebo všeobecne známe zadania. Pridal som k nim však aj odkazy na dokumentáciu, aby si netrávil čas hľadaním kde a ako začať.

Niektoré projekty možno nekorenšpondujú s tvojou ideovou predstavou a môžu byť menej zaujímavé, keď sa však rozhodneš na ňom pracovať získaš hneď niekoľko výhod:

- nestojíš na jednom mieste, ale tvoríš, učíš sa, rastieš
- stretávaš sa s problémami (ver mi, bude ich čím ďalej tým menej), na ktoré hľadáš riešenia
- objavuješ nové spôsoby riešenia problémov, tvoje staré riešenia už nestačia, alebo sú neefektívne

### Level 1 - jednoduché projekty
#### Lunch picker

- Takáto appka už existuje, ale urob vlastnú verziu. Podstata je, že vždy keď sa nevieš rozhodnúť, kam s kamošmi pôjdeš napivo, nechaj to na výpočtovú silu.
- **Zadanie môže mať dve úrovne:** Prvá úroveň je, že databázu miest na "zábavu" si vytvoríš sám a appka náhodne vyberie niektorú z nich. Druhá úroveň by bola, ak použiješ niektoré existujúce API (Google Reviews), ktoré ťa vie lokalizovať a databázu získaš odtiaľ.

#### Collection tracker

- Publikuj svoju zbierku "čohokoľvek" vo forme katalógu. Premysli štruktúru kažej položky, skús ich kategorizovať, implementovať vyhľadávanie. Jednoduchý projektík o niečom, čo ťa skutočne baví.
- **Zadanie môže mať dve úrovne:** Prvá vo forme jednoduchej MVC aplikácie s Bootstrapom, napísaná v Laraveli alebo RubyOnRails. Väčší skiller si môže trúfnuť navrhnúť API a dizajn implementovať v niektorej JS knižnici - VueJS, React.

#### Spoiler blocker pre clanky

- Poznáš to - píšeš recenziu niektorého obľúbeného filmu alebo knihy a nechceš čitateľa tvojho textu nepríjemne prekvapiť vyzradením deja, alebo kľúčovej informácie. Podobne ako fungujú "Zobraziť viac" odkazy, môžeš takúto informáciu ukryť aj pod "Spoiler alert" odkaz. Spoiler v texte môžeš oddeliť pomocou data atribútu pre tvoj `<p>` element: `<p data-spoiler="true">Spoiler text...</p>`.
- **Zadanie môže mať dve úrovne:** Prvá vo forme jednoduchého inline javascriptu, ktorý spustíš niekde na konci svojho textu pomocou `<script></script>` tagu. Druhá úroveň vo forme malej knižnice s využitím [Module Pattern](https://toddmotto.com/mastering-the-module-pattern/), ktorú môže použiť vo svojom Wordpresse ktokoľvek.

#### Tax forecaster

- Aj keď politici sa nás snažia presvedčiť, že si zaslúžime istoty, jedinou istotou v živote sú dane. Navrhni nejakú jednoduchú appku, ktorá bude zbierať sumy tvojich freelance faktúr a na základe vzorca, ktorý zistíš online (a naučíš sa pritom aj prečo platíš toľko na daniach).
- **Zadanie môže mať dve úrovne:** Prvá úroveň je samotný jednoduchý výpočet - zadáš číslo a dostaneš hodnotu, ktorú zaplatíš štátu. Druhou úrovňou môže byť databáza s históriou tvojich FA a implementácia grafov, kde môžeš s pomocou knižnice [D3](https://d3js.org/) vykresliť pekné reporty, koľko si zarobil a ako sa tvoj zárobok vyvíjal. Ak je samotná D3 knižnica príliž komplexná, môžeš sa skúsiť pohrabať v [knižniciach](https://github.com/wbkd/awesome-d3#charts), ktoré používanie D3js zjednodušujú.

#### FlashCard generator

- Ak si v štádiu učenia sa (čo by si mal byť neustále) a snažíš sa zapamätať si niektoré dôležité informácie, koncepty alebo čokoľvek, osvedčená technika pamätania si vecí sú FlashCards. Navrhni appku, ktorá si z databázy, alebo JSON objektu vyberie pole dvojíc, kde prvým prvkom dvojice bude nejaký stručný popis a druhým prvkom bude informácia, ktorú si máš zapamätať. [Tu](https://thoughtbot.com/upcase/decks/1/flashcards/1) je inšpirácia.
- **Zadanie môže mať dve úrovne:** Prvou je implementácia, akú použili v [ThoughtBot](https://thoughtbot.com/upcase/decks/1/flashcards/1) - teda informácia, ktorú sa snažíš naučiť sa len objaví pod heslom. Druhou úrovňou môže byť využitie CSS na zaujímavú animáciu, aby to vizuálne vypadalo ako ozajstné "otočenie karty".

### Level 2 - stredne náročné projekty
#### Bring your umbrella

- Ak nestíhaš ráno sledovať počasie, automatizuj to. Napíš appku (najviac sa asi hodí mobilná appka, ale užitočná môže byť aj webová aplikácia), ktorá ťa lokalizuje a s využitím [API](https://openweathermap.org/api) ti pripomenie, aby si si nezabudol zobrať zo sebou dáždnik - v okolí tvojej lokality bude totiž pršať. Webová appka ti môže poslať e-mail notifikáciu.
- **Zadanie môže mať dve úrovne:** Prvou môže byť aplikácia bez grafického rozhrania. Druhou môže byť plnohodnotná weather appka prispôsobená tvojim potrebám a grafickým nárokom. 

#### Music suggestion app

- Spotify má tiež svoje [API](https://developer.spotify.com/documentation/web-api/). To môžeš použiť na vytvorenie zoznamu skladieb, ktorý budeš tvoriť na základe počúvaných skladieb, ich žánru a iných dostupných dát. [Takto](https://developer.spotify.com/documentation/web-api/reference/player/get-the-users-currently-playing-track/) získaš dáta o skladbe, ktorú používateľ práve počúva. [Tu](https://developer.spotify.com/documentation/web-api/reference/playlists/) je dokumentácia, ako pracovať s playlistom.

#### Expense tracker

- Vo forme mobilnej appky alebo webovej aplikácie môžeš vytvoriť aj svoj tracker príjmov a výdavkov. Ich kategorizácia a kreslenie grafov by malo byť samozrejmosťou. Ak sa ti podarí vyriešiť problém manuálneho zadávania bločkov, daj mi vedieť - do takej aplikácie rád zainvestujem. V [Datamolino](https://www.datamolino.sk/index/) už vedia ako na to.
- Najväčšou challenge pri tomto projekte je asi UI/UX - aplikácia by sa mohla učiť moje zvyky a inteligentne mi podsúvať dáta (kategorizáciu, tagy) podľa histórie mojich nákupov. Na základe týchto tagov a kategórií mi oznámiť, kde by som mohol nabudúce ušetriť. 

#### Downtime tracker

- Ak máš obľúbený web, alebo plánuješ niekoľko svojich projektov, môžeš testovať, či náhodou tvoje aplikácie nemajú nejaký problém. Jednoduchým scriptom pristúpiš na URL svojej aplikácie a ak skript nevráti `HTTP Response 200` , tak ťa tracker notifikuje emailom, že sa niečo deje.
- **Zadanie môže mať dve úrovne:** Prvou úrovňou môže byť notifikácia emailom. Druhou úrovňou môže byť notifikácia pomocou SMS brány (Twilio), alebo web hook do tvojho Slacku - ak používaš slack.

### Level 3 - náročnejšie projekty
#### Slack bot

- Ak poznáš Slack a inšpiruje ťa automatizácia, programovanie botov je teraz in. Niektoré vývojárske teamy denne absolvujú "standup" - odpovedia na jednoduché otázky týkajúce sa aktuálneho projektu/zadania (na čom pracujú, v akom sú štádiu, či sa na niečom zdržali a podobne). S pomocou [Slack API](https://api.slack.com/docs/messages) môžeš vytvoriť jednoduchého bota, ktorý kontaktuje vývojárov z tvojho teamu a opýta sa ich zopár otázok. Ich odpovede môžeš zozbierať a vyhodnotiť v jednej správe, ktorú odošleš do #dev kanála. 

#### Microlearning app

- Denne by si mal venovať nejaký čas svojmu vzdelávaniu - aby si ako programátor rástol. Ak sa účíš napríklad React, alebo VueJS - môžeš skúsiť použiť (alebo napísať vlastný) web scrapper a získať tak jednotlivé sekcie dokumentácie. Denne ti tvoja microlearning aplikácia môže poslať jednu sekciu/stránku z tejto dokumentácie e-mailom na štúdium.

#### Web scraper

- Nájdi svoj obľúbený e-shop a skús vytvoriť vlastnú databázu jeho produktov, kategórií spolu s obrázkami. Web scraping je zaujímavou a nie jednoduchou témou pre programátorov, pretože ku každému webu, ktorý chceme scrapovať musíme pristupovať individuálne.
- Hint: Pred tým, ako sa pustíš do scrapovania niektorej domény, skontroluj v `robots.txt`, či náhodou doména nemá blokovaných niektorých botov.

#### Quiz Maker

- Ak sa nudíš, môžeš prispieť aj k efektivite nášho školstva. Keď som učil ja, učitelia používali Hot Potatoes ako ich testovaciu platformu. Alebo vytlačené testy s kolonkami. Vstupom do tvojej quiz platformy môže byť JSON, ktorý bude obsahovať vhodne zvolenú štruktúru testovacích otázok, možných odpovedí a označenia správnej odpovede.
- **Zadanie môže mať tri úrovne:** Prvou môže byť vygenerovanie testu z holého `.json` súboru. Druhou môže byť vytvorenie adminstračného rozhrania, kde si testujúci otázky a možné odpovede vykliká vo formulári. Treťou úrovňou môže byť implementácia rôzneho typu testovacej otázky (jedna správna odpoveď, viac správnych odpovedí, dopísanie správnej odpovede, zoradenie do správneho poradia, vytvorenie správnych párov, ...)

#### Browser extension

- Naštuduj si ako pracujú browser pluginy a zvýš svoju produktivitu blogovaním distraktorov. Inšpiráciou ti môže byť [BlockSite](https://blocksite.co/) - výborný extension na blokovanie stránok. 
- Blokovanie stránok však nemusí byť jediný tip na doplnok do prehliadača. Doplnky sú fajn na zvýšenie produktivity, teda rôzne poznámkové doplnky, časovače (pomodoro), vytvorenie snímky z aktuálnej stránky a všeličo možné.

### Programátorské výzvy - algoritmické úlohy

Ak nehľadáš nápad na projekt, ale radšej by si sa zdokonalil v riešení algoritmických úloh, mám tu niečo aj pre Teba:

1. [Advent of code](https://adventofcode.com/)
   - Adventný kalendár programátora (každý rok obsahuje nové zadania). Obsahuje 25 zadaní orientovaných na precvičovanie algoritmického myslenia. Ideálne na raňajšie prebudenie mozgu, niektoré úlohy však môžu zabrať viac času. Súčasťou je aj leaderboard, tam sa ja radšej ale nepozerám.
   - Zadania môžeš riešiť v ktoromkoľvek jazyku
2. [Project Euler](https://projecteuler.net/archives)
   - Podobne ako Advent of Code, aj toto je zbierka zadaní, ktoré sú však už len archívom. To však neznamená, že neobsahuje dostatok zadaní - je ich tam takmer 650. Pri každom zadaní je uvedený aj počet ľudí, ktorí zadanie vyriešili.
   - Zadania môžeš riešiť v ktoromkoľvek jazyku
3. [Daily Coding Problem](https://www.dailycodingproblem.com/)
   - Toto je mailinglist, ktorý ti každý deň pošle jeden programátorský problém, ktorý môžeš rozlúsknuť. Problémy z tejto banky pochádzajú z pracovných pohovorov vo firmách, ako sú Google, AirBnB, Facebook, Apple a rôzne iné. Ich obtiažnosť je preto niekedy dosť vysoká. Ak sa ale pripravuješ na pracovný pohovor, tieto úlohy ti môž pomôcť.
   - Nevýhodou je, že k riešeniam sa dostaneš až ak si ich predplatíš.

