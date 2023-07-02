# Meesterproef Read.me

## Inhoudsopgave
- [Introductie](#introductie)
- [Door de weken heen](#weken)
  - [Week 1](#week1)
  - [Week 2](#week2)
  - [Week 3](#week3)
  - [Week 4](#week4)
  - [Week 5](#week5)
- [Door de weken heen](#weken)

## Introductie <a name="introductie"></a>
Daniël, Martijn en ik hebben voor de case 'bRAIN' gekozen. bRAIN is het project rondom het koppelen van weerberichten aan wateropvang/gebruik in de tuin.

Weersextremen in Nederland nemen steeds verder toe. Enerzijds komen periode van droogte tekorten vaker voor en anderzijds hebben we vaker te maken met extreme neerslag, met wateroverlast tot gevolg. Hier willen we als Nederland zijnde op voorbereid zijn. In de gemiddelde gemeente is 50 tot 60 procent van het totaal oppervlak privaat terrein. Daarom is het essentieel dat ook de private ruimte klimaatadaptief wordt ingericht. Dit betekent dat je bewoners moet overtuigen om klimaatadaptief te worden. Een van de manieren om dit te doen waarin je zowel droogte als extreme neerslag voor een deel kan bufferen is doormiddel van regentonnen.

## Door de weken heen <a name="weken"></a>

### Week 1 <a name="week1"></a>

#### De eerste stand-up
In week 1 hebben we de taken verdeeld. Ik ben de man van het design, Martijn is goed in server-side developing en Daniel is goed in Front-End in het algemeen. We hebben besloten de SCRUM tactiek te gebruiken om de taken binnen het project onder elkaar te verdelen, en om bij te houden waar we zijn binnen het project. We hebben elke maandag een stand-up gehouden.

#### Briefing
We zijn als team langs onze opdrachtgever SPATwater geweest. We hebben natuurlijk de opdracht al gelezen op de wiki, maar we wilden toch wat meer weten en we hadden nog wat vragen. Ik heb tijdens de meeting de volgende notities gemaakt. Klimaatadaptatie = Aanpassen op klimaat/inspelen op klimaat Neerslag neemt toe, het regent steeds harder. Ook is er steeds meer droogte, waardoor je hier goed op moet kunnen aanpassen. Aardswetenschappen gestudeerd, master hydrologie. Een tool ontwikkelen op het moment dat mensen een regenton hebben, zodat ze een idee krijgen wanneer ze die moeten legen voordat er weer een bui komt. Een systeem waar water goed wordt vastgehouden. Regenton moet leeg zijn voordat er weer een nieuwe regenbui komt, zodat het water zo veel mogelijk vastgehouden wordt voordat het weg gevoerd wordt. Met regenpijpen moeilijk om de oppervlakte te meten, de daken zijn makkelijk te meten. Eerst kijken naar hoeveel vierkante meter dak je hebt, dan de regenpijpen en dat x4. Voorspellen hoeveel water er in een regenton komt. Belangrijk

Weer kunnen meenemen in de applicatie, aan de hand van KNMI
Aan de hand van deze data zien of het weer gaat regenen, waarschuwen dat de regenton opengezet wordt.
Gebruiksvriendelijkheid
Bewoners meekrijgen in dit verhaal
Makkelijk te gebruiken
Visueel aantrekkelijk
Goed prototype kunnen presenteren
Hoofddoel: bewoners omverblazen met idee
App moet optijd een seintje geven wanneer de ton vol raakt SPATwater verkoopt idee aan gemeente, gemeente verkoopt idee aan bewoners App: Perceelwijzer KNMI API eerst testen, bel ze vooral! Vrijdag 1 -2, aankomende vrijdag digitaal. Om de week fysiek. Wachtwoord WIFI: Carbon2021

#### De-briefing
Samen met Daniel en Martijn heb ik aan de de-briefing gezeten. We hebben dit gedaan om de opdracht te verduidelijk voor beide ons en SPATwater. Dit is de de-briefing:

##### Contactgegevens
Timo van den Berg t.vdberg@spatwater.nl Mees van Milligen de Wit m.vmilligen@spatwater.nl Jesse Schoenmakers j.schoenmakers@spatwater.nl

##### Achtergrondinformatie
30 Mei zijn we voor het eerst langs geweest bij SPATwater in Noord. Hier hebben we kennis mogen maken met drie van de vier werknemers van SPATwater, namelijk Mees, Mees en Jesse. SPATwater is ontstaan toen Mees en Jesse afstudeerden van de master hydrologie. Ze zijn toen begonnen met het opzetten van het bedrijf. Het bedrijf houdt zich voornamelijk bezig met klimaatadaptatie, een cruciaal onderwerp gezien de toename van hevige regenbuien en periodes van droogte. Normaal gesproken geeft het bedrijf adviezen op het gebied van water aan gemeenten door het hele land, maar nu hebben ze een nieuw project. Hiervoor zijn wij ingeschakeld.

##### Opdrachtomschrijving
SpatWater wilt een applicatie waarin gebruikers een regenton kunnen instellen. Aan de hand van de locatie en het weer wordt de regenton digitaal gevuld, en weet de gebruiker de hoeveelheid water in de regenton. Veel water raakt namelijk verloren in het riool door dat regenpijpen rechtstreeks het riool in gaan. Met deze oplossing wordt er meer water afgevoerd in de grond en wordt er ook minder drinkwater verspilt.

##### Aanleiding
Omdat het klimaat zo aan het veranderen is en er tegenwoordig steeds hevigere regenbuien zijn en periodes van droogtes, wilt onze opdrachtgever meer gebruik gaan maken van regentonnen. Dit om meer regenwater op te vangen en dit in de tuin te laten lopen. Het is namelijk zo dat veel van het regenwater nu het riool inloopt en vervolgens wordt gedumpt in sloten en rivieren. Hierdoor verdwijnt het water uiteindelijk in de zee en wordt het zout. Het is dus beter als het regenwater bijvoorbeeld voor het besproeien van de tuin wordt gebruikt en in het grondwater verdwijnt.

##### Projectdoel
SPATwater heeft ons gevraagd een applicatie te ontwikkelen waarbij bewoners een regenton kunnen instellen en met deze applicatie kunnen zien hoeveel regenwater zij hebben opgevangen in de regenton. Hiermee krijgen de bewoners hulp bij het beheren van de opslag van het regenwater. Er zal een melding worden verstuurd wanneer de regenton geleegd moet worden zodat er maximaal water kan worden opgevangen en minder water wordt verspild.

##### Doelstelling
De doelstelling van het bedrijf is het voorkomen van waterverspilling doormiddel van het gebruik van regentonnen of andere klimaatbewuste implementeringen. Ook willen ze de kwaliteit van water zo goed houden als mogelijk in Nederland.

##### Oplevering
De applicatie zal de weersvoorspellingen van openMeteo integreren om te kunnen anticiperen op komende regenbuien. Gebruiksvriendelijkheid is hierbij cruciaal; we willen dat de tool makkelijk te gebruiken en visueel aantrekkelijk is. Het prototype moet indrukwekkend zijn - we willen de bewoners omverblazen met ons idee. De app moet tijdig meldingen sturen wanneer de regenton vol dreigt te raken. Ook moet de gemeente Amsterdam

##### Randvoorwaarden
Het project zal ook uitdagingen met zich meebrengen, zoals het bepalen of het dak schuin of plat is. Hiermee krijg je te maken met verdamping van water waardoor de accuraatheid van de hoeveelheid water in de regenton moeilijker te bepalen wordt. Hierdoor kunnen verkeerde voorspellingen worden gemaakt. Ook kan het zijn dat er meerdere regenpijpen zijn en dat niet elke regenpijp is aangesloten op een regenton. De bewoners staan centraal en hier moet ook op gefocust worden. Als de applicatie niet fijn te gebruiken is door bewoners is het niet functioneel.

##### Gebruikers van het eindresultaat
Onze gebruikers van het eindresultaat zullen klimaatbewust bezig zijn met water. Ze verspillen minder drinkwater en zorgen ervoor dat er meer grondwater in de grond komt. Hierdoor dragen ze bij aan een verbeterd milieu. De bewoners staan centraal en dit is ook de gebruiker. Ook de gemeente Amsterdam moet inzicht kunnen hebben echter moeten we focussen op de gebruiker.

##### Relatie met andere projecten
Er is al een soortgelijke app beschikbaar genaamd Perceelwijzer, waarin je data kan krijgen over verschillende percelen in Nederland. Denk hierbij aan bijvoorbeeld neerslag maar ook of er gemaaid mag worden. Deze app maakt dus al gebruik van het aantal mm neerslag dat er per perceel valt. Wij zullen ook zoiets moeten integreren, maar wij gebruiken hiervoor de KNMI API.

#### Het begin van het design
Als eerst ben ik gaan kijken naar hoe onze web app gedesigned zou moeten worden. Ik heb hierbij de core-functionaliteit van de app meegebracht. Wij hebben als team besloten dat de core-functionaliteit is dat de gebruiker binnen de app een regenton kan aanmaken en dat de gebruiker kan zien hoeveel regen er in de regenton valt, zodat de gebruiker tijdig zijn regenton kan legen en er dus geen water wordt verspilt.

Mijn eerste concept houdt hier rekening mee.

Ik heb een homepage gemaakt waarin de core-functionaliteit centraal staat. De gebruiker kan zien hoeveel water er in zijn regenton zit, en kan de regenton legen zodra deze vol begint te raken. Ik heb ook een state gemaakt waarin de de regenton leeg is. Daarnaast is er een state dat de regenton geleegd moet worden. De app geeft de gebruiker dan een melding dat de regenton bijna vol is, en dat deze geleegd moet worden voordat het water verspilt wordt. Verder hebben we een state toegevoegd waar de regenton al leeg is. De app geeft de gebruiker dan een melding dat de regenton niet geleegd kan worden omdat de regenton al geleegd is. Vervolgens heb ik een pagina gemaakt waar de gebruiker kan kijken naar de gegevens van de regenpijpen die aangesloten zijn aan zijn regenton, de hoeveelheid regentonnen en hoeveel liter deze bevatten en hoe groot zijn dak is. Als laatst heb ik een menu toegevoegd waarin de gebruiker naar andere delen van de app kan navigeren.

### Week 2 <a name="week2"></a>

### Week 3 <a name="week3"></a>

### Week 4 <a name="week4"></a>

### Week 5 <a name="week5"></a>

## Reflectie <a name="reflectie"></a>

### Het proces 
Ik vond het spannend om de meesterproef aan te gaan aangezien ik niet helemaal wist wat ik moest verwachten. Alhoewel ik bijna alle vakken gehaald heb, had elke vak zijn eigen uitdagingen, en ik wist dat elk vak in principe overnieuw doen niet makkelijk ging worden. Gelukkig kan ik zeggen dat ik met mijn team een goed product heb neergezet. De hele minor werk je in je eentje, dus om in teamverband aan de gang te gaan moest je de opdracht wel op een andere manier aanpakken. We hebben bijvoorbeeld gebruik gemaakt van de SCRUM methode om taken te verdelen en om bij te houden wie wat nog moet doen en wat er in het geheel nog gedaan moet worden. Op deze manier hebben we naar mijn idee goed de taken verdeeld. Er waren duidelijk wel wat mensen meer gespecialiseerd in het een dan in het ander. Maar hierdoor konden we wel de taken verdelen op een manier dat iedereen gemotiveerd te werk kon gaan. Ik heb leren omgaan met Figma en ik hoe ik het best me kan voorbereiden op het schrijven van code, omdat ik eerst altijd maar gewoon meteen de code in duik, in plaats van een goed beeld te vormen hoe ik het ontwerp ga neerzetten. Dit bespaarde me tijd.

### Hoe mijn team en ik de lesstof uit de vakken heb ingezet

#### Web App from Scratch
Ik heb veel werk gestopt in het vormgeven van de applicatie. Ik heb hierbij verschillende design principes gebruikt. Ik heb voor de structuur van mijn HTML eerst een schets gemaakt, zodat ik niet tijdens het proces problemen krijg met elementen die ik nog in de HTML moet zetten. Ik heb aan de hand van een API een regen animatie werkend laten krijgen.

#### CSS to the Rescue
Om de onboarding werkend te krijgen heb ik veel moeten experimenteren met grid. Het design neerzetten op Figma is natuurlijk een stuk makkelijker dan om hetzelfde in code te doen. Er zat dus ook een flinke uitdaging in het juist positioneren van de elementen. Ik heb ook flink geëxperimenteerd met animaties, omdat ik zelf eerst een regen animatie wilde maken.

#### Progressive Web Apps
Het team heeft server-side rendering geïmplementeerd met behulp van views en partials. Deze views renderen gegevens vanuit een API-ophaalverzoek. We hebben speciale functies geschreven en in een aparte map geplaatst om dit te faciliteren. Vervolgens hebben we deze gegevens in verschillende functies hergebruikt, zodat er slechts één ophaalverzoek hoeft te worden gedaan. Hierdoor kunnen we de opgehaalde gegevens hergebruiken, wat uiteindelijk tijd bespaart tijdens de uitvoering van onze applicatie.

#### Browser Technologies
Mijn team en ik hebben voordat we begonnen aan de opdracht een doorgrondige de-briefing geschreven. Hiermee hebben we goed de core-functionaliteit van de app duidelijk gemaakt. Ik ben voornamelijk bezig geweest met het maken van de onboarding. Ik heb progressive enhancement toegevoegd zodat de onboarding ook zonder JavaScript zou moeten werken. Ook kunnen gebruikers van screenreaders door de verschillende onboarding schermen heen tabben. Verder heb ik in de onboarding goed gelet op leesbaarheid, visuele hiërarchie, contrast, keuzes in kleuren, gebruiksvriendelijkheid (de onboarding geeft feedback aan de gebruiker wanneer een veld niet is ingevult), etc.

#### Real-time Web
In onze applicatie wordt er gebruik gemaakt van een server-side API en een MongoDB-verbinding. De server bevat een datamodel en zorgt ervoor dat elke client de juiste gegevens ontvangt. Deze gegevens worden opgeslagen in de database en kunnen ook weer worden opgevraagd. Bovendien is er de mogelijkheid om het volledige object dat in de database is opgeslagen te verwijderen, waardoor je de onboarding procedure opnieuw kunt doorlopen.

#### Human Centered Design
We zijn wekelijks langs geweest (fysiek en online) bij de opdrachtgever om feedback te verzamelen op ons product en om ons product te laten testen. Deze feedback hebben we elke keer meegenomen in ons product. Verder staat de gebruiker in ons product centraal.

### Waar ik in ben verbeterd
Dankzij deze minor heb ik weer een opfrissing gehad in het schrijven van code. Ik wilde mezelf hier vele malen in verbeteren, in de hoop dat ik de dingen die ik geleerd heb toe kan passen in bijvoorbeeld het maken van web applicaties. Ik moet zeggen dat ik tijdens deze minor vooral heb gemerkt dat ik totaal geen achtergrond had in specifiek JavaScript. Ik dacht dat ik de basis kennis had, maar dit was duidelijk niet zo. Hierdoor liep ik wel erg vaak tegen blokken binnen de opdrachten die vooral gefocust waren op JavaScript, zoals Real Time Web en Progressive Web Apps. Ik heb wel geleerd hoe ik een applicatie omzet van client side naar server side. Ik heb geleerd hoe ik een API kan implementeren. Ik heb geleerd hoe ik aan de hand van progressive enhancement mijn websites beter beschikbaar kan maken voor iedereen die het web gebruikt. Ik heb geleerd hoe ik met een echt blind persoon kan werken en hoe ik dit persoon haar problemen kan oplossen aan de hand van een ontwerp. Ik heb geleerd met sockets te werken. Ik heb in de opleiding zelfs ruimte gehad om mijn vormgeving vaardigheden te verbeteren. Omdat ik zelf erg onervaren ben met specifiek JavaScript, heb ik wel het idee gehad dat ik te weinig tijd had om echt dieper in de lesstof te gaan, waardoor ik wel het idee heb dat ik nog een stuk meer moet oefenen om echt alles wat ik geleerd heb foutloos te kunnen implementeren. Al met al heb ik mijn code vaardigheden een stuk kunnen verbeteren.
