<html>
<head>
<h1 align="center">Der arduinogesteuerte Gaskocher - Projektseite</h1> 
</head>
<h3 align="center"> Ein Projekt von David Borgmann und Simon Rettmann</h3>
<h3 align="left">Stormarnschule Ahrensburg <br/> Informatik, Bl <br/> Schuljahr 2021/22, 1. Halbjahr </br> </h3> </div>
<h3 align="left"> &#10132; <a href="https://github.com/simonrettmann/Stundenprotokolle"> Stundenprotokolle</a> </h3> 
<h3 align="left"> &#10132; <a href="https://www.youtube.com/channel/UCEljeGxqUxyXQlMq9Q-U8_w"> YouTube Kanal - Novum hotplate</a> </h3>
<br>

<img align="center" alt="Animation" width="700" height="400" src="https://user-images.githubusercontent.com/88385654/144711039-e3602339-827f-42a6-b684-b21d3ee8bcf1.gif">

<br>
<hr>
<h3>Navigation</h3>

<b>1. Grundlagen</b>	

<ul>
	<li> <a href="#Team"> Das Team </a> </li>
	<li> <a href="#Arduino"> Der Arduino - Grundlage des Physical Computing Projekts </a> </li>
	<li> <a href="#Programme"> Verwendete Programme </a> </li>
	<li> <a href="#Lernprozess"> Erlenen der benötigten Fähigkeiten </a> </li>
</ul>

<b>2. Das Projekt</b>	

<ul>
	<li> <a href="#Idee"> Die Idee </a> </li> 
	<li> <a href="#Entwicklungsprozess"> Entwicklungsprozess </a> </li>
	<li> <a href="#Software"> softwaretechnische Umsetzung </a> </li> 
	<li> <a href="#Hardware"> hardwaretechnische Umsetzung </a> </li>
	<li> <a href="#Produkt"> Das Endprodukt </a> </li>
</ul>

<b>3. Reflexion</b>

<ul>
	<li> <a href="#Reflexion"> Reflexion und Fazit des Projektes </a> </li>
	<li> <a href="#Ausblick"> Ausblick auf kommende Veränderungen </a> </li>
</ul>

<hr>

<h4> <a id="Team"> &#10122; &nbsp Das Team</a> </h4>
Für dieses Halbjahresprojekt im Rahmen des Informatikunterricht, schlossen sich David Borgmann und Simon Rettmann zu einem Team zusammen. Als gute Freunde bildeten sie ein gut funktionierendes Team aus Entwicklern, das das Projekt unbedingt nach vorne bringen wollten. Beide besaßen aufgrund einer Teilnahme am Enrichement-Kurs "Das Programmieren von Microcontrollern" schon ein paar Arduinovorkenntnisse. Beigeistert ist die Gruppe vor allem von Physical Computing Projekten, weil es ermöglicht Hardware und Software zu vereinen. Somit kann im Kopf und Computer etwas gesteuert und erschaffen werden, was in der realen Welt tatsächlich funktioniert. Diese Art von Projekten fasziniert die Beiden. 

<h4> <a id="Arduino"> &#10122; &nbsp Der Arduino - Grundlage des Physical Computing Projekts</a> </h4>
Bei dem arduinogesteuertem Gaskocher handelt es sich um ein Physical Computing Projekt. Das bedeutet, dass Anwendungen der Informatik in Wechselwirkung mit der Umwelt stehen. Dazu ist sowohl Hardware, welche mit der physischen Umwelt im Kontakt steht, als auch Software, welche die Hardware interaktiv mit „Leben“ füllt, nötig. Arduino bietet bei diesem Projekt die Plattform, welche die Umsetztung des Projektes ermöglicht. Arduino ist eine aus Soft- und Hardware bestehende open-source Physical Computing-Plattform. 
Das Herzstück der Hardware ist dabei der Micro-Controller, in diesem Fall der Arduino UNO R3. Bei dem UNO handelt es sich um das Standard-Modell des Repertoires. Dieser ist günstig und für viele Projekte im Bezug auf Rechenleistung, Speicher und Anschlussmöglichkeiten völlig ausreichend.
Programmiert wird der Microcontroller mithilfe der integrierten Entwicklungsumgebung. Es handelt sich um eine plattformübergreifende Anwendung. Die Programmiersprache beinhaltet Elemente aus C, C++ und AVR-Assembler und der Code lässt sich von einem Computer mithilfe eines USB-Anschlusses auf den UNO übertragen.

<h4> <a id="Programme"> &#10122; &nbsp Verwendete Programme</a> </h4>
Zur präzisen Umsetzung und ansprechenden Dokumentation wurde eine Vielzahl von verschiedenen Programmen benutzt und dessen Handhabung erlernt.

<ul>
	<li>Arduino IDE</li>
	Der Arduino stellt das Herzstück des Projektes dar. In der Entwicklungsoberfläche wurde das Programm geschrieben und auf den Arduino Uno gespielt.
		 
<details>
	<summary>Entwicklungsoberfläche von Arduino</summary>
		<img alt="Entwicklungsoberfläche" width="1792" src="https://user-images.githubusercontent.com/88385654/144110935-967a7811-2b7d-47cb-ab8c-9f44b3a6a83d.png">
	<a href="https://www.arduino.cc"> - Website von Arduino</a>
	
</details>
	
