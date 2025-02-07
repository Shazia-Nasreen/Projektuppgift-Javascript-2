# Projektuppgift-Javascript-2
Reactify your resume!
Personlig Hemsida / CV - React SPA
Detta projekt är en interaktiv Single Page Application (SPA) som fungerar som mitt personliga CV och hemsida. Webbappen är byggd med React och innehåller sektioner om mina färdigheter, erfarenheter, projekt och kontaktinformation.

Teknisk Information
Webbapplikationen använder React för frontend, React Router för navigation, useState-hooken för lokal statehantering, och Redux för global statehantering. Appen är också byggd med TypeScript och CSS-preprocessor (SASS) för styling.

Funktioner
Komponentstruktur och Dataöde: Återanvändbara React-komponenter strukturerar webbplatsens layout och data skickas mellan komponenter via props för effektivt dataöde.
React Router: Implementerat för navigation mellan tre huvudsakliga sektioner på webbplatsen: 'Om mig', 'Projekt' och 'Kontakt'.
useState Hook: Används för att hantera lokal state, t.ex. för ett interaktivt kontaktformulär.
Redux: Används för global statehantering, t.ex. användarpreferenser som tema eller layout.
CSS (SASS): Användning av SASS för att strukturera och organisera CSS-koden på ett mer effektivt sätt.
Installation och Körning
För att köra applikationen lokalt på din maskin, följ dessa steg:

Kloning av repository:


git clone <[(https://github.com/Shazia-Nasreen/Projektuppgift-Javascript-2)l>
Installera beroenden: Gå in i projektkatalogen och kör följande kommando för att installera alla nödvändiga beroenden:


npm install
Starta applikationen: Kör följande kommando för att starta utvecklingsservern:


npm start
Detta kommer att öppna applikationen i din webbläsare på http://localhost:3000.

Bygg applikationen för produktion: Om du vill bygga en produktionsversion av appen, använd följande kommando:


npm run build
Den minifierade versionen kommer att finnas i build-mappen och kan distribueras på en server.

Struktur
Komponenter
Applikationen är uppbyggd av följande huvudsakliga komponenter:

Home: Välkomstsidan och sammanfattning av mitt CV.
AboutMe: En sektion som beskriver mig, mina intressen och bakgrund.
Projects: En lista över de projekt jag har arbetat på, med länkar till demo och källkod.
Contact: Ett interaktivt kontaktformulär där besökare kan skicka meddelanden.
Statehantering
useState används för att hantera lokal state, t.ex. formulärinput i kontaktsektionen.
Redux hanterar global state för användarpreferenser som tema (ljus/mörkt) och layoutinställningar.
Teknologier som Används
React - För att bygga komponentbaserad användargränssnitt.
React Router - För att hantera navigation mellan olika sidor (views).
Redux - För global statehantering.
TypeScript - För strikt typkontroll och bättre utvecklarupplevelse.
SASS - För att strukturera och förbättra CSS.
Extra Utmaningar (Valfritt)
TypeScript: Projektet är skrivet i TypeScript för att säkerställa typkontroll och mer robust kod.
SASS: CSS-koden är skriven i SASS för att göra styling mer modulär och återanvändbar.
Kodstandard och Dokumentation
Koden är organiserad och kommenterad där det behövs för att förklara komplexa delar och logik. Alla komponenter och funktioner är namngivna på ett konsekvent sätt.


