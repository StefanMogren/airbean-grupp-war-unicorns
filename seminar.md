# AI och datalogiskt tänkande
## 01
Svaren från båda AI-assistenterna skiljer sig åt gällande hur mycket av lösningen som man får. Från ChatGPT så ger den ett mer detaljerat svar utifrån frågan med steg för steg inom varje kategori medan AIZO bollar tillbaka frågan där den ger ledtrådar inom vilket område man behöver tänka för att hitta lösningen.


AIZO gör ytterligare en bedömning om förslag på att t ex göra lösningen med pseudokod, vilket inte ChatGPT gör. Här kan det vara så att AIZO tar hänsyn till att algorithm design hör till ett större arbetsområde och uppmanar frågeställaren till att själv ge ett förslag om pseudokod.
## 02
Båda ger liknande pseudokod fast ChatGPT ger kommentarer till varje steg och även utförlig beskrivning av hela pseudokoden. Aizo i sin tur uppmuntrar att man tänker själv i varje steg och har hjälpt till att bryta ner det till 4 steg där varje steg har en efterföljande fråga kopplad till steget. 


Om vi jämför båda så skriver Aizo att den ger en start till hur man skriver pseudokoden men när vi jämför båda så är pseudokoden likadana på båda, dock har Aizo inte någon kommentar vid sidan av stegen. Här tror vi att Aizo tror att uppgiften är större än vad den är och har således gett hela pseudokoden.


**SVAR FRÅN AIZO:** För att skapa pseudokod behöver vi bryta ner problemet i mindre delar. Här är några frågor och tips för att komma igång:
Starta spelet: Hur börjar vi spelet och initierar variablerna?
Kasta tärningen: Hur representerar vi ett tärningskast och kontrollerar om resultatet är det vi vill ha?

Steg-för-steg: Hur ser vi till att vi kastar om tills vi får rätt nummer i ordningen (1, 2, 3, osv.)?
Räkna kast: Hur håller vi reda på antalet kast?
Här är en liten start på pseudokoden för att komma igång:
Starta spelet
  Sätt nuvarande mål till 1
  Sätt antal kast till 0


Medan nuvarande mål är mindre än eller lika med 6
  Kasta tärningen
  Öka antal kast med 1
  Om tärningskastet är lika med nuvarande mål
    Öka nuvarande mål med 1


Skriv ut antal kast
Kan du fylla i detaljerna och fundera på hur varje del skulle fungera?
## 03
Båda gav JavaScript-koder som fungerade. ChatGPT bakade in hela koden i while-satsen medan Aizo delade upp den i en while och en funktion. I detta exempel skulle Aizos funktion kunna återanvändas i en annan del.


ChatGPT gav med kommentarer till vad som händer i koden vilket gör att förståelsen för stegen kan öka medan Aizo hade noll kommentarer i koden.
## 04
ChatGPT/Aizo kan endast ge svar på det som man promptar till den men har inte förståelse för helheten i ett större projekt. T ex så kan utvecklaren lägga in en viss typ av kod i ett tidigare stadie som sedan kommer användas i ett senare stadie där ChatGPT/Aizo inte kan koppla den tanken om utvecklaren inte förklarar helheten. Detta kommer att kräva tydlighet från den som promptar att ge korrekt och väsentlig information för att kunna få svar som kan lösa projektet.


Vid säkerhetsaspekter kan det uppstå problem då utvecklaren inte kan delge all information vid promptning och därav så kan hjälpen från ChatGPT/Aizo inte fungera fullt ut då den saknar all information. Detta kan även vara likadan om man vill skydda sin unika källkod som ett företag har utvecklat själva.
## 05
Aizo ger ett mer övertydlig referering där den t ex anger första, andra, tredje värdet i sin punktlista medan ChatGPT utgår från att frågeställaren ska koppla svaren till rätt värde. Aizo ger förklaringen av varje värde i hela meningar medan ChatGPT ger dem i punktlistor.


Övrig har båda två ett tydligt och enkelt språkbruk som gör att även de som är nybörjare kan förstå vad varje värde representerar och gör samt vad som sker när man ändrar ett värde.
## 06
Vi fick aldrig tillbaka samma kod som vi skickade in då ChatGPT reviderade koden vid varje promptning.

Vi tror att ChatGPT föreslår att .promise() inkluderas för att den känner till att den koden har använts av tidigare utvecklare inom detta område. Nu när den är utdaterad så vet inte ChatGPT om detta och kan därför inte ta egna slutsatser baserade på att den inte förekommer mer i andras koder. Vi tror att ChatGPT behöver att instruktioner om att denna är utdaterad och då den förekommer i dessa svar så har inte ChatGPT fått vetskap om detta.
## 07
Vi märkte ett lite annorlunda ordval mellan dessa två samt i tabellen så hade
När vi applicerade anpassningen så upplevde vi att i detta exempel så blev det inte mer tydligt för en nybörjare att förstå ämnet. 


Detta kan bero på att ämnet är svårtolkat och att man behöver ge ytterligare instruktioner till ChatGPT att bryta ner delarna. Här kan ChatGPT ha tolkat att det svar som den har gett är på en nybörjarnivå medan vi upplevde att det fortfarande var svårbegriplig.
## 08
En skillnad i den anpassade ChatGPT är att den gav en generell beskrivning av hur funktionen fungerar. När vi tog bort anpassningen så förklarade ChatGPT hur funktionen fungerar utifrån syntaxen. Även i denna version så gav den exempel på texter som man kunde testa funktionen på. Vi tror kanske att detta inte visas för nybörjaren då det blir för mycket saker för nybörjaren att ta in på en gång.