<li>GitHub</li>
	GitHub ist eine Software zur Versionsverwaltung von Software. Für dieses Projekt wurde GitHub für die Dokumentation genutzt, um Stundenprotokolle, eine Art Tagebuch für jede Stunde, und eine Projektseite, eine Zusammenfassung des Halbjahresprojektes, zu erstellen. 
	
<details>
	<summary>Oberfläche von GitHub</summary>
	<img alt="GitHub" width="1792" src="https://user-images.githubusercontent.com/88385654/144112129-7995500f-9060-49eb-b976-9301c159ab12.png">
	<a href="https://github.com/"> - Website von GitHub</a>
	
</details>
	
<li>fritzing</li>
	Fritzing wurde genutzt, um die für die Hardware erforderlichen Steckverbindungen und eingesetzten Geräte, zu digitalisieren.
	
<details>
	<summary>Oberfläche von fritzing</summary>
	<img alt="fritzing" width="1792" src="https://user-images.githubusercontent.com/88385654/144112753-0cdef113-cc82-46a9-89f8-d3e3018bf087.png">
	<a href="https://fritzing.org/"> - Website von fritzing </a>
	
</details>	
	
<li>TinkerCAD</li>
	TinkerCAD ist eine Software, mit der 3-D Objekte modelliert werden können. Für das Projekt war es wichtig, eine Steckverbindung zwischen Gaskocher und Schrittmotor herzustellen. Ein dementsprechendes 3-D Modell wurde erstellt und als .stl Datei exportiert.

<details>
	<summary>Oberfläche von TincerCAD</summary>
	<img width="1792" alt="Obefläche von TinkerCAD" src="https://user-images.githubusercontent.com/88385654/144115179-eeff862f-5fa8-4073-aad6-471d0d160e06.png">
	<a href="https://www.tinkercad.com/things/58xIQMAeis5-sizzling-curcan/edit"> - Oberfläche von TinkerCAD</a>

</details>
	
<li>Cura</li>
	Die mit TinkerCAD erstellte .stl Datei kann mit Hilfe der Software Cura in einen .gcode umgewandelt werden. Dieser Dateityp ist mit 3-D Druckern kompatibel. So wurde das auf TinkerCAD erstellte Modell, nach Anpassung der Druckeinstellungen, gedruckt. 
	
<details>
	<summary>Oberfläche von Cura</summary>
	<img width="1792" alt="Oberfläche von Cura" src="https://user-images.githubusercontent.com/88385654/144115541-6deae014-7fc5-4551-8e25-75105fe808ac.png">
	<a href="https://ultimaker.com/de/software/ultimaker-cura"> - Website von Cura</a>
	
</details>
	
</ul>


<h4> <a id="Lernprozess"> &#10122; &nbsp Erlenen der benötigten Fähigkeiten</a> </h4>
Damit diese Vielzahl von Programmen auch sinnvoll eingesetzt werden konnte, begann die Gruppe immer zuerst mit der Einarbeitung in das jeweilige Programm. Dafür wurden unterschiedliche Quellen und Arten genutzt. Als besonders hilfreich haben sich YouTube-Tutorials für eine grobe Übersicht und Foreneintrage für die Beantwortung konkreter Fragen herausgestellt. Hierbei waren die am meisten verwendeten Quellen:

<ul>
	<li> <a href="https://youtube.com/user/MaxTechTV1">MaxTech - Tutorials und mehr</a></li>
	<li> <a href="https://www.youtube.com/watch?v=zJ-LqeX_fLU">Arduino Course for Beginners - Open-Source Electronics Platform</a></li>
	<li> <a href="https://www.youtube.com/watch?v=RGOj5yH7evk"> Git and GitHub for Beginners - Crash Course</a></li>
	<li> <a href="https://wiki.selfhtml.org/wiki/HTML/Tutorials/Einstieg"> HTML-Tutorials</a></li>	
	<li> <a href="https://www.youtube.com/c/Dronebotworkshop1"> DroneBot Workshop</a></li>
</ul>
	
<hr>

<h4> <a id="Idee"> &#10123; &nbsp Die Idee</a> </h4>

Die Entwickler des Projektes, David und Simon, sind begeisterte Outdoor-Fans. In den Sommerferien eine Woche "Wildcampen" in Schweden und eine Studienfahrt, in der eine Woche auf der Mecklenburger-Seenplatte Kanu gefahren wurde. Neben der Natur begeistert allerdings auch das Kochen die Beiden. So kam es bei der Nahrungszubereitung bei diesen beiden Urlauben zu Problemen: Mal ist der Gaskocher zu heiß - der Reis angebrannt, mal das Wasser zu kalt - die Nudeln werden einfach nicht gar. Als in der Einführung zum Informatikunterricht die Möglichkeit eines "Physical-Computing"-Projekts genannt wurde und zuerst einige Ideen diskutiert wurden, entschieden sich die beiden schnell für einen aurdionogesteuerten Gaskocher. Die Idee für das Projekt war geboren. Ziel war es einen Gaskocher so steuern zu können, dass eine vorher eingestellte Temperatur erreicht und selbstständig gehalten werden kann.

