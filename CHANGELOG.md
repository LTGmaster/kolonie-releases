# Wijzigingslog Sigilmark

Alle versies van Sigilmark (Ltgnetwork; tot en met 0.19.1.1 heette het spel Kolonie). De nieuwste versie staat bovenaan.

## Binnenkort — Gepland / Coming soon
- **0.20.1**: vernieuwde UI-stijl. / *Refreshed UI style.*
- **0.21.6**: missiesysteem en campagnemissies 1 en 2. / *Mission system and campaign missions 1 and 2.*
- **0.22**: multiplayer-server. / *Multiplayer server.*
- **0.23**: campagnemissies 3 tot 5. / *Campaign missions 3 to 5.*
- **1.0**: tutorial in het spel. / *In-game tutorial.*

## 0.21.5.2 — Licentieovereenkomst en privacyverklaring (2026-10-29)
- **Licentieovereenkomst in de installatie**: de installatie toont nu na het welkomscherm de licentieovereenkomst (EULA) en privacyverklaring in het Nederlands en het Engels. Pas na het aanvinken van "Ik ga akkoord" kun je verder. De tekst wordt ook als **EULA.txt** in de installatiemap gezet (en bij het verwijderen weer gewist). / *Licence agreement in the installer: after the welcome screen the installer now shows the end-user licence agreement (EULA) and privacy notice in Dutch and English. You can only continue after ticking "I accept". The text is also installed as **EULA.txt** in the installation folder (and removed on uninstall).*
- **Duidelijkere toestemmingsvraag voor het delen van logboeken**: de vraag en de tooltip zeggen nu eerlijk wat er meegaat: geen naam of account, wel technische gegevens (ook je IP-adres, dat de server ziet), met een verwijzing naar EULA.txt. Delen blijft uit tot je zelf toestemming geeft. / *Clearer consent question for sharing logs: the question and tooltip now state honestly what is sent: no name or account, but technical data (including your IP address, seen by the server), with a reference to EULA.txt. Sharing stays off until you consent.*

## 0.21.5.1 — Hotfix pauzemenu (2026-10-29)
- **Pauzemenu breder en netjes uitgelijnd**: het menu is nu ongeveer 600 px breed (smaller als het venster klein is), de keuzelijsten (UI-schaal, taal, grafische kwaliteit, FPS-limiet) staan in één rechterkolom van gelijke breedte, en waarden zoals 80% en 1.0x raken de scrollbalk niet meer. / *Pause menu wider and neatly aligned: the menu is now about 600 px wide (narrower when the window is small), the dropdowns (UI scale, language, graphics quality, FPS limit) sit in one right-hand column of equal width, and values such as 80% and 1.0x no longer touch the scrollbar.*

- **Klik op een grondstoficoon** in de bovenbalk: de camera gaat naar een eigen productiegebouw van die grondstof (bijv. planken → zagerij, water → waterput) en opent het gebouw. Elke volgende klik gaat naar het volgende gebouw en daarna weer naar het eerste. Zonder producent verschijnt "Geen gebouw dat … maakt". / *Click a resource icon in the top bar: the camera goes to one of your own buildings that produce it (e.g. planks → sawmill, water → well) and opens it. Each next click goes to the next building and then back to the first. Without a producer, "No building that makes …" appears.*
- **Wat is er nieuw** haalt nu ook de nieuwste wijzigingslog online op (zonder internet blijft de ingebouwde staan). Is er een nieuwere versie, dan staat bovenaan "Nieuwe versie beschikbaar: X". / *What's new now also fetches the latest changelog online (without internet the built-in one stays). If a newer version exists, "New version available: X" appears at the top.*
## 0.21.5 — Herenhuis en minikasteel (2026-10-29)
- **Stadsrecht** (tak Economie, na Woningbouw; 10 planken + 8 blokken + 1 gereedschap, 90 s) ontgrendelt het **herenhuis**: verbouw een **rijhuis** (6 planken + 4 blokken + 2 steen) tot een deftig bakstenen huis voor **20 kolonisten**, maar alleen met **3 voedselsoorten of bier** (anders 10). Een herenhuis vraagt zelf 1 vat bier en drinkt er 1 per minuut. / *City rights (Economy branch, after Housing; 10 planks + 8 blocks + 1 tool, 90 s) unlocks the **manor house**: upgrade a **terraced house** (6 planks + 4 blocks + 2 stone) to a stately brick house for **20 settlers**, but only with **3 kinds of food or beer** (otherwise 10). A manor house asks for 1 barrel of beer itself and drinks 1 per minute.*
- **Burcht** (na Stadsrecht + Isolatie; 12 blokken + 4 ijzer + 2 gereedschap, 120 s) ontgrendelt het **minikasteel**: verbouw een **herenhuis of stenen huis** (6 ijzer + 12 blokken + 10 steen + 4 gereedschap) tot een kleine burcht met **24 kolonisten** (vol met 2 voedselsoorten) en **4 extra dragers**. Het stookt, net als het stenen huis, maar 0,4x brandstof. **Maximaal 1 per speler.** / *Keep (after City rights + Insulation; 12 blocks + 4 iron + 2 tools, 120 s) unlocks the **mini castle**: upgrade a **manor house or stone house** (6 iron + 12 blocks + 10 stone + 4 tools) to a small keep with **24 settlers** (full with 2 kinds of food) and **4 extra carriers**. Like the stone house it burns only 0.4x fuel. **At most 1 per player.***
- De computerspelers onderzoeken Stadsrecht en Burcht als laatste en slaan ze over zolang de grondstoffen ontbreken (ze blijven er niet op wachten). Ze bouwen hooguit één minikasteel en maken een herenhuis zodra er 3 voedselsoorten of bier zijn. / *Computer players research City rights and Keep last and skip them while resources are missing (they do not wait for them). They build at most one mini castle and make a manor house once they have 3 kinds of food or beer.*

## 0.21.4 — Rijhuis, stenen huis en een zwaardere start (2026-10-29)
- **Woningbouw** (tak Economie, 8 planken + 4 blokken, 60 s) ontgrendelt het **rijhuis**: drie huisjes onder één dak voor **14 kolonisten**, maar alleen met **2 voedselsoorten** (anders 7). / *Housing (Economy branch, 8 planks + 4 blocks, 60 s) unlocks the **terraced house**: three cottages under one roof for **14 settlers**, but only with **2 kinds of food** (otherwise 7).*
- **Isolatie** (tak Productie, 6 planken + 6 blokken, 60 s) ontgrendelt het **stenen huis**: **6 kolonisten**, maar elke kool of elk hout houdt het **2,5 keer zo lang** warm (ongeveer 0,4x brandstof). / *Insulation (Production branch, 6 planks + 6 blocks, 60 s) unlocks the **stone house**: **6 settlers**, but each coal or wood keeps it warm **2.5 times as long** (about 0.4x fuel).*
- Je bouwt ze niet los: klik een afgebouwd woonhuis aan en kies **Verbouw tot …** (rijhuis 4 planken + 2 blokken + 1 hout, stenen huis 4 blokken + 2 steen). Het verbouwen duurt 30 seconden; de bewoners blijven wonen. / *You do not build them separately: click a finished house and choose **Upgrade to …** (terraced house 4 planks + 2 blocks + 1 wood, stone house 4 blocks + 2 stone). Upgrading takes 30 seconds; the residents stay.*
- **Zwaardere start**: een nieuw spel begint met **20 vrije kolonisten** (was 24) en **4 dragers** (was 5). Oude saves houden hun kolonisten en 5 startdragers. / *Harder start: a new game begins with **20 free settlers** (was 24) and **4 carriers** (was 5). Old saves keep their settlers and 5 starting carriers.*
- De computerspelers onderzoeken Woningbouw en Isolatie en verbouwen hun huizen (rijhuis met 2 voedselsoorten, anders stenen huis), één tegelijk en alleen als er genoeg planken en blokken overblijven. / *Computer players research Housing and Insulation and upgrade their houses (terraced house with 2 kinds of food, otherwise stone house), one at a time and only when enough planks and blocks remain.*

## 0.21.3 — Bier (2026-10-29)
- **Brouwerij** (tab Voedsel, via de technologie Landbouw; 3 planken + 1 blok): brouwt van 1 graan en 1 water 1 bier in 30 seconden. / *Brewery (Food tab, via the Agriculture tech; 3 planks + 1 block): brews 1 beer from 1 grain and 1 water in 30 seconds.*
- **Bier is een genotmiddel**: mijnen en kolenmijnen die bier krijgen, werken **25% sneller** (1 bier per werkcyclus; zonder bier werken ze gewoon op de normale snelheid). Dat telt op bij de bonus van eten. / *Beer is a luxury: mines and coal mines that get beer work **25% faster** (1 beer per work cycle; without beer they simply work at normal speed). This stacks with the food bonus.*
- Bier heeft standaard een productielimiet van 20 en staat niet in de bovenbalk (wel in de voorraad). De computerspelers bouwen een brouwerij zodra ze een boerderij en mijnen hebben. / *Beer has a default production limit of 20 and is not in the top bar (it is in the stock). Computer players build a brewery once they have a farm and mines.*

## 0.21.2 — IJzer, paard en kar, veeteelt (2026-10-29)
- **Metaalketen**: de nieuwe **smelterij** (3 planken + 3 blokken) smelt 1 erts met 1 kolen tot 1 ijzer in 24 seconden. De **smederij** smeedt nu van 1 ijzer en 1 plank een zwaard **of gereedschap**, zonder kolen. Gereedschap maakt ze alleen als je het nodig hebt (na Paard en kar), om en om met zwaarden. **IJzer vervangt erts** in alle kosten (lopende banden). Oude saves: erts en kolen die nog in een smederij lagen gaan terug naar het hoofdkwartier. / *Metal chain: the new **smelter** (3 planks + 3 blocks) smelts 1 ore with 1 coal into 1 iron in 24 seconds. The **smithy** now forges a sword **or tools** from 1 iron and 1 plank, without coal. It only makes tools when you need them (after Horse and cart), alternating with swords. **Iron replaces ore** in all costs (conveyor belts). Old saves: ore and coal still inside a smithy go back to the headquarters.*
- **Houtskool**: de nieuwe technologie **Houtskool** (tak Productie, 5 planken + 2 blokken, 30 s) ontgrendelt de **houtskoolbrander** (2 planken + 1 steen): 2 hout wordt 1 kolen in 24 seconden, ook zonder kolenmijn. / *Charcoal: the new **Charcoal** tech (Production branch, 5 planks + 2 blocks, 30 s) unlocks the **charcoal burner** (2 planks + 1 stone): 2 wood becomes 1 coal in 24 seconds, even without a coal mine.*
- **Kolen gaan eerst naar de smelterij**: woonhuizen stoken pas kolen als er meer dan 4 in voorraad zijn; anders hout (en als laatste planken). / *Coal goes to the smelter first: houses only burn coal when more than 4 are in stock; otherwise wood (and planks as a last resort).*
- **Paard en kar**: de technologie **Paard en kar** (tak Economie, 10 planken + 5 blokken, 60 s) vraagt het Draagjuk **en een gebouwde paardenstal**. Ze ontgrendelt de **wagenmakerij** (4 planken + 2 blokken + 2 gereedschap). Een kar kost 2 planken, 1 ijzer en 1 paard uit de voorraad (dat paard telt dan niet meer mee voor de snellere dragers). Een kar vervoert **6 goederen** per tocht en eet elke minuut 1 graan; zonder graan rijdt hij half zo snel. Je kunt **één kar meer hebben dan je opslagplaatsen**. / *Horse and cart: the **Horse and cart** tech (Economy branch, 10 planks + 5 blocks, 60 s) requires the Yoke **and a built horse stable**. It unlocks the **cartwright** (4 planks + 2 blocks + 2 tools). A cart costs 2 planks, 1 iron and 1 horse from stock (that horse no longer counts towards faster carriers). A cart carries **6 goods** per trip and eats 1 grain every minute; without grain it drives at half speed. You can have **one cart more than you have storehouses**.*
- **Veeteelt**: de technologie **Veeteelt** (na Jacht, 6 planken + 2 blokken, 40 s) ontgrendelt de **varkensboerderij** (1 graan + 1 water → 1 varken in 40 s) en de **slager** (1 varken → 2 vlees in 20 s). Beide staan in de tab Voedsel. / *Animal husbandry: the **Animal husbandry** tech (after Hunting, 6 planks + 2 blocks, 40 s) unlocks the **pig farm** (1 grain + 1 water → 1 pig in 40 s) and the **butcher** (1 pig → 2 meat in 20 s). Both are in the Food tab.*
- IJzer staat in de bovenbalk; erts, gereedschap en varkens alleen in de voorraad. De computerspelers onderzoeken Houtskool, Veeteelt en Paard en kar en bouwen zelf smelterij, houtskoolbrander, wagenmakerij, varkensboerderij en slager. Nieuwe gebouwen zijn eigen modellen in dezelfde stijl, zonder extra GPU-last. / *Iron is in the top bar; ore, tools and pigs only in the stock. Computer players research Charcoal, Animal husbandry and Horse and cart and build the smelter, charcoal burner, cartwright, pig farm and butcher themselves. The new buildings are own models in the same style, with no extra GPU load.*

## 0.21.1.1 — Handgeschilderde texturen (2026-10-29)
- **Handgeschilderde texturen**: nieuwe, eigen handgeschilderde texturen met meer contrast en vorm: grassprieten, rotsbreuken, planken met naden, dakpannen, leien, stenen met diepe voegen en kalkpleister. Daken en muren hebben nu hun eigen materiaal (niet meer geraden op kleur), wegen van tier 0/1 tonen een aarden pad en tier 2 kinderkopjes. Op Laag een lichte variant voor laptops met geïntegreerde GPU (één kleine textuur, eenvoudiger terrein). Op Middel en Hoog ongeveer 70–135 MB minder videogeheugen; de oude fotoscan-terreintexturen zijn weg. / *Hand-painted textures: new, self-made hand-painted textures with more contrast and shape: grass blades, rock fractures, seamed planks, roof tiles, slates, stones with deep joints and lime plaster. Roofs and walls now have their own material (no longer guessed from colour); tier 0/1 roads show a dirt path, tier 2 cobbles. On Low a light variant for laptops with integrated graphics (one small texture, simpler terrain). About 70–135 MB less video memory on Medium and High; the old photo-scan terrain textures are gone.*
- **Boerderij, molen en bakkerij** krijgen ook de handgeschilderde materialen: rieten daken en graan als stro, pleister en vakwerk, stenen sokkel en bakoven, houten balken en toonbank; de ovenmond gloeit. Werkt ook op Laag, zonder extra draw calls of texturen. / *Farm, mill and bakery also get the hand-painted materials: thatched roofs and grain as straw, plaster and timber framing, stone plinth and bake oven, wooden beams and counter; the oven mouth glows. Works on Low too, with no extra draw calls or textures.*

## 0.21.1 — Brood, jacht en een tab Voedsel (2026-10-29)
- **Broodketen**: drie nieuwe gebouwen via de nieuwe technologie **Landbouw** (tak Economie, 7 planken + 2 blokken, 60 s). De **boerderij** (2 planken) verbouwt graan op vrij grasland rondom (straal 3, zoals de bosbouwer): 1 graan per 40 seconden, in de winter rust het land. De **molen** (3 planken + 1 blok) maalt 1 graan tot 1 meel in 20 seconden. De **bakkerij** (3 planken + 2 blokken) bakt van 1 meel en 1 water 2 broden in 30 seconden. / *Bread chain: three new buildings via the new **Agriculture** tech (Economy branch, 7 planks + 2 blocks, 60 s). The **farm** (2 planks) grows grain on free grassland around it (radius 3, like the forester): 1 grain every 40 seconds, resting in winter. The **mill** (3 planks + 1 block) grinds 1 grain into 1 flour in 20 seconds. The **bakery** (3 planks + 2 blocks) bakes 2 loaves from 1 flour and 1 water in 30 seconds.*
- **Jacht is nu een technologie**: de jagershut zit achter de goedkope technologie **Jacht** (3 planken, 20 s). Bij de start heb je voor voedsel alleen de visser, de waterput en de waterdrager. Oude saves met een jagershut krijgen Jacht er gratis bij. / *Hunting is now a technology: the hunter's hut is behind the cheap **Hunting** tech (3 planks, 20 s). At the start your only food buildings are the fisher, the well and the water carrier. Old saves with a hunter's hut get Hunting for free.*
- **Gevarieerd eten**: woonhuizen eten brood, vis en vlees (in die volgorde). Een huis groeit alleen tot zijn volle bewonersaantal met **2 verschillende soorten voedsel**; met 1 soort komt het tot de helft. Het infopaneel van een huis toont hoeveel soorten het heeft. Mijnen, kolenmijnen en kazernes eten nu ook brood of vlees naast vis (zonder eten werken ze gewoon trager). / *Varied food: houses eat bread, fish and meat (in that order). A house only grows to its full number of residents with **2 different kinds of food**; with 1 kind it reaches half. A house's info panel shows how many kinds it has. Mines, coal mines and barracks now also eat bread or meat besides fish (without food they simply work slower).*
- **Tab Voedsel** in het bouwmenu: visser, waterput, waterdrager, jagershut, boerderij, molen en bakkerij staan nu samen. / *Food tab in the build menu: fisher, well, water carrier, hunter's hut, farm, mill and bakery are now together.*
- Graan en meel krijgen standaard een productielimiet van 20; brood en vlees zijn onbeperkt. Graan en meel staan niet in de bovenbalk (wel in de voorraad). Steden verhandelen nu ook brood en graan. / *Grain and flour get a default production limit of 20; bread and meat are unlimited. Grain and flour are not in the top bar (they are in the stock). Towns now also trade bread and grain.*
- **Handelsvoorstellen van de AI** kun je nu in het handelsscherm (tab Akkoorden) accepteren of weigeren. / *AI trade offers can now be accepted or declined in the trade screen (Deals tab).*
- De computerspelers onderzoeken Jacht en Landbouw en bouwen zelf de broodketen. Nieuwe gebouwen zijn eigen modellen in dezelfde stijl, zonder extra GPU-last. / *Computer players research Hunting and Agriculture and build the bread chain themselves. The new buildings are own models in the same style, with no extra GPU load.*

## 0.21 — Slimmere AI: verkennen, plunderen, handelen (2026-10-29)
- **De AI verkent zelf**: computerspelers sturen verkenners uit naar onontdekt land en breiden hun gebied bij voorkeur die kant op uit. Komt een verkenner langs je grens, dan krijg je een melding. / *The AI explores on its own: computer players send scouts into undiscovered land and prefer to expand their territory in that direction. When a scout passes your border, you get a notice.*
- **De AI plundert roverskampen**: heeft een computerspeler genoeg ridders over (en houdt hij er genoeg thuis), dan valt hij een roverskamp aan. Gebeurt dat in jouw zicht, dan zie je een melding. In het begin van het spel plundert de AI nog niet, zodat hij eerst zijn gebied kan opbouwen. / *The AI raids bandit camps: when a computer player has enough spare knights (while keeping enough at home), it attacks a bandit camp. If that happens within your sight, you get a notice. Early in the game the AI does not raid yet, so it can build up its land first.*
- **De AI handelt**: computerspelers zetten zelf handelsroutes op met neutrale steden en doen jou handelsvoorstellen (hun overschot tegen wat zij tekortkomen). Je kunt een voorstel aanvaarden of weigeren; na 2 minuten vervalt het. Weigert de AI jouw voorstel, dan krijg je ook een melding. / *The AI trades: computer players set up trade routes with neutral towns and make you trade offers (their surplus for what they lack). You can accept or decline an offer; after 2 minutes it expires. When the AI refuses your offer, you get a notice too.*
- **Nieuwe meldingen**: vreemde verkenner, verkenner verdwenen, plundering door een computerspeler, buit verloren, aanval afgeslagen, kamp geplunderd door een buur, handelsvoorstel, handel gesloten, handel geweigerd, buurman breidt uit, grenzen raken elkaar en een vreemd zeil langs je kust. / *New notices: strange scout, scout gone, raid by a computer player, loot lost, attack repelled, camp raided by a neighbour, trade offer, trade agreed, trade refused, neighbour expands, borders touch and a strange sail along your coast.*
- **Fix kolenmijn van de AI**: computerspelers vonden vaak geen plek voor een kolenmijn, omdat ze (anders dan jij sinds 0.18.2.1) geen mijn op de berg mochten zetten. Nu mag dat ook voor de AI, en als er echt geen plek is, wacht de AI steeds langer voor hij opnieuw zoekt. / *Fix AI coal mine: computer players often found no spot for a coal mine, because unlike you (since 0.18.2.1) they could not place a mine on the mountain. Now the AI can too, and if there really is no spot, the AI waits longer each time before searching again.*
- **Automatische wegen slimmer**: "Weg aanleggen" naar het wegennet mag nu door een losse (nog niet verbonden) vlag heen lopen; die vlag wordt dan meteen mee aangesloten. Lukt een rechte weg voor de AI niet, dan probeert hij dezelfde automatische route als jij. / *Smarter automatic roads: "Build road" to the network can now pass through a loose (not yet connected) flag, which then gets connected too. When a straight road fails for the AI, it tries the same automatic route as you.*
- De AI blijft volledig voorspelbaar (vaste volgorde, hele ticks), als voorbereiding op multiplayer in 0.22. Alle nieuwe AI-instellingen staan in `data/ai.json` (secties explore, raid en trade, per moeilijkheid aan te passen). Geen invloed op graphics of GPU-last. / *The AI stays fully deterministic (fixed order, whole ticks), in preparation for multiplayer in 0.22. All new AI settings are in `data/ai.json` (sections explore, raid and trade, adjustable per difficulty). No effect on graphics or GPU load.*
- **AI "Moeilijk" niet zwakker**: plunderen wacht tot na het begin (min_s) en houdt een reserve ridders achter; gemeten na 15 min (seed 42): Moeilijk 35 gebouwen (was 33), Makkelijk 21. / *"Hard" AI not weaker: raiding waits until after the opening and keeps a reserve of knights; measured after 15 min (seed 42): Hard 35 buildings (was 33), Easy 21.*

## 0.20.0.5 — Veiligheid: afhankelijkheden en serverheaders (2026-10-28)
- **Controle op bekende kwetsbaarheden**: bij elke release wordt nu een lijst van alle onderdelen van derden gemaakt (Godot-engine en export-template, installer-maker NSIS, bouwhulpmiddelen) en gecontroleerd op bekende beveiligingslekken. Een release wordt tegengehouden bij een ernstig lek in iets dat in het spel zelf zit. Bij deze versie: geen bekende lekken gevonden. / *Known vulnerability check: every release now builds a list of all third-party parts (Godot engine and export template, the NSIS installer builder, build tools) and checks them for known security issues. A release is blocked on a serious issue in anything shipped in the game. This version: no known issues found.*
- **Veiliger rapport-server (voorbereid)**: de nog niet actieve server voor foutrapporten stuurt strikte beveiligingsheaders mee, staat geen verzoeken van websites toe en weigert te grote of verkeerde uploads. / *Safer report server (prepared): the not-yet-active crash report server sends strict security headers, allows no requests from websites and rejects oversized or wrong uploads.*

## 0.20.0.4 — Hotfix vloed alleen aan zee (2026-10-28)
- **Geen vloed meer bij binnenwater**: alleen rivieren en meren die via het water met de zee verbonden zijn, kunnen nog een stormvloed of vloedgolf krijgen. Binnenmeren, vijvers en rivieren zonder verbinding met de zee overstromen nooit. / *No more floods on inland water: only rivers and lakes connected to the sea by water can get a storm flood or tidal wave. Inland lakes, ponds and rivers without a sea connection never flood.*
- De zeeverbinding wordt uit de kaart zelf berekend (deterministisch, geen extra GPU-last) en na het laden opnieuw bepaald, dus ook oude saves werken meteen goed. / *The sea connection is computed from the map itself (deterministic, no extra GPU cost) and recomputed after loading, so old saves are fixed too.*

