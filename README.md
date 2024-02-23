# Hoe gebruik je Jupyter Notebooks met Anaconda?

Hier wordt uitgelegt hoe je Jupyter Notebooks gebruikt in de IDE van Visual studio code en hoe je deze linkt aan een omgeving/environment van Anaconda.


<br><br>







## Inleiding 

### Wat kunnen deze programma's en waarom zou je ze gebruiken?

Met het programma Anaconda kun je omgevingen maken die je softwarepakketten kunnen beheren, zoals Python, Pip en Jupyter om er maar een paar te noemen. 

Jupyter-notebooks zijn een vorm van universeel delen van data science-concepten, waarmee je live code kunt delen.

Visual studio code kan vele soorten coderingsbestanden beheren en kan gebruikt worden als gebruikersinterface, waardoor het praktischer in het gebruik is.

 <br><br><br><br><br><br><br><br><br><br>






## Inhoudsopgave

Hoofdstuk 1 basis: Begrippenlijst:

Hoofdstuk 2 basis: Download Anaconda

Hoofdstuk 3 basis: Download Visual studio code

Hoofdstuk 4 basis: Een Omgeving/environment maken 

Hoofdstuk 5 basis: De benodigde plug-ins downloaden 

Hoofdstuk 6 basis: Een Jupyter-notebookbestand maken in Visual studio code 

hoofdstuk 7 basis: Aansluiten

hoofdstuk 8 basis: Testen

Hoofdstuk 9 basis: Bekende installatieproblemen en hoe deze te debuggen 

Hoofdstuk 10 geavanceerd: Hoe kan je Powershell gebruiken als Terminal

<br><br><br><br><br><br><br><br><br><br>







## Hoofdstuk 1 basis: Begrippenlijst:

<br><br>

### je kan hier op terug kijken als je worden niet begrijpt.

<br><br>

### (Anaconda) 

Een progamma waar je paketjes kan toevoegen aan folders die jij aan maakt, deze folders kan jij vervolgens aan IDE's verbinden zoals Visual Studio code het is dan ook mogelijk om via de command prompt in Visual studio code pakketjes te downloaden in jouw Anaconda Omgeving/Environment.

<br><br>

### (Een Anaconda omgeving/environment) 

Dit is een folder met een bepaalde naam die je maakt binenn de aplicatie Anaconda, Anaconda vult jouw folder met was basis paketjes van code zoals Python en Pip wanneer jouw jouw IDE de paketjes nodig heeft kan die ze lenen van Anaconda's folder.

<br><br>

### (Visual studio code)

Visual studio code is een IDE progamma dus je kan via de user interface van Visual Studio werken aan een hoop type bestanden zoals Python en Jupyter Notebooks.

<br><br>

### (Een IDE) 

Een IDE is een "Geïntegreerde ontwikkelomgeving" / "Integrated Development Environment" deze laat jouw verschillende soorten programmeer bestanden zoals HTML, CSS, Python, en Jupyter notebook gebruiken en bewerken hier kan je dan ook meteen je code testen.

<br><br>

### (Jupyter Notebooks) 

Dit is een bestand type dat bedoelt is om makelijk data en code samen te kunnen delen, het heeft dan ook een functie om code te executeren.

<br><br><br><br><br><br><br><br><br><br>








## Hoofdstuk 2 basis: Download Anaconda:
(Belangrijk!) Download eerst Anaconda en installeer de software vanuit het gedownloade .exe-bestand, voordat je verder gaat met Visual studio code.
Dit andersom doen kan problemen veroorzaken.

<br><br>

### Anaconda Download link: https://www.anaconda.com/download/

<br><br>

Klik op de download van het besturingssysteem van je laptop, zoals Windows.

![alt text](image.png)

<br><br><br><br>

Open jouw "Bestandsverkenner" / "file explorer" links onderaan:
![alt text](image-23.png)

<br><br><br><br>

Zoek vervolgens de gedownloade set-up in kwestie die in jouw "Downloads" folder zit en dubbelklik op het bestand om de toepassingen toe te voegen aan je computer.

![alt text](image-1.png)

<br><br><br><br>

Volg de instructies die Anaconda geeft en verander de standaardaanbevelingen niet, de standaardinstellingen zijn voorlopig goed.

![alt text](image-8.png)

<br><br><br><br><br><br><br><br><br><br>









## Hoofdstuk 3 basis: Download Visual studio code:

### Visual studio code download: https://code.visualstudio.com/download

<br>

Klik op de download van het besturingssysteem van je laptop, zoals Windows.

