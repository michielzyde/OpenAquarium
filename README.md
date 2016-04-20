# OpenAquarium

Omschrijving Project: Met behulp van een Arduino bordje en Raspberry Pi moeten we via een interface ons Aquarium kunnen gaan aansturen. Zo moet het mogelijk zijn om de leds aan of uit te leggen, temperatuur regelen, feeder van de visjes in te stellen op bepaalde tijdstippen etc. Het zal dus de bedoeling zijn om de Pi te laten communiceren met de Arduino en een webserver te laten draaien op de Pi en hierop onze interface aan te gaan maken om zo alle zaken van het aquarium te regelen!

Technologieën

1.	ARDUINO
o	Arduino is een opensource-computerplatform dat is opgebouwd rond de ATmega168 -microcontroller van Atmel en het softwareontwikkelplatform Processing. Dit platform is gemaakt voor mensen die geïnteresseerd  zijn in het maken en ontwerpen van slimme en creatieve objecten die kunnen reageren op hun omgeving. Met Arduino is het mogelijk apparaten en objecten te creëren die reageren op hun omgeving door middel van digitale en analoge inputsignalen. Op basis van deze input kan een Arduinoschakeling autonome act...(line truncated)...

o	Voordelen: 
	Codevoorbeelden beschikbaar, zo heb je een gedacht hoe je eraan moet beginnen!
	Ready to use, gewoon inpluggen in de USB poort en je kan beginnen programmeren!
	Geen moeilijke codetaal
	Communicatie mogelijk met andere devices bv. Raspberry Pi
	…

o	Nadelen: 
	Kostprijs is hoog
	…

2.	RASPBERRY PI
o	De Raspberry Pi is de naam van diverse singleboardcomputers gebaseerd op een ARM-processor die tegen een minimale prijs worden vervaardigd en verkocht. De Raspberry Pi werd ontwikkeld aan deUniversiteit van Cambridge en was bedoeld voor educatieve doeleinden. Er zijn verschillende modellen en versies uitgebracht. De hardware van de verschillende versies van de Raspberry Pi kenmerkt zich door een open structuur die lijkt op de open structuur van de eerste IBM Personal Computers. De aanwezigheid van de GPIO...(line truncated)...

o	Voordelen
	Kostprijs is redelijk laag 
	Communicatie met andere devices zoals de Arduino Controller!

o	Nadelen
	Geen ondersteuning voor x86 OS

Planning: 

•	Arduino uittesten
•	Github project aanmaken
@@ -10,9 +29,11 @@ 
Planning:
•	Verslag opstellen
•	…..

Taakverdeling: 
•	Opzetten Webserver: Tiziano Colpaert
•	Github project aanmaken & structuur indeling: Michiel Zyde
•	Arduino mogelijkheden testen (feeder, lights, temperature,..): Michiel Zyde
•	Verslag opstellen: Tiziano Colpaert & Michiel Zyde
•	Opzetten Webserver: Tiziano Colpaert 	 DONE
•	Github project aanmaken & structuur indeling: Michiel Zyde 	
•	Aanmaken interface: Tiziano Colpaert 	BIZZY
•	Info Arduino op de webserver weergeven: Tiziano Colpaert 	BIZZY
•	Arduino mogelijkheden testen (feeder, lights, temperature,..): Michiel Zyde 	
•	Communicatie tussen de Arduino en Pi 	TO DO
•	Werkende interface & besturing ervan 	TO DO
•	Verslag opstellen: Tiziano Colpaert & Michiel Zyde	 UNDER CONSTRUCTION
