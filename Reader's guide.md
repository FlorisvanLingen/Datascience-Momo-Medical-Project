# <h1> Datascience-Momo-Medical-Project <h1>
![](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/Afbeelding1.jpg?raw=true)
  
 

<h2> Inhoudsopgave </h2>
  <h5> 1. Inleiding </h5>
  <h5> 2. Doelstelling </h5>
  <h5> 3. Kennis van het domein </h5>	
    <ul><h5>3.1. Datacamp cursussen</h5></ul>
    <ul><h5>3.2. Onderzoeksvragen</h5></ul>
    <ul><h5>3.3. Jargon en definities</h5></ul>
    <ul><h5>3.4. Literatuur</h5></ul>
  <h5> 4. project Methoden en planning </h5>
  <h5> 5. Voorbereiding data </h5>
    <ul><h5>5.1. Verkennen data</h5></ul>
    <ul><h5>5.2. Opschonen data</h5></ul>
    <ul><h5>5.3. Voorbereiden data</h5></ul>
    <ul><h5>5.4. Uitleg data </h5></ul>
  <h5> 6. Voorspellende analyse </h5>	
    <ul><h5>6.1. Selectie model</h5></ul>
    <ul><h5>6.2. Configuratie model</h5></ul>
    <ul><h5>6.3. Training model</h5></ul>
    <ul><h5>6.4. Evaluatie model</h5></ul>
    <ul><h5>6.5. Visualisatie model</h5></ul>
  <h5> 7. Evaluatie </h5>	
  <h5> 8. Conclusie </h5>	
  <h5> 9. Reflectie  </h5>
  <h5> 10. Communicatie <h5>
  <h5> 11. Python Notebooks </h5>	
  <h5> 12. Scrum backlog tickets </h5> 
  <h5> 13. Andere opdrachten </h5>

<h2> 1. Inleiding </h2>
Valongevallen bij ouderen is een groot probleem. Volgens het CBS bezochten 108.000 65-plussers in 2018 een spoedeisende-hulpafdeling, hierna SEH, ten gevolge van een valongeval. Dit betekent dat per 100.000 65-plussers 3.320 een SEH hebben bezocht na een valongeval. Van alle bezoeken aan de SEH werd 33% opgenomen in het ziekenhuis in 2017. Naast het aantal ziekenhuis opnames is de sterfte van ouderen ten gevolge van een val een reëel probleem. Volgens het CBS overleden in 2018 4.396 65-plusser als gevolg van een val. Hierdoor was in 2018 een val de nummer één doodsoorzaak bij dodelijke ongevallen bij 65-plussers, namelijk 89% (CBS, 2019). 

  
Voor het onderzoek wordt een opdracht uitgevoerd, die is geleverd door Momo Medical. Momo Medical is een groeiende startup, die een sensor heeft ontwikkeld. Deze sensor wordt geplaatst onder het matras van patiënten in een verzorgingstehuis. Met behulp van deze sensor is het mogelijk om vanuit een applicatie, genaamd BedSense, te zien of een patiënt in zijn of haar bed ligt. Deze functie wordt gebruikt door nachtzusters om te voorkomen dat patiënten ‘s nachts gaan dwalen, vallen als zij uit bed willen stappen en ondersteunt de wisselligging. Het doel van dit onderzoek is een algoritme ontwikkelen dat door middel van de gegevens van de sensor voorspelt wanneer een patiënt zijn of haar bed gaat verlaten. In de toekomst zou de nachtdienst, door middel van het ontwikkelde algoritme, valongelukken die plaatsvinden gedurende de nacht kunnen voorkomen. 
<br/><br/>

<h2> 2. Doelstelling </h2>
Het doel van dit onderzoek is dat een algoritme voor Momo Medical wordt ontwikkeld die valincidenten helpt te voorkomen. Dit algoritme moet zo accuraat mogelijk kunnen voorspellen, wanneer een patiënt zijn bed verlaat. De voorspellingstijd moet hierbij lang genoeg zijn voor zorgpersoneel om de kamer van een patiënt te bereiken en een val te voorkomen. Momenteel kan de BedSense app twintig seconden van tevoren een redelijk accurate voorspelling geven. Meegegeven is dat elke verbetering op tijd een waardevolle situatie is, mits deze ook accuraat is. Door de opdrachtgever is aangegeven dat een voorspelling van één minuut van tevoren zeer wenselijk is. 

