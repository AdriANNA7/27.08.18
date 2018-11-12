# 27.08.18

  Die letzten beiden Stunden haben wir uns erst Tutorials zur Benutzung von GreenFoot und die Arduinosprache angesehen. Diese Stunde beschäftigten wir uns mit **GitHub**. Da wir noch Anfänger sind, wollen wir wissen, wie man den Stundenblog auf GitHub erstellen kann. Wir schauten uns [GitHub Help](https://help.github.com/articles/basic-writing-and-formatting-syntax/#quoting-code) an, um das grundlegende Schreibsyntax zu lernen. Dadurch haben wir erfahren, wie man die Screenshots oder Links einfügen kann. Wir haben uns darüber informiert, was *Branching* und *Commits* darstellen. 


# 28.08.18

  Diese Doppelstunde haben wir uns mit dem Programm **Snap!** beschäftigt. Mit dem Programm **Snap!** kann man graphisch programmieren.  Als Einführung haben wir uns das Programm angeschaut und verschiedene Sachen ausprobiert. Wir setzten uns mit den Befehlen auseinander und stellten fest, dass wir verschiedene Akteure (sog. Sprites) mit Hilfe der Tastatur kontrollieren können.
Wir wollten einen Hund horizontal bewegen lassen. Dafür haben wir auf dem Script den Befehl, unter *Control* Taste 0, *move 10 steps (Motion)* eingefügt.

![1](https://user-images.githubusercontent.com/42734752/44729547-5e38a680-aadf-11e8-9c5f-0ea227e6f0d4.jpg)

  Dazu sollte der Hund "Hello" für zwei Sekunden sagen. Dafür haben wir, unter *Control Leertaste*, den Befehl von *Looks* "say hello for 2 seconds" hinzugefügt.

![2hello](https://user-images.githubusercontent.com/42734752/45362670-ba1e2780-b5d5-11e8-8d06-58754d4527bb.jpg)

  Wir finden, dass **Snap!** als Programm für uns als Anfänger sehr geeignet ist, da es verständlich und einfach zu bedienen ist.


# 10.09.18

  Nachdem wir uns für die blockbasierte Programmiersprache **Snap** entschieden haben, fingen wir den schon fertigen Kurs [*Beauty and Joy of computing*](https://bjc.edc.org/bjc-r/course/bjc4nyc.html) an, der von den Universitäten von California, Berkeley und Education Development Center ausgearbeitet wurde. Der Kurs stellt sieben Units dar, die unterschiedlichen Niveaus entsprechen. Als Anfänger wollen wir zuerst eine theoretische Grundlage erlangen.
Als ersten Schritt, legten wir einen Account an. Es ist wichtig einen eigenen Account zu haben, damit die Dateien auf jeden Fall gespeichert sind. 

# 11.09.18

  In dieser Doppelstunde setzten wir unseren Kurs fort. Wir haben ein neues *Sprite* aus *Costumes* hinzugefügt, und zwar das *Costume* "Unicorn 1!" . Dieses haben wir dupliziert, und daraufhin durch *edit* spiegelverkehrt erstellt. Um das spiegelverkehrte *Costume* sehen zu können, haben wir auf unserem Script die Befehle *when I am **clicked** + *next costume* eingefügt.

![spiegelverkehrt](https://user-images.githubusercontent.com/42734752/45363379-aa074780-b5d7-11e8-907d-fa559fc65d36.jpg)

  Zusätzlich wollten wir, dass sich das "Unicorn" zufällig auf dem Bildschirm bewegt, sobald man es anklickt. Dafür haben wir unter *Motion* den Befehl *go to x: [...]  y: [...]* hinzugefügt und unter *Operators* durch den zusätzlichen Befehl *pick random [number] to [number]* beliebige Koordinaten eingefügt.

![pickrandom](https://user-images.githubusercontent.com/42734752/45364650-f902ac00-b5da-11e8-9402-856f31a79570.jpg)

  Um das "Unicorn" kontinuierlich bewegen zu lassen, setzten wir unter *Control* den Befehl *forever* ein. Allerdings bewegte sich das "Unicorn" immens schnell. Um dies zu verlangsamen setzten wir direkt danach unter *Control* den Befehl *wait 1 sec* ein. Danach bewegte sich das "Unicorn" in einem angenehmen Tempo zufällig weiter. Als wir versuchen wollten, dass das *Costume* immer wieder neu verschwindet, setzten wir den Befehl *change **ghost** effect by **25*** ein. Leider verschwand das "Unicorn" daraufhin komplett und wir konnten es nicht wieder sichtbar machen. Dann kamen wir auf die Idee für den Wert **25** eine negative Zahl einzusetzen. Dies klappte und das "Unicorn" wurde wieder erkennbar.

![ghost](https://user-images.githubusercontent.com/42734752/45365755-85ae6980-b5dd-11e8-8c16-89430781dd55.jpg)

  So wussten wir zwar, wo sich unser *Costume* befindet, aber es war nicht in seiner Original-Form. Dann entdeckten wir den Befehl *clear graphic effects* und setzten diesen ein. Glücklicherweise konnte man das "Unicorn" damit wieder deutlich in Original-Form sehen.



# 17.09.18

  Diesmal haben wir ein simples Spiel programmiert. Wir haben ein *Costume (Costume 1/Pfeil)*, welches man mit Hilfe der Pfeile der Tastatur bewegen kann, eingefügt. 

![apfelspiel](https://user-images.githubusercontent.com/42734752/45690620-15609480-bb57-11e8-9381-96494b7a5ce3.jpg)

  Dazu haben wir ein zweites *Costume (Costume 2/Apfel)* eingefügt, welches sich zufällig auf dem Bildschirm bewegt und jedesmal vorher verschwindet und dann an seiner neuen Position sichtbar wird. Lenkt man *Costume 1* zu *Costume 2* und berührt dieses, wird *Costume 1* größer. 

  ![apfelspiel2](https://user-images.githubusercontent.com/42734752/45690638-214c5680-bb57-11e8-8203-81d8caf1d415.jpg)

  Das Problem besteht darin, dass der Pfeil sich nicht nur, wie gewünscht einmal vergrößert, sondern mehrmals. Dies führt dazu, dass der Pfeil schnell, zu groß für den Bildschirm wird. 

# 18.09.18

  Heute haben wir die Sparte der Grafik bei Snap! ausprobiert. Das Sprite sollte als Stift fungieren. Dies konnte man durch den Block *Pen* einstellen, mit gewünschter Farbe. Zusätzlich sollte das Sprite natürlich mit der Tastatur bewegt werden können, was wir, wie bei den Projekten davor, bewerkstelligten. So konnte man nun mit Hilfe der Pfeiltasten malen. 

# 22.10.18

  Heute sind wir das Problem vom 17.09 angegangen, um unser Spiel zu optimieren. Dafür haben wir für unseren *Apfel(Costume 2)* eingestellt, dass er, wenn er den Pfeil(Costume1) berührt 0.1 sek wartet und dann zu *random position* geht. Nach einigem Ausprobieren haben wir dies endlich geschafft.
  
  ![problemapfel](https://user-images.githubusercontent.com/42734752/47641902-8daf7200-db67-11e8-8999-f4ee83d3f9cd.jpg)


# 23.10.18

  In dieser Unterrichtsstunde arbeiten wir an unserem Spiel weiter. Für die Zukunft, wollen wir das Design unseres Spieles ändern. Deshalb kommen wir zu diesem Punkt ein anderes Mal zurück. 
  Für unser Spiel wollen wir eine Spielstandanzeige einfügen. Dafür haben wir eine neue Variable *Score* erstellt und sie bei 0 eingestellt. 
  
  ![score1](https://user-images.githubusercontent.com/42734752/47366796-b2769600-d6de-11e8-8583-3d49ca9c8015.jpg)

   Wenn *Score* größer als die gegebene Einheit wird, ändert sich unser *Costume1*(Pfeile) in ein anderes *Costume*, das wir davor importiert haben. 
   
  ![score](https://user-images.githubusercontent.com/42734752/47366682-7e02da00-d6de-11e8-833d-3162a416cf11.jpg)
  
# 29.10.18

Heute wollten wir zusätzliche Tools einfügen. um das Spiel spannender zu gestalten. Dafür haben wir eingestellt, dass der Apfel(*Costume 2*), sich nach einem *Score* von 30 schneller bewegt.  
  
![apfelbeschleunigung](https://user-images.githubusercontent.com/42734752/47643411-b89bc500-db6b-11e8-96f1-9f2f1c4090f9.jpg)
  
  Danach wollten wir, dass bei einem *Score* von 30, das erreichen dieses *Scores* gefeiert wird in Form einer goldenen 30, welches im Zentrum für eine Sekunde erscheint. Zuerst hatten wir Probleme damit, dass die 30 wieder verschwindet, damit man weiter spielen kann. Dies war der Fall, weil wir den Befehl bei *Score* >=30 eingestellt hatten und es wiederholte es sich ständig, da es ja ab da immer größer als 30 war. Dies änderten wir zu *Score* = 30, damit es nur bei dem *Score* erscheint.
  
  ![score 30](https://user-images.githubusercontent.com/42734752/47724379-d85be780-dc56-11e8-9af7-61bd4cd80160.jpg)
  
  # 30.10.18
  
  Bis jetzt änderte sich der *Score*, je nach dem wie lange *Sprite 1* das *Sprite 2* berührte. Deshalb wurde der *Score* immer unterschiedlich erhöht. Dies stellte aber ein Problem dar, da man manchmal nicht exakt einen *Score* von 30 erreichen konnte. Außerdem war es viel zu ungenau für ein Spiel. Deswegen haben wir den Block, dass sich der Score um 1 erhöht von dem Script des ersten Sprites zum Script des ZWeiten Sprites verschoben. So erhöht sich der Score jedes mal nur um 1.
  
![score 1 richtig](https://user-images.githubusercontent.com/42734752/47727968-bade4c00-dc5d-11e8-8f45-a98fc57f87de.jpg)

  
  Zusätzlich haben wir das Konzept unseres Spieles ein wenig verändert. Wir wollen eine Art Evolution darstellen. Das heißt wir beginnen mit dem *Costume* eines Einzellers, welcher das *Costume 2* in Form einer Alge, Unterwasser (*Stage*) fangen muss. Bei bestimmten *Scores* entwickelt sich das *Costume 1* weiter. Das heißt, es wecheslt das *Costume*. Dazu wird auch der Hintergrund (*Stage*) in Etappen geändert. Wie auch bei der Evolution vom Wasser zum Land.
 
 
 Dann haben wir herausgefunden, dass unsere "Lösung" vom 29.10 für das Problem, dass das goldene 30 nicht verschwindet, immer noch nicht behoben ist. Deswegen fügten wir zu dem Befehl *Hide* den Befehl *forever* ein. Nun verschwindet das goldene 30 tatsächlich jedes mal wieder.
 
 ![30 losung](https://user-images.githubusercontent.com/42734752/47728483-ba928080-dc5e-11e8-8c37-1de91da2df6f.jpg)
 
 # 06.05.18
 Heute haben wir weiter *Costumes* eingefügt, einen Tintenfisch und einen Krebs. Dabei mussten wir beachten, dass der *Costume-Switch* endet, wenn ein weiteres *Costume* erscheint. Deswegen mussten wir zu *when score > 15* noch *when score < 31* hinzufügen, damit dann das nächste *Costume* erscheinen kann.
 
 ![verschiedene costumes](https://user-images.githubusercontent.com/42734752/48072289-7bbf7600-e1dc-11e8-8f33-7618fb971847.png)

Dazu wollten wir, dass sich der Hintergrund, passenden zum Krebs-Costume, zu einem Sandstrand ändert. Dies bewerkstelligten wir genau, wie bei den *Costumes*.

![stage sand und krebs screen](https://user-images.githubusercontent.com/42734752/48072826-afe76680-e1dd-11e8-968a-2a053c7fb730.png)

Außerdem wollten wir die Befehle für das *Costume* der goldenen 30 noch einmal ändern, da wir immer noch nicht ganz zufrieden mit der aktuellen Situation waren. Dafür haben wir eingefügt, dass das *Costume* nach 2 Sekunden eine Größe von 0 Proznet annimt, also verschwindet. Wenn man das Spiel neu anfängt, ist springt es wieder zu 100 Prozent, ist aber versteckt.

![30 spiel](https://user-images.githubusercontent.com/42734752/48073886-f50c9800-e1df-11e8-9702-34c25f45378c.png)

# 12.11.18

Heute wollten wir das Schwierigkeitslevel des Spieles erhöhen. Es sollte ein Sprite geben, welches unser Sprite1 "tötet" man soll als auch verlieren können. dafür haben wir ein neues Sprite erstellt, welches auf der x-Achse gleitet und das random auf der y-Achse und sich dieses beliebig wiederholt. Wenn Sprite 1 dieses neue Sprite berührt, sagt Sprite 1 Game over, verschwindet und alle Blöcke werden gestoppt.
