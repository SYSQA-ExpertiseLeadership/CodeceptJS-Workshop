# CodeceptJS-Workshop
Op 24-Juli-2018 vond bij SYSQA in Bunnik een workshop CodeceptJS plaats. In deze repository vind je het resultaat van deze workshop. 

## Voorbereiding

Om het project te kunnen gebruiken is het van belang om het volgende geïnstalleerd te hebben:

### Frameworks
Alle onderstaande componenten.

* [JAVA](https://www.java.com/nl/download/) - Version 8 Update 171 of hoger
* [Node package manager](https://nodejs.org/en/) - Versie 8.11.3 of hoger

### IDE/Text edditors 

Eén van de volgende wordt aangeraden. Maar andere opties bestaan.

* [Atom](https://atom.io)
* [Vs Code](https://www.visualstudiocode.com)

## Hoe te gebruiken

Om te beginnen met dit project zijn er een aantal dingen die je moet weten.

### Powershell/cmd

Voor de volgende handelingen heb je de terminal nodig. de eenvoudigste manier om de terminal op de juiste locatie te openen is door naar de src folder te navigeren, de shift toets vast te houden en de rechtermuisknop in te drukken.
![](.\assets\powershell.gif)

### De eerste commands

Voer de volgende twee commands uit in de terminal 
````
npm install
````
````
npm run InstalleerSelenium
````
Deze commands voegen de benodigde packages toe aan het project.

### We kunnen beginnen

* Start Selenium

dit command start de selenium service die je tests gaan gebruiken. Als selenium niet gestart is gaan je tests niet slagen.

Wanneer dit command wordt uitgevoerd heb je geen controle meer over je terminal. het is dan ook handig om dit command in een tweede terminal in te voeren.

````
npm run StartSelenium
````
* Start Tests

Dit command start alle tests in het project en schrijft de resultaten terug naar de terminal.

````
npm run Test
````
* Maak een nieuwe test file

Dit command helpt je met het aanmaken van een nieuwe tests file. Hierdoor kun je tests voor verschillende onderdelen gemakkelijk van elkaar scheiden.

````
npm run NieuweTest
````
## Extra informatie

* [codecept documentatie](http://codecept.io)