## 09
Vi tycker att det är okej att fråga AI om vilka funktioner och verktyg man kan använda sig av samt hur de fungerar. Vidare kan man be AI att förklara delar av andras kod.


Vi tycker att det inte är okej att fråga AI när man har sekretesskänslig kod. Som student är det inte okej att be AI att skapa hela koden åt en.


## 10
Den största risken är att man tror att man kan koda. Studenten får då en falsk tro att man förstår hur programmering fungerar.


En annan risk är att studenter inte utvecklar förmågan att själv ta beslut vilka vägar man kan ta för att lösa problemet utan tar endast förslag från AI som kanske inte är det bästa förslaget. 


AI kan även ge felaktiga eller utdaterade förslag och är inte studenter kritiska till förslagen så kan de ge stora konsekvenser i programmeringen. 
## 11
Styrka: Att den kan hitta små mänskliga fel som att ha glömt en semikolon. Ytterligare styrka är att den kan ge förslag på funktioner som studenten inte har vetskap om och därmed möjliggör att studenten kommer ha fler lösningar att använda sig av i framtiden. 


Svaghet: Den kan skriva koden åt studenten och studenten får därmed aldrig chansen att själv lära sig hur man kodar. Om man förlitar för mycket på den så kan man förlora eller inte utveckla förmågan att hitta buggar. Om man använder sig av förslag på lösningar så kan studenten göra fel val pga mindre erfarenhet jämfört med en senior som kan avgöra om förslagen kommer kunna lösa problemet. Studenten riskerar att bli en promptare istället för att veta hur man löser problemet själv.


## 12
Att man kan fråga Github Copilot om allmänna frågor om ens kod eller förslag på olika t ex funktioner som kan fungera. Ett annat scenario är att den kan leta efter mänskliga småfel som t ex avsaknad av semikolon som gör att en kod t ex inte fungerar. Ytterligare scenario är att ge instruktioner till Github Copilot ska uppföra sig som en lärare och inte ge “facit” direkt utan ger ledtrådar eller förslag på hur man kan lösa problemet.
## 13
Att Github Copilot är integrerat i programmet och man behöver inte växla till något annat fönster eller ge information om koden för att den ska förstå vad man programmerar.


Att den snabbt kan hitta mänskliga fel som semikolon eller felstavat klassnamn.
Man kan spara tid genom att den kan ge förslag på lösningar så att man inte fastnar länge vid ett problem om man har svårt med idéer hur man kan lösa problemet.
## 14
Vi tror att AI kommer att få en viktigare roll inom en utvecklares yrke där det i framtiden kommer att vara ett krav hur man använder AI på bästa sätt. För närvarande kan det vara upp till varje utvecklare att se användningsområden för AI.


Vi tror att rollen som utvecklare fortfarande kommer vara den som tar alla beslut men att det kommer kräva att man klarar av mer komplexa problem. Då AI kan effektivisera inom vissa områden som “enkel kodning” gör att det kan finnas färre roller/tjänster för juniorer att kunna jobba på.


Utvecklare som jobbar med säkerhetsaspekter tror vi kommer att ha en fortsatt liknande roll då man begränsar sig av användning av AI pga risk för att koden kan spridas till andra företag. 


## 15
En risk är att AI kan ge t ex utdaterade funktioner/förslag som inte används längre.


Om man använder sig av endast AI som källa i t ex förslag på lösningar så kan det begränsa till att ta fel/sämre beslut då man förlitar sig på AI då erfarenheten är mer begränsad hos en junior.


AI kan ha fel i sina svar och detta kan ge stora konsekvenser då om man använd t ex AI för att felsöka så kommer den möjligtvis godkänna sin lösning, trots att lösningen från början inte är korrekt.
## 16
Adrenaline AI - En tjänst för utvecklare som hjälper till och svarar på frågor inom programmering. Den använder offentlig kod på Github som referenser och den kan hitta dokumentering om olika saker på olika hemsidor. Man kan ställa frågor om t ex publika repository och få svar om t ex koden på det repot. Den är användbar för studenter som vill lära sig mer om programmering då den ger detaljerade och visuella förklaringar.


AskCodi - Kan integreras i VS code och andra stora IDE:er. Är en intelligent kodningskompis som hjälper till att göra kodningen enklare och snabbare genom att vara en kodgenerator, skapa automatiska tester osv. Den passar för både nybörjare som mer erfarna utvecklare.


TestCraft - Ett AI-tillägg som kan testa olika element på en sida där den ger en överblick över positiva/negativa testresultat. Den kan även generera testidéer. Vidare kan den även hjälpa till med att testa tillgängligheten på sidan.


## 17
Adrenaline tror vi skulle vara mest användbar för studenter då de beskriver sin tjänst att den ger pedagogiska och detaljerade förklaringar och är lämpade för nybörjare. Vidare kan den analysera och förstå stora kodbaser för att hjälpa nytillkomna att förstå ett projekt. Den är även designad för att användas av nybörjare, erfarna, teams samt lärare och studenter.