## 0.20.0.3 — Veiligheid (2026-10-28)
- **Saves strenger gecontroleerd**: een beschadigde of aangepaste save (verkeerde soorten gegevens, onmogelijke waarden, te groot of te diep genest) geeft nu de gewone melding "save is beschadigd" in plaats van een crash. Een save kan nooit objecten of scripts bevatten. / *Stricter save checks: a damaged or tampered save (wrong data types, impossible values, too large or too deeply nested) now shows the normal "save is damaged" message instead of crashing. A save can never contain objects or scripts.*
- **'Wat is er nieuw' veiliger**: tekst die van GitHub wordt opgehaald, wordt als gewone tekst getoond (geen opmaakcodes of afbeeldingen van buitenaf), en links openen alleen naar github.com/LTGmaster. / *Safer "What's new": text fetched from GitHub is shown as plain text (no outside markup or images), and links only open to github.com/LTGmaster.*
- **Veilige invoer**: stadsnamen (ook uit oude of aangepaste saves) en savenamen worden opgeschoond: geen opmaakcodes of links, geen onzichtbare stuurtekens, geen padtekens zoals `../`, en een maximale lengte. / *Safe input: town names (also from old or edited saves) and save names are cleaned: no markup codes or links, no invisible control characters, no path characters such as `../`, and a maximum length.*
- **Releasecontrole op geheimen**: elke release en elke commit wordt automatisch gecontroleerd op per ongeluk meegeleverde wachtwoorden of sleutels; het GitHub-token komt alleen uit de omgeving. / *Release check for secrets: every release and commit is automatically scanned for accidentally included passwords or keys; the GitHub token is only read from the environment.*
- Nieuwe test `test_m20_0_3_security` (beschadigde/te grote saves, geen objecten uit user://, nieuws-escaping en link-whitelist); `tools/secret_check.sh` (gitleaks, `.gitleaks.toml`), pre-commit hook `tools/hooks/pre-commit`. / *New test `test_m20_0_3_security`; `tools/secret_check.sh` (gitleaks) and a pre-commit hook.*

## 0.20.0.2 — Nieuwe meldingen (2026-10-28)
- **Nieuwe meldingskaarten bij vloed**: een aparte waarschuwing voor een vloedgolf, een kaart als een gebouw beschadigd of verwoest is, als het weer hersteld is, als het puin weg is, en "De dijk hield" als je dijken alles droog hielden. / *New flood cards: a separate tidal wave warning, damaged or destroyed buildings, repaired, rubble cleared, and "The dike held".*
- **Woonhuizen**: een kaart als een huis al een minuut water, eten of warmte mist, en als kolonisten daardoor vertrekken. / *Houses: a card when a house has lacked water, food or warmth for a minute, and when settlers leave because of it.*
- **Dieren en jagen**: een kaart bij de eerste wilde dieren, het eerste vlees, een kudde die door jagen klein wordt of verdwijnt, en een kudde die terugkeert. / *Animals and hunting: cards for the first wildlife, the first meat, a herd that dwindles or vanishes through hunting, and a herd that returns.*
- **Paarden**: kaarten bij de eerste wilde paarden, het eerste getemde paard, 3 paarden (dragers sneller) en 8 paarden (nog sneller), en als een paardenstal geen wilde paarden binnen bereik heeft. / *Horses: cards for the first wild horses, the first tamed horse, 3 and 8 horses, and a stable without wild horses in range.*
- **Stadsnamen**: een kaart met de naam van je stad bij de start, en bij een veroverde stad die haar naam houdt of een nieuwe krijgt. / *Town names: a card with your town's name at the start, and when a conquered town keeps its name or gets a new one.*
- Eigen kaart voor Directe levering, en een kaart bij de eerste winter (ijs op het water). / *Own card for Direct delivery, and a card for the first winter.*
- Betere teksten voor Dijk, Opslagplaats, Dragersgilde, Woonhuis en Paardenstal (het gilde bemant geen wegen meer, maar geeft 3 extra dragers die sneller lopen). / *Better texts for Dike, Storehouse, Carriers' guild, House and Horse stable.*

## 0.20.0.1 — Nieuwe stijl en startscherm (2026-10-28)
- **Nieuwe UI-stijl 'slanke plaques'**: één gedeeld thema voor het hele spel. Donkere halftransparante panelen met een gouden linkerrand, knoppen met duidelijke staten (normaal, hover, ingedrukt, uitgeschakeld, primair), plus nieuwe tooltips, tabs, dunne schuifregelaars, een gouden schakelaar en lijstrijen. Geen extra GPU-last. / *New 'slim plaques' UI style: one shared theme with dark translucent panels, a gold left edge, clear button states, new tooltips, tabs, slim sliders, a gold toggle and list rows. No extra GPU cost.*
- **Nieuw startscherm**: de 3D-achtergrond blijft, de menuknoppen zijn nu losse plaques met een gouden icoon, en Afsluiten staat apart. / *New start screen: the 3D background stays, menu buttons are separate plaques with a gold icon, and Quit stands apart.*
- **Echt Sigilmark-logo** in het menu, in de bovenbalk (naast de stadsnaam) en op het laadscherm. / *The real Sigilmark logo in the menu, the top bar (next to the town name) and on the loading screen.*

## 0.20 — Wilde paarden (2026-10-28)
- **Wilde paarden**: elke speler heeft een kudde wilde paarden op open land vlak bij het startgebied. / *Wild horses: every player has a herd of wild horses on open land near the start area.*
- **Nieuw gebouw: Paardenstal** (3 planken, 1 blok, 1 hout): temt wilde paarden binnen zijn straal en brengt ze naar je opslag. Zijn er geen paarden in de buurt, dan meldt de stal "geen wilde paarden binnen straal". Een kudde groeit maar langzaam terug. / *New building: Horse stable. It tames wild horses in range and brings them to your storage.*
- **Paarden maken dragers sneller**: vanaf 3 paarden in de opslag lopen je dragers sneller, vanaf 8 paarden nog sneller. De tooltip bij Transport toont het aantal paarden en de snelheid in tegels per seconde. / *Horses speed up carriers: faster from 3 horses in storage, faster still from 8. The Transport tooltip shows the count and the speed.*
- De AI volgt dezelfde regels: zij bouwt een stal als er paarden in haar gebied lopen. / *The AI uses the same rules.*
- **Oude saves**: bij het laden krijgen alle spelers hun paardenkudde erbij. / *Old saves get their horse herds when loaded.*
- **Lichtere fotoscan-modellen** (hoofdkwartier, opslag, houthakker, steengroeve, rotsen): ze worden bij het laden eenmalig vereenvoudigd, zonder zichtbaar verschil (minder dan 0,1% van de pixels wijkt af, van dichtbij bekeken). Gebouwen tellen 67% minder driehoeken (126k naar 41k). / *Photoscan props are simplified once at load time, with no visible difference. Buildings have 67% fewer triangles.*
- **'Wat is er nieuw' opent vanzelf** bij de eerste start van een nieuwe versie. Het toont altijd de wijzigingen die bij deze versie horen; online wordt alleen de roadmap bijgewerkt. / *'What's new' opens by itself on the first start of a new version and always shows the changes bundled with that version.*
- Tests: `test_m20_horses`, `test_changelog_dev`, `test_m19_3_engine` (save van 0.19.2.1 laadt met paarden, 1 en 8 draden gelijk).

## 0.19.3 — Godot 4.4 (2026-10-28)
- **Het spel draait nu op Godot 4.4.1** (was 4.3): nieuwere engine met stabielere grafische drivers en renderer-fixes. Je saves van 0.19.2.x laden gewoon en het spel rekent er exact hetzelfde mee verder (getest: zelfde controle-hash na 2000 ticks als onder 4.3). / *The game now runs on Godot 4.4.1; saves from 0.19.2.x load and play on identically.*
- **Minder GPU-werk in de schaduwen**: gebouwen en bomen/rotsen werpen hun schaduw nu met een eenvoudiger detailniveau (de schaduw zelf ziet er hetzelfde uit; in een testscène ±7% minder driehoeken, zelfde aantal draw calls). Onder 4.4 ook ±20-29% minder driehoeken per frame in de vaste benchmark. / *Less GPU work for shadows; same look.*
- Lucht/mist ziet er hetzelfde uit als onder 4.3 (4.4 kleurde de lucht anders bij dezelfde instelling).
- Kleine fix: geen foutmelding meer als het deel-logboeken-venster opent terwijl het menu al sluit.
- Tests: `test_m19_3_engine` (save 0.19.2.1 van Godot 4.3 laden, hash gelijk, 2000 ticks verder gelijk, 1 en 8 draden).

## 0.19.2.2 — Hotfix: crash bij bouwen, updatecontrole (2026-10-28)
- **Crash opgelost** (bug Mike: spel sloot meteen af bij het plaatsen van een smederij, ook eerder midden in een spel in 0.19.1; Windows-fout 0xc0000005). Oorzaak: de balkjes boven de woonhuizen (water/eten/warmte) vroegen iconen op die niet bestonden; in de Windows-versie leidde dat tot een harde crash zodra het eerste eigen woonhuis met behoeften in beeld kwam. De iconen komen nu uit de juiste bron en ontbreken nooit meer. / *Fixed a crash (0xc0000005) shortly after building, caused by missing icons for the house-needs bars.*
- **Updatecontrole**: "Updatecontrole mislukt (http_403)" bij elke start kwam door de limiet van GitHub (60 aanvragen per uur per internetadres). Bij 403/429 kijkt het spel nu via de gewone releasepagina (zonder die limiet) of er een nieuwe versie is. / *Update check no longer fails with http_403 (GitHub rate limit): falls back to the release page.*

## 0.19.2.1 — Laden, UI-schaal en stadsnamen (2026-10-28)
- **Laden werkt weer**: saves uit een vorige release (bv. autosaves van 0.19.1/0.19.1.1) werden geweigerd met "controle-hash klopt niet", waardoor 'Laden' niets leek te doen. De controle gebeurt nu over de opgeslagen gegevens zelf; een mislukte poging toont nu ook een venster. / *Loading works again: saves from an earlier release were rejected by the checksum, so 'Load' appeared to do nothing. A failed load now shows a dialog.*
- **UI-schaal Automatisch kleiner**: op 1920x1080 komt Automatisch nu overeen met het vroegere 75% (schaalt mee met de vensterhoogte). Wie Automatisch gebruikt krijgt de nieuwe waarde; handmatige keuzes blijven. / *Automatic UI scale is smaller: at 1920x1080 it now matches the former 75%; manual choices are kept.*
- **Stadsnamen**: bij een nieuw spel kies je de naam van je stad (willekeurige suggestie, 2–24 tekens). Verover je een stad, dan kies je 'Naam behouden' of 'Nieuwe naam'; de AI kiest zelf. De naam staat in de bovenbalk en boven het hoofdkwartier en wordt bewaard (oude saves krijgen een gegenereerde naam). / *Town names: name your starting town (random suggestion, 2–24 characters); when you conquer a town choose 'Keep name' or 'New name'; AI names its towns itself. Shown in the top bar and above the HQ, stored in saves.*
- Tests: `test_m19_2_x_load` (save uit 0.19.1 als fixture), `test_m19_2_x_towns`.

## 0.19.2 — Jagen en minder GPU-last (2026-10-28)
- **Nieuw gebouw: jagershut** (bij wild in de buurt): de jager jaagt op de wilde dieren in zijn straal en brengt **vlees**, dat in de woonhuizen als eten telt naast vis. Kuddes slinken door de jacht en groeien langzaam terug. De AI bouwt ook jagershutten. Productielimiet per type werkt ook hier. / *New building: hunter's hut — hunts wild animals for meat (food next to fish); herds shrink and regrow.*
- **Minder draw calls op 'Hoog'**: de eigenaarsvaandels bij gebouwen worden nu gebundeld getekend (per stuk kaart één keer i.p.v. één keer per gebouw, ook in de schaduwen) — in de testscène ±17-19% minder draw calls (bv. 1086 -> 923 dichtbij, 749 -> 584 midden), hetzelfde aantal driehoeken en hetzelfde beeld. / *Fewer draw calls on High (owner banners batched), same image.*
- **Minder haperingen bij menu-start en laden**: de zware gebouwmodellen (fotoscan-props en LOD's, tot ±390 ms per model) worden nu al in het hoofdmenu op de achtergrond opgebouwd (werkdraad), het menu toont eerst het eenvoudige model. Ook de nieuwe vaandelvormen zitten in de shader-warm-up. / *Fewer one-off hitches: heavy building models are prepared in the background while in the main menu.*
- Spelsimulatie ongewijzigd en deterministisch (alleen weergave). Tests: `test_m19_2_hunting`, `test_m19_2_gpu`; hulpscripts `tools/gpu_bench192.gd`, `tools/hitch_bench.gd`.

## 0.19.1.2 — Sigilmark en Directe levering (2026-10-28)
- **Het spel heet nu Sigilmark** (was Kolonie): venstertitel, hoofdmenu, HUD, Windows-programma (`Sigilmark.exe`, nieuw icoon), installatie (`Sigilmark-0.19.1.2-Setup.exe`, snelkoppelingen, vermelding bij 'Apps') en updatecontrole. Het woord 'kolonie' als nederzetting blijft in de teksten. / *The game is now called Sigilmark.*
- **Je saves, instellingen en logboeken blijven gewoon werken**: het spel gebruikt dezelfde map als voorheen (`%APPDATA%\Ltgnetwork\Kolonie`), er wordt niets verplaatst of gekopieerd.
- **Bijwerken vanaf Kolonie**: de installatie (ook de automatische update vanuit het spel) verwijdert het oude `Kolonie.exe`, de oude snelkoppelingen in het startmenu en op het bureaublad (die op het bureaublad komt terug als 'Sigilmark') en de oude vermelding 'Kolonie' bij Apps. Sigilmark staat daarna in `Program Files\Ltgnetwork\Sigilmark`.
- **Nieuw onderzoek 'Directe levering'** (wens Mike; tak Opslag, na Opslag I; 10 planken + 5 blokken, 100 s): dragers mogen goederen dan **rechtstreeks van een producent** (bv. houthakker) naar een gebouw brengen dat ze nodig heeft — bouwplaats, verwerker (zagerij, smidse...) of woonhuis — als dat korter is dan via de opslag. Anders gaat het zoals voorheen via de opslag. De AI onderzoekt het ook. / *New research 'Direct delivery': carriers bring goods straight from a producer to the building that needs them when that is shorter.*
- Deterministisch (1 tegen 8 draden gelijk), werkt met save/load (effect volgt uit de techboom).
- **Productielimiet geldt nu per gebouwtype** (wens Mike): verander je de limiet van één houthakker, dan geldt die voor al je houthakkers, ook voor nieuwe; zo voor elk type. Oude saves: per type wordt de limiet van het eerste gebouw overgenomen. / *Production limit now applies to all buildings of a type.*
- Tests: `test_m19_1_2_direct` (zonder/met onderzoek, AI, save/load, 1 vs 8 draden), `test_m19_1_2_limits` (limiet per type, save/load, migratie), `test_m19_1_2_rename` (naam, gebruikersmap, export, installer, updater).

## 0.19.1.1 — Hotfix: zoomen in de techboom, automatische UI-schaal (2026-10-28)
- **Zoomen in de techboom zoomt de spelcamera niet meer mee** (bug Mike). Het muiswiel boven de techboom zoomt alleen de boom; ook touchpad-knijpen (pinch) en -schuiven werken nu in de boom zelf.
- Hetzelfde geldt voor **alle schermen en panelen**: handelsscherm, plunderpaneel (roverskamp), pauzemenu met de instellingen, het einde-spel-paneel en elk HUD-element (balken, chips, gebouwpaneel) onder de muis. Zolang een schermvullend paneel open is, bewegen ook WASD/ZQSD en draaien (Q/E) de camera niet.
- **UI-schaal 'Automatisch'** (nieuwe standaard, ook in het hoofdmenu): de grootte van menu's en panelen volgt het echte venster. Kleine vensters (onder 1280x720) worden niet meer extra vergroot, grote schermen worden compacter (1080p ±87%, 1440p ±79%, 4K ±68% van de basis), Windows-schaal (HiDPI) en DPI tellen mee; past zich live aan bij het vergroten/verkleinen van het venster. Handmatige percentages (75%–200%) blijven kiesbaar. Bestaande instellingen worden **eenmalig** op Automatisch gezet.
- **Pauzemenu past altijd op het scherm**: maximaal 640 px hoog en scrollbaar als het venster te laag is (was: vulde een klein venster helemaal).
- **Logbestanden**: frames die alleen traag zijn omdat het spel zichzelf afremt (15 FPS als het venster geen focus heeft of gepauzeerd is) worden niet meer als '[Spike]' gelogd (in Mike's log ~2000 loze regels in 4 minuten); `frames>50ms` in de [Perf]-regel telt ze ook niet meer.
- Tests: `tools/runall_par.sh` sloot per ongeluk ook `test_m17_6_1` uit (naam begint met `test_m17_6`); nu draaien alle 95 tests.
- Test: `test_ui_input_scale` (wiel en pinch met techboom/handel/plunderen/pauzemenu open: camerazoom ongewijzigd; zonder paneel zoomt het wiel wel; auto-schaal bij 800x450 t/m 8K, HiDPI, lage DPI; migratie; pauzemenu-hoogte).

## 0.19.1 — Wilde dieren (2026-10-28)
- **Er leven nu wilde dieren in de wereld** (nieuwe spellen uit het menu): kuddes **herten**, **konijnen** en **wilde zwijnen** rond elke startplek, 16-44 tegels van het hoofdkwartier. Welke soort waar leeft hangt af van het landschap: zwijnen en herten in het bos, konijnen en herten op het gras. Elke kaart (seed) heeft zijn eigen, vaste kuddes.
- Dieren **grazen en zwerven** rustig rond hun leefgebied en blijven als kudde bij elkaar. Ze lopen om water, bergen, rotsen en gebouwen heen.
- **Ze zijn schuw**: komt er een kolonist binnen 5 tegels, dan vlucht de hele kudde (twee keer zo snel) en komt daarna terug.
- **Langzame aanwas**: een kudde die kleiner is geworden groeit elke 3 minuten met één dier tot de normale grootte; een uitgestorven kudde krijgt pas na 15 minuten weer een nieuw paar. (Jagen komt in 0.19.2.)
- **Vogelzwermen** cirkelen boven een deel van de kuddes (alleen beeld).
- Eigen low-poly modellen (geen nieuwe assets), één draw call per soort, alleen dieren in de buurt van de camera worden getekend: geen merkbare extra GPU-last.
- Oude saves laden gewoon (zonder dieren). Deterministisch (1 tegen 8 draden gelijk), dieren in de save.
- Test: `test_m19_1_animals` (spawn uit de seed, biotoop, gedrag, vluchten, aanwas, save/load, oude saves, 1 vs 8 draden, prestatie, weergave/culling).

## 0.19.0.4 — Moeilijker: duurdere techboom, hongerige woningen (2026-10-28)
- **Het spel is duidelijk moeilijker** (wens Mike: het ging te snel). Geldt voor nieuwe spellen (depot-logistiek met woningbehoeften); oude saves en klassieke spellen houden hun regels.
- **Techboom duurder en trager dan vóór 0.19.0.3** (kosten ×1,35 naar boven afgerond, onderzoekstijd ×1,35): o.a. Productie I 9 planken + 3 blokken, 80 s (was 6+2, 60 s); Productie II 14+6, 120 s; Gilden 9+5, 80 s (0.19.0.3: 4+2, 45 s); Draagjuk 11+6, 120 s; Opslag I 7+2, 60 s; Kasseien 6 planken + 6 steen, 60 s; Verharding 9+6, 100 s; Ridders II 6 blokken + 3 zwaarden, 120 s; Scheepvaart 11+3, 80 s; Kolen 6+3, 60 s en **weer pas na Productie I**. Alle vereisten zoals vóór 0.19.0.3.
- **Woningen hongeriger**: elk huis eet en drinkt elke 60 s (was 90 s) 1 vis en 1 water. Waarschuwing na 1 minuut tekort (was 2), kolonisten vertrekken na 2,5 minuten (was 4) en daarna elke 45 s (was 60 s).
- **Bevolking groeit trager**: groei elke 60 s (was 30 s), +1 per twee voldane huizen (was +1 per huis); het HQ geeft alleen nog +1 als geen enkel huis groeit en er geen vrije kolonisten zijn (tegen vastlopen). Nieuwe dragers 'uit een vrije woonplek' hooguit één per minuut (aannemen uit vrije kolonisten blijft direct).
- **Productie**: houthakker, zagerij, visser en mijn werken 15% trager. **Startvoorraad** 10 planken en 5 blokken (was 12 en 6).
- **AI** speelt met dezelfde regels: begint eerder met onderzoek (na 4 i.p.v. 6 plan-stappen, marge 2 planken / 0 blokken), bouwt geen lege woonhuizen meer zolang er nog woonruimte vrij is. Gemeten (twee AI's, 20 min): 30 → 44-51 kolonisten (was 70-85), eerste onderzoek na ±15-16 min, niemand vertrokken.
- Deterministisch (1 tegen 8 draden gelijk); geen nieuwe const-tabellen in werkdraden. Geen grafische wijzigingen.
- Tests: balanstests bijgewerkt (`test_m19_0_3`, `test_m13`, `test_m13_1`, `test_m14`, `test_m12`, `test_techboom_ui`).

## 0.19.0.3 — Woningbehoeften, verzamelaars en techboom (2026-10-28)
- **Woningen hebben water, eten en warmte nodig** (wens Mike, nieuwe spellen): elk woonhuis eet en drinkt elke 90 s 1 vis en 1 water; dragers vullen aan tot 2. Boven elk huis (en in het infopaneel) staan drie balkjes met iconen: water, eten, warmte. Alleen een huis waar aan alle drie voldaan is laat de bevolking groeien (het HQ blijft +1 geven). Na 2 minuten tekort komt een waarschuwing, na 4 minuten vertrekken er kolonisten (elke minuut één vrije kolonist).
- **Verzamelaars laten ophalen**: houthakker, steengroeve, mijn, visser, waterput enzovoort: een vrije drager haalt de goederen op en de verzamelaar blijft werken. Is er geen drager vrij en is de uitvoer vol, dan brengt de werker de lading zelf naar de opslag en ligt de productie zolang stil (status 'brengt zelf weg').
- **Techboom herbalanceerd** voor de nieuwe economie: Gilden (4 planken + 2 blokken, 45 s), Opslag I (4 + 1, 40 s), Draagjuk (6 + 3, 75 s), Kasseien (3 planken + 3 steen, 40 s), Verharding (5 + 3, 60 s); Kolen kan meteen (niet meer na Productie I), voor warmte in de winter. De AI onderzoekt Gilden en Kolen vroeg, begint al na de basiseconomie met onderzoek en houdt minder marge aan (4 planken, 2 blokken).
- **AI** volgt dezelfde regels: bouwt vissers en extra waterbronnen voor zijn woonhuizen. Getest: twee AI's groeien in 20 minuten van 30 naar ruim 70 kolonisten, eerste onderzoek na ±8-10 minuten.
- Oude saves en klassieke spellen: geen behoeften (zoals voorheen). Deterministisch, ook met 1 tegen 8 draden.
- Fix determinisme: veldroutes lazen in werkdraden constante tabellen (Godot 4.3 is daar niet thread-safe), waardoor een drager bij 8 draden heel af en toe een andere route nam dan bij 1 draad (ook al in 0.19). Nu zonder gedeelde constanten; 1 tegen 8 draden blijft gelijk.
- Test: `test_m19_0_3` (en aangepaste techboom-tests).

## 0.19.0.2 — Logboeken delen en opgeruimde tests (2026-10-28)
- **Logboeken automatisch delen** (wens Mike): bij het sluiten van het spel, of bij de volgende start na een crash, maakt Kolonie een zip met de logbestanden (godot.log, kolonie_detail.log met de [Perf]- en [Spike]-regels), het crashrapport en een kort prestatierapport (CPU, GPU, Windows-versie, RAM, resolutie, grafisch profiel, threads, gemiddelde FPS, 1%-low, aantal haperingen), plus spelversie en seed. Gebruikersnamen in paden worden `<user>`. Alleen met toestemming: de eerste start vraagt het, en in Instellingen staat de schakelaar 'Logboeken automatisch delen'. Lukt het uploaden niet, dan blijft de zip in de wachtrij (max 5 zips, elk max 5 MB) en probeert het spel het later opnieuw. Geen geheimen in het spel; de ontvanger (`[share] endpoint`) staat standaard uit tot hij is ingericht (zie `tools/report_receiver`). Ophalen en samenvatten: `tools/fetch_reports.sh`.
- Fix: geen engine-fouten meer in de tests van de meldingskaarten en verhaalteksten ('Parameter "m" is null' bij afsluiten zonder scherm, ontbrekende meta 'focus' bij een kaart zonder doel).
- Fix: `test_vloed_visuals` kan zonder scherm niet meer blijven hangen (waakhond).
- Test: `test_log_share`.

## 0.19.0.1 — Opgeruimde logistiek, meldingskaarten en vloedbeelden (2026-10-28)
Goedgekeurd door Mike.
- **Geen vlaggen meer in beeld** (feedback Mike): in een spel met de nieuwe logistiek worden vlaggen bij gebouwen, aan wegeinden en rond het HQ niet meer getekend, en ook de erfweg rond het HQ niet. Intern bestaan ze nog als ingang. Het vlaggereedschap (en de sneltoets F) is weg uit de bouwbalk.
- **Geen wegvraag meer na het plaatsen** (feedback Mike): een gebouw heeft geen weg nodig. In het infopaneel staat een vrijwillige knop **Weg aanleggen (sneller transport)**; is er te weinig voorraad, dan is de knop grijs en staat erbij wat er ontbreekt ("Ontbreekt: 4 planken"). In beide talen.
- De dialoog 'Meteen een weg?' (klassieke spellen) is weer compact in plaats van schermhoog, en toont ook wat er ontbreekt.
- **'Zonder weg'-schakelaar en de korting van 12,5% voor bouwen zonder weg zijn weg** in de nieuwe logistiek: elk gebouw kost de normale prijs.
- **Paadje wordt weg** werkt zonder het oude 'verbonden': het looppad is de dragersroute van het gebouw naar de dichtstbijzijnde opslag; is het ingesleten, dan kun je er een weg van maken (die de wegploeg aanlegt).
- **Balans van de vroege economie**: dragers nemen op de terugweg productie mee naar de opslag (retourvracht), de **opslagplaats** is goedkoper (**3 planken + 2 blokken**, was 4 + 3) en geeft **+3 dragers** (was +2), en elk **woonhuis +1 drager**. De AI bouwt een opslagplaats zodra al haar dragers onderweg zijn (en daarna 1 per ~10 gebouwen).
- **Standaard productielimiet 20** (wens Mike): nieuwe gebouwen pauzeren bij 20 in voorraad; voedsel- en watergebouwen (visser, waterput, waterdrager) blijven onbeperkt. Aan te passen met −/+; oude saves en bestaande gebouwen houden hun eigen instelling.
- **Dragers hebben woonruimte nodig** (regel Mike): opslagplaats (+3), Dragersgilde (+3) en woonhuis (+1) geven *plaatsen*; een extra drager komt er pas bij als er een kolonist zonder werk is (die wordt drager) of een vrije woonplek. Dragers tellen mee in de bevolking. De tooltip van de transportchip toont bv. 'Dragers 5/9 (4 wachten op woonruimte)'. De AI bouwt een woonhuis als er plaatsen wachten. Oude saves houden al hun dragers; deterministisch.
- **Autosave om de 5 minuten speeltijd** (wens Mike): drie slots rond (`autosave_1`, `autosave_2`, `autosave_3`, het oudste wordt overschreven), kleine melding 'Automatisch opgeslagen', niet tijdens pauze/pauzemenu (speeltijd staat dan stil) en atomair geschreven (een crash laat de vorige save heel). Instelling in het hoofdmenu: uit, 5 of 10 minuten (standaard 5). Autosaves staan in het laadmenu. Perf-log: `KOLONIE_PERFLOG=1` print de duur per autosave (≈4 ms op een kleine kaart).
- Tests: `test_m19_0_1_cleanup` (geen vlag-nodes/-meshes in de depot-modus, wel klassiek; geen korting; paadje → weg), `test_m19_0_1_road_ui` (geen wegvraag, vrijwillige knop nl/en, tekort, compacte dialoog), `test_m19_logistics` uitgebreid (limiet 20, AI niet vast, woonruimte voor dragers), `test_autosave`, `test_meldingen`, `test_vloed_visuals`.

### Onverwacht/UI
- **Meldingskaarten voor alle verhaalgebeurtenissen**: roverskamp ontdekt, etherkristal, schip aangekomen, andere kolonie gezien, tekorten, rivier, aanvallen, veroverd/verloren, landingen, pioniersbonus, plundertochten (ook halverwege), weg gesplitst, afgebrand, te weinig kolonisten, nieuwe kolonisten, grens verlegd, weg aangelegd, en nieuw: **stormvloed op komst** (blijft staan en telt af), **het water slaat toe** en **dijk klaar**. Alleen voor jouw eigen kolonie. / *Event cards for all story events, including a sticky storm-flood countdown.*
- Geen kaartenregen meer: hetzelfde soort melding hooguit één keer per 20 s; herhalingen worden samengevoegd (bv. "Tekort aan planken, steen" of "×3"). / *Repeated cards are merged (max one per kind per 20 s).*
- **Klik op een kaart** met een plek (gebouw, tegel, kamp, vloedstrook): de camera gaat erheen. / *Click a card to move the camera there.*
- **Bouwtooltips** hebben weer hun regelovergangen (naam, kosten, bouwtijd en bediening elk op een eigen regel). / *Build tooltips have their line breaks back.*
- **Beschadigde gebouwen zien er ook beschadigd uit**: roetvlekken, een natte, donkere waterlijn onderaan, vanaf ongeveer een derde schade barsten, vanaf de helft een losgeslagen plank, en een pluim stof of rook. Hoe meer schade, hoe sterker. Na herstel is alles weer schoon. / *Damaged buildings now look damaged (soot, wet waterline, cracks, a loose plank, dust or smoke), scaled by the damage.*
- **Vloedwaarschuwing op de kaart** is zachter: een blauw verloop dat naar het water toe sterker wordt, met een golvende glans die landinwaarts loopt, en een compact aftellabel dat niet meer meegroeit als je inzoomt. / *Softer flood marking with a gentle wave shimmer and a compact countdown label.*
- Nieuw **dijkmodel** (ronde aarden wal met grasrug, schuine stenen bekleding aan de zeezijde, loopplank en palen) en een nieuwe **puinhoop** (bult met brokken, gebroken balken en een plas). De knop **Herstellen** heeft een hamertje. / *New dike and rubble models; the Repair button has a hammer icon.*

## 0.19 — Logistiek zonder vlaggen (2026-10-28)
Goedgekeurd door Mike.
- **Dragers vertrekken vanuit de opslag**: het HQ en je opslagplaatsen (en havens) zijn het vertrekpunt. Een drager haalt het goed in de dichtstbijzijnde opslag die het heeft en loopt door het veld naar het gebouw (of de bouwplaats), en brengt productie naar de dichtstbijzijnde opslag. Je hoeft geen vlaggen meer te zetten of wegen te verbinden om iets geleverd te krijgen; elk gebouw in je eigen gebied is bereikbaar. Dragers lopen om bomen en rotsen heen (of laten ze eerst kappen/ruimen, zoals in 0.18.2.1).
- **Wegen = snelheidsbonus**: een aarden weg is ongeveer 1,6× zo snel als gras, kasseien en verharde wegen nog sneller; dragers kiezen vanzelf de snelste route. Betaalde wegen worden door de wegploeg aangelegd (geen vaste wegdrager meer nodig).
- **Transportcapaciteit zichtbaar**: in de bovenbalk staat **Dragers vrij/totaal** (rood als ze allemaal onderweg zijn); de tooltip toont hoeveel er onderweg zijn, de snelheid, het aantal goederen per tocht en de wegbonus.
- **Je start met 5 dragers**. Elke **opslagplaats +2**, een **Dragersgilde +3** en snellere dragers; met het **draagjuk** nemen ze 2 goederen per tocht mee. De bouwer telt niet mee.
- **Kolonisten zonder werk zwerven rond hun huis** (HQ en woonhuizen, hooguit 16 tegelijk in beeld, bij de AI 6). Alleen weergave: de simulatie verandert er niet door.
- **Fix**: arbeiders die naar hun werk lopen en eenheden die naar huis gaan, lopen niet meer recht door bos en rotsen maar eromheen.
- **Taal tijdens het spel** (wens Mike): het pauzemenu heeft nu ook de taalkeuze Nederlands/English; de wissel gebeurt meteen.
- **Oude saves** laden gewoon en krijgen de nieuwe logistiek: vlaggen en wegen blijven liggen (wegen als snelheidsbonus), goederen die op vlaggen of bij wegdragers lagen gaan naar het HQ, en de dragers gaan terug in de pool. Er gaat niets verloren.
- **AI**: speelt met hetzelfde systeem (dragers vanuit de opslag); haar wegen geven haar ook alleen snelheid.
- Deterministisch: dezelfde seed geeft hetzelfde spel, ook met 1 of 8 werkdraden (routes worden parallel berekend met alleen lezen).
- Tests: `test_m19_logistics` (start 5, bouwen en leveren zonder weg, capaciteit nooit overschreden, opslagplaats/gilde, wegbonus, looppaden om bos, zwervers, oude save omzetten zonder verlies, AI, 1 vs 8 draden), `test_pause_language`.

## 0.18.3 — Stormvloeden, dijken en een beter leesbare winter (2026-10-28)
Wensen van Mike.
- **Stormvloeden en vloedgolven**: aan de kust kan het water toeslaan. De eerste vloed komt nooit in de eerste **20 minuten** (tussen 20 en 30 min, vast per seed), daarna hooguit één keer per **20 à 35 minuten**. Ongeveer één op de vier is een zwaardere **vloedgolf**. Alleen spelers met gebouwen tot 3 tegels van het water worden getroffen, telkens één kuststrook (8 tegels rond een kustgebouw). Alles is deterministisch: dezelfde seed geeft dezelfde vloeden, ook met meer processorkernen.
- **Duidelijke waarschuwing**: **2 minuten** vooraf krijg je een melding ("Stormvloed op komst! Over 120 s…"), en op de kaart licht de bedreigde kuststrook blauw op met een aftellabel boven het midden.
- **Schade**: hoe dichter bij het water, hoe meer: 60% (aan het water), 40% (2 tegels), 25% (3 tegels); een haven of scheepswerf +20%; een vloedgolf ×1⅓. Een beschadigd gebouw werkt trager (50% schade = cyclus 1,5× zo lang). Bij 100% is het **verwoest**: er blijft **puin** liggen (niets terug, voorraad weg), waar je pas weer kunt bouwen als je het puin sloopt of na 5 minuten. Een bouwplaats verliest de helft van zijn voortgang. Het HQ wordt nooit verwoest (max. 90%).
- **Dijk** (nieuw gebouw, tab Opslag, ontgrendeld met *Scheepvaart*): **1 plank + 2 blokken**, bouwtijd 14 s, alleen aan de oever. Beschermt alles binnen **5 tegels**: één dijk houdt **driekwart** van de schade tegen, twee dijken **alles**. De dijk zelf vangt 15% (vloedgolf 30%) per vloed op en kan ook hersteld worden. Bij het plaatsen zie je het beschermde gebied groen op de grond; in het infopaneel staat het bereik.
- **Herstellen**: het infopaneel van een beschadigd gebouw toont de schade en een knop **Herstellen** (per 25% schade 1 plank, per 50% 1 blok; 0,3 s per procent). Tijdens het herstel blijft het gebouw werken.
- **AI**: een AI met een haven zet er twee dijken bij (als ze 2 planken en 3 blokken heeft) en herstelt beschadigde gebouwen; verder bouwt ze gewoon door.
- **Opslaan**: vloeden, waarschuwingen, schade, herstel en puin zitten in de save. Oude saves laden gewoon (zonder vloeden); nieuwe spellen uit het menu hebben vloeden.
- **Gebeurtenissignalen** voor de meldingskaarten (de interface koppelt ze later): o.a. kamp gezien, eerste etherkristal, rivaal gezien, tekort, water in je gebied, aanval/afgeslagen, gebouw veroverd/verloren, plundertocht onderweg, vloedwaarschuwing, dijk klaar.
- Fix test `test_season_visuals` (rookpluimen volgen het grafische profiel).
- Tests: `test_m18_3_floods` (schema, waarschuwing dan schade, verwoest + puin, dijk 1 en 2, herstel, save/load + oude save, AI met haven, 1 vs 8 draden, signalen).

### Onverwacht/UI
- Winter beter leesbaar: meren en zee worden in de winter diep leisteen/teal (bevroren ijs ook donker) en zijn duidelijk donkerder dan het besneeuwde land. Langs de kust ligt een bleke ijsrand met een smalle, donkere natte lijn.
- Sneeuw is minder blauw: een neutraal gebroken wit op land, bomen, gras en wegen. De winterlucht en het licht zijn zachter en minder blauw.
- Ertsheuvels in de sneeuw krijgen alleen een sneeuwkapje, zodat grijze rots en ertskleur zichtbaar blijven. Ze zijn ook minder eentonig: 3 vormvarianten, een eigen draaiing, een lichte kanteling, verschillende maten en een kleine kleurvariatie.
- Verhaalteksten: elke bouwkaart begint zijn tooltip met een korte verhaalregel ("Velt bomen en levert stammen."), en het infopaneel toont onder de naam een korte beschrijving van het gebouw (nl/en).
- Meldingskaarten rechtsonder: belangrijke gebeurtenissen (gebouw klaar, nieuw seizoen, koude huizen, schip te water of gezonken, plundertocht gelukt of mislukt, uitgeput werkgebied, onderzoek klaar, druk paadje, handel, winst en verlies) verschijnen als kleine kaart met icoon, titel en tekst. Gewone kaarten verdwijnen na 6 seconden; belangrijke (winter, koud huis, gezonken schip, einde spel) blijven staan tot je erop klikt. Hooguit 3 tegelijk. De kleine meldingen blijven zoals ze waren.

## 0.18.2.1 — Limieten, mijnen op de berg, terug naar het HQ en een levende roadmap (2026-10-28)
Wensen van Mike.
- **Invoerbuffer begrensd**: bij verwerkende gebouwen (zaagmolen, steenhouwerij, smederij, kazerne) wachten nooit meer dan **6** invoergoederen (grondstof, voedsel en brandstof samen, in het gebouw of al onderweg). Zit het vol, dan brengen de dragers niets meer tot er weer minder ligt; het infopaneel toont 'Invoer vol (6/6)'. De bestaande regel (per goed tot 2× het recept: zaagmolen 2 hout, steenhouwerij 4 steen) blijft, dus de balans verandert niet.
- **Productielimiet per gebouw**: in het infopaneel van elk productiegebouw staat 'Productielimiet' met **−/+** (stappen 0, 5, 10, 15, 20, 30, 40, 50, 75, 100, standaard **onbeperkt**). Haalt je voorraad van het product de limiet, dan pauzeert het gebouw met de status 'pauze: limiet N bereikt' en de werker blijft thuis; zakt de voorraad eronder, dan gaat het vanzelf verder. De limiet wordt opgeslagen; oude saves laden gewoon (onbeperkt).
- **Terug naar het HQ**: **Home** en **spatie** zetten de camera op je HQ, en er is een **huisknop** in de bovenbalk (naast pauze) die altijd werkt. **H** blijft het handelsscherm. Pauze zit nu op **P** (en de Pause-toets) en de pauzeknop. Oorzaak dat Home/spatie niet werkten: een knop met focus slikte de toets; de sneltoetsen worden nu vóór de interface afgehandeld, op de fysieke toets (AZERTY en QWERTY gelijk), en niet als je in een tekstveld typt.
- **Mijnen op de berg**: ertsmijnen en kolenmijnen mogen nu **op** een bergtegel of ader staan, niet alleen aan de voet (de vlag blijft op begaanbaar land; geen hellingslimiet voor de mijn zelf). Andere gebouwen blijven van de berg af. De AI houdt voorlopig het oude gedrag (AI-update 0.21).
- **Lopers om bomen en rotsen heen**: bouwers en lastdragers van gebouwen zonder weg lopen niet meer door bomen of rotsen. Een boom of rots telt als ~8 tegels omweg; is de omweg langer, dan wordt het obstakel eerst gekapt of geruimd (3 s per obstakel, het hout of de steen gaat naar je HQ) en pas daarna vertrekt er iemand. Het olifantenpaadje vormt zich dan iets trager. Deterministisch, ook met meerdere werkdraden; de AI houdt het oude gedrag.
- **'Wat is er nieuw' altijd actueel**: bij het openen haalt het menu de nieuwste wijzigingslog en de roadmap op van GitHub (`LTGmaster/kolonie-releases`, `CHANGELOG.md` en `ROADMAP.md`, time-out 4 s). Offline of bij een fout blijft de ingebouwde tekst staan. `tools/release.sh` zet bij elke release beide bestanden in die repo (`tools/sync_news.sh`, de roadmap komt uit de sectie 'Binnenkort').
- **Werkgebied zichtbaar**: klik je op een gebouw, dan licht zijn werkgebied zacht op de grond op (houthakker, bosbouwer, steengroeve, mijn, visser, waterdrager), en boven het hoofd van zijn werker staat een klein geel **!** zolang het gebouw geselecteerd is. Verder geen visuele wijzigingen.
- Tests: `test_m18_2_1_features` (invoerbuffer, limiet pauzeren/hervatten + save/load + oude save, mijn op de berg, veldroute om een boom en een muur van bomen, sneltoetsen, roadmap-samenvoeging, werkgebied, determinisme 1 vs N draden).

## 0.18.2 — Uitbreiden loont: grotere grenzen, goedkopere wachtposten, rijkere aders (2026-10-27)
Wens van Mike: meer nadruk op uitbreiden. Wie zijn gebied laat groeien krijgt nu meer terug.
- **Grensgebouwen goedkoper en sterker**: de **wachtpost** claimt straal **9 → 12** (oppervlak ×1,8) en kost **2 planken + 1 blok → 1 plank + 1 blok**, bouwtijd **20 → 16 s**. De **wachttoren** claimt straal **14 → 20** (oppervlak ×2,0, nu groter dan het HQ-gebied) en kost **4 planken + 4 blokken → 3 + 3**, bouwtijd **40 → 32 s**. Het garnizoen blijft 1 (wachtpost) en 3 (toren) ridders. De techniek 'Uitkijkposten' geeft nog steeds +2 straal. Het gebied rond het HQ (straal 14) en de startvoorraad zijn niet veranderd: je start precies zoals voorheen.
- **Pioniersbonus**: claimt een wachtpost of toren bij de eerste bezetting veel nieuw land (tegels die van niemand zijn), dan komt er materiaal in het HQ: vanaf **100 nieuwe tegels +1 plank**, vanaf **500 +1 blok**, vanaf **900 +1 plank extra**. Een wachtpost aan de rand levert zo 1 plank terug, een toren die vooral nieuw land opent tot 2 planken en 1 blok. Je krijgt een melding ('Pioniersbonus voor nieuw land'). Veroverde gebouwen en bouwwerken binnen je eigen gebied geven niets, dus slopen en opnieuw bouwen levert geen winst op. De AI krijgt dezelfde bonus.
- **Rijkere grondstoffen verder van het HQ** (oneindige kaart): hoe verder een ader van het HQ ligt (per chunk van 32 tegels, tot 12 chunks), hoe meer er zit. Steen **10 → 32** per tegel, kolen **14 → 47**, erts **16–19 → 74** (was max. 52), etherkristal **4 → 7**. In de eerste chunk rond het HQ (het startgebied) blijft alles precies zoals het was. Het gaat alleen om de hoeveelheid, niet om waar een ader ligt: kaarten, seeds en bestaande saves blijven kloppen (de vaste 48×48-kaart is ongewijzigd). Gemeten gemiddelde per tegel (seed 42): steen 11,5 → 18,0 → 30,0 en erts 24,6 → 39,0 → 69,0 op 1, 5 en 11 chunks van het HQ.
- **Aanvalsbereik mee omhoog**: een eigen militair gebouw kan nu doelwitten tot **30 tegels** ver aanvallen (was 24), in de pas met de grotere claimstralen (toren 14 → 20). Het geldt voor jou én voor de AI en staat in het gebouwpaneel ('binnen 30 tegels'). Zonder dit konden twee AI's op afstand 44 elkaar met de grotere gebieden niet meer bereiken en eindigde een partij niet meer.
- **AI past zich aan**: de AI krijgt dezelfde lagere kosten, grotere stralen, pioniersbonus en aanvalsbereik, en bouwt een wachttoren nu zodra ze 4 planken en 4 blokken heeft (was 5 blokken, 5 planken bij dreiging; de toren kost nu 3 + 3). In de test (15 min, normaal, seed 42) bezet de AI 4 grensgebouwen (straal tot 20) en krijgt 3 pioniersbonussen.
- **Geen kwaliteitsverlies**: geen visuele wijzigingen, dezelfde modellen, shaders en effecten (ertsontsluitingen tonen bij rijke aders gewoon het maximum). Alleen eigen code en CC0-assets.
- Tests: `test_m18_2_expansion` (claimstralen en kosten, rijkdom groeit met afstand voor 3 seeds, startgebied en vaste kaart ongewijzigd, pioniersbonus in het spel, zelfde seed = zelfde state-hash met AI, AI breidt uit); `test_m17`, `test_m16` en `test_m17_6` bijgewerkt voor de nieuwe torenkosten en hoeveelheden; `test_m17_6` (AI-staptijd) draait nu in de seriële groep van `tools/runall_par.sh`, omdat de drempel van 60 ms onder parallelle belasting niet haalbaar is.
### Onverwacht/UI (0.18.1.1, samengevoegd)
- **'Zonder weg' netjes in de bouwbalk** (ui/zonder-weg-uitlijning, screenshot van Mike: "dit lijkt me niet te kloppen qua uitlijning"): de schakelaar met uitleg
  hing als los, breed paneel boven de bouwbalk en overlapte die. Nu is het een slanke rij bovenaan de bouwbalk, in dezelfde stijl als de annuleer-hint: even breed
  als de tabstrook, dezelfde linkerrand, 6 px tussenruimte en geen overlap; de balk groeit omhoog mee. De annuleer-hint vult dezelfde breedte. Geen vaste
  breedtes: de tekst breekt af als het Engels langer is. Alleen weergave (`ui/paden_ui.gd`, `ui/hud.gd`), geen logica.
- **Kortere tekst**: alleen de korting ("−12,5% goedkoper"); de kosten pas als ze afwijken ("−12,5% · 2 planken i.p.v. 3", de grondstofnaam één keer). Eerder
  stond er "kosten 2 planken (normaal 2 planken)". Keys `BUILD_ROADLESS_AVG` (korter), `BUILD_ROADLESS_PCT` en `BUILD_ROADLESS_PCT_TIP` (nl/en). Shots:
  `kolonie-ui-shots/zonder-weg/` (contactsheet.png).

## 0.18.1 — Meer processorkernen, aanpassing aan je pc, wegen om bomen en rotsen (2026-10-27)
- **Multithreading, deterministisch**: het zware zoekwerk in de simulatie draait nu op meerdere processorkernen (WorkerThreadPool): de plekscores en voorfilters van de AI-zoektocht en de veldroutes (Dijkstra) van gebouwen zonder weg. De werkdraden lezen alleen; de resultaten worden in vaste volgorde toegepast. Daardoor geeft dezelfde seed exact hetzelfde spel, of je nu 1 of 20 threads hebt (nieuwe test: zelfde state-hash bij 1 en 8 draden). Gemeten (8000 ticks, 2 AI's): 17,2 s → 12,7 s rekentijd (−26%).
- **Systeemaanpassing**: bij de start leest het spel het aantal CPU-threads en de videokaart (naam, fabrikant, geïntegreerd of laptop) en kiest het aantal werkdraden (bv. i7-12700 met 20 threads → 12) en bij de eerste start het grafisch profiel: sterke losse kaart (zoals RTX 3080 Ti) → Hoog, laptop-GPU → Middel, geïntegreerde GPU → Laag/Middel. Een eerder gekozen profiel blijft staan. Alles staat in `kolonie_detail.log` (`[Sys]`-regel).
- **Wegen niet meer door bomen en rotsen**: je eigen wegen en automatische paden lopen eromheen als dat kan. Ligt er toch een boom of rots op de route, dan wordt die eerst gekapt of geruimd (1 s extra per obstakel); het hout, de steen of de kolen gaan naar je HQ. De AI houdt voorlopig het oude wegengedrag (de AI-update volgt in 0.21).
- **Fix 'Meteen een weg'** (bug Mike): de knop deed vaak niets. Het looppad van een gebouw zonder weg loopt meestal over een stukje bestaande weg of langs een losse vlag; dat traject werd geweigerd, zonder melding. Nu wordt de weg aangelegd tot de eerste aansluiting op het net (zo nodig met een nieuwe vlag op de weg, losse vlaggen onderweg worden knooppunten). Lukt het niet, dan zie je de reden (in de dialoog of als melding). De dialoog meldt ook hoeveel bomen/rotsen eerst geruimd worden. Test: `test_m18_1_direct_road`.
- **Geen kwaliteitsverlies**: dezelfde shaders, schaduwen en anti-aliasing. Het vooraf bakken van de terreinruis is getest maar níet ingevoerd: de pixeldiff (gemiddeld 2,4/255, 2,1% pixels met een zichtbaar rasterpatroon) lag boven het ruisniveau.
### Onverwacht/UI (0.18.0.5, samengevoegd)
- **Ertsontsluitingen in de bergen** (ui/erts-ontsluiting, wens van Mike, "ietsje zachter"): op grondstoftegels steken nu kleine,
  half in de rots verzonken facetbrokken uit de berg/klifwand met wat puin eronder: kolen donkergrijs/zwart, erts roestig met
  een zilverig brokje, steen lichtgrijze blokjes, etherkristal zacht blauwviolette kristallen (geen gloed). Gedempte kleuren,
  dichtheid volgt de resterende hoeveelheid (uitgeput = weg). Eén MultiMesh per soort per chunk (`gfx/ore_outcrops.gd`),
  sneeuw via de bestaande `season_snow`. Ze **vervangen de oude grondstofrotsen** (steen-/ertsrots, `SeasonKit.coal_rock`,
  `EtherKit.crystal_rock`): één verzonken rotsmassa van berggesteente met de gekleurde brokken erin, ongeveer de voetafdruk van
  de oude rots; decoratieve bergkeien blijven. Na review (v3): per tegel één compacte, deels verzonken rotsheuvel in koel
  berggrijs met duidelijk uitstekende brokken (kolen matzwart met blauwgrijze glans, erts roestrood, steen lichte gezaagde
  blokken, ether zachte kristallen), weinig los puin, een lichte donkere/roestige grondvlek onder kolen/erts; kleiner bij minder voorraad. Alleen weergave; leest `Sim.res_at`/`Sim.amount_at`. Test: `tests/test_ore_outcrops.gd`.
- **Bezettingsbadge** (ui/markers-dialoog): het oranje '!' boven gebouwen met te weinig kolonisten is nu een klein bronzen schildje met een kolonistenhoofd en "aanwezig/nodig" (bv. 0/1), zacht deinend en vervagend met de cameraafstand (vanaf 26, weg na 60). Alleen Sprite3D/Label3D zonder collision, dus klikken gaan er doorheen. Data blijft `Sim.building_staffing`/`understaffed_buildings`/`Events.staffing_changed`.
- **Dialoog 'Meteen een weg?'** in de RS-stijl: korte uitleg, lengte in tegels en de kosten nu en later als grondstofchips met icoon (rood bij te weinig voorraad, met melding), een duidelijke accentknop "Weg aanleggen" en "Zonder weg" (`ui/direct_road_dialog.gd`). Test: `tests/test_markers_dialoog.gd`.

## 0.18.0.4 — Geen haperingen meer bij het verkennen (2026-10-27)
- **Minder pieken in de frametijd**: nieuwe stukken kaart worden niet meer in één keer gebouwd. De opbouw van terrein, bomen en rotsen krijgt per frame maximaal 5 ms, en de zwaarste stap (normalen en tangenten van het terrein) draait op een aparte processorkern (WorkerThreadPool). De oude mesh blijft staan tot de nieuwe klaar is, dus je ziet geen gaten. De simulatie merkt er niets van: dezelfde seed geeft hetzelfde spel.
- **Shaders vooraf geladen**: tijdens het laadscherm worden alle gebouwen, de bouwplaats, bomen, rotsen, rook en het vaandel één keer onzichtbaar getekend. Daardoor hapert het spel niet meer de eerste keer dat je zo'n object ziet.
- **Geen kwaliteitsverlies**: dezelfde shaders, schaduwen en anti-aliasing als in 0.18.0.3.
- **Fix**: etherkristal-tegels gaven bij het tekenen van de kaart een foutmelding per tegel (te kleine kleurtabel). Die meldingen kostten ook tijd. Het beeld verandert niet.
- **Prestatielog**: elk frame boven 50 ms komt met een `[Spike]`-regel in `kolonie_detail.log`, met wat er in dat frame gebeurde (chunk-opbouw, sim-ticks, wegen/pathfinding, rest = render/engine). De `[Perf]`-regel telt `frames>50ms`.
- Gemeten in de testrenderer (seed 42, camera schuift over de kaart, sim x4): max frametijd 720 → 171 ms, p99 364 → 101 ms. Nieuwe meethulpen: `tools/spike_bench.gd` en `tools/frametime_bench.gd`. Test: `test_m18_0_4_spikes`.

## 0.18.0.3 — Minder werk voor de videokaart, zelfde beeld (2026-10-26)
- **Tot 78% minder driehoeken per frame** zonder zichtbaar verschil. Gebouwen, bomen en rotsen (ook de gedetailleerde fotoscans op Hoog) krijgen automatische detailniveaus (LOD). De videokaart tekent een eenvoudiger versie alleen als het verschil kleiner is dan een pixel, en ook voor de schaduwen. Gemeten in een dorp met een AI: uitgezoomd 1,66 M → 0,58 M primitives, half ingezoomd 15,5 M → 3,5 M. De frametijd in de testrenderer is 30–57% lager. Een pixeldiff vóór/na geeft gemiddeld minder dan 1,4/255 verschil, en dat komt vooral van wuivend gras en golven.
- Nieuwe meethulpen: `tools/gpu_bench.gd` (frametijd, draw calls, primitives, screenshots) en `tools/gpu_tris.gd` (driehoeken per soort object).

## 0.18.0.2 — Warmte in huizen, betere vlaggen en paden, rivieren overal (2026-10-26)
- **Warmte zichtbaar**: in het huispaneel zie je een warmtebalk (een thermometer van blauw naar oranje) met de resterende stooktijd en de brandstof (kolen, hout, planken). Boven een eigen woonhuis verschijnt een klein ❄-ijskristal zodra het in de winter te koud wordt; warme huizen krijgen niets. Nieuw: `Sim.house_warmth(id)` (0..1) en `Sim.house_heat_info(id)`.
- **Brandstof**: woonhuizen stoken kolen, hout of planken. Kolen zijn het efficiëntst (180 s per stuk, hout en planken 90 s). Dat staat nu in de melding, in de koude-huizen-chip en in het huispaneel. Je hebt dus geen kolen nodig om de winter door te komen.
- **Vlag op een weg**: de weg werd altijd al in twee stukken gesplitst, elk met een eigen drager, maar je merkte het niet. Nu hoor je een geluid en krijg je een melding. In de test verdubbelt de doorvoer (11 → 23 goederen in 120 s).
- **Pad → weg**: ingesleten paden met schuine stappen of omwegen kunnen nu een weg worden. De preview toont altijd de route, of een duidelijke reden waarom het (nog) niet kan.
- **Rivieren door het hele land**: de zone van 45 tegels zonder bronnen rond de start is weg. Rivieren ontspringen nu ook landinwaarts, achter de start. Alleen de HQ-zone (15 tegels) blijft droog: rivieren buigen eromheen, en het vaste bosje en de steen bij de start blijven bereikbaar. **Let op: nieuwe kaarten in watermodus zien er daardoor anders uit**; oude saves en vaste kaarten veranderen niet.
- **Vismeertje**: in ongeveer de helft van de seeds ligt een klein meertje met vis op 15 tot 30 tegels van de start, zodat je vroeg een visser kunt zetten (deterministisch per seed).
- **Prestatielog verbeterd**: de `[Perf]`-regel noemt nu de echte status (menu, spel of pauze; voorheen stond er in het hoofdmenu ten onrechte "(pauze)"), het aandeel frames in de 15-FPS-stand, en de draw calls, primitives en het videogeheugen van de renderer.
- **Updates sneller gevonden**: het spel zoekt elke 10 minuten naar een update (was 30), en ook bij het openen van het hoofdmenu of het pauzemenu, hooguit om de 2 minuten.
- Tests: `test_m18_0_1_house`, `test_m18_0_1_flag`, `test_m18_0_1_track`, `test_m18_water` (droge HQ-zone, vijver, rivieren landinwaarts), `test_updater` (interval en cooldown).

## 0.18.0.1 — Hotfix: minder zwaar voor de GPU (2026-10-26)
- **Oorzaak**: het spel had geen FPS-limiet (`Engine.max_fps` = 0) en dwong vsync niet af. Zet de driver vsync uit, dan tekende het spel zoveel frames als de GPU aankon, ook in het hoofdmenu, in het pauzemenu en met een geminimaliseerd venster. Daardoor liep zelfs een RTX 3080 Ti op ongeveer 90%. Daarnaast kreeg elke GPU standaard Middel (schaduw, 2x MSAA, volle resolutie), ook een laptop-GPU.
- **vsync staat standaard aan** en er is een **FPS-limiet**: standaard 60, in te stellen op 30, 60, 120 of onbeperkt.
- **15 FPS bij pauze, focusverlies of een geminimaliseerd venster** (`GfxSettings.FpsGovernor`).
- **Grafische profielen Laag/Middel/Hoog** bepalen de schaduw, MSAA (uit/2x/4x), renderschaal (75%/90%/100%), de hoeveelheid stof- en rookdeeltjes en hoe ver gras, bomen, rotsen en gebouwen zichtbaar zijn. Uitgezoomd tekent Laag hooguit 7×7 in plaats van 9×9 chunks, en bomen en rotsen ver weg worden niet meer getekend (voorheen geen zichtafstand).
- **Eerste start**: het spel herkent een geïntegreerde of zwakke GPU (`RenderingServer.get_video_adapter_name()`). Intel HD/UHD en software-renderers krijgen Laag, Intel Iris/Xe, Radeon Graphics en Vega krijgen Middel. Andere GPU's houden Middel. De keuze wordt bewaard in `user://settings.cfg` (`[graphics]`).
- **Instellingen**: profiel, vsync en FPS-limiet staan in het hoofdmenu en in het pauzemenu (nl/en). MSAA, renderschaal en FPS-limiet gaan meteen in; modellen en texturen wisselen vanaf het volgende spel.
- **Spelsnelheid x4: geen burst van ticks meer.** De simulatie houdt een vaste tijdstap, maar besteedt per frame hooguit 8 ms aan ticks (minstens één tick per frame). Wat niet past, schuift door naar de volgende frames. De achterstand is begrensd op 40 ticks, dus een trage pc raakt niet in een inhaalspiraal. Alleen het tijdstip van de ticks verandert, niet hun volgorde, dus de partij blijft deterministisch (zelfde state_hash).
- **Prestatielog**: `user://logs/kolonie_detail.log` krijgt bij de start een regel met de videokaart, de renderer, het grafische profiel, vsync, de FPS-limiet en het aantal CPU-threads. Daarna volgt elke 10 s een `[Perf]`-regel met de FPS, de gemiddelde en maximale frametijd, de simulatieticks per frame (gemiddeld en maximaal), de spelsnelheid en het aantal objecten in beeld. In het pauzemenu opent de knop **Open logmap** (en: Open log folder) die map.
- De simulatie zelf verandert niet: de grafische opties zijn alleen weergave en alles blijft deterministisch.
- Nieuwe test `tests/test_m18_0_1_gfx.gd` controleert de profielen, de GPU-detectie, het bewaren en teruglezen, de FPS-limiet en de 15 FPS bij focusverlies en pauze.

## 0.18.0 — Water: zee, rivieren, meren en eilanden (2026-10-26)
- **Water** (wens van Mike): nieuwe oneindige kaarten krijgen een grote zee, rivieren en meren (`worldgen/water_gen.gd`, `WaterGen`).
  - **Zee**: ligt voorbij een golvende kustlijn, op ongeveer 155 tot 245 tegels van het startpunt, in een richting die de seed bepaalt. In de zee ligt af en toe een **eiland**.
  - **Rivieren**: een grof rooster van knopen (48 tegels). Elke knoop stroomt naar een buurknoop die dichter bij de zee ligt, dus er zijn geen lussen en elke rivier mondt uit in de zee. Rivieren worden breder naar de kust toe en hebben geen voorden meer, zodat boten ononderbroken kunnen varen.
  - **Meren** liggen altijd op een rivier en zijn dus via het water met de zee verbonden.
  - Bronnen liggen pas op minstens 45 tegels van het midden. Het startgebied blijft daardoor droog en bouwbaar, en er staat altijd een bosje en wat steen bij het HQ. Binnen een straal van 128 tegels is ruim 90% bouwland (getest: minimaal 55%).
  - **Boten en handelsschepen** varen over rivieren tussen meren en zee. Vindt `Naval.water_path` binnen de gewone kader geen route, dan zoekt hij in watermodus opnieuw met een ruimere kader (160 tegels).
  - **Vissers** werken op rivieren, meren en zee.
  - De watermodus staat in `world["water"]` en gaat mee in de save. Vaste kaarten, oude saves en `Sim.new_game` zonder `opts.water` blijven precies zoals ze waren (zelfde checksums en state_hash). Het hoofdmenu zet de watermodus aan voor nieuwe oneindige kaarten. Alles blijft deterministisch per seed en onafhankelijk van de draad.
  - Kosten: een chunk maken duurt ongeveer 13 ms in plaats van 10,5 ms (op een werkdraad; zie PERF_NOTES).
- Nieuwe test `tests/test_m18_water.gd`: determinisme, verbondenheid via water, meren, zee, eilanden, aandeel land, bootroute van meer naar zee, hout en steen bij de start (ook met 3 AI), vis op rivier en zee, save en kosten per chunk.

## 0.17.7 — Slanker bouwmenu en bovenbalk (2026-10-26)
### UI: bouwmenu en bovenbalk verfijnd (ui/menu-verfijnd, wens van Mike: "lomp")
- Slankere RS3-achtige stijl, via het thema (`ui/theme_builder.gd` → `ui/kolonie_theme.tres`, nieuwe varianten `BarButton`, `BarSeparator`, `BuildPanel`, `BuildTabStrip`, `BuildCard`; `BarPanel`, `ChipPanel`, `TabButton` herzien) i.p.v. losse overrides.
- **Bovenbalk**: één smalle doorschijnende donkere strook met gouden haarlijn; grondstoffen als compacte pillen (icoon 20 px + getal, tooltip); secties gescheiden door subtiele gouden scheidingslijntjes; kleinere platte pauze/snelheid/vensterknoppen (iconen 18 px).
- **Bouwmenu**: categorietabs als kleine pillen vast aan het paneel; gebouwen als kaarten met het 3D-icoon voorop (groter: 62 px i.p.v. 56) en de naam klein eronder (autowrap per woord, breedte volgt het langste woord, geen vaste tekstbreedte); hover = gouden gloed + lift, actief = gouden kader, vergrendeld = grijs met gouden slotje-badge.
- Screenshots voor/na: `tools/menu_verfijn_shots.gd -- <map> <nl|en> <B> <H> <prefix> [tabs]`.

## 0.17.6.1 — Hotfix: AI bouwt weer woonhuizen, beter klikken op gebouwen (2026-10-26)
- **AI bouwt weer woonhuizen** (test_m11 `test_ai_fisher`, seed 42, ai_dist 44). De oorzaak was geen hangende zoektocht en ook geen etherkristal: met 0.17.6 stap 1e (vóór etherkristal) verloopt de partij precies hetzelfde als op main. Door de verdeelde zoektocht beslist de AI een paar ticks later, waardoor de partij anders verloopt. Daarbij raakten de steengroeven van de AI uitgeput. Een uitgeputte groeve telde nog mee in de knelpuntregel (`groeven <= steenhouwerijen`), dus de AI zette nooit een nieuwe. Zonder blokken wachtte het bouwplan eindeloos op de mijn, bleven er vrije kolonisten over (meer dan 2) en kwam de woonhuisregel nooit aan de beurt. Nu sloopt de AI per beslissing één uitgeputte steengroeve (geen steen meer binnen de straal), net als een speler dat zou doen. Na 30 min heeft de AI 2 woonhuizen (bevolking 44/46). De verdeelde zoektocht, de budgetten en de AI-piek blijven ongewijzigd, en het verloop blijft deterministisch. Diagnose: `tools/diag_house.gd`.
- **Klikken op gebouwen** (wens van Mike): de muis rekent nu met het echte terrein in plaats van met een vlak op hoogte 0,1. Een klik op een heuvel komt daardoor op de juiste tegel terecht, ook bij het plaatsen in de bouwmodus. Een klik op het gebouwmodel zelf (ook op het dak) selecteert dat gebouw (AABB per model, `gfx/pick.gd`). Het gebouw onder de muis licht op.
- **Directe weg per tegel** (wens van Mike): kost nu `ceil(lengte / 3 × DIRECT_ROAD_COST_FACTOR)` planken, met minimaal 1 plank (korte wegen zijn niet meer gratis). Een langere weg is dus duidelijk duurder. De dialoog toont de lengte in tegels en de kosten. Het later opwaarderen van een ingesleten pad blijft even duur.
- **Melding "geen grondstof meer"** (wens van Mike): vindt een houthakker, steengroeve, mijn, visser of kolenmijn niets meer in zijn werkgebied, dan verschijnt een klikbare melding die naar het gebouw springt en het infopaneel opent, met een ⚠-icoon boven het gebouw. Backend: `Sim.depleted_buildings(speler)` en `Events.building_depleted(building_id, resource)`. Dat event gaat één keer af per uitputting en pas opnieuw nadat het gebouw hersteld is. Waterputten en waterdragers raken niet uitgeput (grondwater/oever) en een jager bestaat (nog) niet. Teksten in nl/en.
- **Ingesleten pad omzetten in een weg** (bug gemeld door Mike): bij een pad dat 100% ingesleten was, verscheen er geen route en werd de weg soms niet aangelegd. Het veldpad kon over bestaande wegen of vlaggen lopen, en `track_to_road` weigerde dat traject. Nieuw is `Sim.track_preview`: die kort het traject in vanaf de gebouwvlag tot de eerste vlag of weg (zo nodig met een nieuwe vlag op die weg), en `track_to_road` legt precies dat traject aan. In het gebouwpaneel toont "Maak er een weg van" eerst het traject: de route licht op, met de lengte en de kosten erbij. De weg wordt pas aangelegd na **Bevestigen**.
- Nieuwe test `tests/test_m17_6_1.gd`; `tests/test_m17_5.gd` volgt de nieuwe kostenregel.

## 0.17.6 — Etherkristal en een vlottere AI (2026-10-26)
- **Etherkristal** (`"etherkristal"`, `Sim.RES_ETHER`, kaartlaag `WorldGen.RES_ETHER`): een nieuwe, zeldzame en "magische" grondstof die nodig is voor de hogere technologieën.
  - **Vindplaatsen**: op oneindige kaarten krijgt ongeveer 7% van de chunks buiten het startgebied (minstens 2 chunks van het midden) een kleine ader van 1 tot 9 tegels met elk 4 kristallen. Vaste kaarten blijven ongewijzigd. Een **ertsmijn** mag naast een vindplaats staan, ook als er geen erts in de buurt is, en delft daar elke derde cyclus een kristal.
  - **Roverskampen**: ongeveer 30% van de kampen heeft 1 tot 3 etherkristallen in de buit.
  - **Bijproduct**: elke ertscyclus van een ertsmijn heeft 3% kans op een kristal. Die kans is deterministisch (uit het gebouw-id en de tick) en gebruikt de sim-RNG niet.
  - **Handel**: etherkristal is verhandelbaar via het handelshuis en de markt. Steden hebben er weinig van (doelvoorraad 6, basisprijs 400), dus het is duur. De specialiteiten van de steden blijven dezelfde.
  - **Techkosten**: Wachtbereik, Ridders III, Zeehandel en Transportband I kosten elk 1 kristal, Transportband II kost er 2 en Transportband III 3 (samen 9). De basistechs kosten geen etherkristal. Heeft de AI te weinig kristallen, dan slaat ze zo'n tech over en wacht ze niet.
  - **Weergave**: er is een placeholder-icoon en een placeholder-model (rots met blauwe kristallen) in `gfx/ether_kit.gd` (`EtherKit`). UI & Graphics vervangt die later. Vertalingen in nl en en (`RES_ETHERKRISTAL`, `RES_ETHERKRISTAL_DESC`).
- **Geen AI-pieken meer**: de AI zocht haar bouwplek in één tick, wat 27 tot 37 ms kostte (met uitschieters tot 199 ms tijdens het werk). Nu loopt de zoektocht over meerdere ticks, met een vast budget per tick: 5 ticks voorbereiden (chunks laten maken op een werkdraad), 60 kandidaten scoren per tick, 24 controles per tick, en per tick één plaatsing of wegpoging. Daarbij komen een plekcache per chunk (helling, erts in de buurt) en één controle per beslissing voor de upgrade van veldpaden. In het profiel (40 min AI tegen AI) daalt de grootste AI-piek per tick van 33,3 ms naar 11,4 ms. Het aantal ticks boven 16 ms daalt van 11/23/18/37 naar 1/0/0/1 per venster van 10 min.
  - De state_hash verandert **bewust**: de AI beslist nu een paar ticks later, zodra de zoektocht klaar is, en etherkristal wijzigt de kaart en de buit. Het verloop blijft deterministisch: dezelfde seed geeft dezelfde hash, ook na opslaan en laden midden in een zoektocht (die toestand zit in de save).
- Nieuwe test `tests/test_m17_6.gd`.

## 0.17.5 — Directe wegen, sneltoets Home en minder haperingen (2026-10-26)
- Bevat de hotfix 0.17.4.1 (zie hieronder).
- **Minder haperingen in lange partijen**: de tijd per simulatietick groeide met de speelduur (na 40 min ~5,8 ms, nu ~3,2 ms). Dragers op volle vlaggen zochten niet langer kwadratisch naar goederen, het zoeken naar bomen, stenen en vis sorteert niet meer bij elke aanroep, de verdeling slaat goederen zonder voorraad over en het gras bouwt bij een nieuw paadje alleen de omgeving opnieuw op. Het spelverloop blijft identiek (zelfde state_hash); nieuwe test test_perf_long.
### Onverwacht/UI: winterkust beter leesbaar (ui/winter-kust, wens van Mike)
- In de winter waren sneeuw en water moeilijk uit elkaar te houden. Alleen weergave (`gfx/terrain.gdshader`), geen sim/worldgen/data aangepast.
- **Winterwater** wordt donkerder en verzadigder blauw (`c_water_winter`, `winter_water_mix`, gemengd op `max(season_snow, season_ice)`); open ijs krijgt ook een blauwere tint in plaats van sneeuwwit.
- **IJsrand en ijsschotsen** langs de kust (`ice_rim_width`, `c_ice_rim`): goedkope ruis in een smalle band van het kustmasker.
- **Natte kuststrook**: op land verdwijnt de sneeuw in een smalle band langs de waterlijn en blijft donkere natte aarde/steen over (`shore_snow_free`, `shore_wet_strength`, `c_wet_shore`); in de zomer heel licht.
- **Witte waterlijn**: een dunne contrastlijn op de waterlijn in alle seizoenen, sterker in de winter (`waterline_strength`, `waterline_winter`).
- Nieuwe test `tests/test_winter_shore.gd`; screenshots met `tools/winterkust_shot.gd -- <uit.png> <1|3>`.
### Onverwacht/UI (ui/roverskampen)
- **Plunderpaneel**: klik op een roverskamp (een van de 3x3 kamptegels, via `Sim.bandit_camp_at`) en er opent rechts een paneel in de RS-stijl (`ui/raid_panel.gd`, `RaidPanel`). Het toont de status (bewoond / geplunderd), de verdedigers (`x van y` + balk), de buit met grondstoficonen en het aantal beschikbare ridders (`Sim.raid_attackers_available`). Met een schuifbalk + invoerveld kies je hoeveel ridders je stuurt en met **Plunderen** gaat de tocht weg (`Sim.raid_bandit_camp`).
  - Fouten (bijv. al geplunderd, geen ridders, geen pad) komen uit `tr(Sim.error_key(code))`; de knop staat uit zolang `Sim.can_raid` geen `ERR_OK` geeft.
  - Live op `Events.bandit_camps_changed` en `Events.bandit_camp_raided`: na de tocht staat de uitkomst in het paneel ("Gelukt! Buit: …" of "Mislukt: de rovers hielden stand (nog n verdedigers)") en als melding. Esc of het kruisje sluit het paneel.
  - Alle tekst via `UI_RAID_*` (nl/en) in `i18n/kolonie.csv`, met autowrap en zonder vaste knopbreedtes. In `scenes/game.gd` staat er alleen één regel bij in de bestaande klik-/selectieflow.
- **Echte modellen voor de roverskampen** (`gfx/banditkit.gd`, `BanditKit`). Ze vervangen de placeholder in `gfx/bandit_layer.gd` en zijn procedureel low-poly in RS3-stijl:
  - een palissade van gepunte palen met een poort en een bord met een schedel;
  - twee tenten en een afdak met gerafeld en gelapt doek;
  - een kampvuur met een stenen kring, vlammen en een pot aan het spit, rook (dezelfde GPU-rookpufjes als de schoorstenen) en een flakkerend vuurlicht (`OmniLight3D`);
  - een wapenrek met speren, een zwaard en een bijl;
  - een schatkist met munten, kisten, een vat en zakken;
  - een gescheurde rode vlag en een rover met kap per verdediger.
- **Geplunderd**: de palissade heeft gaten en omgeduwde of verbrande palen, een tent is ingezakt, het vuur is uit (alleen as, geen licht of rook), de schatkist staat leeg en open met kapotte kisten ernaast, er zijn geen rovers meer en de vlag is grauw.
- Het model volgt de seizoenen: in de winter ligt er sneeuw op tentdoeken, palen en kisten via het gedeelde `rs_toon`-materiaal (`season_snow`).
- Nieuwe test `tests/test_raid_ui.gd` (paneel, foutteksten, uitkomst, taalwissel, modellen, licht, geplunderde staat). Screenshots: `tools/roverskampen_shots.gd`. Licenties: eigen werk, CC0 (`assets/LICENSES/README.md`).
### Onverwacht/UI
- **Bouwmenu met 3D-gebouwiconen** (wens van Mike): de knoppen in het bouwmenu tonen nu een gerenderd beeld van het echte 3D-model (vaste 3/4-camera, zacht licht, transparant, 128x128; `assets/icons/buildings/`, gemaakt met `tools/render_building_icons.gd` via xvfb-run). Nog niet ontgrendelde gebouwen zijn grijs met een tooltipregel; ontbreekt een PNG, dan valt de knop terug op de oude icoon. Test `test_build_icons`.
- **Eigen tab 'Wonen'** in het bouwmenu (vóór Opslag): het woonhuis staat niet meer onder Opslag.

### Spel/backend (backend/0175, wensen van Mike)
- **Sneltoets Home**: de camera springt naar je eigen HQ.
- **Te weinig kolonisten**: boven je gebouwen zonder kolonist staat een eenvoudig oranje "!" (`gfx/staff_markers.gd`); het verdwijnt zodra er iemand werkt.
- **Vergrendeld gebouw**: een klik erop in het bouwmenu opent de techboom op het onderzoek dat je ervoor nodig hebt (`TechTree.open_at`), met de naam van dat onderzoek in de tooltip.
- **Standaard zonder weg + directe weg**: een gebouw komt standaard zonder weg. Meteen na het plaatsen kun je een weg naar het wegennet laten aanleggen. Die kost 50% meer dan het ingesleten pad later opwaarderen (`Sim.DIRECT_ROAD_COST_FACTOR = 1.5`). Beide kosten staan in de vraag, en het gebouwpaneel heeft een knop "Meteen een weg".
- **Seed**: elk nieuw spel krijgt een willekeurige seed, ook als je het spel rechtstreeks start. Na het starten staat er meteen een nieuwe seed klaar; de knop 'Willekeurig' blijft.
- **Gebouwnamen in je taal**: alle gebouwnamen komen uit de `BLD_<id>`-sleutels (nl/en). Dat geldt in het bouwmenu, het infopaneel, de lijsten en de meldingen, en de namen veranderen mee als je van taal wisselt. Nieuwe test: `test_bld_names`.
- **Nieuwe API voor UI & Graphics**: `Sim.building_staffing(id)` geeft `{have, need}`, `Sim.understaffed_buildings(speler)`, `Events.staffing_changed(building_id)`, `Sim.hq_tile(speler)`, `Sim.building_lock_info(soort)` geeft `{locked, tech_id}`, `Events.raid_failed(camp_id, player, fallen, returned)`, een veld `raid_en_route` per kamp in `Sim.bandit_camps()` en `Sim.raid_win_chance(o, id, n)` met een kans van 0 tot 1. Verder `Sim.direct_road_info` en `Sim.build_direct_road`.
- **Minder pieken**:
  - Nieuwe handelssteden worden niet meer allemaal in dezelfde tick gezocht. Ze komen in een wachtrij en er wordt er hooguit één per 5 s verwerkt; de kaartstukken worden vooraf op een werkdraad gemaakt. Bij een gewoon speltempo verdwijnt zo de piek van ~64 ms.
  - Bij de AI zoekt het bouwplekken alleen nog op het raster en langs wegen. Het spelverloop blijft daarbij gelijk.
  - Gebouwen zonder weg zoeken geen looproute meer als er niets te brengen of te halen valt.
  - De state_hash verandert **bewust**, en alleen omdat nieuwe steden iets later verschijnen. Het spel blijft deterministisch: twee runs geven dezelfde hash (`test_m17_5`).
- Chunktaken op de achtergrond worden nu afgewacht bij een nieuw spel, bij het laden en bij het afsluiten. Dat voorkomt een geheugenfout bij het afsluiten.
- Nieuwe tests: `test_m17_5` en `test_m17_5_ui`.

## 0.17.4.1 — Hotfix: crash bij pad maken, updateknop (2026-10-26)
### Onverwacht/backend
- **Crash bij het maken van een pad of weg verholpen** (wegbouwmodus, `track_to_road`, wegupgrade): na een herstart in dezelfde sessie (spel → hoofdmenu → nieuw spel) bleven lambda-luisteraars van HUD en statistiekenpaneel aan `Events` hangen. Het volgende signaal (bv. `population_changed` of `stats_updated`) riep een verouderde Callable aan (`slot >= slot_max ... get_instance`) en het spel crashte. `Events.clear_scene_listeners()` koppelt ze nu los als het spel de scène verlaat (test_m17_4_1).
- **Updateknop altijd betrouwbaar**: de controle draait nu als autoload (`Updates`), dus ook in het spel (chipje in de HUD en een knop 'Update beschikbaar' in het pauzemenu). Bij een fout (offline, timeout, rate-limit 403/429) volgt een nieuwe poging na 15 s, 1 min en 5 min, daarna elke 30 minuten; ieder resultaat staat in het detaillog. Versies met vier delen (hotfix 0.17.4.1) worden correct vergeleken; voorheen telden maar drie delen. Mock-responsen in test_updater.
- `tools/release.sh` aanvaardt nu ook hotfixversies (x.y.z.w).
### Onverwacht/UI
- Bouwen zonder weg: de tekst "Zonder weg" stond dubbel (knop én preview). De preview toont nu alleen de besparing en kosten.

## 0.17.4 — Roverskampen (2026-10-26)
### Spel/backend: roverskampen die je kunt plunderen (wens van Mike)
- **Kleine roversbases** verschijnen op oneindige kaarten naast de AI-bases: **normaal 3, groot 5, enorm 8**.
  - Willekeurig maar deterministisch: een eigen RNG uit de seed (`sim/bandits.gd`), de sim-RNG blijft onaangeroerd. Zelfde seed = zelfde kampen.
  - Minstens **48 tegels** van elk hoofdkwartier (speler en AI), dus dichterbij dan de AI-bases (140+). Ze liggen in een ring van 48 tot ca. 90 (normaal), 130 (groot) of 190 (enorm) tegels rond de speler, minstens 28 tegels uit elkaar en 12 van een neutrale stad, nooit op water, berg of geclaimd gebied.
  - Een kamp is 3x3 tegels (bomen en steen worden weggehaald); je kunt er niet op bouwen.
  - Elk kamp heeft **2 tot 4 verdedigers** en een kleine voorraad van 3 grondstoffen (4 tot 12 stuks: hout, planken, steen, vis, erts of kolen).
- **Plunderen**: stuur ridders uit je HQ of eigen militaire gebouwen binnen 96 tegels (elk houdt er 1 achter). Dat mag ook in de vredestijd. Bij aankomst volgen duels zoals bij een aanval (rovers vechten als ridders van tier 1).
  - Win je, dan gaat de hele voorraad naar je **dichtstbijzijnde opslag of HQ**, is het kamp geplunderd (grijze vlag) en lopen de overlevenden terug.
  - Verlies je, dan blijft het kamp staan met minder verdedigers.
- **API voor de UI**:
  - `Sim.bandit_camps()` geeft kopieën `{id, x, y, size, defenders, defenders_max, loot, raided, raided_by, raided_tick}`.
  - `Sim.bandit_camp(id)`, `Sim.bandit_camp_at(tegel)` (id of 0), `Sim.raid_attackers_available(o, id)`, `Sim.can_raid(o, id)` en `Sim.raid_bandit_camp(o, id, n)`. De laatste twee geven foutcodes: `ERR_OK`, `ERR_NO_TARGET`, `ERR_CAMP_RAIDED` (nieuw, 39), `ERR_PLAYER_DEFEATED`, `ERR_NO_KNIGHTS` of `ERR_NO_PATH`.
  - Signalen: `Events.bandit_camp_raided(camp_id, player, loot, building_id)` en `Events.bandit_camps_changed()` (bij een nieuw spel, na het laden, als het aantal verdedigers verandert en bij een plundering).
  - Een plundertocht staat in `Sim.attacks` met `kind = "raid"` en `camp`. De ridders zie je dus gewoon lopen via `Sim.units()`.
- **Opties**: met `opts.bandits = false` zijn er geen kampen, met een getal kies je het aantal. Op vaste kaarten (tests) zijn er geen kampen. Geen enkele bestaande test moest worden aangepast.
- **Savegames**: de kampen worden bewaard onder de sleutel `bandits`. Oude saves laden zonder kampen.
- **Placeholder-weergave** `gfx/bandit_layer.gd` (`BanditLayer`): drie tentjes, een omheining van paaltjes en een vlag (rood = bewoond, grijs = geplunderd). De laag leest alleen `Sim.bandit_camps()`, zodat UI & Graphics hem later kan vervangen.
- Nieuwe teksten (nl/en): `ERR_CAMP_RAIDED`, `MSG_RAID_SENT`, `MSG_RAID_FAILED`, `MSG_RAID_WON`, `BANDIT_CAMP`.
- Nieuwe test `tests/test_m17_4.gd` (plaatsing per kaartgrootte, afstand, determinisme, winst/verlies, buit, signalen, foutcodes, save/load, optie uit). Screenshot: `docs_screenshot_rovers174.png` (`tools/rovers174_shot.gd`).
### Spel/backend: bugfix wegen slopen (bug van Mike)
- Sloop je een weg, dan verdwijnen vlaggen die daarna aan geen enkele weg of gebouw meer vastzitten. Vlaggen van een gebouw, van het HQ of op een andere weg blijven staan. Goederen op zo'n vlag gaan naar de dichtstbijzijnde vlag. Nieuwe test `tests/test_m17_4b.gd`.
### UI: bewegingstoetsen volgen de toetsenbordindeling (wens van Mike)
- De cameratoetsen staan nu in de InputMap op **fysieke toetsposities** (`physical_keycode`, `ui/keymap.gd`, acties `cam_forward`, `cam_back`, `cam_left`, `cam_right`, `cam_rotate_left`, `cam_rotate_right`): QWERTY geeft WASD (Q/E draaien), AZERTY geeft ZQSD (A/E draaien). De pijltjestoetsen werken nog altijd.
- Het pauzemenu toont onder de camerasnelheid de lokale letters (via `DisplayServer.keyboard_get_keycode_from_physical`, tekst `UI_HINT_CAM_KEYS`). Nieuwe test `tests/test_keymap.gd`.
### Beknoptere startlog (wens van Mike)
- Op de console komen nu alleen de versie, de laadstappen in grote lijnen ("Spelgegevens geladen", "Wereld geladen"), de updatestatus en echte fouten (`ui/klog.gd`: `KLog.info`/`KLog.error`). Details zoals seed, checksums en aantallen (`KLog.detail`) staan altijd in `user://logs/kolonie_detail.log` en verschijnen op de console met `--verbose` (of `-v`) of met `[debug] verbose_log=true` in settings.cfg. Godots eigen file logging (`user://logs/godot.log`) staat aan in project.godot. Nieuwe test `tests/test_klog.gd`.
### Nog niet klaar
- Nog niet: knop of menu in de UI om een kamp te kiezen en te plunderen, echte modellen, AI die zelf plundert, en kampen in gebieden die later worden verkend (alleen bij de start geplaatst).

## 0.17.3 — Verre startbases en handels-API (2026-10-26)
### Spel/backend: verre startbases (wens van Mike)
- **Vijandelijke en AI-startbases liggen veel verder weg**, zodat je elkaar echt moet zoeken. De minimumafstand tussen alle hoofdkwartieren (ook tot jouw HQ) schaalt mee met de kaartgrootte: **normaal 140, groot 240, enorm 400 tegels** (was 56 / 110 / 200).
  - De bases worden over de kaart verspreid: gelijke hoeken rond de speler met een willekeurige starthoek en een beetje spreiding, en de AI's liggen ook onderling minstens die afstand uit elkaar. Dit geldt nu ook voor de kaartgrootte *normaal* (vroeger een vaste ring tegenover de speler).
  - Deterministisch: een eigen RNG uit de seed (`Sim._spawn_spots`), de sim-RNG blijft onaangeroerd. Zelfde seed = zelfde plekken.
  - Een expliciete `ai_dist` in de opties (tests, screenshots) gebruikt nog de oude ring.
  - Het oorlogspad (`Sim.war_path`) mag bij verre doelen meer knopen doorzoeken (tot de helft van het zoekvak), zodat aanvallen over de grotere afstand blijven werken.
  - **Checksums**: de worldgen-checksums veranderen niet, want de bases worden pas na de worldgen geplaatst. Seed 42: kaart 48x48 = **417953532**, chunk (0,0) = **1490174514**, chunk (1000,−777) = **2675921415**; kaart-checksum na HQ-effenen (48x48) = **104409281**. Nieuwe referentie voor de startplekken (seed 42, 3 AI, zonder reliëf): normaal (0,−1) (−160,−65) (149,−92) (22,154); groot (0,−1) (−296,−38) (233,−182) (89,265); enorm (0,−1) (−424,−120) (345,−257) (154,455).
  - `tests/test_m17.gd` (AI bouwt zonder weg) gebruikt nu `ai_dist: 56`: op de nieuwe plek van seed 42 is er geen terrein waar de AI zonder weg bouwt. De andere AI-tests zijn ongewijzigd.
### Spel/backend: handel
- `Sim.trade_counter` geeft `null` en `Sim.propose_trade` geeft `ERR_BAD_TERMS` als dezelfde grondstof aan beide kanten staat (geven én nemen).
- Nieuw signaal `Events.unit_status_changed(unit_id, kind, status)` voor handelskarren (`kind = "cart"`) en handelsschepen (`"ship_trade"`). `status` is dezelfde waarde als in `Sim.carts()`/`Sim.ships()` (`no_goods`, `load`, `unload`, `moving`, `idle`), of `removed` als de eenheid verdwijnt. Alleen bij een echte verandering (niet elke tick); niet in de save.
- Nieuwe test `tests/test_m17_3.gd` (dezelfde grondstof, statussignaal voor karren en schepen, afstand/spreiding/determinisme van de startbases).
### Onverwacht/UI (ui/handel-api)
- **Handelsscherm op de nieuwe handels-API (0.17.2)**:
  - De tab Routes ververst nu op `Events.routes_changed(o)` (en `trade_completed`), niet meer elke seconde op tick. De status van de kar of het schip komt rechtstreeks uit `status` in `carts()`/`ships()` (laden, lossen, onderweg, wacht op goederen, wacht).
  - Spelersnamen via `Sim.player_name(i)` in plaats van "Tegenstander n" (relaties, akkoorden, partnerkeuze, meldingen).
  - Lopende akkoorden tonen "volgende levering over X s" (`next_in`).
  - Bij een weigering toont het scherm het tegenvoorstel van `Sim.trade_counter` ("Wel bespreekbaar: …", `UI_TRADE_COUNTER`).
  - Geen vaste foutcodes meer: REFUSED en AT_WAR komen uit `Sim.ERR`.
  - Routeformulier: met **+** voeg je per kant tot 3 grondstoffen toe (dezelfde grondstof telt op), met **−** haal je een regel weg.
- Nieuwe sleutels: `UI_TRADE_TERMS`, `UI_TRADE_NEXT_IN`, `UI_TRADE_MORE_TIP`, `UI_TRADE_LESS_TIP`, `UI_TRADE_ADD_LINE`, `UI_TRADE_DEL_LINE`. `tests/test_trade_ui.gd` uitgebreid. Screenshots: `/workspace/kolonie-ui-shots/handelsscherm2/`.

## 0.17.2 — Wind, handelsscherm en paden (2026-10-26)
### Spel/backend: dynamische wind (backend/wind)
- **Wind verandert**: de richting drijft langzaam (enkele graden per minuut) en draait af en toe (om de ~10 min kans op een draai, verspreid over ~1 min); de sterkte golft over enkele minuten (ca. 0,15..0,95) en er komen geregeld **vlagen** van 3 à 7 seconden (ongeveer om de minuut).
  - Nieuwe API: `Sim.wind()` -> `{dir: Vector2 (genormaliseerd), force: 0..1, gust: 0..1}` (`gust` is de vlaag bovenop `force`); pure variant `Sim.wind_at(seed, t)` en `Sim.sim_time()` (simtijd in s).
  - Deterministisch uit seed + simtijd (gladde waardenruis met hash, geen sim-RNG): pauzeert met het spel en volgt `Sim.speed`.
  - Niets extra in de save: de wind volgt uit seed + `tick_count`, dus oude saves laden gewoon en geven dezelfde wind.
  - Nieuw signaal `Events.wind_changed(dir, force)`: hoogstens 1x per simseconde en alleen bij een merkbare verandering (>= 5 graden of >= 0,05 sterkte).
  - De shader-globals `wind_dir` en `wind_force` worden nu centraal in `SeasonLook` uit `Sim.wind()` gezet (sterkte = force + 0,4 x vlaag); `wind_time` en de visuals blijven ongewijzigd.
- Nieuwe test `test_m17_2` (determinisme, bereiken, pauze/snelheid, save/load, vlagen, signaal).
### Spel/backend: handel-API voor het handelsscherm (backend/handel2)
- **Karren en handelsschepen**: `Sim.carts()` en `Sim.ships()` geven nu ook `status` (`"no_goods"`, `"load"`, `"unload"`, `"moving"`, `"idle"`; bij andere schepen dan `ship_trade` leeg) naast de lading `cargo` (lijst van grondstoffen). Ook een handelsschip zonder goederen meldt nu `no_goods`.
- Nieuw signaal `Events.routes_changed(o)`: een route van speler o is toegevoegd, gestopt of beëindigd.
- `Sim.at_war(a, b)` (lopende aanval tussen a en b of relatie < 0) en `Sim.ai_players()` (gesorteerde spelersnummers van de AI's).
- `Sim.ERR`: dict naam -> foutcode, bv. `Sim.ERR["REFUSED"] == Sim.ERR_REFUSED` (sleutels = `error_key` zonder `ERR_`).
- **Namen per speler**: `Sim.player_name(i)` en `Sim.player_name_key(i)` (`PLAYER_0` = Jij, `PLAYER_1..7` = Graaf Arnulf, Gravin Machteld, ...; daarboven `PLAYER_N` "Speler %d"), nl en en.
- `Sim.agreements(o)`: nieuw veld `next_in` = seconden (simtijd) tot de volgende levering.
- **Tegenvoorstel**: `Sim.trade_counter(o, ai, terms)` geeft na een `ERR_REFUSED` voorwaarden `{give, take, every_s}` die de AI nu wél aanvaardt (minder vragen tot wat de AI kan missen, meer bieden van het duurste aangeboden goed), of `null` als niets haalbaar is (oorlog, geen AI, AI heeft niets over). Geen bijwerkingen (relatie blijft gelijk). Nieuwe tekst `UI_TRADE_COUNTER` ("Wel bespreekbaar: %s").
- Nieuwe test `test_m17_2b`.
### Onverwacht/UI (ui/handelsscherm)
- **Handelsscherm** (`ui/trade_screen.gd`, `ui/trade_chart.gd`) in de RS-stijl: knop met muntjes in de bovenbalk en toets **H** (Esc sluit). Klik je in de wereld op een neutrale stad, dan opent de markt van die stad.
  - **Markt**: kies een stad. Per grondstof zie je het icoon, de koop- en verkoopprijs (munten), de voorraad en een sparkline (groen = gestegen, rood = gedaald). Klik op een rij voor de grote prijsgrafiek (`Sim.price_history`, 4 min) met de koop- en verkooplijn. Het tegoed bij de stad staat erbij.
  - **Routes**: lijst van je routes (handelshuis of haven → stad, geven/nemen, herhalen, aantal ritten, status van de kar of het schip: laden, onderweg, lossen, wacht op goederen). Met *Nieuwe route* kies je het gebouw, de stad, geven, nemen en herhalen. *Stoppen* laat de lopende rit afmaken. Fouten komen uit `Sim.error_text`.
  - **Akkoorden**: per AI-speler een relatiebalk (−100..100, rood/groen), lopende akkoorden met *Opzeggen*, en een voorstel (geven, nemen, elke n s). Bij een weigering of oorlog krijg je een duidelijke melding.
  - Het scherm ververst live op `trade_completed`, `price_changed`, `agreement_changed`, `town_added` en `game_started`. De karstatus ververst elke seconde zolang de tab Routes open is.
- Hooks: `ui/hud.gd` (één knop + toets H), `scenes/game.gd` (één regel: klik op stad). De bovenbalk past nog op 1280 px (nl/en).
- Alle tekst via `UI_TRADE_*` (nl/en). Test `tests/test_trade_ui.gd`. Screenshots: `tools/handelsscherm_shots.gd` → `/workspace/kolonie-ui-shots/handelsscherm/`.
### Spel/backend: slijtage-API voor de paden-UI (backend/paden2)
- Nieuw signaal `Events.wear_changed(rect: Rect2i)`: de slijtage veranderde binnen `rect` (tegelcoördinaten). Hooguit 2x per simseconde (om de 5 ticks); wijzigingen daartussen worden tot één gebied samengevoegd. Ook na laden van een save.
- Publieke alleen-lezen API: `Sim.wear_tiles()` -> `{Vector2i: 0..1}` (kopie, alleen tegels met slijtage) en `Sim.wear_at(c)` -> 0..1. De UI leest `Sim._wear` niet meer.
- Nieuwe foutcode `ERR_TRACK_NOT_WORN` (ook in `Sim.ERR["TRACK_NOT_WORN"]`, tekst nl/en "Het pad is nog niet genoeg ingesleten"): `Sim.track_to_road` geeft die nu als het veldpad nog niet genoeg ingesleten is, in plaats van `ERR_NO_PATH`.
- `BUILD_ROADLESS` gebruikt nu `%s` (zoals `BUILD_ROADLESS_AVG`), want de korting is 12,5%; de UI toont `BUILD_ROADLESS_AVG`.
- `WearMap` is nu event-gestuurd (`Events.wear_changed`/`game_started` + `Sim.wear_tiles()`) in plaats van `trails_rev` en `Sim._wear` te pollen.
- Nieuwe test `test_m17_2c`.
### Onverwacht/UI: paden (ui/paden)
- **Uitgelopen paadjes (desire paths)**: de slijtagekaart (`Sim.wear`) gaat als R8 data-texture (`gfx/wear_map.gd`) naar de terreinshader, via een aparte include `gfx/trail_wear.gdshaderinc` (2 regels in `terrain.gdshader`). Stadia: platgetrapt, iets lichter gras -> aarden spoor met zachte, onregelmatige randen (9-tap blur + domain-warp, geen tegelblokjes), kiezels en grasplukjes in het midden. Herfst modderig/donker, winter vertrapte sneeuw. Bijgewerkt bij `Events.wear_changed` (als dat bestaat) of bij een wijziging van `trails_rev`/slijtage (poll 2x/s).
- **Geen windgras op een uitgesleten spoor**: `WearMap.grass_factor` (minder plukjes vanaf 0,15, geen vanaf 0,6) in `gfx/grass_field.gd`.
- **Wegen per tier** (`gfx/materials/road_tier.gdshader`, licht als `rs_toon`): aarden pad met wielsporen en kiezels, keienweg met ronde keien en voegen, geplaveide weg met platen, stoeprand en middenstreep. `RoadMesh.style(seg)` en `add_segment_styled` (UV langs de weg). Een segment met `kind == "conveyor"` krijgt alleen een eenvoudige donkere band (geen nieuw model).
- **Plaatsingspreview zonder weg** (`ui/paden_ui.gd`): knop "Zonder weg" (aan/uit) met "−12,5% gemiddeld" en de kosten (en de normale kosten); een klik plaatst dan met `Sim.place_roadless`. Onbereikbaar: `BUILD_ROADLESS_UNREACHABLE`, knop uit, rode ghost.
- **Gebouwpaneel**: spoorstatus (`TRACK_NONE`/`TRACK_WORN` met %), besparing, knop "Maak er een weg van · kosten" (`Sim.track_to_road`), uitgegrijsd tot `upgradable`. Status `no_builder` via de bestaande statusregel.
- **Offroad-indicator**: stofringetje onder dragers en bouwers met `offroad: true`.
- **Rook en stof in de wind**: schoorsteenrook buigt mee met `wind_dir`/`wind_force`. Windstof (`gfx/wind_dust.gd`, max. 48 deeltjes) waait bij een vlaag (`Sim.wind().gust`) of sterke wind (globals, `Events.wind_changed`) over paadjes en zandoevers.
- Nieuwe i18n-keys: `BUILD_ROADLESS_BTN/_AVG/_OFF`, `TRACK_SAVED`, `TRACK_UPGRADE_COST`, `TRACK_UPGRADE_LOCKED`.
- Tests `test_paden_ui`, `test_wind_paden`; screenshots `tools/paden_shots.gd`.
### Opgelost: bouwen zonder weg vanuit het bouwmenu
- Na plaatsen zonder weg (knop "Zonder weg" in de plaatsingspreview) vroeg het spel meteen om automatisch een weg aan te leggen; met de instelling "altijd" werd die weg zelfs direct gebouwd. Daardoor werd het gebouw toch aan het wegennet gehangen en bleef er van "zonder weg" niets over. Bij plaatsen zonder weg komt er nu geen wegdialoog en geen automatische weg meer.
- De linkerklik in een bouwmodus loopt nu via `game.place_click(c)` (zelfde code voor UI en tests).
- Nieuwe test `test_roadless_ui_flow`: game-scène, houthakker kiezen in het bouwmenu, ver van de weg plaatsen via de klikcode, dan bouwer -> bouw af -> ingesleten spoor.
### In-game updater en GitHub (backend/updater)
- **Update-knop in het hoofdmenu**: bij het opstarten kijkt Kolonie op de achtergrond of er op GitHub (`LTGmaster/kolonie-releases`) een nieuwere versie is (semver-vergelijking met de eigen versie). Zo ja, dan verschijnt de knop **Update beschikbaar (vX.Y.Z)** en in de HUD een klein chipje met de nieuwe versie.
- Klikken downloadt het installatieprogramma naar `user://update/` met een voortgangsbalk. Daarna start het stil (één UAC-vraag), sluit het spel af en start Kolonie na de installatie vanzelf opnieuw (`installer/kolonie.nsi`: wachten in `.onInit`, herstart in `.onInstSuccess` bij `/S`).
- Nieuwe instelling *Updates → Automatisch controleren* (`[updates] check`, standaard aan). Geen internet of een fout: er gebeurt gewoon niets.
- Headless en tests doen nooit netwerkverkeer (`KOLONIE_PAR`, `KOLONIE_TEST`, `KOLONIE_NO_UPDATE`, `-s res://tests/...`).
- **GitHub**: broncode in de privé-repo `LTGmaster/kolonie`, installers publiek in `LTGmaster/kolonie-releases` (release v0.17.1 met Setup.exe). Nieuw script `tools/release.sh <versie>`: export, installer, tag, push en GitHub-release in één keer.
- Nieuwe test `test_updater` (versievergelijking, release-JSON, headless overslaan, menuknop, instelling).

## 0.17.1 — Startgebied met hout en steen, wind en water (26 okt 2026)
### Spel/backend
- **Startgebied altijd bruikbaar**: rond elk HQ (speler én AI, vaste en oneindige kaarten, alle kaartgroottes, elke seed) liggen binnen straal 8 altijd minstens **25 bomen** en **4 bereikbare steentegels** (steen op land, niet in de berg; 4 x 10 = 40 steen). Zo kan je meteen uitbreiden.
  - Is er te weinig, dan vult `Sim._ensure_start_res` bij het plaatsen van het HQ deterministisch aan (hash op seed + plek, geen sim-RNG).
  - Alleen op gras zonder grondstof: nooit op water, bergen of klifranden, nooit in de HQ-zone (straal 5) en bij voorkeur niet in de drie tegels brede gangen langs de assen, zodat de uitgangen en wegen vrij blijven.
  - Nieuwe API: `Sim.start_counts(c)`, constanten `START_R`, `START_TREES`, `START_STONE`.
  - De worldgen-checksums veranderen niet (de aanvulling gebeurt na worldgen, zoals het effenen van het HQ).
### UI/graphics: wind en water (ui/wind-water)
- **Bugfix herfst: loofbomen werden onzichtbaar.** Oorzaak: in `rs_toon.gdshader` gooide de kale-boom-regel (`season_bare`, vanaf eind herfst) elk bladfragment weg met `hole < season_bare * 0.92`; omdat de ruis vrijwel altijd onder 0,92 ligt, verdween bij volle `season_bare` de hele kruin en bleef van een Kenney-loofboom alleen een stompje stam over. Nu valt hooguit `BARE_HOLE` (0,42) weg en wordt de rest een kale, bruine takkenkruin. Nieuwe test `test_wind_water` rekent de discard per seizoen na (≥ 50 % van elke kruin zichtbaar) en controleert dat boommaterialen niet doorzichtig zijn.
- **Besneeuwde dennen**: naaldbomen krijgen in de winter een duidelijke witte sneeuwlaag op de bovenkant van elke takkenlaag, de onderkant blijft donker koelgroen (`rs_toon`, `foliage == 1`). Kale loofbomen zijn donkerder bruin i.p.v. oranje.
- **Globale wind** (`gfx/season_look.gd`): nieuwe globale shaderparameters `wind_dir` (vec2), `wind_force` (0..1, met vlagen, in de winter iets harder) en `wind_time` (in `project.godot`). Richting draait langzaam; `SeasonLook.wind_force_scale = 0` zet alles stil.
- **Bomen wiegen mee met de wind**: vertex-wiegen in `rs_toon` (`sway`), kwadratisch gewogen naar de hoogte (stam/voet blijft staan, kruin beweegt), per instantie in fase verschoven; werkt in de MultiMesh-bossen, ook voor de procedurele LOD-/LOW-bomen (`MeshKit.tree_material()`).
- **Wuivend gras** (`gfx/grass_field.gd`, `gfx/materials/grass.gdshader`): gestileerde grasplukjes via MultiMesh, per cel van 12×12 tegels één draw call, alleen binnen ~26 tegels rond het camerapunt (verre cellen worden opgeruimd, `visibility_range` 44 bij ver uitzoomen), hooguit 9000 plukjes, geen schaduw. Windbeweging in de vertex-shader (voet vast). Herfst: oranje/gouden punten; winter: zakt onder de sneeuw met witte puntjes en wordt bij volle sneeuw niet getekend. Geen gras op water, rots, sneeuw, zandoever, steile hellingen, gebouwen, wegen en vlaggen (bestaande reads: `TerrainInfo`, `Sim.occupied`, `Logistics.is_road`/`flags`); ververst bij nieuwe wegen/gebouwen. Niet bij grafische kwaliteit Laag. Eén hook in `scenes/game.gd`.
- **Golven op het water** (`terrain.gdshader`): drie gerichte sinusgolven met een kleine gerstner-verschuiving naar de kam, mee met de wind; de kust blijft vast. Gestileerd **schuim**: een witte kustlijn, banden die tegen de kust oplopen en schuimkoppen op de hoogste kammen. **Bevroren water blijft stil** (geen golven of schuim op ijs).
- Nieuwe/uitgebreide test `test_wind_water` (wind, wiegen, gras-plaatsing en celbeheer, golven/ijs). Screenshots en gif: `tools/wind_shot.gd`.
### Tests
- Nieuw `test_m17_1`: 30 seeds x 6 kaarten (vast 48/72/96, oneindig normaal/groot/enorm met 3 AI) = 180 spellen en 450 HQ's, elk met genoeg bomen en steen, HQ-zone vrij, nooit aanvulling op verboden tegels, plus determinisme.
- Screenshot `docs_screenshot_start171.png`.

## 0.17.0 — Bouwen zonder weg (26 okt 2026)
### Spel/backend
- **Gebouwen zonder wegverbinding**: met `Sim.place_roadless(type, c, dir, o)` zet je een gebouw neer zonder weg. De bouwer en de dragers lopen er dan zelf heen door het veld.
  - Ze lopen over het wegennet tot de dichtstbijzijnde verbonden vlag, en vandaar over het terrein naar de vlag van het gebouw.
  - Door het veld gaat het trager: in het bos en op hellingen nog trager. Ze lopen nooit over kliffen, water, bergen of vreemd gebied.
  - De **bouwer** moet eerst ter plaatse zijn (nieuwe status `no_builder`, "wacht op bouwer"). Daarna brengen **lastdragers** uit de dragerpool het bouwmateriaal, maximaal 2 tegelijk per gebouw.
  - Is het gebouw af, dan brengen ze ook de input en halen ze de productie op naar de dichtstbijzijnde opslag.
  - Zodra er een weg ligt, nemen de gewone dragers het over.
- **Korting zonder weg**: gemiddeld **12,5%** (`Sim.build_cost(o, type, roadless)`, `Sim.placement_info(...)`).
  - De bouwkosten zijn kleine gehele getallen. Daarom spaar je per speler een tegoed op, en gaat elke volle eenheid eraf (eerst planken).
  - Een toren kost zo 7 in plaats van 8. Bij goedkope gebouwen scheelt het om de paar plaatsingen 1 plank.
  - Bij slopen krijg je de echt betaalde kosten terug (`b.cost`).
- **Olifantenpaadje**: elke stap door het veld slijt de grond (met last 2x zo hard). In `test_m17` (houthakker, 6 tegels door het veld) zie je na ongeveer 1,5 min een paadje. Na ongeveer 5 min is het **opwaardeerbaar**.
  - Dan zet `Sim.track_to_road(o, gebouw)` het om in een **aarden pad**. Dat kost zoveel als een gewone weg en is 2x zo snel aangelegd.
  - Daarna kan het verder naar **keienweg** en **geplaveide weg**, of een lopende band (`Sim.upgrade_road`). De info staat in `Sim.track_info(o, gebouw)`.
- **Snelheden** (gecontroleerd, `Sim.speed_factors()`), van traag naar snel:
  - door het veld: 0,6 (bos 0,45)
  - paadje: 0,69 tot 0,9
  - aarden pad: 1,0
  - keienweg: 1,35
  - geplaveide weg: 1,7
  - lopende band: 2,0 tot 3,3

  Per tegel op vlak gras is dat 8, 7..6, 5, 3,7 en 2,9 ticks. De lastdragers tellen op hun route ook het wegtype mee.
- Lastdragers zitten in de save (`logi.porters`), in `Sim.units()` (`offroad: true`) en in de goederentelling.
- **Bugfix**: een gebouw op een helling (+1 plank) gaf bij slopen vóór het af was die extra plank niet terug.
### AI
- Zet een **bosbouwer** voortaan zonder weg (goedkoper, er gaan geen goederen heen of terug).
- Lukt er geen weg naar een grondstofgebouw (houthakker, steengroeve, visser, waterput, waterdrager), dan bouwt ze het zonder weg in plaats van het op te geven, als het te voet bereikbaar is.
- Zet ingesleten paadjes om in een weg zodra dat kan (met een plankenmarge).
### UI-teksten (nl/en)
- `STATUS_NO_BUILDER`, `BUILD_ROADLESS`, `BUILD_ROADLESS_TIP`, `BUILD_ROADLESS_UNREACHABLE`, `TRACK_NONE`, `TRACK_WORN`, `TRACK_UPGRADE`, `TRACK_UPGRADE_TIP`, `SPEED_OFFROAD`, `SPEED_TRACK`. De bouwknop zelf zit nog niet in de UI. De API staat in de README (0.17).
### Tests
- Nieuw `test_m17` test:
  - kosten en korting (ook gemiddeld over 16 plaatsingen)
  - de preview
  - de snelheidsvolgorde (factoren en echte ticks)
  - een houthakker zonder weg: bouwer, lastdragers, afgebouwd, hout in het HQ
  - het paadje: zichtbaar, opwaardeerbaar, `track_to_road`, kasseien, verhard
  - de dragertelling
  - save/load met lastdragers onderweg (hash en determinisme, ook via `SaveSystem`)
  - slopen terwijl er lastdragers onderweg zijn (goederen en dragers terug)
  - de AI
  - i18n
- Screenshot `docs_screenshot_zonderweg17.png` (hulpscript `tools/zonderweg17_shot.gd`).

## 0.16.1 — Seizoenslook en UI-koppeling (26 okt 2026)
### Spel/backend
- **`Sim.cold_houses(o)`** geeft het aantal koude woonhuizen van speler o (gebouwd, `heated` false of status `unheated`/`no_coal`), dezelfde regel als de HUD-waarschuwing.
- Nieuw event **`Events.cold_houses_changed(o, n)`**: alleen bij een echte verandering van de telling, ook als een status `no_coal` aan- of uitgaat, na bouwen/slopen/verovering (binnen 1 s), na `set_season` en na het laden van een save. Per verwarmingsronde komt er hooguit één event.
- **`Sim.season_time_left()`** geeft de resterende speltijd van het seizoen in seconden (0 zonder seizoenen).
- **`Sim.set_season(s, year = -1)`** heeft een optioneel jaar; `Sim.year_count` volgt mee.
- **Bugfix**: na `Sim.set_season` uit de winter naar een ander seizoen bleven woonhuizen "onverwarmd" en ontevreden tot de volgende lente. Ze zijn nu meteen weer warm.
- De HUD-waarschuwing **koude huizen** luistert nu naar `Events.cold_houses_changed` (en `game_started`) in plaats van elke seconde te tellen.
### Tests
- Nieuw `test_m16_1`: `season_time_left`, `set_season` met jaar (en jaarwissel daarna), `cold_houses` en het event (eenmalig, geen event zonder verandering, sprong naar de lente, slopen), `no_coal` aan/uit, save/load en de chip zonder polling.
- Screenshots `docs_screenshot_winter161.png` (sneeuw) en `docs_screenshot_herfst161.png`, met het seizoen gezet via `Sim.set_season` (hulpscript `tools/seizoen161_shot.gd`).
### Onverwacht/UI (ui/seizoenen, 28247a2)
- **Seizoenslook** (ui/seizoenen): herfstkleuren op bomen en gras, sneeuw in de winter (terrein, daken, keien, naaldbomen besneeuwd, loofbomen kaal) en **bevroren water** (ijs met barsten en stuifsneeuw). Overgangen lopen vloeiend mee met `Sim.season_frac()`: herfstkleuren vanaf eind zomer, sneeuw valt eind herfst en smelt begin lente (niet in de eerste lente van een nieuw spel). Via globale shaderparameters `season_snow`, `season_autumn`, `season_ice`, `season_bare` (gedeclareerd in `project.godot`, gezet door `gfx/season_look.gd`, reageert op `Events.season_changed`), in de bestaande `terrain.gdshader`, `rs_toon.gdshader` en `rock_snow.gdshader`. De Kenney-bomen gebruiken nu `rs_toon` (bladmodus naald/loof/schors). Debug: `-- --season=3`.
- **Koolader** (`WorldGen.RES_COAL`): procedurele rotsen (donker gesteente met zwarte, glanzende kolenbrokken, `SeasonKit.coal_rock`) in plaats van alleen een tint, als MultiMesh in het nabije LOD zoals de steen- en ertsrotsen.
- **Schoorsteenrook** alleen bij verwarmde woonhuizen (`b.heated`), uit bij onverwarmd: `gfx/chimney_smoke.gd`, drie MultiMeshes met GPU-geanimeerde pufjes, max. 48 huizen dichtst bij de camera, in de winter dikker. Het woonhuismodel heeft geen vaste rook meer.
- **Tech-icoon Kolen** vervangt de placeholder (kolenbrokken met sintel, houweel).
- **HUD**: seizoenschip naast de dag/nacht-chip (icoon + "Herfst · jaar 2", tooltip met voortgang en volgend seizoen) en een waarschuwing **koude huizen** (aantal eigen woonhuizen met `heated` false of status `unheated`/`no_coal`; klik = camera naar het volgende koude huis). Nieuwe sleutels `UI_SEASON_0..3`, `UI_SEASON_CHIP`, `UI_SEASON_TIP`, `UI_SEASON_OFF`, `UI_COLD_HOUSES`, `UI_COLD_HOUSES_TIP` (BLD_KOLENMIJN/WATERPUT/WATERDRAGER bestonden al).
- **Bugfix bovenbalk**: sinds 0.16 (kolen- en waterchip) liep de bovenbalk op 1280 logische pixels buiten beeld (dagchip, klok en knoppen onzichtbaar), en het logo verdween niet omdat de breedte van de balk zelf werd gemeten. Nu op de viewportbreedte, met compacte stappen tot alles past (smallere grondstofchips, seizoens-/dagchip alleen naam/icoon, dan bevolkingsbalkje/klokicoon, als laatste de speeltijd).
- **Techboom** luistert naar `Events.game_started` in plaats van elke tick `Sim.tech_rev` te vergelijken (`test_tech_costs` aangepast).
- Test `tests/test_season_visuals.gd`; screenshots met `tools/seizoenen_shots.gd` (per seizoen, rook, koolader, tech-icoon).

## 0.16.0 — Seizoenen, kolen en water (26 okt 2026)
### Spel/backend: seizoenen
- **Vier seizoenen**: lente, zomer, herfst en winter. `Sim.season()` geeft 0..3, `Sim.season_frac()` de voortgang (0..1), `Sim.year_frac()` en `Sim.year_count`. Nieuw event **`Events.season_changed(season)`**, plus een melding per seizoen.
- **Lengte** in `settings.cfg` `[gameplay] season_days` = **dagen per seizoen**, standaard **0,5**. Met de standaarddag van 12 min duurt een seizoen dus 6 min en een jaar 24 min. Een nieuw spel begint aan het begin van de lente; de eerste winter valt na 18 min. `season_days` 0 of altijd dag = geen seizoenen (altijd zomer). Tests geven `opts.season_length` (s) mee; `opts.seasons = false` speelt met de regels van vóór 0.16.
- **Winter**: de bosbouwer plant niet (status `winter_rest`) en jonge bomen groeien niet. (Kolonie heeft nog geen boerderij, bakkerij of brouwerij; zodra die er zijn, volgen ze dezelfde regel.)
- **Verwarming**: in de winter stoken woonhuizen eerst **kolen** (1 kolen = 180 s), anders **hout** of als laatste **planken** (90 s). Vanaf de herfst vragen ze brandstof aan, en dragers brengen die. Woonhuizen hebben het veld **`heated`** (voor de UI), plus `unhappy` en `heat_t`, en het nieuwe event `Events.house_heating_changed(id, heated)`.
- **Onverwarmd**: het huis wordt eerst ontevreden (geen groei, status `unheated`). Daarna verliest de speler per 60 s per koud huis 1 vrije kolonist (`players[o].frozen` telt mee). In de lente is alles weer warm.
- **Save/load**: `season_tick`, `year` en `season_length` zitten in de save. Oudere saves laden gewoon en beginnen in de lente van jaar 1.
### Spel/backend: kolen
- Nieuwe grondstof **`coal`** en tegel-grondstof `WorldGen.RES_COAL` (3, 14 per tegel). Kolenaders liggen in het gebergte (op een deel van de stenen bergtegels) en als dagzoom op de hoge bergflank, te voet bereikbaar. Ze komen uit een eigen ruis met eigen seed; steen en erts op land blijven waar ze waren.
- **Kolenmijn** (`kolenmijn`, 2x2, 3 plank + 1 blok, cyclus 18 s, straal 2, sneller met vis zoals de ertsmijn). Ontgrendeld door de nieuwe tech **Kolen** (productie-tak, na Productie I, 4 plank + 2 blok, 45 s).
- De **smederij** gebruikt optioneel kolen (`fuel`): met kolen is de cyclus 25% korter.
- **Nieuwe checksums** (seed 42):
  - kaart 48x48: **417953532**
  - chunk (0,0): **1490174514**
  - chunk (1000,−777): **2675921415** (ongewijzigd, geen bergen met kolen)
### Spel/backend: water
- Nieuwe grondstof **`water`**.
- **Waterput** (`waterput`, 2x2, 1 plank + 2 steen): alleen op grondwater (`Sim.moisture()` ≥ 0,55, ongeveer een derde van het land). Langzaam: 1 water per 36 s.
- **Waterdrager** (`waterdrager`, 2x2, 2 plank): hut aan een rivier of meer. `b.water` is de watertegel; de UI draait +z daarheen, zoals bij de vissershut. Snel: 1 water per 12 s. In de winter bevriest het water en duurt de cyclus 2x zo lang.
- **Woonhuizen hebben water nodig om te groeien**: alleen een woonhuis met water geeft per groeironde een kolonist, en drinkt daarvoor 1 water. Het HQ blijft +1 geven.
- Nieuwe statuscodes `no_coal`, `winter_rest`, `unheated` en `heated`. Nieuwe foutcodes `ERR_NO_COAL` 35, `ERR_TOO_DRY` 36 en `ERR_NOT_SHORE` 37, met i18n nl/en (ook `WHY_34`/`WHY_35`, gebouwen, grondstoffen, seizoenen, meldingen, tech).
### AI
- Bouwt een waterbron zodra er woonhuizen zijn (waterdrager als er water in het gebied ligt, anders een waterput; 1 per 3 huizen).
- Onderzoekt **Kolen** vanaf de zomer, en bouwt een kolenmijn als er kolen in het gebied liggen.
- Legt brandstof aan: vanaf de zomer een extra houthakker als kolen + hout onder het winterdoel zitten. In herfst en winter geeft ze woonhuizen voorrang op brandstof.
- In `test_m16` (seed 42, 1 AI) is 32 van de 33 gemeten AI-woonhuizen in de winter verwarmd.
### Bouwmenu en techboom
- Grondstoffen: + Kolenmijn, Waterput, Waterdrager. Opslag: + **Dragersgilde** en **Handelshuis**. Die twee stonden sinds 0.13 en 0.15 niet in het bouwmenu en waren daardoor niet te bouwen (bugfix).
- Techboom: nieuwe node `kolen` met een eigen icoon.
### Tests
- Nieuw `test_m16`:
  - settings (standaard 6 min per seizoen, `season_days`, uit)
  - cyclus, frac en events
  - kolenaders en checksums
  - winterrust
  - verwarming (kolen > hout > plank), onverwarmd, krimp en herstel
  - kolenmijn, tech en smederij
  - waterput, waterdrager en bevriezen
  - groei met water
  - save/load (ook een oude save)
  - determinisme
  - AI in de winter
  - i18n en id's gelijk aan `SeasonIds`
- Aangepast:
  - checksums in de oudere tests
  - `test_worldgen` telt kolen
  - `test_m11` (groei volgens de 0.11-regel) speelt zonder seizoenen (`Sim.default_seasons`)
- Screenshot `docs_screenshot_winter16.png` (hulpscript `tools/winter16_shot.gd`). Sneeuw en herfstkleuren komen van UI & Graphics.
### UI & Graphics (ui/seizoenen-modellen, 46f5e2c)
- Modellen vóór de backend, voorlopige id's centraal in gfx/season_ids.gd: kolenmijn (mijningang in een bergwand met stutbalken, rails, mijnkarretje, kolenhopen), waterput (2x2, stenen put met lier en dakje), waterdrager (hut aan de rivier met emmers en steiger); dragerprops emmer (water) en kolenzak (coal) in het bestaande LOADS-systeem; iconen voor coal, water en de drie gebouwen (ui/season_icons.gd). Modellen in gfx/seasonkit.gd, alleen id-hooks in MeshKit/UnitAnim/UiIcons. Test: tests/test_season_models.gd; screenshots: tools/season_shots.gd.

## 0.15.1 — Dag en nacht (26 okt 2026)
### Spel/backend: dag/nacht
- **`Sim.time_of_day()`** geeft 0..1 (0 = middernacht, 0,25 = zonsopgang, 0,5 = middag, 0,75 = zonsondergang). De tijd loopt op de sim-ticks: deterministisch, staat stil bij pauze en volgt `Sim.speed`. Een nieuw spel begint op 0,30 (kort na zonsopgang).
- **`Sim.day_count`** (begint op 1, +1 om middernacht), `Sim.is_night()` en `Sim.set_day_length(s)` (behoudt het tijdstip).
- **`Sim.day_length`** in seconden, uit `settings.cfg` `[gameplay] day_length` in **minuten** (standaard 12). 0 = altijd dag (`time_of_day()` = 0,5, geen events). Testen kunnen `opts.day_length` (seconden) aan `new_game` meegeven.
- Nieuwe events **`Events.dawn(day)`** en **`Events.dusk(day)`**.
- Tijdstip en dagnummer zitten in de save (`time_of_day`, `day_count`); oude saves beginnen op dag 1, 0,30.
- Kolonisten gaan 's nachts (nog) niet vaker naar huis; dat blijft voor later.
### Tests
- Nieuw `test_m15_1`: settings (minuten → seconden, standaard 12 min), cyclus en dagteller, dawn/dusk, pauze en snelheid, altijd dag, save/load (en oude save), determinisme.
- Screenshots `docs_screenshot_dag151.png` en `docs_screenshot_nacht151.png` (hulpscript `tools/dagnacht151_shot.gd`, tijd via `Sim`).
- `test_daynight` test nu de koppeling met `Sim.time_of_day()` in plaats van de lokale klok.
### Onverwacht/UI (ui/dagnacht)
- **Dag/nacht-cyclus** in warme RuneScape-stijl (`gfx/daynight.gd`, `gfx/materials/sky_daynight.gdshader`, `ui/daynight_chip.gd`): zon en maan als DirectionalLight3D met kleurverloop (oranje-roze dageraad/schemering, warm wit overdag, koel blauw 's nachts), ambientbodem 0,42, eigen lucht met sterren, gloeiende vensters en max. 8 lantaarns ('s nachts), tijdstip-chip (zon/maan + dag) in de HUD. Gekoppeld aan `Sim.time_of_day()` en `Sim.day_count` (de lokale klok is weg); debug `-- --tod=0.5`. Test: `tests/test_daynight.gd`.

## 0.15 — Handel (26 okt 2026)
### Spel/backend: handel
- **Neutrale steden** (`neutral_town`, 4x4, altijd afgebouwd, niet te veroveren): 3/4/6 per kaartgrootte (normaal/groot/enorm) rond de spelers. Verder weg komt er in de oneindige kaart ongeveer 1 stad per 3x3 chunks bij, zodra een speler in de buurt grond claimt. Deterministisch uit de seed. De steden zitten niet in de worldgen, dus de worldgen-checksum verandert er niet door. Elke stad heeft 2 goederen met veel aanbod en 2 met veel vraag.
- **Handelshuis** (`handelshuis`, 3x3, opslag): ontgrendeld door de nieuwe tech **Handel**. Handelskarren (kind `cart`) lopen over land (klifvrij pad) naar een stad, laden af, ruilen en komen terug.
- **Handelsschepen** (`ship_trade`, 12 goederen, plank 6 + blok 2) via de scheepswerf na de nieuwe tech **Zeehandel** (vereist Handel en Scheepvaart). Ze varen vanuit de haven naar steden aan het water en staan gewoon in `Sim.ships()`.
- **Handelsroutes** komen steeds terug (`repeat`) en zijn te stoppen (de lopende rit wordt afgemaakt). Maximaal 3 per handelshuis of haven.
- **Dynamische prijzen** per goed per stad, in centen. Middenprijs = basis × 2·40/(voorraad+40); kopen = +15%, verkopen = −15%. Een stad schuift elke 10 s terug naar haar eigen doelvoorraad. Er is een prijsverloop van 24 punten. Ruilhandel: wat je verkoopt geeft tegoed bij de stad, en daarmee betaal je de terugvracht.
- **Handelsakkoorden met de AI**: `propose_trade`. De AI weegt de waarde van de ruil af tegen haar eigen behoefte, haar overschot en de relatie (start 50). Een akkoord ruilt op een vast interval. Oorlog (een aanval tussen beide partijen) verbreekt alle akkoorden en zet de relatie negatief (`ERR_AT_WAR`); de relatie herstelt langzaam.
- **AI-handel**: na Handel bouwt de AI één handelshuis (vanaf 10 gebouwen) en ruilt een overschot (≥25) tegen een tekort (<4) met de dichtstbijzijnde stad.
- Nieuwe foutcodes: `ERR_NO_TOWN` 28, `ERR_NO_TRADE_HOUSE` 29, `ERR_BAD_TERMS` 30, `ERR_REFUSED` 31, `ERR_AT_WAR` 32, `ERR_NOT_AI` 33 en `ERR_ROUTE_LIMIT` 34. Daarnaast i18n (nl+en) voor gebouwen, eenheden, tech-DESC en 12 stadsnamen. Alles zit in de save (`trade`), en is deterministisch.
- Nieuwe events: `trade_completed(o, partner, gave, got)`, `price_changed(town_id)`, `agreement_changed(id)`, `town_added(town_id)` en **`game_started()`**. Dat laatste komt na een nieuw spel én na laden, zodat de UI geen `tech_rev`-controle per tick meer nodig heeft.
### Spel/backend: bergen (feedback Mike: "bergen schieten recht uit de grond")
- **De bergvoet ligt op het maaiveld.** Bergen lopen geleidelijk op naar het midden: hoogte = basis + smoothstep(bergmasker) × flank, met daarboven toppen alleen in de kern. Het masker is laagfrequent, dus er is geen klif aan de voet. De onderste flank is begaanbaar land. Op de rotsige flank liggen steen en (hoger) ertsaders, dus mijnen zijn te voet bereikbaar. Ook rivieren op de flank lopen mee omhoog.
- **Kliffen alleen in de hoge bergkern**: een klif is nu een sprong groter dan `CLIFF_M` waarbij de hoge kant bergterrein is (≥ `MOUNTAIN_M`), via `Sim.cliff_pair(a, b)`. Lage klifwanden op gras of aan het water bestaan niet meer; die stukken worden nu als helling getekend.
- Hoogste top ±27–29 m. `MOUNTAIN_M` 8,75 m en `SNOW_M` 18,25 m blijven gelijk.
- **Nieuwe checksums** (seed 42):
  - kaart 48x48: **1098785000**
  - chunk (0,0): **3015045188**
  - chunk (1000,−777): **2675921415**
- Meetscript `tools/foot_stats.gd`.
- Screenshots: `docs_screenshot_bergen15.png` en `docs_screenshot_handel15.png`.
### Tests
- Nieuw `test_m15`:
  - steden (aantal, 4x4, determinisme, cellen)
  - prijzen en herstel
  - tech-slot
  - kar-route (velden, animaties, herhalen, stoppen)
  - foutcodes
  - handelsschip
  - akkoorden en oorlog
  - AI-handel
  - save/load
  - determinisme
  - bergvoet: geen kliffen op de onderste flank, en vanaf de bergrand een begaanbaar pad omlaag
  - i18n
- `tools/runall_par.sh`: tijdgevoelige tests (`test_m11_3`, "cached pad te traag") draaien na de parallelle batch alleen, met dezelfde drempel.
- Aangepaste tests:
  - m10: spreiding en diagonale wegen draaien vlak (pure geometrie)
  - m13_1: kliffen alleen in de kern
  - m14: hoekhoogtes
  - worldgen: erts op de flank
### Onverwacht/UI (ui/handel: handelsmodellen, nog zonder API)
- **Eigen procedurele handelsmodellen** in `gfx/tradekit.gd` (RS-stijl, MeshKit-bouwstenen met rs_toon): het **handelshuis** (`handelshuis`, 3x3) met drie marktkramen onder gestreepte luifels, een weegschaal, een uithangbord, waren (kisten, vaten, zakken, stoffen) en een pakhuis met takel; vaandels in de spelerskleur als apart mesh (`TradeKit.owner_banners`, kleur via materiaal zoals het eigenaarsvaandel). De **neutrale stad** (voorlopig `neutral_town`, 4x4): vijf huizen, een palissade met poort, een marktplein met put en kramen, en een neutrale vlag zonder spelerskleur. De **handelskar** (`cart`): een kar met huif, zichtbare vracht en een os met losse poten (loopanimatie en draaiende wielen in `gfx/cart_view.gd`). Het **handelsschip** (`ship_trade`): breder dan de kogge, twee masten met rood-crème gestreepte zeilen, een hut op het achterkasteel en kisten aan dek uit `cargo`; het gebruikt de ShipView-animaties (varen, laden, zinken, schade).
- Alle voorlopige id's en kinds staan centraal in `gfx/trade_ids.gd`. De koppeling loopt alleen via id/kind: één regel in `MeshKit.building`/`MeshKit.icon` en in `ShipKit.ship`, en in `game.gd` de vaandels bij het handelshuis. Nieuwe iconen in `ui/trade_icons.gd` (bouwmenu, kar, schip, handelsroute, munten, handelswaar). Het handelsscherm volgt zodra de API er is.
- Nieuwe test `tests/test_trade_models.gd` (winding, AABB, footprint, koppeling, animaties), het hulpscript `tools/handel_shots.gd`, en `tools/runall_par.sh` kent nu `PARDIR` voor een eigen logmap.
- 0.15 UI: neutrale stad krijgt een LOD-model (TradeKit.town_lod, 452 tris i.p.v. 11.827) dat via visibility_range ver weg (>45 m) inwisselt; CartLayer (gfx/cart_layer.gd) toont handelskarren uit Sim.carts_cached/carts_rev met laad-/losanimatie en vracht uit cargo, veilig zonder karren-API.
### Onverwacht/UI (ui/bergen-bijstellen, past op de nieuwe flanken)
- Bergen afgestemd op de nieuwe drempels (`SNOW_M` 18,25 m, `MOUNTAIN_M` 8,75 m, `H_SCALE` 0,65) en voorbereid op de lange flanken van 0.15:
  - Terreinshader: banden gras → rots → sneeuw vooral op hoogte (plus helling), met zachte ruisranden en grasplekken hoog op de flank. Alle drempels zijn uniforms (`rock_y0`, `rock_y1`, `band_noise`, `grass_patch`, `ledge_slope0/1`, `snow_*`), gevuld door `TerrainInfo.apply_uniforms` uit `MOUNTAIN_M`/`SNOW_M`.
  - Richels alleen op steile kernwanden, fijner (2 per klifhoogte). Grillige toppen lager en zachter. Zachtere sneeuwrand. Flankrots iets lichter.
  - Props: sneeuwkapkeien alleen vlak onder de sneeuwlijn (eerst lag er sneeuw op de hele berg), geen keien of puin meer op een flauwe voet, puin geschaald op de klifhoogte. Grondstofstenen op bergen kleiner en gevarieerder (geen witte spikkelvlakte meer).
- Techboom op de definitieve API: `tech_state().nodes[id]` (cost/time/have/missing/affordable), aangevuld via `Sim.tech_cost` en `Sim.stock_amount`. De voortgangsbalk volgt `Events.tech_progress`. Ververst op `stock_changed(o)`, en op `tick` alleen bij een gewijzigde `Sim.tech_rev`. Geen `_process` of eigen interpolatie meer, en de fallback via json/`stock_of` is weg.
- Screenshots (voor/na, spelcamera, ook een testhoogtekaart met een geleidelijke kegelberg): `/workspace/kolonie-ui-shots/bergen2/`.
### Onverwacht/UI (ui/bouwmenu)
- Bouwmenu gesplitst in een vaste, gecentreerde tabstrook en daaronder een knoppenpaneel dat altijd gecentreerd is en in 0,15 s meegroeit/-krimpt met het aantal knoppen (alleen knoppen + kleine marge). Tabs springen niet meer. Getest bij UI-schaal 1.0/2.0 en 30% langere teksten (tests/test_build_bar.gd).


## 0.14.1 — Lagere bergen en techkosten (26 okt 2026)
### Spel/backend
- **Bergen lager en zachter** (wens van ui/bergen en Mike: "de flanken schieten te hoog op"):
  - **Alle hoogtes x 0,65** (`WorldGen.H_SCALE`). De grenzen schalen mee:
    - `MOUNTAIN_M` gaat van 13,5 naar **8,75 m**. Het bergterrein ligt op dezelfde plek, want de vorm wordt intern nog in ruwe meters bepaald (`MOUNTAIN_RAW` 13,5).
    - `SNOW_M` gaat van 28 naar **18,25 m**.
    - `CLIFF_M` blijft 1,5 m.
    - De hoogste top is nu ±26–30 m (was ±47 m).
  - **Echte toppen**: elk massief heeft cellulaire toppen in plaats van een plateau. Sneeuw ligt alleen op de toppen (seed 42: ±6% van de bergtegels, was ±50%).
  - **Zachte, getrapte flanken**: brede voetheuvels op het grootschalige bergmasker. Heuvelterrassen hebben treden van ±1,95 m (was 3 m), bergflanken van ±1,6 m.
  - **Kliffen alleen bij echte sprongen**: de landhoogte wordt vervaagd met een 5x5-tentfilter, alleen uit de wereldfunctie, dus naadloos over chunkgrenzen; bergen houden hun ruwe toppen. Klifranden tussen begaanbare tegels: seed 42 van 1616 naar 11, seed 7 van 1869 naar 32. Kliffen staan nu vooral nog aan de bergrand en aan steile oevers. Bouwbaar land: 97–98% (was 85–86%).
  - **Bredere rivierdalen** in hoger land.
  - Nieuw: `Sim.corner_height(k)` (hoogte per tegelhoek) en `Sim.tile_corners(c)` (vier hoeken, klifbewust), voor een glad mesh.
  - Een chunk genereren kost nu ±10,6 ms (was 4,4 ms).
  - Meetscript: `tools/relief_stats.gd`.
  - Screenshot vanuit de spelcamera: `docs_screenshot_bergen14.png`.
- **Kosten in de techboom** (voor ui/tech-kosten):
  - Nieuwe velden in `tech_state(o).nodes[id]`:
    - `cost`: {grondstof: aantal}
    - `time`: duur in s
    - `have`: wat er nu in voorraad is
    - `missing`: het tekort, leeg als het betaalbaar is
    - `affordable`: bool
  - `Sim.tech_cost(id)` geeft `{cost, time}`.
  - `Sim.stock_amount(o, res)` geeft de voorraad over alle eigen opslagen. `Sim.stock(o, res)` kon niet als naam: `Sim.stock` is al de voorraad-dict van speler 0.
  - `Events.stock_changed(o)` komt nu per speler, hooguit één keer per tick, en alleen als de HQ- of pakhuisvoorraad veranderde. Dit was `stock_changed(Dictionary)`; de HUD is minimaal aangepast.
  - `Sim.tech_rev` gaat omhoog als `affordable` van een node omslaat.
  - `Events.tech_progress(o, id, frac)` komt hooguit één keer per seconde tijdens het onderzoek.
- **Nieuwe checksums** (seed 42):
  - kaart 48x48: **1124135190**
  - chunk (0,0): **4112961827**
  - chunk (1000,−777): **2911011259**
- Een paar tests met vaste geometrie draaien nu op een vlakke kaart: m6 duel, m7 walk_back, m10 auto-route en m13 pull.
- **AI-fix**: de AI legt niets anders meer aan zolang er geen afgebouwde zagerij is en er minder dan 6 planken zijn (anders kon "moeilijk" op hellingen vastlopen zonder planken). De AI kiest ook liever vlakke bouwplekken.
- **Save/load-fix**: chunks die nog op de achtergrond voor een vorige kaart werden gegenereerd, kwamen soms in de geladen wereld terecht. Laden en nieuw spel gooien die wachtrij nu weg.
- `tools/runall_par.sh` gebruikt overal `PARDIR` (standaard `/tmp/par_backend`).
### Onverwacht/UI (ui/tech-kosten)
- Techboom: elke kaart toont kosten per grondstof (icoon + bedrag) en onderzoeksduur; tekort rood als heb/nodig (bv. 12/20), alles betaalbaar groen, anders goud; tooltip met "Tekort: …". Ververst op `Events.stock_changed` (anders 1 s zolang open). Bron: tech_state-velden (0.14) > `Sim.tech_cost` > techboom.json + `Sim.stock_of`. Test: tests/test_tech_costs.gd.
### Onverwacht/UI (ui/bergen: mooiere bergen, techboom zonder polling)
- Bergen: grillige toppen, klifwanden met richels, spleten en AO, en hoekige rotsfacetten. Sneeuw (hoogte = biome `snow`) heeft een zachte rand. Er staan geen mosstenen of keien meer in de sneeuw: rotsen vlak onder de sneeuwlijn krijgen een witte kap (`gfx/materials/rock_snow.gdshader`), en aan de voet van kliffen ligt puin. Techboom: verversen via `Events.tech_started`/`tech_researched` en `Sim.tech_rev` in plaats van elke 0,25 s. De tooltip van een vergrendelde node toont de reden (`blocked` via `Sim.error_key`) naast de DESC-tekst.

## 0.14.0 — Olifantenpaadjes
- **Buiten de weg lopen**: dragers, werkers, wandelaars en ridders lopen ook door het veld (nooit over een klif), maar trager dan op een weg: ongeveer 0,6x op gras, 0,45x in het bos, en extra trager op een helling.
- **Slijtage**: elke voetstap buiten de weg slijt de grond in (`Sim.wear(c)`, 0..1). Vanaf 0,3 is het een zichtbaar paadje, waar je ook sneller loopt (tot 1,5x). Ongebruikte paadjes groeien vanzelf weer dicht (vol ingesleten is na ongeveer 17 minuten weer weg).
- **Voorstel**: is een paadje tussen twee eigen vlaggen druk genoeg (slijtage 0,6), dan stelt het spel één keer voor om er een weg van te maken (`Events.trail_suggest`). Omzetten kost hetzelfde als een gewone weg, maar de aanleg gaat twee keer zo snel.
- **Wegniveaus**: aarde (1x), kasseien (1,35x, kost steen) en verhard (1,7x, kost blokken).
- **Lopende band**: een band in drie niveaus (2x, 2,6x en 3,3x). Dragers lopen er niet leeg terug. Een band kost planken en erts.
- **Techboom**: een nieuwe tak Wegen, met Kasseien → Verharding → Transportband I–III.
- **AI**: onderzoekt kasseien en verharding en waardeert zijn drukste wegen op.
- Nieuwe foutcodes 22–27 (o.a. ERR_LOCKED en ERR_ROAD_TIER), in het Nederlands en het Engels.
- Slijtage en wegniveaus worden mee opgeslagen. Het spel blijft deterministisch en de wereldchecksums zijn ongewijzigd.
- Nieuwe test: test_m14.

## 0.13.1 — Reliëf (24 okt 2026)
### Spel/backend
- **Hoogtekaart.** Elke chunk heeft nu een laag `height` (byte, 0,25 m per stap, 0 tot 63,75 m) en een laag `moist` (vocht). Het reliëf bestaat uit glooiend laagland, heuvels met terrassen (treden van 3 m die kliffen vormen), echte bergketens met geribde ruis en sneeuw op de toppen (vanaf 28 m). Berg betekent nu hoogte ≥ 13,5 m, en daar liggen steen en erts. Rivieren volgen dezelfde lopen als voorheen, maar graven een dal. Hun waterspiegel daalt van de bergvoet (≈3,4 m) naar meer of zee, dus er zijn geen watervallen (getest).
- **Kliffen.** Een hoogteverschil van meer dan 1,5 m met een buurtegel is een klifrand. Wegen (A*), automatische wegen, dragers die door het veld lopen en ridderpaden gaan daar niet overheen; schepen werken zoals voorheen.
- **Helling** (0..1, 1 = 2 m verschil met een begaanbare buur):
  - Bouwen kan alleen bij een helling onder 0,6 en zonder klif tussen gebouw en vlag; anders is de reden „te steil” (`WHY_33`, `STATUS_TOO_STEEP`, `ERR_TOO_STEEP`).
  - Op een helling duurt bouwen langer (× (1 + helling)), en vanaf helling 0,25 kost een gebouw 1 plank extra.
  - Dragers lopen trager over hellende wegen (× (1 + 0,6 × gemiddelde helling) per segment).
- **HQ op vlak land.** Spawns zoeken eerst een vlak stuk. Rond elk HQ wordt het terrein geëffend; die effening (`flats`) staat in de save. De hoogte zelf komt niet in de save, maar wordt uit de seed opnieuw gemaakt.
- **API:** `Sim.height(c)` (m), `Sim.slope(c)` (0..1), `Sim.cliff(c)` (bitmasker N=1, O=2, Z=4, W=8), `Sim.moisture(c)` (0..1), `Sim.biome(c)` (`grass`/`forest`/`rock`/`sand_shore`/`snow`, en `water`), plus `Sim.height_to_world(m)` en `Sim.ground_y(pos)` voor de weergave.
- **Nieuwe checksums** (seed 42): kaart 48x48 = **3875125161**, chunk (0,0) = **3390781641**, chunk (1000,−777) = **645936138**. Alle tests zijn bijgewerkt.
- **Techboom voor ui/techboom:** `tech_state(o).nodes[id] = {blocked, done, researching}`, waarbij `blocked` een foutcode is (`ERR_OK`, `ERR_PREREQ`, `ERR_NO_RESOURCES`, `ERR_RESEARCHING`, `ERR_ALREADY_RESEARCHED`, …). Verder `Events.tech_started(o, id)`, `Sim.tech_rev` (telt op bij elke wijziging) en het effect `carrier_tier: 2` op Gilden. Alle `TECH_*_DESC`-teksten noemen nu de getallen (tier 2: 67% sneller).
### Weergave (minimale hooks)
- Het terreinmesh gebruikt `Sim.height` en maakt geen eigen hoogte meer. Klifranden worden verticale wanden; binnen een bergmassief blijft het oppervlak glad. Gebouwen, wegen, vlaggen, bomen, eenheden en schepen staan op de echte grondhoogte.
- `TerrainInfo.apply_uniforms` (één keer) en `TerrainProps.build` (per chunk) van ui/rs-detail zijn aangesloten. `TerrainInfo.height` geeft wereld-y.
- `tools/bench_relief.gd`: een chunkmesh in vol detail kost 74 ms met reliëf en 49 ms zonder; `height`, `slope` en `cliff` samen kosten ≈22 µs per tegel. `bench_anim` (1000 eenheden) blijft op 2,8 ms en de sim op 1,8 ms per tick (4 spelers).
### Tests
- Nieuwe `tests/test_m13_1.gd` dekt kliffen tegen paden en wegen, steil bouwen, duurder en trager bouwen, de looptijdfactor, biomen en sneeuw, samenhangende rivieren, determinisme, save/load zonder hoogte, de nieuwe checksums en de techboom-API.
- Oudere tests met vaste coördinaten draaien op een vlakke kaart (`Sim.default_relief = false`). De AI- en veroveringstests (m6, m7, m11) draaien met reliëf en zijn groen.
- `runall_par.sh` schrijft naar een eigen logmap (`PARDIR`, standaard `/tmp/par_backend`), zodat hij niet botst met de runs van de UI-bot.
### Onverwacht/UI (ui/rs-detail: meer detail in RuneScape 3-stijl)
- Gedeeld gestileerd materiaal `gfx/materials/rs_toon.gdshader` (handgeschilderde ruis, zachte toonbelichting, rimlight). Gebouwen hebben nu dakpannen of een rietrand met overstek, rook uit de schoorstenen, verlichte vensters, deurbeslag, funderingsstenen, lantaarns en props, met een kleurtint per gebouw. Bewoners kregen haar, een vest, een riem met buidel en laarzen, en variatie in haar-, huid- en kledingkleur zonder extra LOD-kosten. Schepen kregen planken, een reling, want, een zeil met embleem en lantaarns. Het terrein heeft rotshellingen (triplanar), sneeuw op de toppen en wuivend gras; `TerrainInfo` en `TerrainProps` liggen klaar voor `Sim.height`, `Sim.slope` en `Sim.cliff`.
### Onverwacht/UI (ui/techboom)
- **Techboomscherm** (`ui/tech_tree.gd`) in de RS-stijl (navy/goud). De nodes staan op het raster uit `Data.tech` (`col`/`row`), met takkoppen en gouden verbindingslijnen (vol goud als de vereiste klaar is). Elke node toont zijn status: vergrendeld, beschikbaar, wordt onderzocht (met voortgangsbalk) of klaar. De tooltip toont naam, effect (`TECH_*_DESC`), kosten, duur, vereisten en status. Een klik roept `Sim.research(0, id)` aan; een foutcode verschijnt als melding via `tr(Sim.error_key(code))`. Schuiven door te slepen, zoomen met het wiel of met −/+/1:1/[ ] (passend). Openen met de knop in de bovenbalk of met **K** (T is de vlagrichting, F3 het debugpaneel), sluiten met Esc of het kruisje. 14 nieuwe `UI_TECH_*`-sleutels.
- **Eigen icoon per techboom-node** (`ui/tech_icons.gd`, SVG, CC0), met een terugvaloptie per tak.
- **Dragersgilde** (`gfx/guildkit.gd`, 2x2): gildehuis in vakwerk met gildebord, jukkenrek, handkar en manden, plus een bouwmenu-icoon. **Snelle dragers** (`tier == 2`) dragen een gouden sjerp. Met het **Draagjuk** (`capacity == 2`) dragen ze een juk met een vracht aan elke kant (`item2`, anders twee keer hetzelfde). Alleen dichtbij te zien: de LOD van `UnitAnim` is ongewijzigd. `tools/bench_anim.gd` (headless, gemiddelde van 3 runs, 300/1000 eenheden): main 1,61/2,55 ms, deze branch 1,64/2,57 ms, alle dragers snel en met juk 1,66/2,63 ms (binnen de ruis).
- Nieuwe tests `tests/test_techboom_ui.gd` en `tests/test_guild_models.gd`, en het hulpscript `tools/techboom_shots.gd`.

## 0.13 — Techboom (24 okt 2026)
### Spel/backend
- **Techboom** (`data/techboom.json`, `sim/tech.gd`). Er zijn vijf takken; elke knoop heeft `col`/`row` voor de weergave, voorwaarden, kosten en een onderzoekstijd. Er loopt één onderzoek tegelijk. De kosten gaan eerst uit het HQ en daarna uit de andere opslag.
  - **Productie I/II:** zagerij, steenhouwerij en smidse werken 15% en daarna 30% sneller.
  - **Opslag I:** 12 goederen per vlag in plaats van 8. **Opslag II:** 4 goederen aan de uitgang in plaats van 2.
  - **Verdediging:** de echte ridder-tiers 2 en 3 (hp 10/13/16, schade 3/4/5), uitgerekend als duelkans. Bij gelijke tiers blijft de oude balans precies gelijk. **Wachtbereik** geeft wachtposten en torens +2 claimbereik.
  - **Economie:** **Gilden** ontgrendelt het Dragersgilde (2x2). Met een afgebouwd gilde zijn alle dragers snel (tier 2). **Draagjuk** laat ze 2 goederen tegelijk dragen.
  - **Ontsluiting:** **Scheepvaart** ontgrendelt de scheepswerf en de haven.
- API: `Sim.tech_state(o)`, `Sim.can_research(o, id)`, `Sim.research(o, id)`, het signaal `Events.tech_researched(o, id)`, `Sim.is_unlocked(o, type)` en `Sim.knight_tier(o)`. Gebouwen die nog op slot zitten, geven bij `can_place` de reden „niet ontgrendeld”.
- In een nieuw spel zit alles op slot tot je het onderzoekt. In oude saves zonder techboom blijft alles beschikbaar, zonder effecten.
- De AI onderzoekt volgens een eigen volgorde per niveau (`data/ai.json` → `research`) en houdt daarbij een marge in de voorraad aan. Normaal begint met Scheepvaart.
- **Vaste foutcodes.** Schip-, landing- en onderzoekscommando's geven nu een getal terug in plaats van een Nederlandse tekst: `Sim.ERR_OK` (0), `ERR_NO_SHIP`, `ERR_NOT_OWNER`, `ERR_NOT_WARSHIP`, `ERR_NO_TARGET`, `ERR_OWN_TARGET`, `ERR_PEACE`, `ERR_TARGET_TYPE`, `ERR_PLAYER_DEFEATED`, `ERR_NO_KNIGHTS`, `ERR_NO_ROUTE`, `ERR_NO_SHORE`, `ERR_OUT_OF_RANGE`, `ERR_NO_PATH`, `ERR_SHIP_BUSY`, `ERR_UNKNOWN_TECH`, `ERR_NO_TECH_TREE`, `ERR_ALREADY_RESEARCHED`, `ERR_RESEARCH_BUSY`, `ERR_PREREQ_MISSING`, `ERR_NO_RESOURCES` en `ERR_UNKNOWN`. Gebruik `Sim.error_key(code)` voor de i18n-sleutel `ERR_*` (nl+en) en `Sim.error_text(code)` voor de vertaalde tekst.
- **Vloot (backend voor ui/vloot):**
  - Ook transportschepen kunnen landen. Lading die nog aan boord is, gaat eerst de haven in.
  - `Sim.can_land(o, schip, gebouw)` geeft een foutcode. `Sim.knights_free(o)` is nu officieel.
  - `Sim.ship_attack(o, schip, doel)` werkt ook op vijandelijke gebouwen aan de kust (binnen 3,5 tegels van bereikbaar water). Het doel is een schip-id als er een vijandelijk schip met dat id bestaat, anders een gebouw-id. Een beschieting doodt verdedigers (garnizoen tot 1, of ridders in de opslag) maar verovert niet; daarvoor blijft een landing nodig.
### Reparaties uit 0.12
- **Terugvaart:** het schip wacht na een landing tot 90 s aan de kust. Ridders die het overleven, varen mee terug naar de haven of werf, en anders naar het HQ.
- **Havens trekken goederen aan:** elke haven houdt een vraaglijst bij van wat het net achter een partnerhaven nodig heeft. Dragers brengen die goederen (tot 8 per soort) naar de haven, en het transportschip neemt ze mee. Een route over water telt pas als de weg minstens 1,5 keer zo lang is. De ship-API is niet veranderd.
### Onverwacht/UI (merge van ui/vloot, 0.12.1)
- Werfpaneel, schipselectie, landingspaneel en vlootteller van de UI-bot zijn samengevoegd. `ship_ui.gd` zet de foutcodes om met een kleine helper `_err()`.
### Tests
- Nieuwe `tests/test_m13.gd` dekt kosten en voorwaarden, effecten, ridder-tiers in een gevecht, Dragersgilde met 2 goederen, save/load (ook een oude save), het onderzoek van de AI, determinisme, de terugvaart, de vraag tussen havens, landing per transportschip, beschieting en de foutcodes.
- `test_m6` is robuuster: alle lussen zijn begrensd in ticks, er komt altijd een RESULT-regel, en bij parallel draaien (`KOLONIE_PAR`) geldt een ruimere tijdsgrens. `test_menu_flow` zet de echte-tijd-ticks stil (`Engine.time_scale = 0`) rond quickload.

## 0.12.1 — Vloot-UI (opgenomen in 0.13)
### Onverwacht/UI (ui/vloot: bediening van de vloot)
- **Scheepswerfpaneel** (`ui/ship_ui.gd`, onder het infopaneel): transportschip of oorlogsschip bestellen, schakelaar Herhalen, voortgangsbalk uit `b.ship_progress` en een knop Bestelling annuleren (`set_ship_order(b, "", false)`).
- **Schip selecteren:** klik op een schip voor een gouden selectiering en een infopaneel met romp-hp, vrachticonen, taak en toestand. Rechtsklik op water = `ship_move`, rechtsklik op een vijandelijk schip = `ship_attack`. Rechtsklik op een vijandelijk gebouw opent de landing, want `ship_attack` kent alleen schepen.
- **Landing:** knop „Landing…”, doel kiezen met een rechtsklik, aantal ridders met een slider (tot `Naval.knights_free`), daarna `naval_landing`. Kan het niet, dan staat de reden van de sim in het paneel.
- **Vlootteller** linksboven (`Vloot n/8`) met een klikbare lijst van de eigen schepen.
- Alles via `tr("UI_...")` (32 nieuwe sleutels, live taalwissel), houten panelen in navy/goud, geen vaste knopbreedtes. `game.gd` krijgt alleen invoerroutering. Werf en haven draaien nog maar één keer (via `b.water` in `_water_yaw`). Nieuwe test `tests/test_ship_ui.gd` (mock-sim) en het hulpscript `tools/vloot_shots.gd`.

## 0.12 — Scheepvaart (24 okt 2026)
### Spel/backend
- **Scheepswerf** (`scheepswerf`, 3x3, kost 4 planken en 2 steen): staat aan de oever. De werf moet een watertegel raken (`b.water`); daar ligt de helling. Een scheepsbouwer (een kolonist) bouwt schepen uit planken: een transportschip kost 6 planken en duurt 40 s, een oorlogsschip kost 8 planken en duurt 60 s. Er zijn nog geen zeil of ijzer, dus alleen planken. De bestelling staat in `b.ship_order` (de speler krijgt standaard één transportschip); `Sim.set_ship_order(b, kind, repeat)`. Het bouwstadium staat in `b.ship_progress` (0..1) en `b.ship_kind`. Maximaal 8 schepen per speler.
- **Haven** (`haven`, 2x2, kost 3 planken en 2 steen): een opslagplaats aan de oever en de aanlegplaats voor schepen.
- **Schepen** varen over watertegels, met een deterministische A* (8 richtingen, geen hoeken afsnijden).
  - **Transportschip** (8 plaatsen, 12 hp): vaart vanzelf tussen twee eigen havens aan hetzelfde water, als die niet over de weg verbonden zijn of als de weg langer is. Het trekt de voorraad gelijk; ridders blijven aan land.
  - **Oorlogsschip** (30 hp, 3 schade per seconde, bereik 2,5 tegel): valt vijandelijke schepen binnen 8 tegels vanzelf aan, of op bevel (`Sim.ship_attack`).
  - **Landing** (`Sim.naval_landing(o, schip, doelwit, n)`): het oorlogsschip haalt ridders op bij de dichtstbijzijnde eigen haven of werf, vaart naar een kustplek binnen 12 tegels van het doelwit en zet ze daar af voor een gewone aanval. Ridders die het overleven, komen meteen terug in een eigen gebouw: er is nog geen terugvaart.
  - Gezonken schepen verdwijnen na 3 s, samen met hun lading.
- **API:** `Sim.ships(o)` en `Sim.ships_cached(o)` geven per schip `id`, `owner`, `kind` (`ship_transport`/`ship_war`), `pos`, `prev`, `heading`, `speed`, `cargo` (lijst van goed-id's), `cargo_max`, `hp`, `hp_max`, `anim_state` (`idle`/`sail`/`load`/`unload`/`fight`/`sink`), `anim_target`, `task` en `tile`. Daarnaast `Sim.ship_move` en de signalen `Events.ship_built` en `Events.ship_sunk`.
- **AI:** bouwt na zijn bouwplan een haven en een scheepswerf als er water in zijn gebied ligt. Hij bestelt oorlogsschepen bij dreiging over water of als de vijand over land onbereikbaar is, en dan doet hij ook landingen. Met twee havens neemt hij een transportschip. De verovertests (normaal tegen normaal) blijven groen.
- Nieuwe sleutels in `kolonie.csv` (nl/en): BLD_SCHEEPSWERF, BLD_HAVEN, UNIT_SHIP_TRANSPORT, UNIT_SHIP_WAR, STATUS_NO_WATER, STATUS_BUILDING_SHIP, MSG_SHIP_BUILT, MSG_SHIP_SUNK, MSG_NAVAL_LANDING.
- Schepen worden opgeslagen in de save (alleen als er ooit een schip is geweest, zodat spellen zonder schepen dezelfde state-hash houden). De checksums blijven gelijk.
- Nieuwe test `test_m12`: bouwen aan de oever, een schip bouwen, transport tussen twee havens, een zeeslag, een landing, de AI die een werf bouwt bij water, save/load en determinisme.

### Onverwacht/UI (ui/scheepswerf: modellen, iconen en animaties voor de scheepvaart)
- **Eigen procedurele modellen** in `gfx/shipkit.gd` (MeshKit-stijl, geen externe assets): scheepswerf (3x3, helling met schip in aanbouw, kraan, steigerwerk, houtopslag en werkplaats), haven (2x2, steiger, bolders, kisten, kleine kraan en pakhuis), kogge (`ship_transport`, zeil, ruim met kisten per vrachtsoort uit `cargo`) en oorlogsschip (`ship_war`, groter, vlag en schilden in spelerskleur, ijzeren ram). Schadebeeld bij `hp/hp_max` < 50 % en < 25 %. Bouwstadia op de helling (kiel → spanten → beplanking → dek → mast) uit `b.ship_progress`/`b.ship_kind`. Werf en haven draaien met +z naar het water, net als de vissershut.
- **Animaties** (`gfx/ship_view.gd`, `gfx/ship_layer.gd`): dobberen, kielzog bij varen, laden/lossen met een kist tussen steiger en ruim, vechten, zinken (kantelen, wegzakken, bellen en wrakhout). Eén gecachete mesh per schip en alleen transforms per frame (~0,07 ms voor 6 schepen). Haakt pas in als `Sim.ships` bestaat; tot dan verandert er niets in het spel.
- Alle id's, kinds, anim-states en veldnamen staan centraal in `gfx/naval_ids.gd`. Nieuwe bouwmenu-iconen in `ui/icons.gd`, 9 nieuwe i18n-sleutels, nieuwe test `tests/test_ship_models.gd` (AABB's, winding en normalen naar buiten per deel) en het hulpscript `tools/scheepswerf_shots.gd`.

## 0.11.4 — Snellere animaties en losse testmappen (24 okt 2026)
### Spel/backend
- **Elke test krijgt zijn eigen map voor instellingen en saves.** Een headless test (`-s res://tests/test_<naam>.gd`) gebruikt automatisch `user://test_<naam>/` (dus `settings.cfg` en `saves/` daarin). Daardoor kunnen tests parallel draaien zonder dat ze elkaars savebestanden overschrijven (eerder faalde `test_menu_flow` daardoor).
- Overschrijven kan met de omgevingsvariabele `KOLONIE_DATA_DIR` of met `-- --data-dir=<pad>`. Het spel zelf blijft `user://` gebruiken.
- `GameSettings.data_root()`/`cfg_path()` worden nu overal gebruikt: in de instellingen, `SaveSystem.DIR`, de grafische kwaliteit in AssetLib en de pad-keuze in `game.gd`.
- Nieuw script `runall_par.sh` (parallel, 8 tegelijk): alle 25 tests OK in ~77 s (serieel ~3,5 min). Getest zowel serieel als twee keer parallel.
- Opnieuw gemeten met `tools/bench_units.gd`: volledige weergave-update 1,39 ms bij 300 eenheden en 3,64 ms bij 1000 eenheden (in 0.11.3: 2,36 en 6,18 ms).

### Onverwacht/UI (ui/anim-perf: snellere UnitAnim.update)
- **Verre eenheden (LOD) hebben een vaste plek** in één `PackedFloat32Array` per MultiMesh (`lod` en `lod_load`, 12 floats transform + 4 kleur), die in één keer via `multimesh.buffer` wordt doorgegeven in plaats van per instantie `set_instance_transform`/`set_instance_color`. Vrije plekken krijgen een nul-transform en worden hergebruikt; bij veel gaten wordt alles opnieuw toegewezen.
- **Verre eenheden worden gespreid bijgewerkt:** lopend om de 2 frames, stilstaand om de 8 frames (`FAR_EVERY_MOVE`/`FAR_EVERY_IDLE`, gespreid per id). Wie niet aan de beurt is, laat zijn plek in de buffer staan. De opgespaarde tijd telt mee bij de volgende beurt (loopfase, en de afvlakking van richting en snelheid wordt samengesteld alsof elke frame was bijgewerkt). Is de lijst dezelfde als de vorige frame (`from_sim` tussen twee ticks), dan wordt een eenheid die niet aan de beurt is overgeslagen zonder haar dictionaries te lezen.
- **Dichtbij:** romp, hoofd, armen en benen gaan rechtstreeks naar hun MultiMesh (geen naam-opzoeking per deel), de handen worden alleen berekend als er gereedschap, een schild of een vis in zit, en de `MeshKit.PART_*`-maten zijn lokale constanten. Minder dictionary-werk en geen `stats`-dictionary meer per frame.
- Gemeten met `tools/bench_units.gd` (nieuw: `anim_update` = alleen `UnitAnim.update`, gemiddelde van 2 runs, llvmpipe): bij 300 eenheden van 1,72 naar 0,78 ms, bij 1000 eenheden van 4,85 naar 2,54 ms. De volledige weergave-update (`from_sim` + animatie) gaat van 2,30 naar 1,36 ms en van 5,96 naar 3,66 ms.
- **Visueel:** dichtbij is alles getalsmatig gelijk (`tools/anim_dump.gd`: alle transforms en kleuren dezelfde tot op 1e-3) en de close-ups uit `tools/anim2_shots.gd` zijn pixelgelijk (contactsheet in `kolonie-ui-shots/anim-perf/`). Compromis bij de verre eenheden (> 18 tegels): een draai of state-wissel komt tot 8 frames later in beeld, lopers schuiven met 30 in plaats van 60 updates per seconde, en de overgang van ver naar dichtbij kan tot 8 frames later vallen als de camera beweegt.
- Nieuwe hulpscripts: `tools/bench_anim.gd` (microbenchmark van alleen `UnitAnim.update`, optioneel met een nieuwe lijst per sim-tick) en `tools/anim_dump.gd` (dumpt alle instanties om twee versies te vergelijken). `UnitAnim.last_cost_us` geeft de CPU-tijd van de laatste update.
- Geen wijzigingen aan de sim, `scenes/game.gd`, worldgen of data; de checksums blijven 1990944826 / 3114690342 / 2317426177.

## 0.11.3 — Snellere eenheden en marcherende ridders (24 okt 2026)
### Spel/backend
- **Goedkoop pad voor de weergave:** `Sim.units_cached()` geeft een gedeelde, alleen-lezen lijst die hooguit één keer per tick opnieuw wordt opgebouwd (of eerder, als er eenheden, gebouwen of aanvallen bij komen of verdwijnen). `Sim.units_rev` telt elke herbouw. `Sim.units_into(arr)` vult een eigen array met dezelfde lijst. `UnitAnim.from_sim(..., rev)` werkt tussen twee ticks alleen de posities bij.
  - Gemeten met `tools/bench_units.gd`, update van de weergave: van 4,9 naar 2,4 ms bij 300 eenheden en van 12,6 naar 6,2 ms bij 1000 eenheden. Wat overblijft is het tekenen van de poses.
  - `Sim.units()` + `from_sim` samen: van ~2,1 naar 0,12 ms per frame bij 300 eenheden (`tools/bench_units_split.gd`).
- **Ridders op weg van de kazerne naar een post** staan nu in `Sim.units()` als `kind: "knight"` met `role: "march"` en `tier`, niet meer als drager met item `knight`.
- Aanvallende en terugkerende ridders krijgen hun echte `tier` (uit de aanval; standaard 1, want ridders hebben nog geen tiers in de sim).
- Een visser die met vangst naar huis loopt (zijn hut wordt gesloopt terwijl hij een vis draagt) houdt `item: "fish"` en `fish_caught`.
- `game.gd`: de ongebruikte `_add_workers`/`_add_unit` zijn verwijderd.
- Nieuwe test `test_m11_3` (tier, march, vangst, cache en een prestatie-eis van < 2 ms, state-hash-neutraal, checksums).

### Onverwacht/UI (ui/i18n: alle UI-teksten vertaald en live)
- **Alle UI-teksten lopen nu via `tr("UI_...")`.** HUD, pauzemenu, infopaneel, prioriteiten, statistieken, annuleer-hint, debugpaneel (F3) en het hoofdmenu. De UI-sleutels hebben voortaan allemaal het voorvoegsel `UI_` (`HUD_*` → `UI_HUD_*`, `MENU_*` → `UI_MENU_*`, `CAT_`/`TIP_`/`HINT_` en `STOCK`/`ROAD`/`FLAG`/`DEMOLISH` idem). `BLD_`/`RES_`/`STATUS_`/`MSG_`/`DLG_`/`MAP_`/`AI_` blijven zoals ze zijn.
- `UiText.t` is vervangen door `tr()`, en `ui/ui_text.gd` is verwijderd.
- 28 nieuwe sleutels in `i18n/kolonie.csv` (pauzemenu, tooltips in de bovenbalk, grafische kwaliteit Laag/Middel/Hoog, debugpaneel, voorraad-tooltip, enz.), elk met een Engelse vertaling.
- **Live taalwissel overal**, via `NOTIFICATION_TRANSLATION_CHANGED` en het nieuwe `ui/ui_tr.gd` (`UiTr.bind`/`UiTr.key`/`UiTr.items`/`UiTr.refresh`): de teksten worden ter plekke vervangen. Dat geldt ook voor het Esc-/pauzemenu tijdens een lopend spel, het infopaneel, de statistieken en de statuschip. Het hoofdmenu wordt niet meer herladen, dus de achtergrond, de muziek, de ingevulde seed en de open pagina blijven staan.
- **Langere Engelse teksten:** labels in het hoofdmenu lopen nu door over meerdere regels in plaats van uit te lopen, en ook de teksten in de statistieken wrappen. Op smalle schermen (1080p) worden de tussenruimtes in de bovenbalk krapper, zodat de menuknop niet meer buiten beeld valt (dat gebeurde in 0.11.2 al in het Nederlands).
- Nieuwe test `test_i18n_ui`: `ui_text.gd` is weg, het hoofdmenu, het pauzemenu en de statistieken wisselen live van taal, de invoer blijft behouden, en in het Engels staat er geen Nederlandse UI-tekst meer in beeld.
- Nieuw hulpscript `tools/i18n_shots.gd`: maakt screenshots per taal en resolutie en controleert of er tekst wordt afgekapt of buiten beeld valt.

### Onverwacht/UI (ui/animaties-v2: animaties op de nieuwe velden van Sim.units())
- **De weergave leest nu rechtstreeks `Sim.units()`**, via `UnitAnim.from_sim()`. Die interpoleert `prev` → `pos` (prev is nu echt voor dragers en lopers) en slaat eenheden binnen gebouwen over. De eigen lijstopbouw in `game.gd` is vervangen door één regel.
- **Richting en snelheid komen uit de sim** (`heading`, `speed` in tegels/s) in plaats van afgeleid uit de verplaatsing per frame. Alleen als de sim stilstaat (slenterende dragers) valt de weergave terug op de verplaatsing.
- **Slagen op het ritme van de cyclus:** bijl, pikhouweel en schoffel slaan een geheel aantal keren per productiecyclus (`work_phase`), en de laatste klap valt precies op het einde van de cyclus (rekening houdend met de vis-versnelling). Bouwers houden een eigen hamerritme, omdat hun `work_phase` de bouwvoortgang is.
- **Visser:** kijkt naar zijn watertegel (`anim_target`), en op de terugweg (`fish_caught`) draagt hij een vis in de hand, naast de mand op zijn rug.
- **Ridders lopen nu als echte poppetjes.** Aanvallers en terugkerende ridders (`kind: "knight"`, id's vanaf 1800000000) en ridders die van de kazerne naar een post gaan (een drager met item `knight`, zonder kist) dragen een helm, een schild en een speer of zwaard. Per tier: 1 = leren kap, 2 = ijzeren helm met neusstuk en maliën, 3 = gepolijste helm met gouden band, pluim en maliën. Bij de aanval: stevige pas, schild voor de borst en het wapen rechtop. Bij de terugkeer: het wapen laag en een tragere pas.
- De oude aanvallersmesh (één groot poppetje per aanval, `_attacks_mm`) is verwijderd.
- Lopers naar huis dragen niets (`item` null).
- Prestaties (`tools/bench_units.gd`, CPU-tijd van de weergave-update): bij 300 eenheden van 3,2 naar 5,0 ms, bij 1000 eenheden van 8,1 naar 12,5 ms. De extra tijd zit vooral in `Sim.units()`, dat elke frame alle eenheden kopieert.
- Nieuwe test `test_anim_v2`, nieuw hulpscript `tools/anim2_shots.gd` (contactsheet, ridders, demo-video).
- Geen wijzigingen aan de sim, worldgen of data; de checksums blijven 1990944826 / 3114690342 / 2317426177.

## 0.11.2 — English (24 okt 2026)
### Spel/backend
- **Kolonie is nu ook in het Engels te spelen.** Kies de taal in Instellingen (Nederlands / English). Het wisselen gebeurt meteen, ook tijdens een spel.
- De standaardtaal is de systeemtaal als die Nederlands of Engels is; anders Nederlands. De keuze wordt bewaard in de instellingen (`[display] locale`).
- Alle teksten staan in `i18n/kolonie.csv` (sleutel, nl, en): gebouwen, goederen, statussen, redenen waarom bouwen niet kan, meldingen, het hoofdmenu, de HUD, het pad-dialoog en de hints. `UiText.t` probeert eerst de vertaling en valt terug op het Nederlands.
- De taal zit niet in de simulatie: de interne status blijft Nederlands, dus savegames, determinisme en de terrein-checksums blijven gelijk.
- Het wijzigingslog zelf blijft Nederlands.
- Nieuwe test `test_m11_2`: elke sleutel heeft nl en en, er worden geen sleutels in de code gebruikt die niet in de csv staan, live wisselen verandert de bouwknoppen, en determinisme en checksums blijven ongewijzigd.
- Het debugpaneel (F3) blijft Nederlands.
- `Sim.units()` geeft nu per eenheid ook `heading` (richting), `speed` (tegels/s), `work_phase` (0..1 in de werkcyclus), `tier` en `item`. De visser heeft een `anim_target` op het water en `fish_caught`. Ridders die aanvallen of terugkeren staan als `kind: "knight"` in de lijst (met `role` attack/return). Alles wordt afgeleid, dus de state-hash blijft gelijk.

### Onverwacht/UI (ui/animaties: procedurele animaties)
- **Procedurele animaties voor alle kolonisten** (arbeiders, bouwers, dragers, lopers en lopers naar huis), in het nieuwe `gfx/unit_anim.gd` (`UnitAnim`). Puur weergave: de sim, worldgen en data zijn ongewijzigd, de checksums blijven 1990944826 / 3114690342 / 2317426177.
- **Poppetje in losse delen** (`MeshKit.part`): romp, hoofd (met neus, zodat de kijkrichting zichtbaar is), twee armen en twee benen, elk met een pivot op heup, nek of schouder. Per deel is er één MultiMesh voor alle eenheden, dus het aantal draw calls ligt vast (~25), los van het aantal eenheden.
- **LOD:** eenheden verder dan 18 tegels van de camera gebruiken het oude poppetje uit één stuk en wippen alleen.
- **Per state:**
  - lopen: arm- en beenzwaai synchroon met de werkelijke snelheid, draaien in de looprichting;
  - `carry_walk`: last op de rug (boomstammen, planken, steen of erts, mand met vis, of een kist), voorovergebogen met een kortere en tragere pas;
  - `idle` en `wait_flag`: ademen, rondkijken, af en toe de schouders ophalen of een stapje verzetten (bij de vlag met de armen over elkaar);
  - `stroll`: slenteren met de handen op de rug;
  - `chop` (bijl), `mine` (pikhouweel), `build` (hamer), `farm` (schoffel): heffen, kort vasthouden en een snelle slag;
  - `saw`: heen-en-weer zagen;
  - `fish`: hengel uitwerpen, dan een lijn met een dobber die op het water deint en af en toe onderduikt;
  - `fight`: zwaard (of speer bij oneven id) met schild in de eigenaarkleur;
  - `return_home`: lopen met lege handen en een ruimere armzwaai.
- **Zachte overgangen:** bij elke state-wissel vloeit de pose in 0,2 s over vanaf de laatst getoonde pose.
- Werkende eenheden draaien naar `anim_target`.
- **Eigen procedureel gereedschap (CC0):** bijl, pikhouweel, hengel, hamer, zaag, schoffel, zwaard, speer, schild en dobber (`MeshKit.tool`).
- `scenes/game.gd`: de oude interpolatie met wipbeweging (`_update_workers_view`, de dragerlus en `_heading`) is vervangen door het verzamelen van eenheden en één aanroep van `UnitAnim.update`. De draaglast van dragers wordt nu door UnitAnim getekend.
- **Prestaties (300 eenheden, Xvfb + llvmpipe):** de weergave-update ging van ~1,6 naar ~3,2 ms per frame. De frametijd wordt gedomineerd door de software-renderer (~400–460 ms voor en na).
- Nieuw: `tests/test_anim.gd`, `tools/bench_units.gd`, `tools/anim_shots.gd`. Er zijn geen nieuwe UI-teksten.

## 0.11.1 — Levende kolonisten (24 okt 2026)
### Spel/backend
- **Arbeiders lopen echt naar hun werk en terug**, tegel voor tegel en deterministisch:
  - de houthakker loopt naar een boom, hakt en de boom verdwijnt;
  - de steengroevewerker gaat naar een rots;
  - de visser loopt naar de waterkant;
  - de bosbouwer plant op een vooraf gekozen plek;
  - de mijnwerker gaat de mijn in (onzichtbaar);
  - zagerij, steenhouwer, smid en kazerne werken bij de deur.
- De productietijden zijn ongewijzigd: het lopen telt mee in de cyclus (maximaal 30% per richting). De werker loopt naar het doel dat bij de start van de cyclus het dichtstbij lag. De oogst blijft de oude regel volgen (dichtstbijzijnd aan het eind), wat vrijwel altijd hetzelfde doel is. Oogsten op het startdoel of de RNG-volgorde van de bosbouwer aanpassen veranderde de economie zo, dat Normaal niet meer veroverd werd; daarom kiest de bosbouwer zijn loopdoel via een hash en blijft de plantplek bij de sim-RNG.
- **Bouwers** wachten bij de vlag tot het materiaal er is. Daarna lopen ze naar de bouwplaats en bouwen er.
- **Vrije dragers** wachten om de 4 s bij de vlag of slenteren 1–2 tegels rond hun rustpunt. Dat wordt deterministisch gekozen (een hash, niet de sim-RNG), dus de economie verandert niet.
- **Naar huis:** de bewoner van een gesloopt gebouw loopt naar het dichtstbijzijnde HQ of woonhuis en wordt daar vrije kolonist. Onderweg telt hij mee in de bevolking. Bewoners van verbrande gebouwen gaan verloren, zoals voorheen.
- **API voor de UI-bot:**
  - `Sim.units(o = -1)` geeft een lijst eenheden: `{id, owner, kind ("worker"|"builder"|"carrier"|"walker"|"home"), building/segment, anim_state, anim_target (Vector2 of null), pos, prev (Vector2, tegelcoördinaten; tussen ticks interpoleren met de tick-fractie), inside, item}`.
  - `anim_state` is een van: idle, walk, carry_walk, wait_flag, stroll, chop, mine, fish, build, saw, farm, fight, return_home.
  - Het signaal `Events.unit_anim_changed(unit_id, state)`.
  - Arbeiders staan ook in `b["worker"]`, bouwers in `b["builder"]` en dragers in `sg["carrier"]` (`anim_state`/`anim_target`/`id`). Lopers naar huis staan in `Sim.home_walkers`.
- Minimale weergave in game.gd: arbeiders, bouwers en lopers bewegen vloeiend tussen tegels en wippen tijdens het lopen; vrije dragers slenteren zichtbaar.
- **Dragers tellen nog niet mee in de bevolking.** Elke weg krijgt automatisch een drager; zou die een kolonist kosten, dan valt de start (30) al bij ~25 wegen vol en raakt de balans en de AI-verovering uit evenwicht. Dit is voor later.
- Oude saves blijven werken: eenheden worden bij de eerste tick aangemaakt. De terreinchecksums zijn ongewijzigd (1990944826 / 3114690342 / 2317426177).
- `Sim.population_free(o)` geeft het aantal vrije kolonisten.
- De vissershut wordt in het spel zo gedraaid dat de steiger (+z) naar het dichtstbijzijnde water wijst.
- De UI-takken ui/annuleren-knop, ui/statistieken en ui/woonhuis-visser zijn samengevoegd.
- Tests: `tests/test_m11_1.gd`.
### Onverwacht/UI
- **Annuleer-hint (bouw-, weg- en sloopmodus):** de kale knop is vervangen door een balk in de navy/goud-stijl: icoon + naam van de actieve modus ("Bouwen: Houthakker", "Weg aanleggen", …), een rood getinte RS-knop "Annuleren" met eigen SVG-kruis, een toetskapje "Esc" en een eigen rechtermuisknop-icoon. Fade-in bij openen; breedte groeit mee met de tekst (geen vaste breedtes).
- **Actief-staat bouwknoppen:** de gekozen knop krijgt een goud kader, dikkere onderrand, gouden gloed en gouden tekst.
- Nieuwe tekstsleutels: `UI_CANCEL`, `UI_CANCEL_TIP`, `UI_KEY_ESC`, `UI_OR`, `UI_RMB`, `UI_MODE_BUILD`, `UI_MODE_ROAD`, `UI_MODE_FLAG`, `UI_MODE_DEMOLISH` (via `UiText.t()`, dat `tr()` gebruikt met Nederlandse terugval).
- **Statistiekenpaneel (F2 of de grafiekknop in de bovenbalk):** RS-venster met per grondstof een rij: icoon, binnen/min, verbruik/min, netto (groen/rood) en een sparkline (productie gevuld groen, verbruik rood). Waarden uit `Sim.stats_rates()` (venster 60 s), ververst op `Events.stats_updated`.
- Klik op een rij: grote lijngrafiek over de tijd (`Sim.stats_history()`, 1 punt per 30 s, tot 1 uur) met assen, rasterlijnen, labels (minuten terug, "nu"), legenda en de voorraad op een eigen schaal rechts. Nogmaals klikken klapt de grafiek in.
- Nieuwe tekstsleutels: `UI_STATS_TITLE`, `UI_STATS_CLOSE`, `UI_STATS_SUB`, `UI_STATS_GOOD`, `UI_STATS_PROD`, `UI_STATS_CONS`, `UI_STATS_NET`, `UI_STATS_TREND`, `UI_STATS_STOCK`, `UI_STATS_EMPTY`, `UI_STATS_HINT`, `UI_STATS_ROW_TIP`, `UI_STATS_NOW`, `UI_STATS_AXIS_X`, `UI_STATS_BTN`, `UI_GOOD_<GOED>`.
- **Woonhuis** (`house`, 2×2): eigen procedureel model in plaats van de placeholder: stenen onderbouw, overkragende vakwerkverdieping met consoles, bloembakken, dakkapel, pannendak met schoorsteen en een tuintje met hekje, bankje en regenton. Ook een eigen bouwmenu-icoon.
- **Vissershut** (`fisher`, 2×2): hut met rieten dak, steiger op palen het water in (+z-zijde), bootje met roeispaan, visnetten met drijvers, droogrek met vissen, mand met vangst, ton en kist. Bouwmenu-icoon met water en vis.
- Footprints ongewijzigd (data/buildings.json, size 2).
- **Bevolking in de bovenbalk:** chip met eigen SVG-icoon (drie kolonisten), "x/y", een vulbalkje (rood als het maximum bereikt is) en een tooltip met uitleg.
- **Vis-icoon** opnieuw getekend (eigen SVG, CC0).
- Nieuwe tekstsleutels: `UI_POP_TITLE`, `UI_POP_TIP`, `UI_POP_FULL`, `UI_POP_GROW`, `UI_POP_NOTE`.

## 0.11.0 — Water, vis, bevolking en statistiek (23 okt 2026)
### Spel/backend
- **Rivieren en meren:**
  - Rivieren ontspringen aan de bergvoet en worden breder naar het laagland, tot ze uitkomen in een meer of de zee.
  - Een rivier is een smalle band langs de nullijn van een eigen ruisveld, dus een pure functie van (seed, x, y). Ze loopt daardoor naadloos door over chunkgrenzen, ook op de oneindige kaart.
  - Om de paar tegels ligt er een voorde (een droge plek in een grof 4×4-raster), zodat land niet volledig afgesneden raakt. Bruggen kunnen later komen.
  - Er zijn extra meren bijgekomen.
- Water is niet bebouwbaar en niet begaanbaar. Wegen, auto-pad en de AI-routes lopen eromheen.
- **Vissershut** (2 planken):
  - Moet aan de oever staan (water binnen 2 tegels) en vangt vis binnen straal 4.
  - Een leeggeviste watertegel is na 3 minuten weer vol. De visstand wordt in saves bewaard.
- **Vis als voedsel:** de mijn en de kazerne vragen vis. Met vis is hun cyclus 40% korter; zonder vis werken ze zoals voorheen.
- **Bevolking:**
  - Nieuw gebouw: het **Woonhuis** (1 hout + 2 planken) verhoogt het maximum met 8.
  - Het HQ geeft een basis van 30. De start is gelijk aan voorheen: 24 vrije kolonisten + 6 ridders.
  - Een productiegebouw heeft een bewoner nodig (status "wacht op kolonist"). Elke ridder kost een kolonist.
  - Groei: elke 30 s komt er 1 kolonist bij per woonhuis (+1 voor het HQ), zolang er plaats is.
  - Dragers tellen nog niet mee.
  - API: `Sim.population(o)` en `Sim.population_max(o)`, met het signaal `Events.population_changed(player, pop, max)`. Een minimaal label "Bev. x/y" staat in de bovenbalk; de styling volgt van de UI-bot.
- **Statistiek:**
  - `Sim.stats_rates(o)` geeft per goed `{prod_per_min, cons_per_min, net}` over een glijdend venster van 60 s simtijd.
  - `Sim.stats_history(o, goed)` geeft samples per 30 s (ringbuffer van 120, dus 1 uur), elk met `t`, de drie waarden en `stock`.
  - Het signaal `Events.stats_updated(player)` volgt na elke sample.
  - Verbruik telt input, voedsel en bouwmateriaal.
  - De statistiek is deterministisch en zit in saves. Oude saves beginnen met een lege historie.
  - Een minimale weergave staat onder F3; het paneel volgt van de UI-bot.
- **AI:** bouwt een vissershut als er water in het eigen gebied ligt en er al een kazerne staat (maximaal 2). Een woonhuis bouwt ze zodra de bezette bevolking (bewoners + ridders) op 80% van het maximum zit en er hooguit 2 vrije kolonisten over zijn. Met de eenvoudigere regel "bevolking ≥ 80%" bouwde de AI te vroeg huizen, omdat vrije kolonisten het maximum altijd opvullen, en werd Normaal niet meer veroverd.
- **Nieuwe checksums** (seed 42), omdat het terrein door rivieren en meren verandert. Dit is bewust zo en de nieuwe waarden zijn vastgepind:
  - 48×48: 1990944826 (was 1354473476);
  - chunk (0,0): 3114690342 (was 1836412371);
  - chunk (1000,-777): 2317426177 (was 2373107621).
- Tests: `tests/test_m11.gd`. Normaal wordt nog steeds binnen de testtijd door de AI veroverd (test_m6/test_m7).
### Onverwacht/UI (minimale hooks)
- Placeholder-model voor het woonhuis via MeshKit, een vis-icoon, de vissershut en het woonhuis in het bouwmenu, en het bevolkingslabel.

## 0.10.3 — Poppetjes en menustijl (23 okt 2026)
### Onverwacht/UI
- **Fix: dragers en ridders zagen eruit als halve figuurtjes.** `MeshKit.box()` bouwde de vier zijvlakken met een omgekeerde winding en een normaal naar binnen, waardoor de voorkant werd weggeculd en je de binnenkant van de achterwand zag. De windingfix van 0.10.1 gold alleen voor cilinders en rotsen. Nu krijgen alle vlakken een vaste normaal naar buiten. Dat herstelt ook kisten, houtstapels, tinnen en de goederenkistjes.
- **Nieuwe poppetjes** met een volledig silhouet: hoofd, romp, armen met handen en benen. Dragers hebben een strohoed en een zak op de rug, ridders een helm met punt en neusstuk, een schild in de eigenaarkleur en een speer. Een drager telt ~110 driehoeken en een ridder ~124. Het blijft één mesh per soort (MultiMesh).
- Screenshotscript `tests/make_screenshot_poppetjes.gd` (close-up + in-game).
- **Nieuwe menustijl** (een eigen fantasy-look, alles zelf getekend met StyleBox en gegenereerde texturen, geen externe assets): donkere navy- en leisteenpanelen met dunne bronzen randen en gouden sierhoeken, titelbalken met een gouden Cinzel-titel en een rode sluitknop, secties met kleine kopjes, brede donkere knoppen met een licht verloop en een duidelijke gouden actief-staat.
- Het pauzemenu is nu een optievenster met een rij icoonknoppen (verder, opslaan, laden, prioriteiten, hoofdmenu), de secties Spel, Instellingen (met UI-schaal) en Verlaten.
- Het hoofdmenu heeft een navigatiepaneel, pagina's met een titelbalk en de instellingen in secties.
- Dialogen zoals "Pad aanleggen?" krijgen de stijl via het thema.
- De autosave-melding komt via `Events.autosaved` (het `QUIET_PREFIXES`-filter is weg). Het infopaneel toont de status uit `b.status` via `Sim.status_text()`.
### Spel
- Dragers draaien nu in hun looprichting (zoals ridders) en zijn iets groter (x1,15).

## 0.10.2 — Bugfix: bouwmodus verlaten (23 okt 2026)
- **Fix:** je kon de bouwmodus niet meer verlaten. Nu:
  - Esc annuleert de bouw-, weg-, vlag- of sloopmodus. Het pauzemenu opent alleen als er geen modus actief is.
  - Een rechtermuisklik annuleert de modus. Slepen met de rechtermuisknop (meer dan 8 px) annuleert niet.
  - Nogmaals op de actieve bouwknop klikken (of nogmaals R/F/X drukken) zet de modus uit.
  - Zolang er een modus actief is, staat onderaan de knop "Annuleren (Esc / rechtermuisklik)".
  - Het spel start zonder actieve modus. Een klik op een gebouw opent het gebouwpaneel.
- **Camera draaien:** sleep met de middelste muisknop. Horizontaal draai je om het kijkpunt, verticaal kantel je de camera (35–75°). Slepen met de rechtermuisknop draait ook, maar pas vanaf 6 px; een korte rechtsklik annuleert de modus. Q/E blijven werken. De kanteling wordt opgeslagen in saves (oude saves krijgen de standaardhoek).
- Hint in het help-overzicht en in de tooltip: "Middelste muisknop slepen: camera draaien".
- Nieuwe test `tests/test_m10_2.gd` met input-simulatie.

## 0.10.1 — Nieuwe gebouwmodellen (23 okt 2026)
### Onverwacht/UI
- **Nieuwe gebouwmodellen in Siedler-stijl** (eigen procedurele modellen, CC0, op alle kwaliteitsniveaus):
  - vakwerkwanden met balken en schoren, stenen sokkels, rieten, houten en pannen- of leidaken met overstek, nokbalk en dakrijen, schoorstenen, deuren met drempel en vensters met luiken;
  - per type een herkenbaar silhouet: burcht met vier hoektorens (HQ), lange schuur met hijsbalk en laadperron (opslag), kwekerij met hek (bosbouwer), stammenstapel en hakblok (houthakker), open zaagloods met zaagblad (zagerij), rotswand en kraan (steengroeve), werkbank en blokken (steenhouwer), gestutte ingang, rails en ertskar (mijn), grote schoorsteen en esse (smederij), schilden en oefenpaal (kazerne), houten wachtkamer met piramidedak (wachthuis), ronde toren met omloop en spits (toren).
- Elk gebouw is één mesh met één materiaal (één draw call), 400–1750 driehoeken. Footprints en afmetingen ongewijzigd.
- Fix: kegels, cilinders en rotsen van de procedurele modellen hadden een omgekeerde winding (achterkant zichtbaar).
- Screenshotscript `tools/gebouwen_shots.gd` voor alle gebouwtypes.
- Vaandelhoogtes in het spel afgestemd op de nieuwe silhouetten.

## 0.10.0 — M10: automatisch pad, kromme wegen en grotere kaarten (23 okt 2026)
### Spel/backend
- **Automatisch pad:** na het plaatsen van een gebouw vraagt het spel "Pad aanleggen naar het dichtstbijzijnde pad? Ja/Nee".
  - Instelling *Automatisch pad*: Altijd, Vragen of Nooit (`settings.cfg`, `[game] auto_road`).
  - Bij Ja zoekt het spel met A* (8 richtingen) de dichtstbijzijnde verbonden vlag of weg van het eigen net, alleen over bebouwbaar eigen gebied.
  - Om de 4 tegels komt er een vlag, een weg wordt zo nodig gesplitst en de normale kosten gelden (bouwplaats per segment).
  - Is er geen route, dan meldt het spel dat duidelijk.
- **Kromme wegen:** wegen die je zelf trekt mogen nu ook diagonaal (8 richtingen), dus elke bocht kan. Ze worden getekend als een vloeiende Catmull-Rom-spline door de tegelmiddens, met een licht wisselende breedte en een donkere rand (`gfx/road_mesh.gd`). De sim blijft tegelgebaseerd en deterministisch. De AI legt nog wegen in 4 richtingen, zodat haar gedrag en de balans gelijk blijven.
- **Kaartgrootte** bij Nieuw spel: Normaal, Groot of Enorm.
  - Minimale afstand tussen alle HQ's: 56, 110 of 200 tegels.
  - Vredestijd: 10, 15 of 20 minuten.
  - Groot en Enorm plaatsen de spawns op een ring met een willekeurige starthoek en jitter. Plekken te dicht bij een ander HQ worden afgewezen en grasland heeft de voorkeur; dit gebruikt een eigen RNG uit de seed, dus het is deterministisch.
  - Een vaste kaart groeit mee (x1,5 of x2).
  - Normaal is ongewijzigd.
  - Gebouwen ver van de camera worden niet getekend; de AI daar wordt alleen gesimuleerd.
- **Signaal `Events.autosaved(slot, err)`:** de UI hoeft niet meer op de tekst "Autosave" te filteren.
- **Vaste statuscodes voor gebouwen:**
  - `b["status"]` bevat een code zoals `active`, `no_road`, `no_input`, `no_knight`, `no_forest`, `output_full` of `garrisoned`, met parameters in `b["status_p"]`.
  - De Nederlandse tekst komt uit `Sim.STATUS_TEXT` / `Sim.status_text()`.
  - `b["state"]` blijft de tekst, voor oudere code en saves.
- **Resolutie:** de optie "Native/huidig scherm" is de nieuwe standaard en forceert geen venstergrootte.

### UI (UI-bot, branch ui/hud-polish)
- **UI-schaal:** de schaal past zich automatisch aan resolutie, OS-schaal en DPI aan, waardoor de UI op 1440p en 4K compact blijft. Nieuwe instelling *UI-schaal* (Auto, 75%–200%) wordt opgeslagen in `settings.cfg` en meteen toegepast. 3840×2160 staat nu ook in de resolutielijst.
- **Siedler-stijl:** houten panelen met sierrand en klinknagels, een houten bovenbalk met verloop en gouden bies, knoppen en tabs met diepte (indrukken keert de rand om) en perkamenten tooltips. Alles wordt procedureel gegenereerd, zonder externe assets.
- **Bovenbalk:** past op 1280×720 dankzij een kortere statustekst ("Vrede 9:58 · AI 1/1"). Voorraadtooltips tonen het aantal, een voorraad van 0 wordt gedimd en de snelheidsknop heeft een label (1x/2x/4x).
- **Bouwmenu:** compacter. Het menu krimpt mee met de inhoud, de categorieën zijn kleinere tabs en lange namen worden niet meer afgekapt. Tooltips noemen alleen een cyclus als die er is.
- **Meldingen:** grote meldingen staan boven het bouwmenu. "Autosave ok" en "Gekozen: …" verschijnen als kleine melding rechtsonder die na 2,5 s vervaagt.
- **Infopaneel:** een scheidingslijn, knoppen rechts uitgelijnd en een grotere sluitknop.
- **Pauzemenu:** een donkerdere overlay, gegroepeerde knoppen en waarden bij de schuifregelaars (80%, 1.0x). Het bouwmenu is verborgen zolang het pauzemenu open is.
- **Hoofdmenu:** zelfgemaakt titelbeeld (wapenschild, Cinzel met sierlijnen en een glans), een compacter paneel en in-animaties. De achtergrond heeft camera-drift en stofdeeltjes, en er is een hook voor optionele menumuziek.
- **Thema:** betere contrast voor gedimde tekst, een tekstschaduw en volledige hover-, ingedrukt- en uitgeschakeld-states.
- Nieuw screenshotscript: `tools/ui_shots.gd`.

## 0.9.0 — M9: nieuwe menu's en HUD + verre blik gerepareerd (23 okt 2026)
- **Fix "grote blokken achter het gebied":** de verre LOD tekende bergen als zwevende 4x4-platen en grondstoftegels als lichte vierkanten. Het terrein is nu een doorlopend hoogteveld:
  - de hoekhoogte is in beide LOD's gelijk, en bergen hebben reliëf;
  - rokken langs de chunkranden voorkomen kieren;
  - ver weg zijn er geen grondstofvlekken meer, wel eenvoudige verre bossen, en mist aan de horizon.
- **Nieuw hoofdmenu:**
  - een langzaam draaiende 3D-wereld als achtergrond, de titel in Cinzel en tekst in Inter (beide OFL);
  - glaspanelen met animaties bij hover en indrukken;
  - pagina's: Nieuw spel, Laden, Instellingen, Wat is er nieuw en Afsluiten.
- **Instellingen:** grafische kwaliteit, volume, volledig scherm, resolutie en camerasnelheid.
- **Nieuwe HUD:**
  - een bovenbalk met grondstoficonen en aantallen, speeltijd, pauze, snelheid, prioriteiten en menu;
  - een bouwmenu met iconen per categorie (Wegen, Grondstoffen, Productie, Militair, Opslag);
  - een infopaneel bij selectie, meldingen die vervagen, een pauzemenu onder Esc en debug-info achter F3.
- Eén thema (`ui/kolonie_theme.tres`) en eigen SVG-iconen (CC0).
- Git-repository met tags `v0.8.0` en `v0.9.0`.

## 0.8.0 — M8: high-res graphics met CC0-assets (23 okt 2026)
- CC0-assets van Kenney (Fantasy Town Kit, Castle Kit, Nature Kit) en Poly Haven (2k PBR-texturen, HDRI-lucht, fotoscanmodellen). De bronnen staan in `assets/LICENSES/README.md`.
- Nieuw terrein met een splat-shader: zachte overgangen tussen gras, bos, zand en rots, normal maps en golvend water.
- Gebouwen per type opgebouwd uit Kenney-bouwdelen. Is een model er niet, dan valt het terug op de procedurele modellen.
- Bomen en rotsen als CC0-modellen (MultiMesh), wegen met een aardetextuur, een HDRI-lucht, schaduwen en mist.
- Instelling voor de grafische kwaliteit (Laag/Middel/Hoog) in het hoofdmenu.
- Knop "Wat is er nieuw" in het hoofdmenu, met dit wijzigingslog.
- Windows-build (`Kolonie.exe`) en een installatieprogramma (`Kolonie-0.8-Setup.exe`).
- Simulatie, saves en checksums zijn ongewijzigd.

## 0.7.0 — M7: partijen eindigen + eigen graphics
- Erts groeit terug na 300 s. De aders zijn groter en verre chunks zijn rijker.
- Ridders lopen via A* om water en bergen heen, en overlevenden lopen terug naar huis.
- De AI verdedigt zich: ze bezet grensgebouwen eerst en bouwt torens bij dreiging.
- De standaardafstand tussen HQ's is 56 tegels. Een AI-tegen-AI-partij eindigt nu met de verovering van een HQ.
- Eigen procedurele low-poly modellen per gebouwtype, bomen, rotsen, vlaggen, dragers en ridders, plus UI-iconen.

## 0.6.0 — M6: AI-tegenstanders en strijd
- 1 tot 3 AI-tegenstanders (makkelijk/normaal/moeilijk) met een bouwvolgorde en knelpuntregels.
- Aanvallen op militaire gebouwen, duels, verovering, winnen/verliezen en een vredesperiode.
- Een vijandpaneel met een aanvalsknop, en opties in het menu. Het saveformaat is v3.

## 0.5.0 — M5: militair
- Gebied rond gebouwen, met wachtposten en torens die het gebied uitbreiden.
- Smederij (zwaard), kazerne (ridder) en bezetting van de militaire gebouwen.
- Procedurele geluidseffecten.

## 0.4.1 — M4b: oneindige kaart
- Een oneindige wereld in chunks die rond de camera wordt gegenereerd, met LOD.
- De camerastand wordt in saves meegenomen. De kaartgrootte is te kiezen.

## 0.4.0 — M4: opslaan en laden
- Saves met een versienummer en een hashcontrole, quicksave (F5) en quickload (F9).
- Een hoofdmenu met saves (nieuw, laden, verwijderen) en autosave.

## 0.3.0 — M3: economie verfijnd
- Prioriteiten per goed, en een gebouwpaneel met status, aan/uit en slopen.
- Ertsmijn, uitputbare steen en erts, en een groeitijd voor bomen.
- Stresstest met meer dan 500 dragers.

## 0.2.0 — M2/M2b: logistiek
- Vlaggen, wegen en dragers die goederen van vlag naar vlag brengen.
- Opslagplaats en de productieketen hout → plank en steen → blok.

## 0.1.0 — M1: prototype
- Wereldgeneratie op de achtergrond (deterministisch, met vaste checksums), en de grondstoffen steen en erts.
- Houthakker, bosbouwer, steengroeve en het hoofdkwartier.