Die Erfindung stellt insofern eine Marktlücke dar, als es die Art und Weise des Kochens revolutioniert. Beim Backofen stellt man eine bestimmte Temperatur ein, die erreicht werden soll. Der Backofen gibt ein Feedback, sobald die vorher eingestellte Temperatur erreicht ist. Beim Kochen auf Herdplatten gibt es diese Einstellung nicht. Herdplatten werden in verschiedenen Stufen mit unterschiedlicher Leistung eingestellt. Welche Temperatur die Herdplatte oder der zubereitete Topfinhalt gerade hat, kann nicht transparent für den Benutzer eingesehen werden. Lediglich durch das Verhalten des jeweiligen Inhalts kann eine Schätzung der Temperatur vorgenommen werden. so ist es natürlich bekannt, dass Wasser bei 100 °C zu sieden beginnt. Ob der Inhalt jedoch 70, 80 oder 110, 120 °C hat kann nicht unterschieden werden. 
Bei einem Gaskocher, insbesondere einem Campinggaskocher, wird diese Problem weiter verstärkt. Die Einstellung des Gasflusses geschieht stufenlos. Der Benutzer kann so nur aufgrund der Größe der Gasflasche beurteilen, ob der Topf bald heißer oder kälter sein wird. 
Da die Temperatur beim Backen von Kuchen und Keksen von einer größerer Bedeutung als beim Kochen ist, gab es in dieser Branche bereits einen Wechsel hin zu temperaturregulierten Öfen. Beim Kochen fehlt diese Veränderung, obwohl es auch dort für den Benutzer deutlich transparenter wäre und einige Gerichte eine präzise Einstellung erfordern. 
Beispiele für Gerichte, bei denen es auf eine genaue Temperierung ankommt sind die Herstellung von Karamell, das Schmelzen von Schokolade oder das Sous vide garen von Steaks. Daher stellt dieses Informatikprojekt einen ersten Schritt in der Revolution des Kochens dar und bietet dem Benutzer ein besseres Kocherlebnis. 
	
<h4> <a id="Entwicklungsprozess"> &#10123; &nbsp Entwicklungsprozess</a> </h4>

Der Entwicklungsprozess startete am 3.8.2021, der ersten Informatikstunde mit einer Brainstormingphase und dem Aufgreifen der Idee des arduinogesteuerten Gaskochers. Es folgte ein viermonatiger Entwicklungsprozess, in dem eine Software geschrieben wurde, die ein Thermometer auslesen kann, einen über ein rotary encoder eingestellten Wert mit dem gemessenen Wert ins Verhältnis setzt und auf dieser Grundlage einen Schrittmotor anspricht. Außerdem wurde die Hardware so entwickelt, dass ein Gaskocher an eine Gasflasche angeschlossen wird und ein Schrittmotor über eine Halterung an das Ventil der Gasflasche montiert ist und dieses Öffnen kann. Ein Topf wurde so präpariert, dass ein Thermometer, wasserdicht verpackt, durch ein Loch im Deckel mit dem Wasser in Berührung kommt und die Temperatur misst. <br> Um den zeitlichen Ablauf des Entwicklungsprozesses graphsich anschaulich und transparent darzustellen, wurde eine Zeitleiste erstellt.

<details>
	<summary>zeitlicher Ablauf des Entwicklungsprozesses</summary>
		<img alt="zeitlicher Ablauf" src="https://user-images.githubusercontent.com/88385654/144395754-24319105-3f47-42e6-99ec-6d0e5d974ef3.png">
</details>

