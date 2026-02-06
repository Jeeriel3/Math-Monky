## Extra informatie  bij onze website
In dit document nog even alle extra informatie die nodig is om in te leveren bij de site. (in .md format om maar bij de stijl van developing te blijven :))

## Functioneel ontwerp
We hebben veel dingen toegevoegd en aangepast aan ons functioneel ontwerp, dus deze hebben we opnieuw als PDF ingeleverd.

## Samenwerking
Onze website is gemaakt door Jeriël Ram, Manoah Wanders en Chris Kingma.

## Praktisch

 - De website staat op de server van Jeriël Ram.
 - Helaas is het niet mogelijk om afbeeldingen of bestanden te verslepen op maken.mijn-in.nl.
	 - Hierdoor hebben we een vrij rommelige betands-folder.
	 - Ook zijn nu in de scripts sommige afbeeldingen via :afbeeldingen/ en anderen worden via de root-folder gedefineerd.
 - Alle code in onze website is door ons gemaakt, behalve de .js bestanden. (JavaScript code).
	 - Dit hebben we met mevrouw Overgoor overlegd en dit was prima.
	 - De website is volledig werkend zonder JavaScript code, maar dit voegt extra dingen toe aan de website.
 - We hebben in onze website ook een eigen lettertype als .ttf bestand geüpload. Helaas gaat dit bestand kapot wanneer het wordt geopend.
	 - Het is dus belangrijk om dit bestand in de editor niet te openen. Dan werkt het font ook mooi.
	 - We hebben voor dit lettertype gekozen, omdat dit in ons functioneel ontwerp staat en het een heel mooi lettertype is.
## Onderzoeksmethode
De onderzoeksmethode hebben we ook aan ons functioneel ontwerp toegevoegd, maar hier hebben we nog wat extra informatie staan, omdat dit niet in ons functioneel ontwerp paste!

Voor de evaluatiemethode gaan wij voor de NPS-score. We laten elke gebruiker (kinderen) vragen of ze iets hebben geleerd op onze website via een score van 0 (helemaal niks geleerd) tot 10 (Ik ben nu Albert Einstein).

Dit gaan we doen door een simpele database op te zetten via Supabase, en een AI te vragen om simpele JavaScript code te schrijven.

Nadat we genoeg data hebben verzameld, weten we of we de juiste spellen hebben gekozen en of deze leerzaam genoeg zijn.

  

Hieronder ook nog de referentie voor NPS popup UI:

![Ahh, is het toch weer met die afbeelding mis gegaan. Als u dit ziet, dan kijkt u denk ik maar even in het functioneel ontwerp, daar staat de afbeelding ook :)](https://i.ibb.co/hxJ14t4K/Screenshot-2026-02-02-10-41-04.png)

Om de resultaten van de NPS-score meting te zien heb ik de data naar een .csv bestad geëxporteerd. Deze kunt u hieronder bekijken!

## Uitwerking NPS score:
| id | score | user_name | created_at               |
|----|-------|-----------|--------------------------|
| 7  | 8     |           | 2026-01-06T11:04:05.735Z |
| 8  | 10    |           | 2026-01-06T11:06:09.342Z |
| 9  | 10    |           | 2026-01-06T11:06:18.197Z |
| 10 | 10    |           | 2026-01-06T11:06:55.406Z |
| 11 | 8     |           | 2026-01-08T09:55:44.609Z |
| 12 | 7     |           | 2026-01-08T09:58:02.169Z |
| 13 | 8     |           | 2026-01-08T09:59:21.149Z |
| 14 | 7     |           | 2026-01-08T10:00:19.259Z |
| 15 | 10    |           | 2026-01-13T10:39:47.628Z |
| 16 | 10    |           | 2026-01-13T10:40:48.072Z |
| 17 | 10    |           | 2026-01-13T10:42:14.325Z |
| 18 | 10    |           | 2026-01-13T10:42:28.576Z |
| 19 | 10    |           | 2026-01-13T10:43:15.685Z |
| 20 | 10    |           | 2026-01-13T10:45:29.770Z |
| 21 | 1     |           | 2026-01-13T10:46:35.632Z |
| 22 | 10    |           | 2026-01-13T10:46:54.914Z |
| 23 | 10    |           | 2026-01-13T10:51:09.937Z |
| 24 | 10    |           | 2026-01-13T10:51:18.599Z |
| 25 | 10    |           | 2026-01-13T10:51:28.492Z |
| 26 | 10    |           | 2026-01-13T10:54:31.429Z |
| 27 | 8     |           | 2026-01-13T10:54:32.846Z |
| 28 | 10    |           | 2026-01-13T10:54:59.277Z |
| 29 | 10    |           | 2026-01-13T10:55:51.488Z |
| 30 | 10    |           | 2026-01-13T10:56:21.689Z |
| 31 | 10    |           | 2026-01-13T10:57:17.353Z |
| 32 | 6     |           | 2026-01-13T10:58:05.096Z |
| 33 | 10    |           | 2026-01-13T11:00:48.339Z |
| 34 | 10    |           | 2026-01-13T11:00:57.029Z |
| 35 | 10    |           | 2026-01-13T11:01:05.767Z |
| 36 | 10    |           | 2026-01-13T11:01:13.340Z |
| 37 | 10    |           | 2026-01-13T11:01:29.900Z |
| 38 | 5     |           | 2026-01-13T11:02:12.643Z |
| 39 | 1     |           | 2026-01-13T11:03:00.216Z |
| 40 | 1     |           | 2026-01-13T11:03:50.409Z |
| 41 | 1     |           | 2026-01-13T11:04:23.563Z |
| 42 | 1     |           | 2026-01-13T11:04:39.446Z |
| 43 | 10    |           | 2026-01-13T11:04:40.182Z |
| 44 | 10    |           | 2026-01-15T13:53:22.141Z |
| 45 | 8     |           | 2026-01-15T14:42:21.359Z |
| 46 | 1     |           | 2026-01-18T09:23:56.781Z |

Helaas is het user_name systeem niet goed doorgekomen...

## Usabilaty opdrachten:
Website: www.fi.uu.nl/rekenweb
Uitleg website:
www.fi.uu.nl/rekenweb is een website waarop je rekenspelletjes kan spelen. Spellen door de website zelf en spellen van anderen zijn te spelen. De website heeft een specifieke doelgroep: Jongere kinderen (basisschool groep 3-8). De website heeft een zoekfunctie om tussen alle spellen te zoeken. Het is gemaakt voor leerlingen en docenten, al valt dat soms wel door elkaar.

Evaluatie:
De knoppen werken, maar brengen je vaak naar een 404 error, of de webserver werkt niet. Het hele idee van de website is om games te spelen, maar het spelen van de games zelf werkt niet. De knop om een spel te starten is heel klein en bijna niet te zien. Het thema is niet mooi, de website en interface is niet responsive, op een groot scherm is dus de helft van het scherm wit, terwijl op kleinere schermen veel buiten beeld valt.
Als je de website opent, kom je op het home scherm, het is duidelijk op welk scherm je moet en wil komen. Elke knop heeft een duidelijke omschrijving en is groot. Daarna weet je niet goed waar je bent, en je kan niet makkelijk terug. Veel knoppen zijn niet te vinden en belachelijk klein.
De GUI van de site is inconsistent. Alles ziet er anders uit en het is onoverzichtelijk.
De optie ‘rekenbrief’ is leeg en je kan niet meer terug.

Wat werkt:
Er is een nieuws optie, met nieuws over de school, dit werkt prima omdat hij je naar een andere site brengt die een stuk beter werkt.

Opdracht 10:
Usefulness: Het concept is opzich nuttig, want je kan op deze website oefenen met rekenen, maar de uitvoering daarentegen niet want de helft van de website werkt niet. Leuk idee, minder leuke uitvoering.
Findability: De website is aardig overzichtelijk. Er zijn kopjes met daarop wat ze doen en een tekst erbij die nog meer info geeft. De tekst binnenin de kopjes is echter wel enorm klein en bijna niet leesbaar.
Credibility: Knopjes zeggen: “Speel hier”, maar als je op een knop klikt dan doet het niks, dus credibility is zeer matig.
Desirability: Knopjes zeggen: “Speel hier”, maar als je op een knop klikt dan doet het niks, dus desirability is zeer matig.
Value: Het werkt niet en heeft hetzelfde idee als andere betere gratis sites, dus is deze site, en dit concept aardig nutteloos.

GEEL = Zou ik zeker op mijn eigen site zetten.








Opdracht 19:
Doel onderzoek:
We willen dat de website goed werkt, dat alle knoppen doen wat ze moeten doen en dat de website er professioneler en gebruiksvriendelijker uitziet.

Onderzoeksvraag:
Hoe kunnen we de website consistent en gebruiksvriendelijker maken? 

Hypothese:
Wij denken dat de website duidelijker gemaakt kan worden door de kleuren aan te passen zodat alle pagina’s op elkaar lijken en soepel in elkaar overlopen. De tekst moet overal dezelfde kleur krijgen en even groot zijn. Ook denken wij dat een terug-knop de gebruiksvriendelijkheid flink kan vergroten.


## Dat was 'm
Nu heeft u alle nodige informatie om onze site te kunnen bekijken ;)
