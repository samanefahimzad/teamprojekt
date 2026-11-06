# Kafé Commit — Grupp [7]

## Roller
- Scrum Master: [Samane]
- Utvecklare: [Samane,Isac,Ghada,Dino]

## Tavla
Länk till Google Kalkylark/Docs: [https://docs.google.com/spreadsheets/d/1WR81oWInIVeNxMlSF3tVlZGvMKN1NBDW8cJRn0OhV7M/edit?usp=sharing]

## Sprintmål
När sprinten är klar ska kaféets startsida visa information om adress, kaffepris, wifi, telefonnummer, nötter, parkering, veckans erbjudande och eventkvällen.

## Daily standups
3/11-2026 Tisdag
-[Dino]: Har gått igenom projektets kod för att förstå hur den är uppbyggd. Idag ska han skriva en user story som hör till funktion 9. Inga hinder.
-[Ghada]: Har skapat tavlan och lagt in länken i README.md så att alla i gruppen kan komma åt den. Idag ska hon skriva en user story för funktion 3. Inga hinder.
-[Isac]: Har skrivit en user story och ska idag koppla den till funktion 7. Inga hinder.
-[Samane]: Jag har skapat gruppens GitHub-repository. Idag ska jag skriva en user story kopplad till funktion 5. Inga hinder.

4/11-2026 Onsdag
-[Dino]: Har arbetat med user story 10, skapat en branch, pushat koden till GitHub och skapat en Pull Request. Har även granskat Isacs user story och genomfört merge. Idag ska han fortsätta arbeta med att färdigställa funktionen. Inga hinder.
-[Ghada]: Har arbetat med user story 4, skapat en branch, laddat upp koden till GitHub, skapat en Pull Request och genomfört merge. Har även granskat Samanes user story. Idag ska hon slutföra funktionen. Inga hinder.
-[Isac]: Har arbetat med user story 7, skapat en branch och laddat upp sina ändringar till GitHub. Har även granskat Dinos user story och gett återkoppling. Idag ska han påbörja arbetet med user story 8. Inga hinder.
-[Samane]: Jag har arbetat med user story 5, skapat en branch, laddat upp min kod till GitHub och skapat en Pull Request. Jag har även granskat Ghad​​as user story och gett återkoppling. Idag ska jag påbörja arbetet med user story 6. Inga hinder.

5/11-2026 - Torsdag
- [Dino]: Slutförde userstory 10 igår och har även skrivit sin personliga reflektion. Idag ska han vara med och diskutera teorifrågorna med gruppen och sedan genomföra retrospektivet. Inga hinder.
- [Ghada]: Blev färdig med userstory 4 igår och har gjort klart sin personliga reflektion. Dagens plan är att arbeta tillsammans med gruppen kring teorifrågorna och delta i retrospektivet. Inga hinder.
- [Isac]: Avslutade arbetet med userstory 8 igår och skrev sin personliga reflektion. Idag kommer han att fokusera på gruppens teorifrågor och retrospektiv. Har inga hinder.
- [Samane]: Färdigställde userstory 6 igår och har också hunnit skriva min personliga reflektion. Idag är planen att tillsammans med gruppen besvara teorifrågorna och hålla retrospektiv. Inga hinder.



## Retrospektiv
- Start: Synka med alla utvecklare så vi använder samma kodformaterare.
- Stop: Tycker inte vi hade något som fungerade dåligt eller sinkade oss förutom det ovanstående om kodformateringen.
- Continue: Forsätta med korta effektiva dailies där alla jobbar på sina egna branches. Det gav en bra överblick för alla i gruppen och vi kunde undvika konflikter.
- Konkret förbättring: Kanske bestämma en regel att varje PR ska granskas inom en viss tidsram

## Teorifrågor

### 1. Vad är agil utveckling, och vad i ert arbetssätt den här veckan var agilt?
Agil utveckling är ett sätt att arbeta där man delar upp arbetet i mindre delar och utvecklar steg för steg. Den här veckan arbetade vi agilt genom att planera en sprint, använda en gemensam Kanban-tavla och följa upp arbetet genom daily-möten. Vi samarbetade, fördelade uppgifterna mellan oss och kunde hela tiden se vad som var klart och vad som behövde göras. På så sätt kunde vi följa arbetet tillsammans och se till att vi kom framåt.

### 2. Vilka Scrum-roller och moment använde ni? Beskriv hur de fungerade i er grupp.
Vi använde rollerna Scrum Master och utvecklare. Vi planerade arbetet tillsammans, delade upp uppgifterna och arbetade i en sprint. Vi hade daily-möten för att följa upp arbetet och använde en gemensam tavla för att se hur långt vi hade kommit. I slutet gick vi igenom resultatet och diskuterade vad som fungerade bra och vad vi kunde förbättra.


### 3. Beskriv hur en user story gick från Att göra till Klart hos er, med branch, Pull Request, review och merge.
Kortet gick från "att göra" till "pågår" när den ansvarige utvecklaren skapade och började arbeta på sin branch. Sedan från "pågår" till "granskning" när koden var pushad och utvecklaren öppnat en pull request på github. Där sedan en annan utvecklare i teamet fick granska diffen under changed files, kommentera & godkänna innan en merge pull request för att kortet ska bli "klart".

### 4. Vad är en merge-konflikt, när uppstår den och hur löser man den på GitHub?
En merge-konflikt uppstår när samma rad ändrats på olika sätt i två branches från samma utgångsläge, så att Git inte kan avgöra vilken version som gäller. Man löser den i PR:en på GitHub genom att klicka på Resolve conflicts, välja vilken ändring som ska behållas, ta bort konfliktmarkörerna och sedan Mark as resolved och Commit merge, följt av ett nytt Approve innan PR:en mergas. Exempel: om en branch ändrat return-raden i funktion01 till "Öppet: 08–16" och en annan branch till "Öppet: 09–15", och den första mergas in i main, måste den andra PR:en resolva konflikten i editorn och välja vilken text som kommer med. Prettier omformaterade hela filen i en branch, vilket vi löste genom att återställa filen, stänga av Prettier och committa igen på branchen, så att bara den aktuella funktionens ändring kom med i PR:en.


## Personlig reflektion
### [Ghada]
Jag har lärt mig hur man arbetar med Git och GitHub i ett team. Jag har tränat på att skapa branches, göra commits och Pull Requests samt granska andras kod. Till nästa gång vill jag bli säkrare på Git.
### [Samane]
Den här veckan har jag lärt mig hur man arbetar tillsammans i ett projekt med Git, GitHub och Scrum. Jag har lärt mig att skapa branches, göra ändringar i koden, använda Pull Requests och följa upp arbetet på en Scrum-tavla. Jag har också förstått hur viktigt det är att planera arbetet och ha bra kommunikation i gruppen. Till nästa gång vill jag bli ännu säkrare på GitHub.
### [Isac]
Jag har lärt mig hela flödet från branch och commit till Pull Request, code review med inline-kommentarer och merge, och hur någon annan i teamet alltid godkände min kod innan den lades in i main. På Scrum-sidan har jag lärt mig skriva user stories med acceptanskriterier, hålla tavlan uppdaterad och delta i dailies där vi stämde av vad var och en gjort och vad som låg framför, så att vi visste var sprinten låg. Till nästa gång vill jag bli säkrare på hela GitHub-flödet, från branch till mergad Pull Request, så att jag inte behöver kolla instruktionerna för varje steg.
### [Dino]
Jag har lärt mig att Git och pullrequests gör det mycket enklare att samarbeta i grupp utan att behöva trampa på varandras kod. Scrum hjälpte oss att hålla koll på vem som gör vad och dailies och tavlan gjorde att vi kände helt synkade och hade stenkoll på överblicken över sprinten. Ser fram emot att jobba på samma sätt i framtida projekt.
