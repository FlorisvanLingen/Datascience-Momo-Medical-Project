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
  <h5> 7. Conclusie </h5>	
  <h5> 8. Reflectie  </h5>
  <h5> 9. Evaluatie </h5>
  <h5> 10. Communicatie <h5>
  <h5> 11. Scrum backlog tickets </h5> 


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

<details>
<summary>1.	Introduction to Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/1.%20certificate%20-%20introduction%20to%20python-1.jpg" width="30%"></details>
<details>

<summary>2.	Intermediate Python</summary>
<br>
<img src="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Datacamp-accomplishments/2.%20certificate%20-%20Intermediate%20Python-1.jpg" width="30%">
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

<details>
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


<h4>3.2 Onderzoeksvragen</h4> 

<h6>Hoofdvraag</h6> 

<ul>
  <li>Wat is het optimale machine learning algoritme die kan voorspellen dat een patiënt diens bed verlaat, met behulp van verzamelde data van de BedSense (versie 9) sensor van Momo Medical</li>
</ul>

<h6>Deelvragen</h6> 

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

  <h4>3.3. Jargon en definities</h4>
  
  
  <details>
  <summary>Begrippenlijst</summary>
  <table>
    <tr><th>Begrip</th><th>Definitie</th></tr>
    <tr> <TD>Logistic regression(logreg)</td> <td>Met logistische regressie kan je een dichotome uitkomstvariabele (dood versus leven, wel of geen klachten, etc.) relateren aan één of meerdere predictoren. Het basis idee achter logistische regressie is dat je de uitkomstvariabele zodanig transformeert dat er een soort lineaire regressie mogelijk is.</td></tr>
    <tr> <TD>Support vector machine(SVM)</td> <td>Een support vector machine (SVM) is een voorbeeld van zo'n algoritme. Dit type algoritme is supervised: in dit geval wordt een model getraind met een historische dataset. Je laadt heel veel historische data in het model, zodat het model patronen in deze data gaat ontdekken en herkennen.</td></tr>
    <tr> <TD>features</td> <td>