Ook moet het aantal foutieve meldingen omlaag.  In de huidige situatie gaat er in minder dan 23,4% van de totale signalen wanneer iemand op zijn bed gaat zitten gaat iemand ook weer liggen. In andere woorden betekent dit dat 76,6% van de signalen correct zijn. Het is ons doel om in de nieuwe situatie dit percentage omlaag te krijgen. 
<br/><br/>

<h2> 3. Kennis van het domein </h2>

  <ul><h4> 3.1 Datacamp cursussen </h4>
  Om een goede beoordeling te krijgen voor het "Datacamp" gedeelte van de verplichte criterea is het afronden van 90 procent van de curssussen vereist.
  Hieronder zijn de zeventien Datacamp cursussen weergegeven die ik heb afgerond. Hiervan is 1 cursus niet verplicht gesteld door de opleiding maar deze heb ik gedaan om 
  meer te leren over hoe machine learning en cross-validation worden toegepast bij tijdseriesmodellen.
  <br></br>

<table>
  <tr>
    <td width="40%"><details>
<summary>1.	Introduction to Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/1.%20certificate%20-%20introduction%20to%20python-1.jpg" width="60%">
</details>

<details>
<summary>2.	Intermediate Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/2.%20certificate%20-%20Intermediate%20Python-1.jpg" width="60%">
</details>

<details>
<summary>3.	Python Data Science Toolbox (Part 1)</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/3.%20certificate%20-%20Python%20Data%20Science%20Toolbox%20(Part%201)-1.jpg" width="60%">
</details>

<details>
<summary>4.	Python Data Science Toolbox (Part 2)</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/4.%20certificate%20-%20Python%20Data%20Science%20Toolbox%20(Part%202)-1.jpg" width="60%" />
</details>

<details>
<summary>5.	Pandas Foundations</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/5.%20certificate%20-%20pandas%20Foundations-1.jpg " width="60%" />
</details>

<details>
<summary>6.	Manipulating DataFrames with pandas</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/6.%20certificate%20-%20Manipulating%20DataFrames%20with%20pandas-1.jpg  " width="60%"/>
</details>

<details>
<summary>7.	Introduction to Data Visualization in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/7.%20certificate%20-%20Introduction%20to%20Data%20Visualization%20in%20Python-1.jpg " width="60%"/>
</details>

<details>
<summary>8.	Data Types for Data Science in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/8.%20certificate%20-%20Data%20Types%20for%20Data%20Science%20in%20Python-1.jpg  " width="60%"/>
</details>

<details>
<summary>9.	Cleaning Data in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/9.%20certificate%20-%20Cleaning%20Data%20in%20Python-1.jpg  " width="60%"/>
</details>
</td>
 <td width="40%"><details>
<summary>10.	Merging DataFrames with pandas</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/10.%20certificate%20-%20Merging%20DataFrames%20with%20pandas-1.jpg  " width="60%"/>
</details>

<details>
<summary>11.	Preprocessing for Machine Learning in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/11.%20certificate%20-%20Preprocessing%20for%20Machine%20Learning%20in%20Pyhton-1.jpg " width="60%"/>
</details>

<details>
<summary>12.	Exploratory Data Analysis in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/12.%20certificate%20-%20Exploratory%20Data%20Analysis%20in%20Python-1.jpg  " width="60%"/>
</details>

<details>
<summary>13.	Hyperparameter Tuning in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/13.%20certificate%20-%20Hyperparameter%20Tuning%20in%20Python-1.jpg  " width="60%"/>
</details>

<details>
<summary>14.	Writing Efficient Python Code</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/14.%20certificate%20-%20Writing%20Ecient%20Python%20Code-1.jpg " width="60%"/>
</details>

<details>
<summary>15.	Winning a Kaggle Competition in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/15.%20certificate%20-%20Winning%20a%20Kaggle%20Competition%20in%20Python-1.jpg  " width="60%"/>
</details>

