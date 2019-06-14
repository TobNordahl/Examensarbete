# Examensarbete
Här ligger alla filer till examesnarbetet. Projektet är ett försök till att visualisera variansen på pensionen och ge användaren ökad 
kunskap och intresse.
## Filer
Huvudfilerna är Test_plot_vXX.html där XX representerar verisonen. Högre versionsnummer betyder senare version.</br>
Test_plotvXX.html ska gå att köra uten att behöva ladda ner biblioteken d3 och jquerry, Test_plotvXX.html läser in d3 från deras hemsida 
när pogrammet körs.</br>
d3.min.js är d3 biblioteket som används (den behövs ej laddas ner för att köra koden).</br>
jquerry-3.3.1.js används inte längre.
## Bra att veta
Just nu plottas premiepension och tjänstepension i plotten som visualiserar de totala tillgångarna.</br>
I plotten där man ser sin lön är Inkomstpension,Premiepension,Tjänstepension och garantipension inkluderat.</br>
Det går att inkludera privat sparande på rad "1064" genom att sätta "enable_ps" till 0/1. 0=Använd ej 1=Använd.</br>
Det samma gäller tjänstepensionen på rad "1065". Vill man sänga av den sätt "enable_TP" till 0.</br>
## Senaste versionen
Den senaste verisonen är "Konfidensintervall.html".</br>
Jag har försökt att lägga till några vägledande kommentarer i koden för att underlätta läsningen. </br>
I denna verison är även funktionen för att räka ut pensionen uppdaterad så resultatet ser mer realistiskt ut.
Funktionerna ska även vara mer lättläsliga 
## Kommande arbeten
I nästa version som kommer är tanken att sidan ska fungera bättre när storleken på föstret ändras och även så jobbar ja på bättre läslig kod.
