# Moment 3 - Uppgift 3 i kursen Dt207G, Backend-baserad webbutveckling

### Webbplatsen
På den här webbplatsen kan du lagra ditt CV i form av anställningar med Företagsnamn, arbetstitel, ort, start och sluttid för anställningen samt en längre beskrivning av arbetet. Inläggen sparas i en databas med hjälp av ett api. Inläggen ligger synligt för alla som använder sidan och skriv därför inte in känslig information. 

### Sidan består av följande:
* Startsida
  * Här syns alla CV-inlägg eftersom att de hämtas med ett fetch get-anrop efter att sidan har laddats in.
  * Det går att välja vilket inlägg som ska tas bort eftersom att id-knappen innehåller index för inlägget som skickas med till databasen genom ett fetch delete-anrop.
* Lägg till-sida:
  * Formulär som läser in data och skickar vidare till apin med ett post-anrop om alla värden är ifyllda. Där sparas inlägget in till en databas.
* Om sidan-sida:
  * Information om sidan.
 
### Uppbyggnad
*Webbplatsen skapades i ett node.js-projekt och använde parcel som atomatiserad utvecklingsmiljö.
*Skriven i html, css och javaScript

Här går det att testköra webbplatsen [på denna länk](https://ditt-cv.netlify.app/). Koden innehåller många kommentarer som kan svara om fler frågor finns om webbplatsen. En mer ingående beskrivning av api-funktionerna och hur den används hittar du [här](https://github.com/MarkusVickman/dt207g-moment3/).

### Replikera
För att jobba vidare på webbplatsen eller testköra koden lokalt behövs node.js vara installerat på datorn. Sedan ska kommandot "npm install" köras i rotkatalogen för webbplatsen. För att testköra används kortkommandot "npm run start" eller "npm run build" för att skapa en produktionsfärdig webbplats.

## Markus Vickman
Jag läser till en högskoleexamen i datateknik med inriktning webbutveckling på mittuniversitet.

### Student ID: mavi2302
