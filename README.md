# Parfymer på hyllan

En webbsida för att hålla koll på sina parfymer. Allt finns i en enda fil, `index.html`, och den fungerar utan konto och utan server.

## Vad sidan gör

- **Idag:** föreslår dagens doft efter väder, säsong, tid på dygnet och tillfälle, med dosering och spraypunkter.
- **Hyllan:** din samling, som går att gruppera, fälla ihop, visa som kort eller lista, betygsätta och märka som favorit.
- **Önskelista:** dofter du vill köpa, med målpris.
- **Hitta nya:** fritextsökning i en inbyggd katalog med drygt 300 dofter, alternativ i tre prisklasser och förslag per fack och per parfymhus.
- **Matris och Sprayguide:** räknas fram ur hyllan.
- **Statistik:** vad du bär, hur ofta, och vilka flaskor du har glömt bort.
- **Import och säkerhetskopia:** klistra in en lista (till exempel från Google Keep) eller välj en .txt- eller .csv-fil. Hyllan kan sparas och läsas in igen som .json, och laddas ner som .csv.

## Var data sparas

Allt sparas i webbläsarens lokala lagring (`localStorage`) på den enhet du använder. Ingenting skickas till någon server. Därför delas inte hyllan mellan telefon och dator. Använd **Säkerhetskopia** under Hyllan för att flytta den.

Vädret hämtas från [Open-Meteo](https://open-meteo.com/), med ortnamn eller ungefärlig plats avrundad till cirka en kilometer.

## Priser och katalog

Priserna i katalogen är ungefärliga svenska butikspriser och varierar. Länkarna på varje kort leder till Fragrantica (doftnoter), Deloox och Google Shopping (priser).

## Publicering

Sidan publiceras med GitHub Pages från grenen `main`, mappen `/` (rot).
