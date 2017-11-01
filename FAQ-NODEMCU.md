# Beginnen met de NodeMCU
_Een NodeMCU is een kleine computer met allerlei in- en uitgangen die eenvoudig met het internet is te verbinden. Je kunt een NodeMCU herkennen aan de micro-USB aansluiting aan de ene kant en een wifi-antenne op de andere kant. Het printplaatje heeft afmetingen van ongeveer 5 x 2,5 cm. Je programmeert de NodeMCU met enkele instructies in de taal Lua, wat 'maan' betekent in het Portugees. Met deze tips gaat dat lukken._

## Wat heb je nodig
* Een NodeMCU
* Een micro-USB kabeltje
* Een Windows- of OS X computer (Linux kan ook, maar het gebruik daarvan beschrijven we hier niet)
* Beschikking over een wifi toegangspunt

Verder is een breadboard met minimaal 400 gaatjes handig en draadjes waarmee je gemakkelijk op het breadboard verbindingen kunt maken. Op je Windows- of OS X computer moet een USB-driver voor de NodeMCU worden geïnstalleerd. Ook moet de ESPlorer programmeeromgeving worden gedownload. Om deze te kunnen gebruiken is Java nodig, die meestal al wel op de computer staat.

## Werken met de programmeeromgeving

## Verbinding maken met de NodeMCU

## Je eerste programma op de NodeMCU
Met het programma `blink.lua` laat je een ingebouwde led op de NodeMCU knipperen. Je controleert met dit programma of je alles goed op je computer hebt geïnstalleerd en ziet gelijk je NodeMCU werken.

## Je NodeMCU met het internet verbinden

## Een sensor aansluiten op je NodeMCU

## Gebruik maken van de kracht van het internet
Je NodeMCU kan heel eenvoudig een webpagina opvragen met de instructie `http.get("http://adres-van-de-webpagina")`. Sommige webpagina's voeren taken voor je uit, voordat ze de pagina tonen. Ze kunnen bijvoorbeeld een twitterbericht voor je versturen, of namens jou een email verzenden. Zo'n taak-uitvoerende-website is `IFTTT.com`, wat voor _IF_ _This_ _Then_ _That_ staat ("als dit, dan dat"). Je kunt met IFTTT instellen dat als je er een speciale pagina (je noemt dat een _websocket_) opvraagt, IFTTT voor jou een activiteit uitvoert. Je maakt, zoals IFTTT het noemt, een _applet_. Het adres van die speciale pagina kopieer je in je NodeMCU. Nu kan de NodeMCU op ieder moment de applet aanroepen, bijvoorbeeld als een nieuwe sensorwaarde beschikbaar is.

* <small>Download de USB driver voor de NodeMCU voor <a href="">Windows</a> of voor <a href="">OS X</a></small>
* <small><a href="https://www.java.com/en/download/installed.jsp">Controleer of Java op je computer staat</a></small>
* <small><a href="">Download de ontwikkelomgeving ESPlorer</a></small>