![alt text](image-2.png)

<br><br><br><br>

Open jouw "Bestandsverkenner" / "file explorer" links onderaan:
![alt text](image-23.png)

<br><br><br><br>

Zoek vervolgens de gedownloade set-up in kwestie die in jouw "Downloads" folder zit en dubbelklik op het bestand om de toepassingen toe te voegen aan je computer.

![alt text](image-3.png)

<br><br><br><br>

Volg de instructies die Visual studio code geeft en verander de standaardaanbevelingen niet, de standaardinstellingen zijn voorlopig goed.

![alt text](image-22.png)

<br><br><br><br><br><br><br><br><br><br>








## Hoofdstuk 4 basis: Een Omgeving/Environment maken:

<br><br>

Selecteer eerst het tabblad "Omgeving" / "Environment" en klik linksonder op "Maak" / "Create".

![alt text](image-4.png)

<br><br><br><br>

Vink aan "Python" als dat nog niet het geval is en geef de Omgeving/Environment een passende naam. Als je klaar bent, klik je rechtsonder op "Maak" / "Create".

![alt text](image-5.png)

<br><br><br><br><br><br><br><br><br><br>










## Hoofdstuk 5 basis: De benodigde plug-ins downloaden:

<br><br>

Voor Visual Studio code installeer je de "Python" en "Jupyter" plug-ins.

Je vind ze linksboven door op het pictogram van de vier vierkantjes te klikken en de naam van de plug-in op te zoeken. Je hoeft alleen de hoofdplug-in te installeren, de rest wordt standaard geïnstalleerd.

![alt text](image-6.png)

<br><br><br><br>

Op de "Thuis"/"Home" van "Anaconda's Navigator" applicatie download je de volgende plug-ins: "Jupyter Notebook", "Jupyter Lab" en "QT Console".

![alt text](image-7.png)

<br><br><br><br><br><br><br><br><br><br>









## Hoofdstuk 6 basis: Een Jupyter-notebookbestand maken in Visual studio code:

&nbsp;

Ga naar "Bestand" / "File" en klik op "Nieuw bestand" / "New file".

![alt text](image-9.png)

<br><br><br><br>

Dit opent een prompt Selecteer "Jupyter Notebook".

![alt text](image-10.png)

<br><br><br><br>

Als je je bestand/file wilt opslaan, doe je het volgende: 

ga naar "Bestand" / "File" > "Opslaan als" / "Save as" > voer een naam in en geef bestandslocatie naar keuze.

Als je opslaat moet het bestandstype .ipynb zijn, de computer hoort dit voor je doen als je alles na de punt weg laat.

![alt text](image-11.png)

<br><br><br><br><br><br><br><br><br><br>









## Hoofdstuk 7 basis: Aansluiten:

<br><br>

gebruik de toetsen: ctrl > shift > P in Visual studio code typ dan "Python: Selecteer Tolk" / "Python: Select Interperter":

![alt text](image-13.png)

<br><br><br><br>

Selecteer in de nieuwe prompt de Omgeving/environment die je eerder hebt gemaakt.

![alt text](image-14.png)

<br><br><br><br>

Gebruik de toetsen: ctrl > shift > P in Visual studio code typ dan "Terminal: Selecteer Standaard Profiel" / "Terminal: Select Default Profile"

![alt text](image-24.png)

<br><br><br><br>

Selecteer de "Command prompt" optie.

![alt text](image-25.png)

<br><br><br><br><br><br><br><br><br><br>








## Hoofdstuk 8 basis: testen:

<br><br>

Schrijf deze code als een functionaliteitstest.

![alt text](image-12.png)

<br><br><br><br>

Je hebt een open terminal nodig om te testen of je omgeving/environment verbonden is.

Als je geen terminal open hebt staan, kun je een terminal openen door linksboven op "Terminal" te gaan staan en op "Nieuwe Terminal" / "New terminal" te klikken:

![alt text](image-15.png)

<br><br><br><br>

Nu kun je de juiste opdrachtprompt openen via de rechteronderkant door over het pijltje naast de + te gaan en op "Opdrachtprompt" / "Command prompt" te klikken.

![alt text](image-16.png)

<br><br><br><br>

Als je verbonden bent met je omgeving/environment, zie je de omgeving/environment naam links onderaan in de opdrachtprompt, gevolgd door de pathing naar de bestanden.

![alt text](image-17.png)

<br><br><br><br>

Je kan nu jouw "Command Prompt" Terminal testen door "conda" te typen en daarna enter te clicken:

![alt text](image-26.png)

