# Angular Ramschema – Kursöversikt för Webbutvecklingsprogrammet

Detta är en Angular-applikation som presenterar kursdata från Webbutvecklingsprogrammet vid Mittuniversitetet. Applikationen hämtar kursinformationen från en JSON-fil och visar den i en interaktiv tabell där användaren kan sortera och filtrera data.

## Funktionalitet

- Hämtar data från `ramschema.json`
- Visar kurskod, kursnamn och progression i tabellform.
- Sortering på alla kolumner (kurskod, kursnamn, progression).
- Filtrering i realtid baserat på sökfras i kurskod eller kursnamn.
- Gränssnittet uppdateras direkt med Angulars data-bindning, utan sidomladdning.

## Teknik

- Angular
- TypeScript
- HTML / CSS
- HttpClientModule