<h4> <a id="Software"> &#10123; &nbsp softwaretechnische Umsetzung </a> </h4>
Die Aufgabe der Software ist es, unter Berücksichtigung der eingestellten Zieltemperatur, die gemessene Temperatur in ein Öffnungsgrad des Ventils zu übertragen. Dazu werden verschiedene Werte erhoben, welche tatsächlich durch die physische Umwelt oder den Benutzer des Produktes verändert werden:
<ul>
	<li>Die Zieltemperatur wird durch den rotary encoder definiert. Dabei handelt es sich um eine Integer-Variable (int) mit dem Namen „eingestellteTemp“. Gespeichert werden die ganzzahligen Werte vom encoder als Temperatur in °C. Zur Programmierung des rotary encoders ist eine spezielle Art der Programmierung nötig, welche eine Besonderheit des Programms darstellt. Die Problematik ist, dass der rotary encoder selber nicht speichert, in welcher Position er sich befindet oder welcher Wert äquivalent zu der momentanen Stellung ist. Es werden lediglich Stromimpulse bei jedem Schritt abgegeben. Doch können die Signale im Loop-Abschnitt des Programms nur dann ausgelesen werden, wenn ein entsprechender Abschnitt zur Zeit der Signalübertragung durchgeführt wird. Wird gerade ein anderer Befehl, wie z.B. ein „delay“, ausgeführt, kann der Stromimpuls nicht verarbeitet werden. Um einen präzise funktionierenden encoder zu programmieren, ist es nötig, dass alle gesendeten Daten vom Programm bearbeitet werden. Gelöst wurde diese Herausforderung mit einer Interrupt-Routine. Es handelt es sich um einen gesonderten Programmteil, welcher durch einen festgelegten Auslöser jederzeit gestartet und durchgeführt werden kann. Nach der Unterbrechung wird die Hauptschleife an der Stelle der Unterbrechungen fortgesetzt. Bei der Programmierung konnte sich die Bauweise des rotary encoders zu Nutze gemacht werden. Bei jedem Schritt liegt für einen kurzen Abschnitt keine Spannung am Clock-Pin des Encoders an. Sobald also der Zustand „LOW” am PinA anliegt, wird um einen Schritt gedreht. Dies wird als Auslöser der ISR (= Interrupt-Service-Routine) festgelegt. Je nach der Drehrichtung folgt nun entweder ein „LOW” Signal des Datenpins (PinB) oder es wird kein weiterer Impuls übermittelt. Das Programm überprüft diese Bedingungen. Somit kann ermittelt werden, ob die „eingestellteTemp“ um den Schrittwert „rotarySchrittwert“ erhöht oder verringert werden soll. Die größte Herausforderung war es „bouncing“ in den Griff zu bekommen. Fehlerhafte Signale, die durch unsaubere Kontaktschließung bei der Hardware entstehen, sorgen beim rotary encoder für den Anschein, dass der Encoder um bis zu mehrere hundert Schritte gedreht wurde. Die Lösung dieses Problems hat der Gruppe einige kurze Nächte beschert. Verhindern ließ sich dieses Phänomen schlussendlich, indem der Zeitabstand zwischen den Signalen überprüft wird. Sind seit dem vorherigen Signal weniger als 5ms vergangen, handelt es sich um einen „Bounce“. Das Signal wird folglich ignoriert. </li>
	<li>Der Schrittwert „rotarySchrittwert“ kann zwei Zuständen annehmen. Wenn der encoder gedrückt wird, also „HIGH“ am „PinSW“ anliegt, dann ist der Schrittwert als 1 °C pro Schritt definiert, anderenfalls beträgt der Schrittwert 5 °C pro Schritt. So kann der Benutzer zwischen einer schnelleren oder präziseren Eingabe der Zieltemperatur wechseln und dies flexible an seine Bedürfnisse anpassen, je nachdem ob der rotary encoder eingedrückt oder lediglich gedreht wird. </li>
	<li>Die gemessene Temperatur des Thermoelements wird „tatTemp“ genannt. Es handelt sich um eine „Float“-Variable, welche die Temperatur auf zwei Nachkommastellen genau speichert.  Es wird etwa zwei- bis dreimal pro Sekunde, zu Beginn jeder Loop, gemessen, wie die aktuelle Temperatur in °C innerhalb des Topfes ist. Die Programmierung funktioniert über eine library, welche speziell für das Driverboard des Elements programmiert wurde.</li>
</ul>

Diese Parameter alleine reichen aber nicht aus, um den Kocher zu betreiben. Es müssen Konstanten sowie Rechenvariablen bekannt sein:
<ul>
	<li> Die „tempDifferenz“ stellt als "Float"-Varibale die Differenz zwischen der gemessenen Temperatur und der eingestellten Temperatur dar.</li>
	<li>Die spezifischen Parameter des Schrittmotors und die Eigenschaft des Ventils sind nötig, um zu errechnen, wie viele Schritte der Motor machen muss, um das Ventil um 1% zu öffnen.
</ul>
Grundsätzlich werden Variablen und Konstanten vor dem Setup-Teil des Programms definiert. So werden als erstes die benötigten Bibliotheken eingebunden und dann die Pins für den Schrittmotor, den rotary encoder, das I2C-LCD und das Thermoelement festgelegt. Die Zuweisung der Pins erleichtert später den Überblick. Auch die vorher erwähnten Konstanten und Variablen werden definiert. Anschließend müssen sowohl der Schrittmotor und das LCD, als auch das Thermomodul als Objekte initialisiert werden. Folglich kann nun mit den jeweiligen Bibliotheken gearbeitet werden, in welchen die Parameter der spezifischen Objekte eingespeist wurden. <br>
Der Setup-Teil des Programms wird nur einmal ausgeführt. In diesem Teil wird als erstes die serielle Kommunikation gestartet. Der Arduino kann mit dem Computer seriell kommunizieren, um Daten auszutauschen. In unserem Fall dient der serielle Monitor des Computers später als Kontrollbildschirm. Außerdem wird das LC-Display gestartet und die Arbeitseinstellung des Schrittmotors definiert. Die ISR wird im Setup dem oben beschriebenen Auslöser zugeordnet. Sobald das Setup erfolgreich ausgeführt wurde, übermittelt der Arduino das Signal „Start“, welches nun im seriellen Monitor erscheint. <br>
Der sich endlos wiederholende Loop des Programms beginnt mit der Auslesung des Thermoelements. Der gemessene Wert wir in die Variable „tatTemp“ überführt. Es folgt eine serielle Übermittlung aller interessanten Variablen an den seriellen Monitor. Nun erfüllt der Kontrollmonitor seine Funktion. Damit auch bei dem Endprodukt überprüft werden kann, wie die gemessene oder eingestellte Temperatur des Kochers ist, werden diese beiden Werte im nächsten Teil über das LC-Display ausgegeben. Eine Schwierigkeit war zunächst, dass die mit jedem Loop neu hinzugefügten Schriftzeichen alten Zeichen überschrieben haben, ohne diese gänzlich zu entfernen. Deshalb müssen vor jeder Änderung der Anzeige zunächst alle Zeichen für ein Frame entfernt werden, bevor die neuen Zeichen auf dem LCD erscheinen. Der Nebeneffekt dieser Darstellung ist jedoch ein für den Benutzer wahrnehmbares flackern des Displays.<br>
Nach der Aktualisierung der verschiedenen Anzeigen wird mit dem Herzstück des Codes fortgefahren. In dem Abschnitt findet die Verrechnung der eingestellten Parameter statt. Dazu wird die Temperaturdifferenz „tempDifferenz“ gebildet. Die nötige Position des Steppers setzt sich aus der nötigen Öffnung des Ventils in Prozent, multipliziert mit der Schrittanzahl, welche für 1% Öffnung nötig ist, zusammen. Daraus folgt eine Position in Schritten, welche später von dem Schrittmotor angefahren wird. 
Nach der Aktualisierung der verschiedenen Anzeigen wird mit dem Herzstück des Codes fortgefahren. In dem Abschnitt findet die Verrechnung der eingestellten Parameter statt. Dazu wird die Temperaturdifferenz „tempDifferenz“ gebildet. Die nötige Position des Steppers setzt sich aus der nötigen Öffnung des Ventils in Prozent, multipliziert mit der Schrittanzahl, welche für 1% Öffnung nötig ist, zusammen. Daraus folgt eine Position in Schritten, welche später von dem Schrittmotor angefahren wird. 
Nun wird mit einer mathematischen Funktion ermittelt, wie groß die Öffnung des Ventils in % entsprechend der Temperaturdifferenz sein muss. Der f(x)-Wert der Funktion steht für die Ventilöffnung in Prozent und ist eine „Float“-Variable mit dem Namen „pVentil“. Der x-Wert der Funktion ist die Temperaturdifferenz „tempDifferenz“. Jeder Temperaturdifferenz soll eine Ventilöffnung in Prozent zugeordnet werden. Grundsätzlich muss folgender Zusammenhang gelten: Je größer die Temperaturdifferenz, desto großer die prozentuale Ventilöffnung. Ein einfacher linearer Zusammenhang eignet sich aber nicht, da so lange wie möglich viel Hitze erzeugt werden soll, damit sich der Topf schnell aufheizen kann. Das Projekt soll den Kochprozess vereinfachen und nicht unnötig in die Länge ziehen. Jedoch ist es ebenso wichtig, dass bei geringer Temperaturdifferenz die Flamme zunehmend kleiner wird, um das exakte Erreichen der Zieltemperatur zu gewährleisten. Folglich scheint es sinnvoll eine Funktion zu nehmen, welche eine logistische Kurve aufweist. Die Entscheidung fiel nach vielen Versuchen mit unterschiedlichen Funktionen auf folgende Funktion: !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! 

