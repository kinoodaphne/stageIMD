# Platform/game om de fonemische ontwikkeling bij kleuters te bevorderen

## Contents table

- [Stageopdracht](#stageopdracht)
- [Project](#project)
- [Fases](#fases)
   - [Eerste fase](#eerste-fase)
   - [Latere fase](#latere-fase)
- [Kick-off meeting: 11/02](#kick-off-meeting:-11/02)
- [Oefeningen](#oefeningen)
- [Learning Management Systems](#learning-management-systems)
- [Mogelijke frameworks & engines](#mogelijke-frameworks-engines)
- [Nuttige links](#nuttige-links)
- [Tutorials](#tutorials)

## Stageopdracht 🚀
De stageopdracht bestaat erin het maken van een eerste **Proof of Concept** van een applicatie om het fonemisch bewustzijn bij kleuters te bevorderen. Deze applicatie zal volledig met web technologie worden gebouwd volgens het principe van een **progressive web app**.

De student staat in vanaf het design en technologisch onderzoek tot en met de implementatie van het demo product. Een product owner wordt beschikbaar gesteld aan de student. Deze bepaalt welke functionaliteit deze applicatie dient te bevatten.

## Project 📄
Kleuters kunnen via een tablet of desktop verschillende oefeningen maken waar ze hun fonemische klanken kunnen bevorderen. 

> (Audio bestanden als ondersteuning van de klank bij het visuele worden voorzien) || Werken met **Bitbucket** voor overdracht en opslag van project (soortgelijk aan Github)

Project uitwerken in kleinere stappen; dwz functionaliteit **per functionaliteit**. Geen al te grote taken in 1 hap proberen uit te werken. Zien dat 1 deeltje werkt vooraleer aan een nieuw te beginnen.

## Fases 🕐

### Eerste fase 
onderzoeken welke technologie het beste is om deze te maken. Een game engine met Lua zoals Defold of eerder meer hands-on programmeren met React of Vue? (Andere platformen zijn mogelijk, zolang ze maar Javascript mee ondersteunen).

**11/02:** kick-off meeting met de stakeholders. Deze is verlopen via video-call samen met de stagementor. Hier werd duidelijk gemaakt langs de stakeholders kant wat zij als conceptbeschrijving zien van het project. 

### Latere fase
- Platform zodanig uitwerken dat een verbinding met bijhorende server mogelijk is.
- Meerdere levels implementeren (n-aantal makkelijk, n-aantal gemiddeld, n-aantal moeilijk)

> Wat maakt een bepaald woord moeilijker dan een ander? Welke zijn te gemakkelijk en welke te moeilijk? Waar zit de criteria om deze in categorieën te plaatsen?

## Kick-off meeting: 11/02 📆
**Recap:** Er werd gevraagd om een demo product uit te bouwen (of alleszins mijn taak een proof-of-concept) voor VIVES Brugge. Zij willen graag een app waarbij kinderen hun fonemische klanken kunnen leren on ondersteunen op een leuke, speelse manier.

Momenteel zijn er veel apps op de markt, maar zijn de uitspraken van deze klanken toch niet zoals ze moeten zijn. ***Bijvoorbeeld de Nederlandse G die uitgesproken wordt als*** [GUH] ***of de Engelse I die uitgesproken wordt als*** [AJ], waardoor er soms verwarring bestaat in het begrijpen en uitspreken van sommige klanken alsook het verkeerd aanleren en ontwikkelen van deze klanken.

> Encyclopedie luidt fonemisch in het Nederlands: [εnsiklopedi]. Succes spreek je dan weer uit als [sukses].

Een voorbeeld van zo'n oefening is dat ze bijvoorbeeld de juiste letter of foto bij de klank aanduiden (dmv een audiobestand) en ook omgedraaid. Hier moeten ze dan begrijpen dat **K-A-T** het woord **kat** vormt, **S-T-A-R-T** wordt **start** en dat het woord **begin** bestaat uit **B-E-G-I-N**. Het verschil kunnen horen tussen bijvoorbeeld **hard** en **hart** is ook zeer belangrijk, etc.

Niet alleen moet het een leuke uitdaging worden voor de kinderen, maar mag dit ook niet blijven hangen op een behaalde moeilijkheidsgraad. Naar mate de kinderen oefenen, zullen de woorden moeilijker worden om zo hun vaardigheden te testen.

> Hoe gaat dit level systeem ingevoerd worden? Gaat men automatisch door naar de volgende of kom je na afloop van een goede oefening terug in de level-keuze lijst?

Een zekere functionaliteit die ze in de app willen zien, is een systeem om bij te houden wie op welk level zit, en welke woorden hij/zij fout heeft. Zo kunnen ze de kinderen op een goede manier bijsturen en mogelijke herhalingen van problemen vroegtijdig opsporen.

> App moet op een latere basis kunnen connecteren met een database waar deze gegevens opgeslagen worden. Wil de docent dan ook een overzicht krijgen van haar klas met daar dan de mogelijk elke leerling individueel hun process te bekijken? Willen ze ook weten hoelang de leerling over een oefening doet?

Waar deze app met moet uitblinken is dat je na afloop van een goede oefening geen standaard _"Goed gedaan"_ of _"Super! Op naar de volgende"_ feedback krijgt, maar dat de klank nog eens herhaald wordt waarom deze juist is. Vice versa voor als je een oefening fout hebt. Uitleggen waarom deze klank fout is en zeker en vast de klank nog eens laten horen.

> Het verschil tussen de 2 klanken laten horen om een duidelijker onderscheid te maken wanneer de oefening fout is.  

## Oefeningen 🎯
[Fien en Fons (isoleren)]()


## Learning Management Systems 📋
 - [What is LMS and the 20 best for 2019](https://elearningindustry.com/the-20-best-learning-management-systems)
 - [https://atutor.github.io/](https://atutor.github.io/)

## Mogelijke frameworks & engines 💥
- [Vue](https://vuejs.org/) (library)
- [React](https://reactjs.org/) (library)
- [Defold](https://defold.com/) (Lua)
- Vanilla html/css/js?
- [Angular](https://angular.io/)

## Nuttige Links 📎
- [React vs Vue](https://www.javatpoint.com/react-vs-vue)
- [React vs Angular](https://www.javatpoint.com/reactjs-vs-angularjs)
- [React vs React Native](https://www.javatpoint.com/reactjs-vs-reactnative)
- [Defold game engine](https://defold.com/)
- [Pros & cons - VueJS](https://naturaily.com/blog/pros-cons-vue-js)
- [Pros & cons - ReactJS](https://www.javatpoint.com/pros-and-cons-of-react)
- [Pros & cons - AngularJS](https://www.altexsoft.com/blog/engineering/the-good-and-the-bad-of-angular-development/)
- [Pros & cons - Lua (Defold)](https://www.reddit.com/r/lua/comments/6dd6c1/what_are_the_pros_and_cons_of_lua/)
- [Drag and Drop with ReactJS](https://codeburst.io/react-drag-and-drop-an-easier-tutorial-e0b739607c91)
- [Codepen: Todo drag delete](https://codepen.io/pasoevi/pen/ooOrpo)
- [Vue drag drop api](https://vuejsexamples.com/a-lightweight-vue-wrapper-that-abstracts-away-the-wonkier-parts-of-the-drag-and-drop/)
- [https://github.com/SortableJS/Vue.Draggable](https://github.com/SortableJS/Vue.Draggable)
- [https://github.com/pankajladhar/speedy-math REACTJS](https://github.com/pankajladhar/speedy-math)
- [https://github.com/skidding/flatris](https://github.com/skidding/flatris)

## Tutorials 💻
[Angular](https://www.freecodecamp.org/news/learn-how-to-create-your-first-angular-app-in-20-min-146201d9b5a7/)
[Vue](https://www.taniarascia.com/getting-started-with-vue/)
[Defold](https://defold.com/tutorials/getting-started/)
