---
layout: team
kind: team
myName: Jet Stream
shortDescription:  Das Projekt CloudMiner übernimmt die Aufgaben, die vorhandene Software von evoila um zwei Kernkompetenzen zu erweitern. ChargeBack Rechnungserstellung Sammeln und archivieren von rechnungsrelevanten Daten zum Erstellen von rechtskräftigen Rechnungen. Monitoring Echtzeitanzeige von verwendeten Ressourcen Sammeln von Betriebsdaten zur Kostenoptimierung und zum Aufzeigen von Engpässen.
partnerIndustry: Evoila
images:
  - overview.png
  - qs-code.png
  - Rechnungslayout.png
  - sprintBurndownChartLast.png
  - Testabdeckung.png
  - wordwolke.PNG
files:
  - poster.pdf
---

<!-- Example 2:
	 1) No divs are used
	 2) Specfic classes are used
	 3) Team group picture only
	 4) No Logo for industry and Team
	-->


<!-- ***************** -->
<!-- Team Description -->
<!-- ***************** -->

<p> Aktuell gibt es ein prototypisches System, welches bereits die Funktionen der Konfigurationserstellung und Kundenbetreuung ermöglicht. Die Rechnungen werden derzeit noch über ein Festpreisverfahren in Abhängigkeit der Mietdauer erstellt.<br />

Evoila möchte die Nutzung dieses Systems, wie branchenüblich, über ein skalierendes Berechnungsverfahren in Abhängigkeit zur verursachten Auslastung stellen. Zurzeit fehlt jedoch eine Möglichkeit, die verbrauchten Ressourcen und damit verbundenen Kosten zu beobachten und sie dem Kunden in Rechnung zu stellen. Dies bedeutet im Genauen, dass die Ressourcen für die vom Kunden gebuchten, virtuellen Server im Verhältnis zum Buchungszeitraum berechnet werden müssen. Dies wären z.B. Speicherplatz, Anzahl der CPUs u.a. aber auch die Anzahl der Konfigurationen, die vorgehalten werden. Die hierfür benötigten Daten befinden sich jedoch sowohl auf den angemieteten Cloud-Servern, als auch auf den virtuellen Maschinen der Kunden. Es fehlt zudem eine Möglichkeit, die Ressourcen in Echtzeit zu überwachen, um das System zu warten.<br />

Das Endprodukt CloudMiner soll einen Überblick über die Auslastung und Nutzung des Systems von evoila verschaffen und die Rechnungsstellung automatisieren. Dazu soll das System die Auslastungs-, Aktitvitäts- und Verbrauchsdaten der Kunden und Server auslesen, sammeln, archivieren und auswerten können. Als erstes werden Daten in Echtzeit von den verschiedenen Servern und Anwendungen gesammelt. Anschließend werden diese archiviert und auf Anfrage entweder für die automatische Rechnungserstellung oder zur Überwachung verwendet. Die relevanten Daten sollen gefiltert und in verschiedenen Darstellungsformen graphisch repräsentiert werden können. Weiterhin soll das System eine Langzeitarchivierung von Rechnungsdaten ermöglichen. </p>


<h2 class="classH2">Lessons Learned</h2>
<ul>
	<li>Vor dem Abgabetermin einen Feedbacktermin festlegen und einhalten</li>
    <li>Eigene Testumgebung schaffen, beinhaltet auch Datenbank-Server</li>
    <li>Frühzeitige Erfassung von QS-Zielen und -Maßnahmen</li>
    <li>Pflichtbewusste Zeiterfassung - ggf. mit professionellen Werkzeugen</li>
    <li>regelmäßige, gemeinsame Codereviews mit dem ganzen Team, um einheitliches Verständnis zu fördern</li>
    <li>frühzeitig Feedback für Dokumente einholen</li>
</ul>


<!-- ***************** -->
<!-- Partner Industry name and logo -->
<!-- ***************** -->

