# Projektseite

### Inhaltsverzeichnis
<li><a href="#kapitel1.1">Programme</a></h2></li>
<li><a href="#kapitel1.2">Idee</a></h2></li>
<li><a href="#kapitel1.3">Anleitung</a></h2></li>
<li><a href="#kapitel1.4">Ergebnis</a></h2></li>
<li><a href="#kapitel1.5">Fazit</a></h2></li>
  
<h2 id="kapitel1.1">Programme</h2>

![Logo Greenfoot](Bilder/Greenfoot_Logo.png "Logo Greenfoot")

Für unser Projekt in diesem Halbjahr haben wir uns mit "Greenfoot" beschäftigt. "Greenfoot" ist ein Programm, bei welchem man mit "Java", einer objektorientierten Programmiersprache, arbeitet. Das Programm und die Programmiersprache wurden primär für Ausbildungszwecke entwickelt und zeichnen sich durch eine einfache Entwicklung zweidimensionaler graphischer Simulationen und Spiele aus. 

<h2 id="kapitel1.2">Idee</h2>
Die Idee unseres Spiels war ursprünglich etwas Wüstenähnliches beziehungsweise etwas zu programmieren, wo die Wüste eine Rolle spielt und was kein "Jump and Run" Spiel wie im ersten Halbjahr ist. Da wir uns auch erst einmal in ein neues Programm einarbeiten mussten haben wir uns dazu entschieden, ein Kaktus Labyrinth zu gestalten, welches von unserer Figur durchdrungen werden muss. Unser erster Gedanke war ein unendliches Labyrinth zu programmieren, damit wir zusätzlich noch einen anderen Spielaufbau als in unserem ersten Spiel haben. Wir mussten jedoch schnell feststellen, dass es einfacher ist, mehrere Level zu programmieren als ein unendlich laufendes Spiel, was eventuell auch dem Zeitfaktor geschuldet ist, da wir im ersten Halbjahr deutlich mehr Zeit zum Einarbeiten hatten als dieses Halbjahr.

<h2 id="kapitel1.3">Anleitung</h2>
Ziel unseres Spieles ist es, dass sich das Kamel durch das Kaktus-Universum bewegt und am Ende den Glücksklee zu finden und zu berühren. Die Spielsteuerung erfolgt über die Tastatur mit den Tasten "A" (= nach links), "D" (= nach rechts), "S" (= Drehung nach rechts) und "W" (= Drehung nach links). Der Spieler muss das Kamel so durch das Kaktus-Universum lenken, dass es weder die Kakteen noch die Spinnen berührt. Erschwert wird das Ganze durch zufällig erscheinende Bomben, die das Kamel sofort töten, weshalb das Spiel von vorne begonnen werden muss. Im ersten Level  gilt es das Holzfass (FassMitWasser) zu erreichen, um dem Kamel neue Ernergie für das zweite Level zu geben. Im zweiten Level muss das Kamel ebenfalls den Kakteen und Spinnen ausweichen und erreicht das Ziel, wenn der Glücksklee gefressen wurde. 

<h2 id="kapitel1.4">Ergebnis</h2>
In unserem Spiel muss sich ein Kamel durch ein Labyrinth aus Kakteen bewegen, wobei das Kamel pro Level 5 Leben hat, die in Form von roten Punkten am rechten, oberen Bildschirmrand angezeigt werden. Sowohl bei Berührung der Kakteen, als auch der Spinnen verliert das Kamel ein Leben. Trifft eine der zufällig erscheinenden Bomben das Kamel, ist das Kamel tot und das Spiel vorbei. Im Anschluss erscheint unser GameOver Bildschirm und das Spiel muss von vorne begonnen werden. 

**Level 1:**

![Level 1](Bilder/Endergebnis_Level_1.png "Level 1")

**Level 2:**

![Level 2](Bilder/Endergebnis_Level_2.png "Level 2")

<details id="Link"><summary>Erklärung Ergebnis</summary>

<details id="Link"><summary>Erklärung Code SandWorld</summary>
  
**Erklärung Code SandWorld**

![SandWorld](Bilder/Screenshot_Code_SandWorld_1.png "SandWorld")

![SandWorld](Bilder/Screenshot_Code_SandWorld_2.png "SandWorld")

![SandWorld](Bilder/Screenshot_Code_SandWorld_3.png "SandWorld")

![SandWorld](Bilder/Screenshot_Code_SandWorld_4.png "SandWorld")
</details>
  
<details id="Link"><summary>Erklärung Code Kamel</summary>
  
**Erklärung Code Kamel**

![Kamel](Bilder/Screenshot_Code_Kamel.png "Kamel")
</details>
  
<details id="Link"><summary>Erklärung Code Bombe</summary>
  
**Erklärung Code Bombe**

Für die Gravitation muss eine Variable mit einem "integer" erstellt werden, damit man in der "void"-Methode die Fallgeschwindigkeit immer um 1 erhöhen kann, wodurch das Fallen der Bombe realistischer aussieht. Damit sich die Bomben am Ende nicht alle am unteren Bildschirmrand sammeln, musste noch programmiert werden, dass die Bomben verschwinden, sobald sie den Rand des "Spielfeldes" berühren.

![Bombe](Bilder/Screenshot_Code_Bombe.png "Bombe")
</details>
  
<details id="Link"><summary>Erklärung Code TotenKopf</summary>
  
**Erklärung Code TotenKopf**

![TotenKopf](Bilder/Screenshot_Code_TotenKopf.png "TotenKopf")
</details>
  
<details id="Link"><summary>Erklärung Code Spinne</summary>
  
**Erklärung Code Spinne**

![Spinne](Bilder/Screenshot_Code_Spinne.png "Spinne")
</details>
</details>

<h2 id="kapitel1.5">Fazit</h2>
In diesem Halbjahr sollte es eine Steigerung zum Projekt des ersten Halbjahres geben, weshalb wir nich noch einmal mit "Snap" arbeiten durften, sondern uns in ein neues Programm einarbeiten mussten. Hierfür haben wir uns "Greenfoot" ausgesucht, da schon im ersten Halbjahr einige mit diesem Programm gearbeitet haben und von einer relativ einfachen Handhabung erzählt haben. Leider konnten wir die einfache Handhabung auch nach längerem Arbeiten nicht feststellen und unser Arbeiten beschäftigte sich größtenteils mit Fehler beheben, Ansätze zum Programmieren googlen und Herrn Buhl oder Mitschüler um Hilfe bitten, wenn wir alleine keinen Lösungsansatz finden konnten. Aus diesem Grund haben wir es leider nicht schaffen können, unserer Anfangsvorstellung om Projekt gerecht zu werden und unsere eigenen Ansprüche zu erfüllen. Dennoch haben wir nach der intensiven Arbeit mit diesem Programm den Umgang mit "Java" gelernt und ebenso, den Aufbau dieser Programmiersprache, was uns trotz der vielen Probleme und Rückschritte positiv in Erinnerung bleiben wird.
