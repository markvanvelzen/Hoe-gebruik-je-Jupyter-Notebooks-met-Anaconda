# Hoe gebruik je Jupyter Notebooks met Anaconda?

Hier wordt uitgelegt hoe je Jupyter Notebooks gebruikt in de IDE van Visual studio code en hoe je deze linkt aan een environment/omgeving van Anaconda.


&nbsp;


## Inleiding 

### Wat kunnen deze programma's en waarom zou je ze gebruiken?

Met het programma Anaconda kun je omgevingen maken die je softwarepakketten kunnen beheren, zoals Python, Pip en Jupyter om er maar een paar te noemen.

Jupyter-notebooks zijn een vorm van universeel delen van data science-concepten, waarmee je live code kunt delen.

Visual studio code kan vele soorten coderingsbestanden beheren en kan gebruikt worden als gebruikersinterface, waardoor het praktischer in het gebruik is.

&nbsp;

## begrippenlijst

&nbsp;

### je kan hier op terug kijken als je worden niet begrijpt.

&nbsp;

(Anaconda) een progamma waar je paketjes kan toevoegen aan folders die jij aan maakt, deze folders kan jij vervolgens aan IDE's verbinden zoals Visual Studio code het is dan ook mogelijk om via de command prompt in Visual studio code pakketjes te downloaden in jouw Anaconda omgeving/environment.

(Een Anaconda omgeving/environment) dit is een folder met een bepaalde naam die je maakt binenn de aplicatie Anaconda, Anaconda vult jouw folder met was basis paketjes van code zoals Python en Pip wanneer jouw jouw IDE de paketjes nodig heeft kan die ze lenen van Anaconda's folder.

(Visual studio code / IDE) een IDE progamma of Integrated Development Environment/Geïntegreerde ontwikkelomgeving laat jouw verschillende pogrameer bestanden hosten 


&nbsp;

## Inhoudsopgave

Hoofdstuk 1: De benodigde software downloaden 

Hoofdstuk 2: Een omgeving maken 

hoofdstuk 3: De benodigde plug-ins downloaden 

hoofdstuk 4: Een Jupyter-notebookbestand maken in Visual studio code 

hoofdstuk 5: Aansluiten en testen 

hoofdstuk 6: Bekende installatieproblemen en hoe te debuggen 

&nbsp; 

## Hoofdstuk 1: De benodigde software downloaden:
(Belangrijk!) Download eerst Anaconda en installeer de software vanuit het gedownloade .exe-bestand, voordat je verder gaat met Visual studio code.

&nbsp;

### Anaconda Download link: https://www.anaconda.com/download/

&nbsp;

Klik op de download van het besturingssysteem van je laptop, zoals Windows.

![alt text](image.png)

&nbsp;

Zoek de gedownloade set-up in kwestie die in jouw mapjes zit bij downloads en dubbelklik erop om de toepassing toe te voegen aan je computer.

![alt text](image-1.png)

&nbsp;

Volg de instructies die Anaconda geeft en verander de standaardaanbevelingen niet, de standaardinstellingen zijn voorlopig goed.

![alt text](image-8.png)

&nbsp;

### Visual studio code download: https://code.visualstudio.com/download

&nbsp;

Klik op de download van het besturingssysteem van je laptop, zoals Windows.

![alt text](image-2.png)

&nbsp;

Zoek de gedownloade set-up in kwestie die in jouw mapjes zit bij downloads en dubbelklik erop om de toepassing toe te voegen aan je computer.

![alt text](image-3.png)

&nbsp;

Volg de instructies die Visual studio code geeft en verander de standaardaanbevelingen niet, de standaardinstellingen zijn voorlopig goed.

![alt text](image-22.png)

&nbsp;

## Hoofdstuk 2: Een omgeving maken:

&nbsp;

Selecteer eerst het tabblad Omgeving en klik linksonder op Maak.

![alt text](image-4.png)

&nbsp;

Selecteer Python als dat nog niet het geval is en geef de omgeving een passende naam. Als je klaar bent, klik je rechtsonder op create.

![alt text](image-5.png)

&nbsp;

## Hoofdstuk 3: De benodigde plug-ins downloaden:

&nbsp;

Voor Visual Studio code installeer je de Python en jupyter plug-ins.

Je kunt ze vinden door op het pictogram van 4squares linksboven te klikken en de naam van de plug-in op te zoeken. Je hoeft alleen de hoofdplug-in te installeren, de rest wordt standaard geïnstalleerd.

![alt text](image-6.png)

&nbsp;

Op de startpagina van Anaconda's software applicatie download je de volgende plug-ins: Jupyter Notebook, Jupyter Lab en QT Console.

![alt text](image-7.png)

&nbsp;

## Hoofdstuk 4: Een Jupyter-notebookbestand maken in Visual studio code:

&nbsp;

Ga naar bestand/file en klik op nieuw bestand/new file.

![alt text](image-9.png)

&nbsp;

Dit opent een prompt Selecteer "Jupyter Notebook".

![alt text](image-10.png)

&nbsp;

Als je je bestand wilt opslaan, doe je het volgende: 

ga naar bestand > opslaan als > voer een naam en bestandslocatie naar keuze in.

Als je opslaat moet het bestandstype .ipynb zijn, de computer moet dit voor je doen.

![alt text](image-11.png)

&nbsp;

## Hoofdstuk 5: Aansluiten en testen:

&nbsp;

Schrijf deze code als een functionaliteitstest.

![alt text](image-12.png)

&nbsp;

gebruik de opdracht: ctrl > shift > P in Visual studio code typ dan Python: Selecteer tolk/interperter:

![alt text](image-13.png)

&nbsp;

Selecteer in de nieuwe prompt de omgeving die je eerder hebt gemaakt.

![alt text](image-14.png)

&nbsp;

Je hebt een open terminal nodig om te testen of je omgeving verbonden is.

Als je geen terminal open hebt staan, kun je een terminal openen door linksboven op Terminal te gaan staan en op Nieuwe Terminal te klikken:

![alt text](image-15.png)

&nbsp;

Nu kun je de juiste opdrachtprompt openen door naar de rechteronderkant te gaan, over het pijltje naast de + te gaan en op "Opdrachtprompt" te klikken.

![alt text](image-16.png)

&nbsp;

Als je verbonden bent met je omgeving, zie je de naam links onderaan de opdrachtprompt, gevolgd door de pathing naar de bestanden.

![alt text](image-17.png)

&nbsp;

## hoofdstuk 6: Bekende installatieproblemen en hoe te debuggen:

&nbsp;

Probleem 1: 
In sommige gevallen moet je Python installeren in de Microsoft store om een omgeving te kunnen selecteren in Visual studio code.

![alt text](image-18.png)

&nbsp;

Probleem 2:
Soms toont de terminal je omgeving niet op deze manier:

![alt text](image-17.png)

&nbsp;

In dit geval moet de Kernel worden gewijzigd in de omgeving, om de terminal aan je omgeving te koppelen.

Ga met de muis over Kernel en klik op "Selecteer een andere kernel...".

![alt text](image-19.png)

&nbsp;

Selecteer Python-omgevingen.

![alt text](image-20.png)

&nbsp;

Selecteer nu je omgeving.

![alt text](image-21.png)

&nbsp;