<div class="partnerIndustry">
	<h2>Partner Industry</h2>
	<div>
		<!-- ****** EDIT NAME OF INDUSTRY HERE ******* -->
		<h3>Evoila</h3>
	</div>
	<!-- ****** EDIT IMAGE NAME OF INDUSTRY HERE ******* 
		 ****** NOTE ONLY CHANGE THE NAME ie "reajet.gif" ***** -->
</div>
<div class="clear"></div>


<!-- ***************** -->
<!-- team group pic -->
<!-- ***************** -->

<!-- ******* NEED ONLY IF THERE IS A GROUP PIC OF THE TEAM ******** -->
<div>
	<!-- team picture -->
	<h2>Team</h2>
	<!-- ***** link to big image (OPTIONAL) ****** 
		 ***** CHANGE THE IMAGE NAME ONLY ****** -->
	<a href="{{ "Gruppenbild.JPG" | prepend:'img/' | prepend:folderLink | prepend:site.baseurl }}">
		<!-- small image image to be displayed -->
		<!-- ***** EDIT IMAGE NAME ONLY ***** -->
		<img src="{{ "Gruppenbild.JPG" | prepend:'img/' | prepend:folderLink | prepend:site.baseurl }}">
	</a>
</div>
<div class="clear"></div>



<!-- ******************************* -->
<!-- Techonologies Name, Link-->
<!-- ******************************* -->
<h2 class="classH2">Benutzte Technologien</h2>
<dl>
	<dt><a href="">Spring</a></dt>
	<dd>Spring ist ein Framework zur Entwicklung großer firmenbasierter Software. Es bietet unter anderem Unterstützung zu Dependency Injection und aspektorientierter Programmierung.
	<dt><a href="">Eclipse</a></dt>
	<dd>Eclipse ist eine IDE. Anfänglich für Java entwickelt, dient es heute zur Entwicklung von Software verschiedenster Art.</dd>
	<dt><a href="">kunagi</a></dt> 
	<dd>Ein Projektmanagement-Tool, das auf den Entwicklungsprozess Scrum spezialisiert ist.</dd>
	<dt><a href="">Jenkins</a></dt>
	<dd>Jenkins ist ein webbasiertes System zur Verwaltung von Continuous Integration. Es unterstützt Tools wie Maven und Git und automatische Testtools wie JUnit. Darüber hinaus verwaltet es Testergebnisse und bereitet diese optisch auf.</dd>
	<dt><a href="">Maven</a></dt>
	<dd>Maven ist ein Projekverwaltungswerkzeug zur Verwaltung von einzelnen Modulen/Komponent und deren Zusammenstellung. Des Weiteren schlüsselt Maven Abhängigkeiten zu anderen Frameworks auf.</dd>
	<dt><a href="">Git</a></dt>
	<dd>Git ist eine frei verfügbare Software zur Versionsverwaltung von Dateien. In der 	Softwareentwicklung wird es meist zur Verwaltung des Quellcodes eingesetzt.</dd>
	<dt><a href="">Gerrit</a></dt>
	<dd>Gerrit ist ein kollaboratives Review-System für Git- Repositories.</dd>
	<dt><a href="">Postgres</a></dt>
	<dd>Postgres ist ein freies Datenbanksystem auf Basis von SQL.</dd>
	<dt><a href="">pgAdmin</a></dt>
	<dd>pgAdmin ist ein Programm zur Verwaltung von PostgreSQL Datenbanken.</dd>
	<dt><a href="">MongoDB</a></dt>
	<dd>MongoDB ist ein dokumentbasiertes Datenbanksystem.</dd>
	<dt><a href="">UMongo</a></dt>
	<dd>Ein Programm zur Verwaltung von Mongo Datenbanken.</dd>
	<dt><a href="">RabbitMQ</a></dt> 	
	<dd>Die RabbitMQ ermöglicht asynchrone Nachrichtenübermittlung mit einem Queueingsystem.</dd> 
</dl>