# Mitt webbprojekt 👩‍💻
Det här projektet är en webbplats som jag har skapat som en del av min webbutvecklingskurs.

Webbplatsen är skapad med fokus på en tydlig struktur och enkel navigering. 

## Tekniker
- Projektet är byggt med HTML.

## Publicerade versioner av webbplatsen 
Du kan se min webbplats på följande plattformar: 
- https://ewvvs.github.io/dt224g_Evelina_Bjork/

- https://dt224g-evelinabjork.netlify.app

## git Q/A
*Vad är skillnaden mellan git add och git commit?*
`git add` lägger till de ändringar jag vill spara i nästa commit och placerar dem i staging area. Om jag lägger till en punkt `git add.` läggs alla ändrade filer till på en gång. `git commit` skapar sedan en ny version med dessa ändringar i med ett commit-meddelande i ditt lokala repo. 

*Varför använder man branches istället för att jobba direkt i main?*
Branches gör det möjligt att utveckla och testa ändringar separat från `main`. På så sätt kan jag göra ändringar utan att påverka den färdiga versionen direkt. T ex om jag vill arbeta på en ny funktion eller fixa en bugg. När ändringar är klara kan de mergas in i `main`. Det är även i branches som jag gör alla commits. 

*Vad händer rent praktiskt när man gör en merge?*
När jag gör en merge kombineras ändringarna från en branch med en annan branch - t ex kan ändringar från `dev`slå ihop med huvudgrenen `main` 

*Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?*
Att pusha till Github innebär att jag skickar mina ändringar och commits till Github för versionshantering och lagring av projektet. Att publicera på Netlify innebär att webbplatsen görs tillgänglig på internet så att andra kan besöka den. Github kan även kopplas till Netlify så att ändringar automatiskt publiceras när jag pushar till den valda branchen. 

*Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?*
Jag skapar en ny textfil som heter *gitignore* i projektets rotmapp. Sen kan jag lista filnam eller mappar rad för rad. 

Exempel:
- /scrap
- /uploads
- *.log





<!--
    * En kort beskrivning av webbplatsen
    * Vilka tekniker som använts (HTML och eventuellt CSS)
    * Länkar till de publicerade versionerna
    * Svar kortfattat på följande frågor om git:
        * Vad är skillnaden mellan git add och git commit?
        * Varför använder man branches istället för att jobba direkt i main?
        * Vad händer rent praktiskt när man gör en merge?
        * Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
        * Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
-->