Een feature is een individueel meetbare eigenschap of kenmerk van een waargenomen fenomeen.</td></tr>
    <tr> <TD>datetime</td> <td>datum en tijd functie van pandas in python</td></tr>
    <tr> <TD>deep learning</td> <td>Deep learning is een subveld van machine learning. Deep learning wordt gebaseerd op kunstmatige neurale netwerken. Deep learning stelt computers in staat om nieuwe dingen te leren van grote hoeveelheden data. Voorbeelden zijn beeldherkenning, spraakherkenning, spelen van bordspel programma's of vertalingen.</td></tr>
    <tr> <TD>neurale netwerken</td> <td>Een neuraal netwerk, vroeger neuronaal netwerk genoemd, is een groep van verbonden neuronen (zenuwcellen). De twee belangrijkste vormen zijn biologische neurale netwerken, in het bijzonder het menselijk brein, en kunstmatige neurale netwerken.</td></tr>
    <tr> <TD>fourrier transformatie</td> <td>worden gezien als dat signaal in het "frequentiedomein". De fouriertransformatie generaliseert voor niet-periodieke functies de fourierreeks van een periodieke functie. Een generalisatie van de fouriertransformatie is de laplacetransformatie.</td></tr>
    <tr> <TD>false positive(FP)</td> <td>test resultaat waarbij de positieve klasse voorspelling niet hetzelfde is als de werkelijke situatie</td></tr>
    <tr> <TD>false negative(FN)</td> <td>test resultaat waarbij de negatieve klasse voorspelling niet hetzelfde is als de werkelijke situatie</td></tr>
    <tr> <TD>true positive(TP)</td> <td>test resultaat waarbij de positieve klasse voorspelling hetzelfde is als de werkelijke situatie</td></tr>
   <tr> <TD>true negative(TN)</td> <td>test resultaat waarbij de negatieve klasse voorspelling niet hetzelfde is als de werkelijke situatie</td></tr>
    <tr> <TD>daily standup</td> <td>De Daily Scrum, ook wel standup meeting of daily standup meeting genoemd, is een dagelijkse bijeenkomst van het Scrumteam van maximaal 15 minuten. </td></tr>
    <tr> <TD>Sampling frequentie</td> <td>is, onder meer bij digitale signaalbewerking en regeltechniek, het aantal keren per seconde (de frequentie) waarmee een continu signaal wordt bemonsterd.</td></tr>
    <tr> <TD>unix-tijd</td> <td>De Unix Epoch is de datum en tijd die correspondeert met de waarde 0 van de klok en de timestamp van Unix. Op de meeste Unix-systemen is de epoch gelijk aan 00:00:00 GMT op 1 januari 1970. De meeste Unix-systemen gebruiken 1 'tick' per seconde. De Unix-tijd is dan het gehele aantal seconden na de Unix Epoch.</td></tr>
    <tr> <TD>dataframe</td> <td>Een dataframe lijkt op een matrix. Het is ook een verzameling gegevens in tabel vorm.</td></tr>
    <tr> <TD>overfitting</td><td>de productie van een analyse die te nauw of precies overeenkomt met een bepaalde set gegevens, en daarom mogelijk niet in staat is om aanvullende gegevens te passen of toekomstige waarnemingen betrouwbaar te voorspellen</td></tr>
    <tr> <TD>underfitting</td><td>Underfitting betekent dat een model een te simplistisch beeld van de werkelijkheid geeft.</td></tr>
    <tr> <TD>accuracy></td><td>(TP + TN)/N</td></tr>
    <tr> <TD>precision</td> <td>TP / (TP + FP)</td></tr>
    <tr> <TD>recall</td> <td>TP / (TP + FN) </td></tr>
    <tr> <TD>cross validation</td> <td>Het opdelen van je data in een training, test en evaluatieset om te kunnen zien of je resultaten generaliseerbaar zijn.</td></tr>
    </table>
</details>
  
  
  
  
  
  
  
 
  

  <h4>3.4. Literatuur</h4>
  
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
    <tr>
      <td> A Review on Support Vector Machine for Data Classification.</td>
      <td>Uitleg over een SVM </td>
      <td>14-10-2020</td>
      <td><a href="https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1039.2508&rep=rep1&type=pdf">Link 12</a></td>
    </tr>
  </table>
 </ul>

Wat ik uit de verschillende litreratuur heb gehaald is hoe verschillende modellen werken en waarom deze handig kunnen zijn voor ons project. Een voorbeeld hiervan is het gebruik van logistic regression of een support vector machine. Ook hebben we door deze papers inzicht gekregen in hoe we crossvalidation kunnen toepassen en hoe dit de validiteit van de resultaten van ons onderzoek kan aantonen. Ook hebben deze papers visuele ondersteuning geboden voor het begrijpen van time shifts of verschillende vormen van crossvalidation en hoe we dit zelf ook zouden kunnen visualiseren. 
De kern van mijn bevinden van het literatuur onderzoek heb ik besproken tijdens de stand ups en teems meetingen wanner deze relevant waren voor de te nemen stappen in het onderzoek. Deze papers hebben ervoor gezorgd dat ik inzicht kreeg in bepaalde best practices op het gebied van datascience en ons project. Ook diende bepaalde papers als bewijs dat menselijke bewegingen te classificeren moeten zijn door middel van machinelearning. Zonder een aantal van deze papers zou ik nooit in staat zijn geweest om de code van ons eerste voorspellende model op te zetten.
  
 





<h2>4. Project methoden en planning</h2>
  <ul>
    <h6>Methoden</h6>