<br><br><br><br>

Als je dit goed gedaan hebt leest de Terminal informatie uit over het programma van Anaconda zoals hier:

![alt text](image-27.png)

<br><br><br><br><br><br><br><br><br><br>










## hoofdstuk 9 basis: Bekende installatieproblemen en hoe deze te debuggen:

<br><br>

### Probleem 1: 

In sommige gevallen moet je Python installeren in de Microsoft store om een omgeving/environment te kunnen selecteren in Visual studio code.

![alt text](image-18.png)

<br><br><br><br>

### Probleem 2:

Soms toont de terminal je omgeving/environment niet op deze manier:

![alt text](image-17.png)


<br><br><br><br>

In dit geval moet de Kernel worden gewijzigd naar jouw omgeving/environment, om de terminal aan je omgeving/environment te koppelen.

Ga met de muis over "selecteer kernel" / "select kernel" en klik op "Selecteer een andere kernel..." / "select Another Kernel...".

![alt text](image-19.png)

<br><br><br><br>

Selecteer "Python-omgevingen" / "Python-environments".

![alt text](image-20.png)

<br><br><br><br>

Selecteer nu jouw omgeving.

![alt text](image-21.png)

<br><br><br><br><br><br><br><br><br><br>








## Hoofdstuk 10 geavanceerd: Hoe kan je Powershell gebruiken als Terminal

<br><br>

Vind de "Scripts" folder in de "anaconda3" folder het zou de zelfde pad / path moeten hebben, het doorkruisde deel is de "user" die jij gebruikt.

![alt text](image-28.png)

<br><br><br><br>

Klik nu rechtermuisknop op de "Scripts" folder naam van het vorige plaatje, en selecteer "Kopieer Address als tekst" / Copy Address as text.

![alt text](image-29.png)

<br><br><br><br>

Hou eerst je vinger op de Windows knop, vervolgens druk op de R knop zonder los te laten van de Windows knop.

Als het goed is zie je nu dit scherm links onderaan:

![alt text](image-30.png)

<br><br><br><br>

Typ in de prompt het volgende "sysdm.cpl" en klik op Oke links onderaan de prompt.

![alt text](image-31.png)

<br><br><br><br>

Een nieuwe prompt opened selecteer bovenaan "Geavanceerd" / "Advanced" en click onderaan "Omgeving Variabelen" / "Environment Variables"

![alt text](image-32.png)

<br><br><br><br>

Selecteer bij de "Systeem Variabelen" / "System Variables" de "Pad" / "Path" 

Selecteer vervolgens "Edit..." / "Bewerken..." rechts onderaan.

![alt text](image-34.png)

<br><br><br><br>

Selecteer in de nieuw prompt "Nieuw" / "New" 

![alt text](image-33.png)

<br><br><br><br>

Druk nu de knoppen:  ctrl > V  om het "Pad" / "Path" van eerder daar neer te plakken.

![alt text](image-35.png)

<br><br><br><br>

Klik nu op de "oke" rechts onder.

![alt text](image-36.png)

<br><br><br><br>

Doe het zelfde met de "oke" op de "Omgeving Variabelen" / "Environment Variables" van eerder.

![alt text](image-37.png)

<br><br><br><br>

En de op de "oke" van "Systeem Eigenschappen" / "System properties" van eerder.

![alt text](image-38.png)

<br><br><br><br>

Zoek op "Windows Powershell" in de search bar links onder op je computer.

![alt text](image-40.png)

<br><br><br><br>

Klik nu rechtermuisknop op de "Windows Powershell" en selecteer "Uitvoeren als administrator" / "Run as administrator"

![alt text](image-39.png)

<br><br><br><br>

Schrijf in de Windows Powershell prompt "Set-ExecutionPolicy RemoteSigned" en klik "Enter" op je toetsenbord.

![alt text](image-41.png)

<br><br><br><br>

Nu vraagt het of je deze verandering wilt maken typ Hoofdletter "Y" en druk "Enter" op je toetsen board om veder te gaan.

![alt text](image-42.png)

<br><br><br><br>

Je kan nu de prompt sluiten door op het kruisje te klikken.

![alt text](image-43.png)

<br><br><br><br>

sluit je Visual Studio Code af, druk rechtermuisknop op de Visual Studio Code icoon en selecteer "Sluit venster" / "Close window" 

![alt text](image-44.png)

<br><br><br><br>

Ga naar de search bar links onder en typ "visual studio code" en dubble klik het icoon boven aan van Visual Studio Code 

![alt text](image-45.png)

<br><br><br><br>