<details>
	<summary>Graph der Funktion</summary>
</details> 
		
<br>
Im Bereich geringer Temperaturdifferenzen nährt sich die Flamme der geringsten Intensität an. Bei steigender Differenz steigt die Funktion jedoch stark, sodass viel Hitze erzeugt wird und die Zieltemperatur schnell erreicht werden kann. Bei besonders hohen Differenzen wiederum nährt sich die Funktion einem Grenzwert von etwa 80% Ventilöffnung an. Beim Testen ist klar geworden, dass eine Ventilöffnung von 100% unbrauchbar ist, da bei dieser großen Gasmenge viele, hohe Flammen am Topf vorbeischlagen. Die Funktion verfügt somit über einen Wertebereich für die Ventilöffnung von 0,3% bis 80% Öffnung. Deshalb geht die Flamme nie gänzlich aus, sie wird aber auch nie so groß, dass die Benutzerfreundlichkeit oder Sicherheit gefährdet wird. <br>
Zuletzt wird die errechnete Schrittstellung des Schrittmotors angefahren. Die Programmierung des Motors gestaltet sich dank der verwendeten Bibliothek simpel. Als erstes wird ein Ziel in Schritten festgelegt, welches angefahren werden soll. Anschließend wird der Befehl erteilt, dass der Motor dieses Ziel anfahren soll. Während der Bewegung des Schrittmotors wird der Code angehalten. Unter anderem aus diesem Grund ist die Verwendung der „ISR“ unumgänglich. Nach dem Erreichen des festgelegten Ziels, werden alle für den Motor relevanten Pins deaktiviert. Der Vorteil davon ist eine Energieersparnis, da kein Strom fließen kann. Folglich erhitzt der Schrittmotor nicht so stark, sodass ein Dauerbetrieb ohne Sorge möglich ist.

<h4> <a id="Hardware"> &#10123; &nbsp hardwaretechnische Umsetzung </a> </h4>

Die Hardware ist erfolderlich, damit die entwickelte Software auch in der Realität getestet werden kann und der "physical" Teil des physical computing Projekts umgesetzt werden kann. 
<ul>
<li> Das Herzstück der Software ist natürlich der Gaskocher, der bei Amazon bestellt wurde. <a href="https://www.amazon.de/gp/product/B085ZJJ2Q5/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1"> Kauflink von Amazon</a> Über eine passende Gasflasche wird der Kocher mit Gas versorgt. Der Gasfluss kann manuell mit einem Drehregler eingestellt werden. </li>
</ul>
	
<details>
	<summary>Bild des Gaskochers</summary>
<b>Bild des Gaskochers</b> <img alt="Bild des Gaskochers" src="https://user-images.githubusercontent.com/88385654/144746538-a3a069a7-3398-41c4-8aec-4cbb6bee9ebf.jpg">
</details>
	