Tijdens dit project hebben we gewerkt volgens de scrum methode. Onze sprints waren elk twee weken lang waarbij er elke dag een dailystandup is gehouden. Hierbij vertelde ieder projectlid om beurten wat hij of zij had gedaan. Ook werd er dan verteld waar tegenaangelopen was en wat hij of zij ging doen de komende dag. Verder hebben we na elke sprint een sprint review/retrospective gehouden. Dit hebben we gedaan om de problemen tijdens vorige sprints te voorkomen en de samenwerking te verbeteren. We hebben asl tool hiervoor ook Trello gebruikt. Hierin werd onze backlog bijgehouden en de taken gedefineerd.
  
  <details>
  <summary>Voorbeeld van ons trello board</summary>
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/trello.PNG?raw=true"width="60%"/>trello.PNG</a>
  </details>

  
   <h6>Planning</h6>
Hieronder is een link te vinden naar onze globale planning die wij aan het begin van het project hebben opgesteld. Uiteindelijk heeft deze ons erg veel geholpen in het scherp houden van de scope.
  <a href="https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/planning%20(2).xlsx">Link naar planning.xlsx</a>
  </ul>

<h2>5. Voorbereiding data</h2>
  <ul>
    <h4>5.1. Verkennen data</h4>
  <br></br>
    <h4>5.2. Opschonen data</h4>
  <br></br>
    <h4>5.3. Voorbereiden data</h4>
  <br></br>
    <h4>5.4. Uitleg data</h4>
  
De dataset aangeleverd door MomoMedical bestaat uit circa 12539 csv bestanden. Deze is door middel van FileZilla met Linux commands opgesplitst in een training en validatie    set bestaande uit 11346 csv bestanden en een evaluatie set van 1193 csv bestanden. Er is gekozen om week vijf als evaluatie set te gebruiken aangezien deze de kleinste in        omvang is en ongeveer 10% uit van de gehele aangeleverde dataset uitmaakt. Deze dataset is niet aangeraakt tot de laatste versie van het model bekend was.
Later hebben we ook nog een extra dataset aangeleverd gekregen met daarin 102 csv bestanden dit de data van 24uur. Deze was opgestuurd door MomoMedical zodat wij om de 30 seconden voorspellingen konden maken op data die het model nog niet gezien had.
<br></br>
Alle data die door MomoMedical is aangeleverd is verzameld door middel van hun sensorplaat, deze maakt gebruik van drie typen sensoren voor het verzamelen van de data. Deze zijn hieronder in de tabel weergegeven.
<br></br>
<table>
    <tr><th>Sensor type</th><th>Hoeveelheid</th><th>Sampling frequentie</th><th>Beschrijving</th></tr>
    <tr><td>Force sensingresistors (FSR)</td> <td>8</td> <td>10HZ</td> <td>Deze sensoren worden gebruikt voor het meten van de druk op acht locaties op de sensorplaat. </td></tr>
  <tr><td>Piezoelectric sensors (PE)</td> <td>6</td> <td>120HZ</td> <td>Deze sensoren meten vibraties, er zijn zes sensoren verspreidt over de sensorplaat.</td></tr>
  <tr><td>Accelerometer (PE)</td> <td>1</td> <td>10HZ</td> <td>Deze sensor meet de versnellig en beweging van de sensorplaat. Deze wordt gebruikt om de orientatie van de sensorplaat te bepalen</td></tr>
</table>
<br></br>
De rauwe aangeleverde csvfiles bestaan uit 92 kolommen. Dit zijn de belangrijkste kolommen: time, bedstatus, sp_electric-kolommen, sp_resistive-kolommen, sp_accelero-kolommen en device_id. Allereerst wil ik toelcihten waarom er zoveel kolommen zijn, dit heeft met de sampling fequency te maken. Sommige sensoren meten vaker dan anderen zoals te halen is uit de tabel hierboven. MomoMedical heeft ons een visualisatie script aangeleverd waarin alle sensoren worden omgezet naar een frequentie van 120HZ.
<br></br>
Hieronder staat een link naar een Python notebook die ik heb gebruikt om de kolommen van de rauwe data uit te printen. Als eerst heb ik genavigeerd naar de juiste map om de data te kunnen bereiken. Daarna heb ik met pd.read_csv() de data ingelezen. Hierna heb ik het dataframe geprint en een lijst met kolomnamen gemaakt en deze geprint.
<br></br>
https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Python-Code/Read%20raw%20csv%20file.pdf
<br></br>

