# airbean-grupp-war-unicorns
**Lam Mai**<br>
**Stefan Mogren**<br>
**Thapa**

Länk till FigJam: https://www.figma.com/board/tNgz6TZnQGExygZzP8skjb/War-Unicors---Gruppexamination-Airbean?node-id=0-1&t=aayqtrhBtKsBuAyS-1

# Sammanfattning
## Decomposition
För att utläsa färgerna så har vi valt att färger representerar olika stegnivåer i systemet: <br>
Lila - Huvudnivå <br>
Gul, orange, röd - Nedgående underkategorier i systemet<br>
Grå - Databastabeller där information antingen lagras eller hämtas från databastabeller beroende på vilken sida eller funktion som användaren använder.<br>

Som användare så kommer man kunna ha möjlighet att göra beställning som gäst eller som inloggad. Som gäst kommer man endast att nå orderstatus (som försvinner när tiden löpt ut) medan som inloggad kommer man även kunna se orderhistoriken samt att ordernumret sparas där. För gästen/inloggad kan även få kvitto med ordernumret via sms men måste fylla i telefonnummer för detta.

Vi har lagt till “Kontaktformulär” inom kundhantering där användaren kan kontakta företaget vid eventuella klagomål/felbeställningar eller allmänna frågor. För snabbare hantering kommer det krävas ordernummer.

I beställningen har vi tolkat “Take my money” som att gå till betalning och inte samma som verifiera och bekräfta beställningen. Detta gör att den vyn endast anses som att visa varukorg och att det kommer ytterligare en sida senare för att genomföra köpet.
Som inloggad kommer leveransadressen att vara ifylld vid beställning men att man har möjlighet att välja en annan leveransadress medan gästen kommer behöver fylla i dessa uppgifter.

Vi har lagt in en funktion med push-notiser för att få kunder att “komma tillbaka” och köpa sin kaffe. Detta genom att visa när det är dagar som man kan få rabatt. 

Vi anser att det är för få produkter att beställa i denna app så att det inte finns något behov av något filtersystem eller sökfunktion.

## Pattern recognition
Användarbeteenden som vi identifierar i appen är huvudsakligen att beställa kaffe. Därefter beror det på om användaren väljer att genomföra köpet som gäst eller som inloggad. För både gästen och inloggade kommer de kunna se orderstatus via overlay i appen, banner samt avisering på skärmen medan för de som är inloggade kommer det även finnas möjlighet att se sin orderhistorik.

För köp av kaffe ska ske smidigt hamnar kunden omedelbart på produktsidan och kan göra beställning.

Ett användarbeteende för inloggade kunder skulle kunna vara att se sina tidigare ordrar samt eventuella rabatter. Detta görs genom sin profilsida efter att man ha loggat in.

För kunder som har åsikter om tjänsten/produkten så finns det möjlighet att ta kontakt via kontaktformulär och ordernummer får man som gäst möjlighet att få på sms medan inloggad även har det i sin orderhistorik.

## Abstraction
De stora stegen i appen är att användaren ska kunna beställa kaffe som gäst eller som inloggad. Därefter har båda möjligheten att välja kaffe, ange leveransadress, betalningsmetod samt se orderstatus.

Vi har sedan presenterat alla huvuddelar med tillhörande beståndsdelar som är av vikt för att användaren ska kunna genomföra ett köp och tagit bort onödiga element. Detta blir då vår strukturkarta över vilka delar som behöver ingå.

## Alghorithm design
Vi har gjort ett flödesschema som presenterar hur flödet ser ut för att göra en beställning som gäst, kund eller en användare som vill bli kund. För gästen skiljer det sig åt när man gör betalningen där den behöver fylla i leveransadress samt telefonnummer för att få ordernummer medan en som är inloggad kommer istället kunna se det i sin orderhistorik. Vidare har även den inloggade möjlighet att ta del av erbjudanden. Både gästen och inloggade kommer kunna få aviseringar/banner gällande orderstatusen.

Det kommer finnas två möjligheter för en användare att logga in. Ena sättet är genom min profil medan andra sättet är precis före man gör sin betalning. Då blir användaren tillfrågad om de vill logga in/skapa konto för att t ex få fördel med sparad orderhistorik samt ta del av erbjudanden. Är användaren redan inloggad så blir den inte tillfrågad om detta.<br>

Lila rektangel: Sidor/händelser/funktioner<br>
Gul rund cirkel: Val för användare<br>
Grå diamant - Intern kontroll