<ul>
	<li> Ebenfalls essenziell für das Projekt ist ein arduinofähiges Thermometer. Die Wahl fiel auf das MAX6675. <a href="https://www.amazon.de/ANGEEK-MAX6675-thermocouple-Temperature-arduino/dp/B07X41RG6K/ref=sr_1_2_sspa?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=max6675&qid=1630502970&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE3WkxHNEVaR0RIODUmZW5jcnlwdGVkSWQ9QTAzODIyOTMxVUI3TVFJTVk4VzNZJmVuY3J5cHRlZEFkSWQ9QTA2ODY3NDQxUTUxRVNaSlU2QTdSJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ=="> Kauflink von Amazon</a> Dieses Thermometer zeichnet sich durch einen hohen Toleranzbereich aus, was für die Arbeit mit Feuer sehr wichtig ist. Zunächst stand der genaue Einsatzbereich des Thermometers noch nicht fest und über eine Anwendung im Flammenbereich wurde gesprochen. Letztendlich entschied sich die Gruppe dafür das Thermometer in den Deckel zu integrieren und so die Temperatur des Topfinhaltes zu ermitteln. Bei dieser Idee, die für den Nutzer die transparenteste Darstellung bietet, ergaben sich allerdings zwei Probleme. Erstens ist der gemessen Wert etwas verzögert, da das Wasser sich nur träge erwärmt und die Restwärme des Topfbodens und der Gasflamme nicht berücksichtigt wird. Zweitens ist das Thermometer selbst nicht wasserdicht, sodass es abgedichtet werden musste. Dafür wurde das Thermometer in eine Kupferröhre gelegt und mit Gummidichtungen abgedichtet. Außerdem wurde das Thermometer in den Topfdeckel integriert, damit der Topf frei beweglich bleibt und nur der Deckel fest mit dem Versuchsaufbau verbunden ist. Durch diese Befestigung, die ebenfalls mit einer Gummidichtung verschlossen wurde, konnte ein Messfehler durch vorbeischlagende Flammen und die Erhitzung des Topfmaterials verhindert werden. </li>
</ul>
		
<details>
	<summary>Bilder des Thermometers</summary>
<b>Produktfoto von Amazon</b> <img alt="Foto von Amazon" src="https://user-images.githubusercontent.com/88385654/144747225-fcb04dbb-05b6-4ce7-90b7-404dee4d755c.jpg">
<b>abgedichtetes Thermometer von der Seite</b> <img alt="Thermometer von der Seite" src="https://user-images.githubusercontent.com/88385654/144747285-2ef88078-3c94-4cbe-ad3c-f3cbb8325a52.jpg">
<b>abgedichtetes Thermometer von oben</b> <img alt="Thermometer von oben" src="https://user-images.githubusercontent.com/88385654/144747339-24c4b179-e3e3-4dc5-b00e-c582d85e4a4a.jpg">
<b>in den Deckel integriertes Thermometer</b> <img alt="intergriertes Thermometer" src="https://user-images.githubusercontent.com/88385654/144747404-27191672-7abd-4362-8e79-351dfe617311.jpg">
</details>

<ul>
	<li>Die Steuerung der Gasmenge, die verbrannt wird, wurde durch einen Schrittmotor übernommen. Der Motor sollte über eine Verbindung den Gasregler des Kochers greifen und diesen drehen kann, damit mehr oder weniger Gas fließen kann. Die Wahl fiel auf den 
"STEPPER MOTOR PM GEARED UNI 12" <a href="https://www.digikey.de/de/products/detail/adafruit-industries-llc/918/5629415?utm_adgroup=Stepper%20Motors&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Motors%2C%20Solenoids%2C%20Driver%20Boards%2FModules_Returning&utm_term=&productid=5629415&gclid=Cj0KCQiA47GNBhDrARIsAKfZ2rCAzhqzbNzZGrUsjejqYNCxjTkvTUfVFHDXiyRKR401iU-asx9D3XMaAojuEALw_wcB"> Link zum Motor</a> Durch ein 3D gedrucktes Verbindungsstück wurde eine Verbindung von Schrittmotor zu Gasregler hergestellt. Das Verbindungsstück wurde mit TinkerCAD erstellt, nachdem mit einer Schieblehre alle wichtigen Maße erhoben worden und dann mit einem 3D Drucker gedruckt. Nach mehreren Fehlversuchen ist ein Teil entstanden, dass sowohl auf den Schrittmotor als auch auf den Gasregler gesteckt werden konnte und auch bei Belastung nicht durchdrehte. Damit der Schrittmotor Kraft gegen das Ventil aufbringen kann, musste sichergestellt werden, dass der Motor sich nicht mitdreht, sondern mit statischen Teilen verbunden ist. Zu diesem Zweck wurde eine Plattform aus dünnen Blech auf das Ventil gebaut und mit einer Steckverbindung sicher verankert. Anschließend wurde eine Verlängerung aus Winkeln gebaut und sowohl an dem Schrittmotor als auch an dem Blech befestigt. Der Schrittmotor war nun fest verankert, sodass er Kraft auf das Ventil aufbrinken kann, um es zu öffnen oder zu schließen. Durch die Winkellängerung wurde auch eine Flexibilität der Halterung erreicht. Diese Beweglichkeit führte zu zwei wichtigen Vorteilen: Erstens wurde die Ausrichtung erleichtert und zweitens kann somit auch die Vor- und Zurückbewegung des Gasgewindes ausgelgichen werden. </li>
		
</ul>		
<details>
	<summary>Bilder des Schrittmotors
