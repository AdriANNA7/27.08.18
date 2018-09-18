# 27.08.18

Die letzten beiden Stunden haben wir uns erst Tutorials zur Benutzung von GreenFoot und die Arduinosprache angesehen. Diese Stunde beschäftigten wir uns mit **GitHub**. Da wir noch Anfänger sind, wollen wir wissen, wie man den Stundenblog auf GitHub erstellen kann. Wir schauten uns [GitHub Help](https://help.github.com/articles/basic-writing-and-formatting-syntax/#quoting-code) an, um das grundlegende Schreibsyntax zu lernen. Dadurch haben wir erfahren, wie man die Screenschots oder Links einfügen kann. Wir haben uns darüber informiert, was *Branching* und *Commits* darstellen. 


# 28.08.18

Diese Doppelstunde haben wir uns mit dem Programm **Snap!** beschäftigt. Mit dem **Snap!** kann man graphisch programmieren.  Als Einführung haben wir uns das Programm angeschaut und verschiedene Sachen ausprobiert. Wir setzten uns mit den Befehlen auseinander und stellten fest, dass wir verschiedene Akteure (sog. Sprites) mit Hilfe der Tastatur kontrollieren können.
Wir wollten einen Hund horizontal bewegen lassen. Dafür haben wir auf dem Script den Befehl, unter Control Taste 0, move 10 steps (Motion) eingefügt.

![1](https://user-images.githubusercontent.com/42734752/44729547-5e38a680-aadf-11e8-9c5f-0ea227e6f0d4.jpg)

Dazu sollte der Hund Hello für zwei Sekunden sagen. Dafür haben wir, unter Control Leertaste, den Befehl von Looks "say hello for 2 seconds" hinzugefügt.

![2hello](https://user-images.githubusercontent.com/42734752/45362670-ba1e2780-b5d5-11e8-8d06-58754d4527bb.jpg)

Wir finden, dass Snap! als Programm für uns als Anfänger sehr geeignet ist, da es verständlich und einfach zu bedienen ist.


# 10.09.2018

Nachdem wir uns für die blockbasierte Programmiersprache **Snap** entschieden haben, fingen wir den schon fertigen Kurs [*Beauty and Joy of computing*](https://bjc.edc.org/bjc-r/course/bjc4nyc.html) an, der von den Universitäten von California, Berkeley und Education Development Center ausgearbeitet wurde. Der Kurs stellt sieben Units dar, die unterschiedlichen Niveaus entsprechen. Als Anfänger wollen wir zuerst eine theoretische Grundlage erlangen.
Als ersten Schritt, legten wir einen Account an. Es ist wichtig einen eigenen Account zu haben, damit die Dateien auf jeden Fall gespeichert sind. 

# 11.09.2018

In diese Doppelstunde setzten wir unseren Kurs fort. Wir haben ein neues *Sprite* aus *costumes* hinzugefügt, und zwar das *costume* Unicorn 1 . Dieses haben wir dupliziert, und daraufhin durch *edit* spiegelverkehrt erstellt. Um das spiegelverkehrte *costume* sehen zu können, haben wir auf unserem Script die Befehle *when I am **clicked** + *next costume* eingefügt.

![spiegelverkehrt](https://user-images.githubusercontent.com/42734752/45363379-aa074780-b5d7-11e8-907d-fa559fc65d36.jpg)

Zusätzlich wollten wir, dass sich das Unicorn zufällig auf dem Bildschirm bewegt, sobald man es anklickt. Dafür haben wir unter *motion* den Befehl *go to x: [...]  y: [...]* hinzugefügt und unter *operators* durch den zusätzlichen Befehl *pick random [number] to [number]* beliebige Koordinaten eingefügt.

![pickrandom](https://user-images.githubusercontent.com/42734752/45364650-f902ac00-b5da-11e8-9402-856f31a79570.jpg)

Um das Unicorn kontinuierlich bewegen zu lassen, setzten wir unter *control* den Befehl *forever* ein. Allerdings bewegte sich das Unicorn immens schnell. Um dies zu verlangsamen setzten wir direkt danach unter *control* den Befehl *wait 1 sec* ein. Danach bewegte sich das Unicorn in einem angenehmen Tempo zufällig weiter. Als wir versuchen wollten, dass das *costume* immer wieder neu verscchwindet, setzten wir den Befehl *change **ghost** effect by **25*** ein. Leider verschwand das Unicorn daraufhin komplett und wir konnten es nicht wieder sichtbar machen. Dann kamen wir auf die Idee für den Wert **25** eine negative Zahl einzusetzen. Dies klappte und das Unicorn wurde wieder erkennbar.

![ghost](https://user-images.githubusercontent.com/42734752/45365755-85ae6980-b5dd-11e8-8c16-89430781dd55.jpg)

So wussten wir zwar, wo sich unser *costume* befindet, aber es war nicht in seiner Original-Form. Dann entdeckten wir den Befehl *clear graphic effects* und setzten diesen ein. Glücklicherweise konnte man das Unicorn damit wieder deutlich in Original-Form sehen.



#17.09.2018

Diesmal haben wir ein simples Spiel programmiert. Wir haben ein *Costume (Costume 1/Pfeil)*, welches man mit Hilfe der Pfeile der Tastatur bewegen kann, eingefügt. 

![apfelspiel](https://user-images.githubusercontent.com/42734752/45690620-15609480-bb57-11e8-9381-96494b7a5ce3.jpg)

Dazu haben wir ein zweites *Costume (Costume 2/Apfel)* eingefügt, welches sich zufällig auf dem Bildschirm bewegt und jedesmal vorher verschwindet und dann an seiner neuen Position sichtbar wird. Lenkt man *Costume 1* zu *Costume 2* und berührt dieses, wird *Costume 1* größer. 

![apfelspiel2](https://user-images.githubusercontent.com/42734752/45690638-214c5680-bb57-11e8-8203-81d8caf1d415.jpg)

Das Problem besteht darin, dass der Pfeil sich nicht nur, wie gewünscht einmal vergrößert, sondern mehrmals. Dies führt dazu, dass der Pfeil schnell, zu groß für den Bildschirm wird. 

#18.09.2018

Heute haben wir die Sparte der Grafik bei Snap! ausprobiert. Das Sprite sollte als Stift fungieren. Dies konnte man durch den Block *Pen* einstellen, mit gewünschter Farbe. Zusätzlich sollte das Sprite natürlich mit der Tastatur bewegt werden können, was wir, wie bei den Projekten davor, bewerkstelligten. So konnte man nun mit Hilfe der Pfeiltasten malen. 