Hieronder staat een andere link naar het visualisatiescript van MomoMedical dit script transformeert alle sensoren naar de zelfde sampling frequentie en verminderd het aantal kolommen drastisch.
<br></br>
https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Python-Code/visualisatiescriptMOMO.PNG

Hieronder staat een link  naar de rauwe data gevisualiseerd. Op de x-as staat de tijd en op de y-as staat van beneden naar boven de hoeveelheid trillingen,druk en bedstatus.
<br></br>
https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Python-Code/visualisatie%20raw%20data.PNG

Nog even terug naar de niet uitgelegde kolommen, time is de tijd in unix-tijd. De bedstatus is of de patient in bed ligt, zit of niet in bed is. Een bedstatus van 2 betekent dat de patient in bed ligt, als die 1 is betekent het dat de patient de intentie heeft om uit bed te gaan een waarschijnlijk op het bed zit, 0 betekent dat de patient niet meer in of in de buurt van het bed is.De sp_electric-kolommen slaan de gemeten data op van de piëzo sensoren, de sp_resistive-kolommen slaan de gemeten data op van de FSR-sensoren en de sp-acccero-kolommen slaan de data op van de versnellingsmeter. Device_id staat voor de identificatie code van de desbetreffende sensoreplaat.
  </ul>
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
<h2>6. Voorspellende analyse </h2>
<ul>
  <h4>6.1. Selectie model</h4>
  
<details>
<summary>Link naar de Python notebook van code die door mij is geschreven.</summary>
[Model 3 Two class SVM](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Python-Code/Model%203%20Two%20class%20SVM.pdf)
</details>
  
  <details>
<summary>Het selecteren van het model met Python code</summary>
![](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Python-Code/Select%20model.PNG?raw=true)
</details>

Tijdens dit project heb ik vrijwel volledig alles vanaf de selectie van het model tot aan de visualisatie op mij genomen, behalve de feature selection. Uiteraard is er veel input gevraagd vanuit de groep maar ik ben verantwoordelijk geweest voor het doorvoeren van veranderingen aan het model.   
Voor het uiteindelijke model is er gekozen voor LinearSVC, dit is een Linear support vector machine(svm). Na het verkennen van verschillende modellen door middel van literatuur onderzoek heb ik dit model gevonden en voorgelegd aan de groep om te gaan gebruiken. Hetzelfde geldt voor logistic regression.
LinearSVC is een model dat onder toezicht leert en gebruikt wordt voor classificatie en regressie analyse. Aangezien het ons doel is om een klasse te voorspellen en geen getal te benaderen gaat het om een classificatie probleem. Gebaseerd op andere onderzoeken met betrekking tot classificatie die een SVM gebruiken is besloten als eerste model te gaan experimeneteren met een SVM. Een voorbeeld van een van de onderzoeken waar deze keuze op gebaseerd is, zijn het volgende onderzoeken:
   <br></br>
Bhavsar, H., & Panchal, M. H. (2012). A Review on Support Vector Machine for Data Classification. International Journal of Advanced Research in Computer Engineering & Technology, 1(10), 185–189. https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1039.2508&rep=rep1&type=pdf 

K. Nurhanim, I. Elamvazuthi, L. I. Izhar and T. Ganesan, "Classification of human activity based on smartphone inertial sensor using support vector machine," 2017 IEEE 3rd International Symposium in Robotics and Manufacturing Automation (ROMA), Kuala Lumpur, 2017, pp. 1-5, doi: 10.1109/ROMA.2017.8231736. https://ieeexplore.ieee.org/abstract/document/8231736
 <br></br>
  
  


  <h4>6.2. Configuratie model</h4>
