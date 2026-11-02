# nikeochwilliam.github.io
Bröllopssida för Nike och William

## Tillfälligt lösenord

Lösenordet är `snart2027`. Ändra `SITE_PASSWORD` i `index.html` för att byta
det. Efter rätt lösenord kommer webbläsaren ihåg upplåsningen med `localStorage`,
även efter omladdning eller omstart. Lösenordet sparas inte i webbläsarens lagring.
Rensa webbplatsens lagring för att låsa sidan igen. Andra webbläsare eller enheter
behöver låsas upp separat. Om lagring blockeras fungerar upplåsningen fortfarande,
men lösenordet behöver anges igen vid nästa besök. JavaScript måste vara aktiverat.
Ett lösenordsbyte låser inte ute webbläsare som redan har låst upp sidan; ändra även
`UNLOCK_STORAGE_KEY` om tidigare upplåsningar ska återställas.

Detta är bara ett enkelt insynsskydd för vanliga besökare, inte säker
åtkomstkontroll. Både lösenordet och innehållet finns i den offentliga
källkoden och kan läsas utan att låsa upp sidan. Använd inte ett lösenord som
används någon annanstans. För verkligt skydd krävs åtkomstkontroll hos en
server eller värdtjänst; GitHub Pages stöder inte detta för den här publika sidan.

När sidan är klar: ta bort lösenordsskärmen och skriptet, flytta ut sidans
`main` ur `template` och återställ sidtiteln.
