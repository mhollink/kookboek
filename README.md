# Kookboek

Kookboek is een kleine react app waarin verschillende recepten kunnen worden opgeslagen.
Alle recepten die op de website weergegeven worden zijn geschreven in markdown en gebruiken
de [CommonMark](https://commonmark.org/) syntax.
Daarnaast zijn alle recepten voorzien van
stukje [frontmatter](https://dev.to/dailydevtips1/what-exactly-is-frontmatter-123g) om de recepten te voorzien van extra
meta-informatie.

## Frontmatter schema

Binnen het stukje frontmatter van een recept kun je de volgende velden gebruiken:

1. `titel` - De titel van het recept
2. `afbeelding` - Een afbeelding van het recept
3. `beschrijving` - Een korte beschrijving van het recept
4. `ingredienten` - Een lijst van ingredienten die nodig zijn voor het recept
5. `keuken` - De keuken waar het recept bij hoort zoals `Nederlandse`, `Italiaanse`, `Mexicaanse`, etc.
6. `vegetarisch` - Een boolean waarmee het recept wordt gemarkeerd als vegetarisch of niet
7. `gang` - Het type van het recept zoals `hoofdgerecht`, `voorgerecht`, `dessert`, etc.
8. `servings` - Het aantal personen dat het recept voorziet
9. `bereidingstijd` - De bereidingstijd van het recept in minuten
10. `voedingswaarden` - De voedingswaarden van het recept zoals `kcal`, `proteïnen`, `vetten`, etc.
11. `notities` - Eventuele notities of tips die bij het recept horen
12. `tags` - Een lijst van tags die het recept helpen te categoriseren
13. `rating` - De rating van het recept zoals `5` of `4`
14. `auteur` - De auteur van het recept
15. `datum` - De datum waarop het recept geplaatst is
16. `source` - De bron van het recept zoals `https://www.example.com/recept`

Bekijk de [voorbeeldrecepten](https://github.com/mhollink/kookboek/tree/main/public/recepten) voor een voorbeeld van hoe het stukje frontmatter eruit ziet.