<b>Produktbild von digikey</b><img alt="Produktbild" src="https://user-images.githubusercontent.com/88385654/144747822-e6f11729-bca4-4690-b1ac-8fdc9646971a.jpg">
<b>Bild des 3D-Verbindungsstückes</b> <img alt="Verbindungsstück" src="https://user-images.githubusercontent.com/88385654/144748936-545565d5-8019-4317-9ab3-bde5a10a6bd5.jpeg">
<b>Bild der Winkelverbindung zum Schrittmotor</b> <img alt="Winkelverbindung" src="https://user-images.githubusercontent.com/88385654/144749209-f82a8302-f0d7-4fcc-bb83-b723baece09f.jpg">
<b>Blechplattform auf dem Ventil der Gasflasche</b> <img alt="Plattform" src="https://user-images.githubusercontent.com/88385654/144749222-d67bf05a-0ed0-4973-9913-175274c65055.jpg">
</details>






<h4> <a id="Produkt"> &#10123; &nbsp Das Endprodukt </a> </h4>
Der viermonatige Entwicklungsprozess mit vielen Testungen und Lösungen von Problemen, hat letzendlich zu einem funktionierenden Prototypen geführt. 

<details>
	<summary>Video eines erfolgreichen Experiments - novum hotplate</summary>
<a href="https://www.youtube.com/watch?v=mMkYHf9HaGQ&t"> <img src="https://user-images.githubusercontent.com/88385654/144663860-19e3b678-31f6-41d4-84ab-b127c74e58e5.jpeg"></a>
</details> 
	
<details> 
	<summary>Bilder der Verbindung vom Schrittmotor zum Gasregler</summary>
<b> Bild der Verbindung von oben </b> <img alt="Bild der Verbindung von oben #1" src="https://user-images.githubusercontent.com/88385654/144712415-9438f4ad-bb94-4634-9735-5d4a1ef488c8.jpg">
<b> Bild der Verbindung von oben #2 </b> <img alt="Bild der Verbindung von oben #2" src="https://user-images.githubusercontent.com/88385654/144712443-f4b32d50-2695-4c6b-a35f-74440c7bcfd3.jpg">
<b>Bild der Verbindung von der Seite</b> <img alt="Bild der Verbindung von der Seite" src="https://user-images.githubusercontent.com/88385654/144712447-8eb4af4b-4a83-41d2-b094-f6fb76846b28.jpg">
</details>
	
<details> 
	<summary>Bild der Verbindung vom Ventil der Gasflasche zur Befestigung des Schrittmotors</summary>
<b>Verbindung vom Ventil der Gasflasche zur Befestigung des Schrittmotors</b> <img alt="Bild der Verbindung Gasflasche - Befestigung" src="https://user-images.githubusercontent.com/88385654/144712515-e62ca042-f9e7-4525-9306-8daab9ce9ac8.jpg">
</details>	

<details> 
	<summary>Bild des Gaskochers</summary>
<b> Bild des Gaskochers</b> <img alt="Bild des Gaskochers" src="https://user-images.githubusercontent.com/88385654/144712667-099b86cd-aeeb-4291-8455-68a8a97586e7.jpg">
</details>

<details>
	<summary>Bilder des Topfes mit integriertem Thermometer</summary>
<b>Bild des geschlossenen Topfes von oben</b> <img alt="Bild des Topfes von oben" src="https://user-images.githubusercontent.com/88385654/144713410-7d113ccb-af0e-4b76-aa14-580f5a456b78.jpg"> 
<b>geschlossener Topf von der Seite</b> <img alt="Bild des Topfes von der Seite" src="https://user-images.githubusercontent.com/88385654/144713517-ac251685-7834-47ec-8a22-06eedeef4d6d.jpg">
<b>Bild des integrierten Thermometers von unten</b> <img alt="Bild des Thermometers von unten" src="https://user-images.githubusercontent.com/88385654/144713521-86303ce7-36a7-44f6-b49f-6ef1a144bd0f.jpg">
</details>
	
<details>
	<summary>Bilder des Netzteils</summary>
<b>Netzteil von vorne</b> <img alt="Netzteil" src="https://user-images.githubusercontent.com/88385654/144712838-272ec29c-0eb4-4f05-9d9c-32df7a695509.jpg">
<b>Bild der Klemmverbindung</b> <img alt="Klemmverbindung" src="https://user-images.githubusercontent.com/88385654/144712872-0bb5fea9-4ed0-4356-b207-e64660f0057f.jpg">
</details>

<details>
	<summary>Bilder des LC-Displays</summary>
<b>ausgeschaltet LC-Display</b><img alt="Display off" src="https://user-images.githubusercontent.com/88385654/144713053-fa4b06a1-84c8-404d-948b-11c1c76b1671.jpg">
<b>eingeschaltetes LC-Display</b><img alt="Display on" src="https://user-images.githubusercontent.com/88385654/144713076-88889dc2-449d-420a-ba7f-bdd674039c22.jpg">
</details>
	
<details>
	<summary>Steckverbindungen</summary>