Uit het literatuur onderzoek is gekomen dat men door middel van het gebruik van een timeshift een voorspellend model kan maken. Nadat ik dit had gevonden heb ik aan de groep     voorgelegd om dit te gaan implementeren en na diverse gesprekken met de begeleiders hebben we dit toegepast. De manier waarop het dataframe is vormgegeven is specifiek door     mij bedacht. Elke rij vormt één situatie waarin iemand uiteindelijk wel of niet uit bed gaat de kolommen bestaan uit de sensordata op bepaalde punten in tijd voot het moment     van uit bed stappen. 
Dit is anders dan bij de meeste voorspellende modellen waarin de verloop van de tijd als het ware van boven naar benede loopt door de rijen. Bij ons is de verloop van tijd uitsluitend in de kolommen. De literatuur over de time shift is te vinden in de literatuurlijst als Link 8. De literatuur over de SVM is te vinden onder link 12.
  

  
  
  Er zijn bepaalde features bedacht. de gebruikte features zijn:
  
  - Bed_status2
  
  - left
  
  - right
  
  - Avg_column
  
  - slope
  
  - FSR_25s_variance
  
  - Slopelmr*
  
  
  <h4>6.3. Training model</h4>
  Voor het trainen van het uiteindelijke model is er gebruik gemaakt van de bovenstaande featureset.  
  De training en validatie dataset is door middel van de onderstaande code opgesplitst in “train” en “valid” waarbij de trainingsset 70% is van de dataset voor trainen en        validatie. Er is voor deze verhouding gekozen omdat het gezien wordt al een standaard.
