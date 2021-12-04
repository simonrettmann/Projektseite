<html>
<head>
<h1 align="center">Der arduinogesteuerte Gaskocher - Projektseite</h1> 
</head>
<h3 align="center"> Ein Projekt von David Borgmann und Simon Rettmann</h3>
<h3 align="left">Stormarnschule Ahrensburg <br/> Informatik, Bl <br/> Schuljahr 2021/22, 1. Halbjahr </br> </h3> </div>
<h3 align="left"> &#10132; <a href="https://github.com/simonrettmann/Stundenprotokolle"> Stundenprotokolle</a> </h3>

<img align="center" alt="Animation" width="500" height="300" src="https://user-images.githubusercontent.com/88385654/144711039-e3602339-827f-42a6-b684-b21d3ee8bcf1.gif">

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

<h4> <a id="Software"> &#10122; &nbsp softwaretechnische Umsetzung </a> </h4>

<h4> <a id="Hardware"> &#10122; &nbsp hardwaretechnische Umsetzung </a> </h4>

<h4> <a id="Produkt"> &#10122; &nbsp Das Endprodukt </a> </h4>

<details>
	<summary>Video eines erfolgreichen Experiments - novum hotplate</summary>
<a href="https://www.youtube.com/watch?v=mMkYHf9HaGQ&t"> <img src="https://user-images.githubusercontent.com/88385654/144663860-19e3b678-31f6-41d4-84ab-b127c74e58e5.jpeg">
</details>
	
<details> 
	<summary>Bilder der Verbindung von Schrittmotor zum Gasregler</summary>
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
<b>Steckverbindung des Thermometers</b> <img alt="https://user-images.githubusercontent.com/88385654/144713242-cf867406-5674-4c8a-95bd-096a48159876.jpg">
<b>Übersicht der Steckverbindungen</b> <img alt="https://user-images.githubusercontent.com/88385654/144713257-0644e4bb-effb-4a7d-a74f-b533f7beaf0b.jpg">
</details>
	
<h4> <a id="Reflexion"> &#10124; &nbsp Reflexion und Fazit des Projekts </a> </h4>