<details>
<summary>16.	Introduction to Deep Learning with PyTorch</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/16.%20certificate%20-%20Introduction%20to%20Deep%20Learning%20with%20PyTorch-1.jpg" width="60%"/>
</details>

<details>
<summary>17.	Machine Learning for Time Series Data in Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/17.%20certificate%20-%20Machine%20Learning%20for%20Time%20Series%20Data%20in%20Python-1.jpg" width="60%"/>
</details></td>
 </tr>
 </table>





</ul>

<h4>Hoofdvraag</h4> 
<ul>
  <li>Wat is het optimale algoritme die kan voorspellen dat een patiënt diens bed verlaat, met behulp van verzamelde data van de BedSense (versie 9) sensor van Momo Medical</li>
</ul>
<h4>Deelvragen</h4> 
<ul>
<li>Wat zijn de mogelijkheden en beperkingen van de BedSense versie 9?</li> 
<ul>
<li>Wat is een BedSense? (Doel, functie, sensoren)</li> 
<li>Wat zijn de mogelijkheden qua detectie? (Hartslag, etc.)</li> 
<li>Wat zijn de beperkingen van de sensoren?</li> 
<li>Welke mogelijkheden kunnen gebruikt worden voor het algoritme?</li>
</ul>
<li>Wat is de kwaliteit van de data die verstreken is door Momo Medical?</li> 
<ul>
<li>Aan welke eisen moet de data voldoen om bruikbaar te zijn voor het algoritme?</li> 
<li>Welke datamanipulaties moeten worden toegepast om de data startklaar te krijgen?</li> 
</ul>
<li>Welke algoritmes zijn bruikbaar voor het voorspellen door middel van de data?</li> 
<ul>
<li>Wat is een algoritme?</li> 
<li>Welke variabelen zijn relevant om te gebruiken in het algoritme?</li> 
<li>Welk algoritme is het beste om te gebruiken voor ons project?</li> 
</ul>
<li>Hoe kunnen de false positives en false negatives, voortkomend uit het algoritme, worden teruggedrongen?</li> 
<ul>
<li>Hoe worden de false positives en false negatives in termen van het onderzoek gedefinieerd?</li> 
<li>Wat zijn de mogelijkheden om false positives en false negatives voortkomend uit dit algoritme terug te dringen?</li> 
</ul>
</ul>


























!!!!The contents of your personal portfolio should reflect your contribution to the project, your abilities and what you have learned!!!!

<h2> 2. Kennis van het domein </h2>	
Hieronder worden alle bronnen weergegeven die ik heb gevonden tijdens dit project.
<br/><br/>

