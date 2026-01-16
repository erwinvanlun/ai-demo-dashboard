🤖 AI-Assisted Frontend Dashboard Challenge

⏱️ Timebox: 2 hours

Context

Je werkt als ervaren frontend developer in een team waar AI-assistenten (zoals ChatGPT, Claude, Cursor of Cline) actief worden ingezet tijdens development.


Wij suggeren hier het gebruik van Cursor, een speciale versie van VS Studio Code waar AI totaal is geintegreerd, omdat de eerste week gebruik gratis is.

In deze challenge bouw je samen met AI een frontend dashboard applicatie, startend vanuit een lege repository met alleen deze README.md.

De focus ligt niet op pixel-perfect UI, maar op:

- teamwork, zowel met elkaar als met jullie AI

- architectuur & structuur en consistentie

- slimme inzet van AI op alle (onverwachte) terreinen.

- vastleggen van beperkingen en verassende mogelijkheden van AI

🎯 Doel

Bouw een Dashboard Application die data ophaalt uit één of meerdere publieke API’s en deze inzichtelijk maakt voor een gebruiker.

De applicatie moet:

- data ophalen via HTTP

- status tonen (loading / error / success)

- data visualiseren en/of structureren

- enige vorm van interactie bevatten

- een minimale vorm van testing hebben.


🧱 Functionele eisen
1. Dashboard layout

Het dashboard bevat minimaal:

- Header
  - titel van de applicatie
  - korte beschrijving of context

- Main content
  - twee of meer "widgets" / panels
  - elke widget toont data uit een API
  - widgets mogen verschillend van type zijn (lijst, kaart, tabel, grafiek, detailpaneel)
  - advanced: combineer data van verschillende bronnen

- State feedback
  - loading indicator
  - foutafhandeling
  - lege state (indien van toepassing)

2. Data & API’s

Deze API’s hieronder zijn suggesties. Ken je betere, leukere? Voel je vrij die te gebruiken. 

Open API's (geen registratie nodig)
- https://opendata.rdw.nl/resource/m9d7-ebf2.json?kenteken= + kenteken
- http://swapi.co/                            - Star Wars API
- http://api.openweathermap.org/data/2.5/weather
- http://ergast.com/mrd/                     - Formule 1 data
- https://randomuser.me/api/?results=10
- http://www.omdbapi.com/                    - Movies (gebruik liefst eigen key)
- https://api.github.com/users/
- http://dev.markitondemand.com/Api/v2/Quote/json?symbol=AAPL
- https://restcountries.eu/rest/v1/all
- http://api.postcodedata.nl/v1/postcode/
- http://opendata.cbs.nl/
- https://data.pdok.nl/datasets
- https://coinmarketcap.com/api/
- https://www.anwb.nl/feeds/gethf
- https://api.spacexdata.com/v3/launches/

API's met registratie (optioneel, complexer)
- https://developer.marvel.com/
- https://www.rijksmuseum.nl/nl/api
- https://www.themoviedb.org/documentation/api
- http://www.last.fm/api
- https://developers.google.com/youtube/v3/
- https://freemusicarchive.org/api
- https://api.nasa.gov/

3. Interactie (kies minimaal 2)

Voorbeelden (je mag zelf variëren):

- filteren of zoeken in data

- selectie van een item → detailweergave

- sorteren

- wisselen van API-bron

- refresh / reload

- simpele instellingen (bijv. stad, gebruiker, land)

🧠 Technische eisen
Framework

Gebruik een bekend frontend JavaScript framework dat je collega's waarschijnlijk ook kennen. 

- React / Vue / Angular 
- Met Typescript


Best-practices

Laat zien dat je ervaring hebt door je prompts aan AI goed te formuleren. 

- duidelijke componentstructuur

- scheiding tussen:
  - data fetching
  - state management
  - presentatie

- herbruikbare componenten

- consistente naming

- logische mapstructuur

- nette foutafhandeling

Perfectie is niet vereist, helderheid wel.


🤝 AI-inzet 

AI is onderdeel van de opdracht, geen valsspelen.

Je mag AI gebruiken voor ALLES:

- interpretatie van deze opdracht

- project setup

- architectuurvoorstellen

- componentstructuur

- data-modellen

- boilerplate

- refactoring

- opzetten van tests

- runnen van tests

- runnen van je lokale applicatie

- bouwen van je applicatie

uitleg of alternatieven


Verwachting

- Experimenteer!!!!! Durf fouten te maken. Durf 'te snel' te gaan. 

- Na verwachting moet je zowel de structuur als elke  regel code kunnen verantwoorden


🚀 Snel starten (belangrijk)

Je hoeft geen tijd te besteden aan het configureren van AI.

Aanpak

- Open je AI-tool naar keuze (ChatGPT, Claude, Cursor, Cline, etc.)

- Laat AI deze README lezen. 'Hey AI, je volgende taak is beschreven in de README'.

- Gebruik prompts zoals:
  - "Generate a minimal React + TypeScript dashboard scaffold based on this README"
  - "Suggest a clean component architecture for this challenge"
  - "Help me implement API X with proper loading & error handling"

- Kies tooling waar je zelf snel mee bent en waarvan je verwacht dat de meeste collega's van je het ook beheersen.

- Als je tevreden bent met het tussen resultaat: commit. Als je vindt dat AI een sub taak heeft afgerond, squash dan alle gerelateerde commits en review te code. Vraag dan AI om evt aanpassingen te doen op de code quality.

🧪 Wat leveren we op?

Aan het einde van 2 uur verwachten we:

- een werkende frontend applicatie (lokaal)

- leesbare code

- duidelijke structuur

- (optioneel) korte notities in de README over:
  - wat heb je geleerde tijdens deze 2 uur
  - welke prompts heb je gebruikt? Wat werkte? Wat werkte niet? 
  - wat je anders doen nu je 2 uur ervaring hebt?

Geen deployment nodig.

🧩 Extra uitdaging (optioneel)

Als je tijd over hebt:

- voeg een simpele visualisatie toe (chart, progress, KPI)

- combineer data uit twee API's

- voeg caching toe

- introduceer theming (licht/donker)

- voeg tests toe

- maak het dashboard uitbreidbaar via configuratie

🧘‍♂️ Tot slot

Dit is geen wedstrijd in “afmaken”, maar in denken, structureren en samenwerken met AI.

Veel plezier — en laat zien hoe jij AI inzet als force multiplier 💥