<br></br>
(link https://link.springer.com/article/10.1007/s41066-017-0049-2)
<br></br>
  Hierna is er gezorgd dat er in de trainingset een verhouding was van 50% gevallen dat mensen uit bed gaan en 50% van gevallen waarin mensen niet uit bed gaan. Dit zorgt ervoor   dat het model geen voorkeur heeft om de positieve of negatieve klasse te voorspellen. Het balanceren van de trainingset is gedaan omdat na de datasplit de trainingset weer uit   balans kan zijn zoals beschrveen in de bovenstaande literatuur. Hierna zijn de accuracy,recaal en precision scores berekent over de training en validatieset. Als eerst de    trainingsset om te kijk hoe goed het model uiteindelijk fit op de trainingsdata en de validatie set om te kijken of het model bij nieuwe data niet over of underfit.

  De model socres gebaseerd op de trainings-dataset waren:
  - accuracy:  0.8046204620462046
  - precision: 0.8825082508250826
  - recall:    0.7635636778983438

  De model socres gebaseerd op de validatie-dataset waren:
  - accuracy:  0.8220786846741045
  - precision: 0.8835807050092764
  - recall:    0.8429203539823009

  Deze scores zullen altijd tussen de 0 en 1 liggen waarbij 1 hest beste is.
  
  De scores van de validatieset zien er uit als volgt:
  ![](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/confusion%20matrix%20validatieset.PNG?raw=true)
  
  <h4>6.4. Evaluatie model</h4>
  Voor de evaluatie van het model is altijd cross validation gebruikt. Dit betekent dat de data wordt opgesplitst in een training en test set. 
    ![](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/confusion%20matrix%20validatieset.PNG?raw=true)
  
  Ook is er een evaluatie set appart gehoud die alleen gebruikt zou worden voor het aantonen van de validiteit van het model als deze definitief was. De scores hiervan werden geintepreteerd door middel van een confusionmatrix die door mij gemaakt is. Een bron die uitlegd waarom een confusion matrix gebruiken voor het evalueren van een classificatie model een goede aanpak is, staat hieronder:
  https://algorithmia.com/blog/evaluating-machine-learning-models-with-a-confusion-matrix
  
  De scores van de evaluatie set zien er uit als volgt:
  <br></br>
  ![](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/evaluatieset.PNG?)
  

  
  <h4>6.5. Visualisatie model</h4>
  ![](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Images/verhoudingen%20train%20en%20test%20set.PNG?)
  
  
  
</ul>


<h2>7. Conclusie </h2>

Tijdens dit onderzoek wilden we de volgende vraag beantwoorden: "Wat is het optimale machine learning algoritme dat kan voorspellen dat een patiënt zijn bed verlaat met behulp van de verzamelde gegevens van de BedSense-sensor (versie 9) gemaakt door Momo Medical?".

Optimaal voor ons team betekende de volgende twee dingen:
- Het minste aantal false positives en false negatives.
- Voorspellen zo ver mogelijk vooruit.

De belangrijkste conclusie is dat het optimale algoritme dat werd gevonden een lineaire supportsvectormachine was. Met dit als basis is het nu mogelijk om te voorspellen dat patiënten 1 minuut voordat ze uit bed komen uit bed komen. Het huidige model dat deze selectie van functies gebruikt, produceert gemiddeld het minste aantal fout-positieven en fout-negatieven.


<h2>8. Reflectie </h2>

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

<h4>Evaluatie project als geheel</h4>
Als eerste wil ik graag aangeven dat ik blij ben met de gehaalde resultaten en dat ik het idee heb dat we iets hebben opgeleverd waar de opdrachtegver wat aan heeft. Wel vind ik achteraf gezien dat we tijdens het project meer tijd hadden moeten stoppen in feature engineering en minder lang in hetzelfde configuratie hadden moeten blijven hangen. 
  
Door Covid-19 is het project vooral vanuit huis uitgevoerd en hoewel ik redelijk gewend was aan thuiswerken mis je toch de synergie die ontstaat als je elkaar fysiek ziet. Ik denk niet dat het weinige fysiek elkaar zien binnen de projectgroep heeft bijgedragen aan minder goede resultaten. Wel denk ik dat we hierdoor minder efficient hebben gewerkt aangezien thuis vaak afleiding is en het betrekken van elkaar bij het project op momenten dat iedereen moe is of geen zin meer heeft is dan lastig. Er had naar mijn idee meer gehaald kunnen worden uit de gesprekken met begeleiders als deze fysiek hadden plaatsgevonden. Elke begeleider heeft zo zijn of haar kwaliteiten en voor vele is het benaderen van de juiste persoon op het juiste moment toch wat makkelijker als deze fysiek aanwezig is op locatie.



<h2>9. Evaluatie </h2>

<h4>Evaluatie onderzoek</h4>

Er zijn een aantal belangrijke aanbevelingen die gemaakt kunnen worden voor toekomstig onderzoek om het huidige model en de bijbehorende features te verbeteren. Deze aanbevelingen zijn:
Piëzo elektrische sensoren gebruiken voor het meten van de hartslag en dit gebruiken als feature
Het gebruik van deep learning neurale netwerken
Het is mogelijk om het signaal van de piëzo elektrische sensoren te gebruiken door middel van het apparaat dat gebruikt wordt om de data te verzamelen. Uit dit signaal zou dan door middel van een fouriertransformatie gefilterd kunnen worden zodat hieruit het ademhalingsritme en de hartslag gefilterd kan worden. Deze zou dan gebruikt kunnen worden om betere voorspellingen te geven. De hypothese is dat voordat een patiënt uit bed stapt deze vaak eerst wakker of actiever wordt. Hierdoor zou ruim van tevoren de hartslag dan omhoog gaan en dit kan dan gebruikt worden voor het geven van een voorspelling met minder valse positieven. Ook kan het detecteren dat een patiënt uit bed gaat mogelijk eerder al door middel van deze features.
De manier waarop de data geleverd is leent zich ook heel erg voor het gebruik van deeplearning of neurale netwerken. Neurale netwerken maken gebruik van meer data en vereist niet dat de data gestructureerd is en er door onderzoekers features worden bedacht. Met het gebruik van de totale hoeveelheid data ,dat mogelijk gebruikt kan worden voor het geven van voorspellingen, wordt er verwacht dat dit de beste manier is om op een grotere schaal verder te gaan.


<h2>10. Communicatie</h2>

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

Hier is een link naar de [paper](https://github.com/FlorisvanLingen/Datascience-Momo-Medical-Project/blob/Paper/paper%20v1.0.d). Mijn bijdrage aan het schrijven van de paper is de discussie en de methods geweest. Verder ben ik actief bezig geweest met het geven en verwerken van feedback op stukken geschreven door andere groepsleden. Voor het gemak staat een kopie van de stukken ook hieronder:

<details><summary>Methods</summary>
    
**Linear support vector machine (LSVM)**
  
Linear Support Vector Machine is a model for classification and regression problems. It can solve linear and non-linear problems and work well for many practical problems. The   idea of SVM is as follows: The algorithm creates a line or a hyperplane which separates the data into classes. [3]. They are widely used for classification tasks [4]. Since    the objective is to estimate a class it is a classification problem. Based on other research regarding classification tasks that use a SVM like the one below it was decided to   experiment with SVM’s.[5, 6]

**Two class**

Two class or binary classification means that there are two classes, in case of this research a bedstatus with either a value of zero or one. The positive class zero means a patient has left their bed. The negative class 1 means a patient is in their bed. 

**Logistic regression**

Logistic regression is a classification algorithm, used when the value of the target variable is categorical in nature. This model is most commonly used when the data in question has binary output, so when it belongs to one class or another, or is either a 0 or 1. Based on other research regarding classification tasks that use logistic   regression to get good results like the one below it was decided to experiment with this kind of regression.[7, 8]
</details>

<details><summary>Discussion</summary>

In this paragraph the validity of this research will be discussed. The data used to make predictions comes from three different nursing home departments: Psychogeriatrics, Somatic and Rehabilitation. The dataset includes information of 78 to 99 anonymized patients. The nature of the conditions the patients have is only generalizable since it is seen as personal data and was not included in the dataset. Therefore, we cannot be certain the results will be consequent since the researched sample might not represent the population. 
Also, the machine learning model was trained to predict when a patient is getting out of bed, not in their bed. Hence when the model is used in real time when patients might get into their beds the results may vary. Configuring the correct settings in a real time program is necessary to get the best results.
Another thing to note is that the ground truth is based on the bed status. This algorithm is developed to calculate if a patient is in bed according to sensor data but not by having an actual observer in the patients’ room. This does affect the validity of the results, but this was known up front.
The methods used during this research are reliable because they were based on best practices like (insert cross validation, balancing dataset, desk research). The literature used was trustworthy because it consisted mostly of peer-reviewed papers.
One of the expectations of this research was to be able to make better predictions than Momo Medical could do as well as extend the prediction time to a minute. Both goals were achieved as expected and it was determined what the best machine learning model is for this application.
A big limitation of the research was the time factor. Due to uncertainties of getting the right results with neural networks this research was started with machine learning experiments. Unfortunately results with machine learning that were good enough to start experimenting with neural networks came in too late for it to be feasible to step over to neural networks. Because of this we excluded neural networks from the scope of this project.
Based on a study about human activity recognition [11] the expectation was that with the aid of machine learning it is possible to recognize and predict when someone is going to get out of bed. In the end the expectations were met since the machine learning model was able to make accurate predictions.
This research shows that a linear support vector machine using time shifted features is the best model to be able to make correct predictions for this application.
Momo medical can use this model to aid in preventing fall accidents among elderly and or revalidating patients in nursing homes. Due to the recall, accuracy and precision of the predictions personnel hopefully will not lose their trust in the use of the model when this gets implemented in real time.

</details>

<h2>11. Scrum backlog tickets </h2>







</body>
</html>








 