<h4>Literatuur</h4>
<details>
<summary>Tabel met literatuur</summary>
<table>
  <tr>
    <th>Titel</th>
    <th>Beschrijving</th>
    <th>Geraadpleegd op</th>
    <th>URL/Link</th>
  </tr>
  <tr>
    <td>The Complete Guide to Linear Regression Analysis</td>
    <td>Uitleg over lineaire regressies inclusief voorbeelden</td>
    <td>15-9-2020</td>
    <td><a href="https://towardsdatascience.com/the-complete-guide-to-linear-regression-analysis-38a421a89dc2">Link 1</a></td>
  </tr>
  <tr>
    <td>Feature Engineering on Date-Time Data</td>
    <td></td>
    <td>15-9-2020</td>
    <td><a href="https://towardsdatascience.com/feature-engineering-on-date-time-data-90f6e954e6b8">Link 2</a></td>
  </tr>
  <tr>
    <td>Getting started with Gaussian process regression modeling</td>
    <td>A quick guide to the theory of Gaussian process regression and in using the scikit-learn GPR package for regression</td>
    <td>15-9-2020</td>
    <td><a href="https://towardsdatascience.com/getting-started-with-gaussian-process-regression-modeling-47e7982b534d">Link 3</a></td>
  </tr>
  <tr>
    <td>Survival Analysis — Part A</td>
    <td>An introduction to the concepts of Survival Analysis and its implementation in lifelines package for Python.</td>
    <td>15-9-2020</td>
    <td><a href="https://towardsdatascience.com/survival-analysis-part-a-70213df21c2e">Link 4</a></td>
  </tr>
  <tr>
    <td>Data Science Methods and Machine Learning Algorithm Implementations for Customized Pratical Usage</td>
    <td>Uitleg over machine learning in een praktische setting.</td>
    <td>24-9-2020</td>
    <td><a href="https://www.ceeol.com/search/article-detail?id=894806">Link 5</a></td>
  </tr>
  <tr>
    <td>Advanced Sensing and Human Activity Recognition in Early Intervention and Rehabilitation of Elderly People</td>
    <td>Herkenning menselijke activiteit van ouderen door middel van machine learning. Onder andere zitten staan en liggen.</td>
    <td>2-10-2020</td>
    <td><a href="https://link.springer.com/content/pdf/10.1007/s12062-020-09260-z.pdf">Link 6</a></td>
  </tr>
  <tr>
    <td>The Challenges of Data Quality and Data Quality Assessment in the Big Data Era</td>
    <td>In dit document staat een framework voor het beoordelen van de kwaliteit van data.</td>
    <td>2-10-2020</td>
    <td><a href="https://datascience.codata.org/articles/10.5334/dsj-2015-002">Link 7</a></td>
  </tr>
  <tr>
    <td>Time Series Machine Learning Regression Framework</td>
    <td>Website met uitleg over time based machine learning and crossvalidation(heel erg handig voor ons eerste model)</td>
    <td>6-10-2020</td>
    <td><a href="https://towardsdatascience.com/time-series-machine-learning-regression-framework-9ea33929009a">Link 8</a></td>
  </tr>
  <tr>
    <td>Complete guide to Python’s cross-validation with examples</td>
    <td>crossvalidation 2.0</td>
    <td>14-10-2020</td>
    <td><a href="https://towardsdatascience.com/complete-guide-to-pythons-cross-validation-with-examples-a9676b5cac12">Link 9</a></td>
  </tr>
  <tr>
    <td>Visualizing cross-validation behavior in scikit-learn</td>
    <td>Verschillen in visualisatie tussen scikit-learn modules voor crossvalidation</td>
    <td>14-10-2020</td>
    <td><a href="https://scikit-learn.org/stable/auto_examples/model_selection/plot_cv_indices.html">Link 10</a></td>
  </tr>
  <tr>
    <td>Multiclass model</td>
    <td></td>
    <td>12-11-2020</td>
    <td><a href="https://towardsdatascience.com/multiclass-classification-with-support-vector-machines-svm-kernel-trick-kernel-functions-f9d5377d6f02">Link 11</a></td>
  </tr>
  </table>
</details>







<h4>Jargon</h4>

<h4>evaluation</h4>

<h4>existing data sets</h4>





















<h2> 3. Voorspellende Modellen </h2>

<h2> 4. Voorbereiding data </h2>

<h2> 5. Data Visualisatie </h2>	

<h2> 6. Data verzameling </h2>	

<h2> 7. Reflectie en Evaluatie </h2>	

<h4>Situatie</h4>
Voor de minor Applied Data Science en opdrachtgever MomoMedical moest ik samen met de rest van de projectgroep een machine learning model maken dat kan voorspellen wanneer patiënten hun bed verlaten. Hierbij was het eerste doel dat de voorspelling een minuut van tevoren gegeven moest worden. Het tweede doel was om in meer dat 70% van de gevallen dat patiënten uit bed bed gaan een correcte voorspelling te maken.
De aanleiding voor dit project is het hoge aantal valongelukken bij ouderen in de zorg. Het bedrijf MomoMedical heeft een sensorplaat ontworpen waarmee ze de houdingen van patienten kunnen monitoren en kunnen  aangeven wanneer deze van houding moeten veranderen in verband met doorligwonden. Uit de praktijk is de vraag gekomen of er door middel van deze sensorplaat ook voorspeld kan worden wanneer patiënten hun bed verlaten. 
De projectgroep bestaande uit Roy, Salah, Jeanine, Nick, Theo en ik zelf waren betrokken bij dit project. Uiteraard was de opdrachtgever ook betrokken bij dit project vooral Thomas en Maarten. Ook waren er een hoop begeleiders betrokken bij dit project om ons raad te geven en te sturen tijdens dit project. Het ging om Jeroen, Ruud, Brian, Gerda en Tony.
Het project speelde zich vooral vanuit huis af vanwege de maatregelen omtrent COVID-19. Wel is er zoveel mogelijk toen der tijd op de HaagseHogeschool afgesproken om samen te werken. Ook zijn we bij MomoMedical op locatie geweest.
De duur van het project was 1 semester beginnende op 31 augustus 2020.
<br/><br/>