<b>digitalisierter Schaltplan von fritzing</b> <img alt="digitaler Schaltplan" src="">
<b>Steckverbindung des Schrittmotors</b> <img alt="Steckverbindung des Schrittmotors" src="https://user-images.githubusercontent.com/88385654/144713178-4dc65553-10ac-4708-bc5a-465017ca3dc8.jpg">
<b>Steckverbindung des rotary encoders</b> <img alt="Steckverbindung rotary encoder" src="https://user-images.githubusercontent.com/88385654/144713214-fa8f43f1-de85-4387-8a83-e92b9f6d5d65.jpg">
<b>Steckverbindung des Thermometers</b> <img alt="Steckverbindung Thermometer" src="https://user-images.githubusercontent.com/88385654/144713242-cf867406-5674-4c8a-95bd-096a48159876.jpg">
<b>Übersicht der Steckverbindungen</b> <img alt="Übersicht Steckverbindung" src="https://user-images.githubusercontent.com/88385654/144713257-0644e4bb-effb-4a7d-a74f-b533f7beaf0b.jpg">
</details>

<hr>

<h4> <a id="Reflexion"> &#10124; &nbsp Reflexion und Fazit des Projekts </a> </h4>

Der arduinogesteuerte Gaskocher - aus einer spontanen Idee ist Wirklichkeit geworden. Grundsätzlich lässt sich festhalten, dass die Gruppe mit dem Prototypen und der graphsichen Darstellung des Projektes sehr zufrieden ist. Auch wenn der Entwicklungsprozess mit hohem zeitlichen Aufwand, einigen sehr kurzen Nächten und manchmal auch Flucherei verbunden war, überwog dauerhaft der Wille das Projekt nach vorne zu bringen und die eigenen Kenntnisse zu erweitern. <br>
Durch diese Projektarbeit gewonnen beide Gruppenmitglieder große Einblilcke in das Programmieren von Microcontrollern und die Darstellung von Informationen mit HTML. Wie in dem Punkt "verwendete Programme" dargestellt, wurden auf dem Weg des Projekts aber auch viele andere Fähigkeiten hinzugewonnen. Beispielhaft dafür ist das Erstellen und Drucken von 3D-Modellen oder die Erstellung von YouTube-Videos. Für diese Möglichkeit ist die Gruppe sehr dankbar. Hierdrin besteht auch ein großer Vorteil bei physical computing Projekten, da arbeiten auf ganz unterschiedlichen Ebenen erledigt werden müssen. Dadurch werden Projekte natürlich schnell anspruchsvoll, aber eben auch sehr vielseitig. <br>
Die zurückliegende Gruppenarbeit wurde anhand von verschieden Kriterien beurteilt und reflektiert. 
<ul>
	<li>Die Planung des Projektes verlief unkompliziert. Während der gesamten Projektphase war die Stimmung innerhalb der Gruppe gut und die Arbeitsphasen produktiv. An Absprachen wurde sich gehalten und die Bereitschaft auch außerschulisch das Projekt voranzubringen war vorhanden. </li>
	<li>Mit der geleisteten Arbeit ist die Gruppe zufrieden, obwohl nicht alle Ziele umgesetzt werden konnten. Aufgrund von zeitlichen Schwierigkeiten wurden, anders als eingangs geplatn, die Steckverbindungen nicht gelötet und auch keine Transportbox gebaut. Die Gruppe entschied sich dafür die hardwaretechnische Umsetzung für den Prototypen in den Hintergrund zu stellen und die Software in den Vordergrund zu rücken. Wichtig bei der Hardware war nun, dass diese funktional war, damit Testungen erfolgen können. Durch diese Misskalkulation lernt die Gruppe, dass es zwar wichtig ist sich Ziele zu setzen, allerdigns auch adaptiv und flexibel sich auf äußere Umstände anpassen zu können</li>
</ul>
Nach der Reflexion des Projektes war für die Gruppe schnell klar, dass die Zusammenarbeit auch für das kommende Halbjahr weitergeführt werden soll. Es ist wichtig, dass ein gutes Klima in der Gruppe herrscht und dass sich die Mitglieder aufeinander verlassen können. Während der finalen Phase des Projektes hat sich ebenfalls abgezeichnet, dass die Gruppe das Projekt des arduinogesteuerten Gaskochers weiterführen möchte. Im Hinterkopf stehen dort auch Ideen wie die Teilnahme am Wettbewerb Jugend forscht. Der entstandene Prototyp hat gezeigt wie viel innerhalb von vier Monaten möglich ist und dass dieses physical computing Projekt die Gruppe begeistert. Damit aus dem Protoyp ein fertiges Produkt wird, sollen in der nächsten Arbeitsphase einige Änderungen vorgenommen werden. Die Brainstormingpahse dieses neuen Abschnittes startete bereits. Abschließend lässt sich dieser Unterichtsabschnitt als erfolgreich bewerten, weil viel dazu gelernt wurde, es viel Spaß bereitet hat und ein funktionaler Protoyp entstanden ist, der die Grundlage für die weitere Entwicklung darstellt. 

<h4> <a id="Ausblick"> &#10124; &nbsp Ausblick auf kommende Veränderungen </a> </h4>

Beim Brainstormingprozess kamen folgende Ideen auf:
<ul>
	<li>Handysteuerung der Temperatur</li>
	<li>Programmierbarkeit eines Kochprogramms mit zeitlicher Komponente</li>
	<li>ordentliches Kabelmanagement mit Verlötung und Aufbewahrung</li>
	<li>akkustiches oder optisches Signal bei Erreichen der Zieltemperatur</li>
	<li>weitere Optimierung der Funktion zur Ermittlung des Öffnungsgrads</li>
	<li>eigenständige Entzündung des Gaskochers</li>
</ul>


