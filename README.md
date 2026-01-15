🤖 AI-Assisted Frontend Dashboard Challenge

⏱️ Timebox: 2 hours

Context

Je werkt als ervaren frontend developer in een team waar AI-assistenten (zoals ChatGPT, Claude, Cursor of Cline) actief worden ingezet tijdens development.

In deze challenge bouw je samen met AI een frontend dashboard applicatie, startend vanuit een lege repository met alleen deze README.md.

De focus ligt niet op pixel-perfect UI, maar op:

- architectuur & structuur

- slimme inzet van AI

- frontend best-practices

- duidelijke keuzes en trade-offs onder tijdsdruk

🎯 Doel

Bouw een Dashboard Application die data ophaalt uit één of meerdere publieke API’s en deze inzichtelijk maakt voor een gebruiker.

De applicatie moet:

- data ophalen via HTTP

- status tonen (loading / error / success)

- data visualiseren of structureren

- enige vorm van interactie bevatten

- eenvoudig uitbreidbaar zijn

🧱 Functionele eisen
1. Dashboard layout

Het dashboard bevat minimaal:

Header

- titel van de applicatie

- korte beschrijving of context

Main content

- één of meerdere "widgets" / panels

- elke widget toont data uit een API

- widgets mogen verschillend van type zijn (lijst, kaart, tabel, grafiek, detailpaneel)

State feedback

- loading indicator

- foutafhandeling

- lege state (indien van toepassing)

2. Data & API’s

Gebruik minimaal één, maximaal drie van onderstaande API’s.
Mocking is toegestaan als fallback, maar real API-gebruik heeft de voorkeur.

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

Gebruik een bekend frontend JavaScript framework

- React / Vue / Angular / Svelte / Solid / etc.

- TypeScript is sterk aanbevolen

Best-practices

Laat zien dat je ervaring hebt:

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

🤝 AI-gebruik (belangrijk)

AI is onderdeel van de opdracht, geen valsspelen.

Je mag AI gebruiken voor o.a.:

- project setup

- architectuurvoorstellen

- componentstructuur

- data-modellen

- boilerplate

- refactoring

- uitleg of alternatieven

Verwachting

- Gebruik AI actief en bewust

- Laat zien dat jij de regie houdt

- Blind copy-pasten zonder begrip is niet het doel

🚀 Snel starten (belangrijk)

Je hoeft geen tijd te besteden aan het configureren van AI.

Aanpak

- Open je AI-tool naar keuze (ChatGPT, Claude, Cursor, Cline, etc.)

- Kopieer deze README

- Gebruik prompts zoals:
  - "Generate a minimal React + TypeScript dashboard scaffold based on this README"
  - "Suggest a clean component architecture for this challenge"
  - "Help me implement API X with proper loading & error handling"

- Kies tooling waar je zelf snel mee bent.

🧪 Wat leveren we op?

Aan het einde van 2 uur verwachten we:

- een werkende frontend applicatie (lokaal)

- leesbare code

- duidelijke structuur

- (optioneel) korte notities in de README over:
  - gemaakte keuzes
  - wat je zou verbeteren met meer tijd
  - hoe AI je geholpen heeft

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