<h4>Taak</h4>
Het was mijn taak om samen met de andere projectleden de projectdoelen te halen. De subtaken die ik heb uitgevoerd om dit te bereiken zijn eerder beschreven en toegelicht.
Mijn rol naast projectlid, binnen dit project, was notulist. Naast het samenvatten en vastleggen van alle vergaderingen was ik ook verantwoordelijk voor het bijwerken van het Microsoft Teams kanaal. Met bijwerken wordt versiebeheer en mappenstructuur bedoeld.
Naast dat ik de door de opdrachtgever gestelde doelen graag wilde behalen wilde ik ook leren coderen in python speciaal voor datascience. Verder wilde ik meer leren over de werking van machine learning en hoe je dit middels verschillende modellen kan toepassen.
Van mij werd door de opdrachtgever verwacht dat ik samen met mijn projectleden de juiste stappen zou zetten om middels een model de gestelde doelen zou behalen. Door de docenten werd verwacht dat ik de keuzes gemaakt tijdens dit project goed kan vastleggen en onderbouwen. Verder dat er met een professionele houding omgegaan wordt met de opdrachtgever zodat deze in het vervolg nog wil samenwerken met de hogeschool. 
Verder verwachtte ik van mezelf tijdens dit project dat ik goed vanuit huis zou kunnen werken aangezien ik dit ervoor ook gedwongen heb moeten doen met mijn stage. Ook dat ik mijn best zou doen om goede resultaten te halen aangezien ik de opdrachtgever niet teleur wilde stellen.
Ik vond dat het erg belangrijk was om van te voren alle dataverwerkingen vast te leggen zodat onze stukken python code op elkaar aansluiten en geen fouten maken die de validiteit van de resultaten in gevaar brachten. <br/><br/>

<h4>Actie </h4>
Allereerst pakte ik dit project aan door een duidelijke taak verdeling en planning te maken. De groepsleden waren het er mee eens dat een duidelijke planning en taakverdeling vereist was voor het uitvoeren van dit project.
Ieder groepslid kreeg zijn extra rol en subtaken toegewezen. Verder zijn we begonnen met het aanleren van de technische skills om dit project te kunnen voltooien middels datacamp curssussen. Tegelijk is iedereen begonnen met het uitvoeren van deskresearch opzoek naar peer-reviewed-journals waarin soortgelijke problemen behandeld werden. 
Toen we uiteindelijk aan de slag gingen met ons eerste model hebben vanaf dat moment het iteratieve proces van choose, train, evaluate en tune model gebruikt. Tijdens het project kwamen we er achter dat we veel focus hadden gelegd op het schrijven van stukken code die onze data transformeerde voor het gebruik in een model en dat we te weinig focus hadden gelegd op het maken van goede features. Als het ware liep ons model tegen een muur aan. Ik voelde me onzeker of we met deze koers nog wel de juiste resultaten zouden halen. Dit werd besproken met de rest van de groep en vanaf dat moment hebben we twee weken vol ingezet op feature engineering. 
<br/><br/>

<h4>Resultaat</h4> 
Uiteindelijk verbeterde onze resultaten enorm waardoor we de voorspellingstijd naar voren hebben kunnen schuiven naar een minuut in plaats van 10 seconden van tevoren. Hierbij gingen onze evaluatie scores wel een stukje naar beneden maar hielden we nog een accuracy score van circa 80% over. We hebben toen nog gewerkt aan een script waarmee het model om de 30 seconden voorspellingen maakte op basis van nieuwe data en dit voorgelegd aan de opdracht gever. De was uiteindelijk erg tevreden met de verbetering en de resultaten. Verder denk ik dat de begeleiders het er ook mee eens zijn dat het goed is dat we uiteindelijk feature engineering de aandacht hebben gegeven die het verdient. 
<br/><br/>

<h4>Reflectie</h4> 
Over het algemeen vond ik dat ik het goed gedaan heb tijdens dit project, vooral om met enige tegen slagen toch de motivatie te vinden om verder te gaan. Ik ben erg tevreden met de uiteindelijk behaalde resultaten. Wel vraag ik me af waar we hadden kunnen eindigen met meer tijd, of als we eerder de focus hadden gelegd op feature engineering. Verder hebben we deep learning buiten de scope gelaten tijdens dit project en vind ik het jammer dat we daar geen ervaring mee heb kunnen op doen. 
Ik heb tijdens deze minor veel geleerd over coderen in python, niet alleen voor datascience. Na het volgen van deze minor heb ik de werking van verschillende modellen beter leren begrijpen. Ook heb ik geleerd hoe belangrijk feature engineering is in het proces en voor het zorgen van goede resultaten.
De volgende keer zou ik meer focus leggen op feature engineering daarnaast zou ik ook eerder aan de bel trekken als een experiment het niet waard is om meer tijd in te investeren. Daarvoor heb ik uiteraard de ervaring nodig die ik tijdens dit project opgedaan heb. Dit is het eerste datascience project waarin ik meegewerkt heb en uiteraard heb ik fouten gemaakt waarvan ik geleerd heb. Ook zou het volgen van extra cursussen voor programmeren in python veel tijd hebben kunnen schelen in het efficiënter maken van de code.
Ik heb vanuit de groep vooral meegekregen dat ze de samenwerking als erg aangenaam hebben ervaren. Tussendoor hebben we wel Jeanine gehad die ervoor gekozen heeft op te stoppen maar ik ben van mening dat dit niet door de groep komt. Wel heb ik aan het begin als feedback gekregen meer ruimte voor anderen over te laten om hun mening te kunnen geven en dit heb ik vanaf dat punt dan ook gedaan. Ik heb veel meer gevraagd wat anderen ervan vonden en ik heb gemerkt dan sommige groepsleden daardoor ook mondiger werden. 
Alhoewel ik betwijfel dat ik op korte termijn iet ga doen met de technische skills die ik heb geleerd tijdens deze minor, heb ik wel veel geleerd over mezelf tijdens deze projectmatige samenwerking. 







<h2> 8. Diagnostiek van het leerproces </h2>
<h2> 9. Communicatie <h2>

<h4>Presentaties</h4>
Hieronder staan de presentaties waar ik aan bij heb gedragen:
<ul>  
<li>
<a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%206.pptx">Week 6</a>
- 05 Oktober  : De interne presentatie is gemaakt en gegeven door mij.
</li>
<li> 
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%208.pptx">Week 8</a>
    - 23 Oktober  : De externe presentatie is gemaakt en gegeven door Nick, Roy en ik.
</li>
<li>
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%209.pptx">Week 9</a>
    - 03 November : De presentatie aan MomoMedical is gemaakt en gegeven door ... en ik.
</li>
<li> 
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%2010.pptx">Week 10</a>
    - 10 November : De presentatie aan MomoMedical is gemaakt en gegeven door ... en ik.
</li>
<li> 
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%2011.pptx">Week 11</a>
    - 17 November : De presentatie aan MomoMedical is gemaakt en gegeven door ... en ik.
</li>
<li> 
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%2014.pptx">Week 14</a>
     - 08 December: De presentatie aan MomoMedical is gemaakt en gegeven door ... en ik.
</li>
<li> 
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%2015%20-%2014.pptx">Week 15</a>
     - 14 December: De interne presentatie is gemaakt en gegeven door ... en ik.
</li>
<li> 
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Presentations/Week%2015%20-%2018.pptx">Week 15</a>
     - 18 December: De presentatie aan MomoMedical is gemaakt en gegeven door ... en ik.
</li>
</ul>
<h4>Schrijven van de paper</h4>
Mijn bijdrage aan het schrijven van de paper is de discussie en de methods geweest. Verder ben ik actief bezig geweest met het geven en verwerken vn feedback op stukken geschreveb door ander egroepsleden.
  
<h2> 10. Python Notebooks </h2>	

<h2> 11. Scrum backlog tickets </h2> 

<h2> 12. Andere opdrachten </h2>














 







