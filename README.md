# Projekt Brut-Kasten

## Aufbau 'Proof of Concept'
Die RGB LED's vom Typ APA106-8 haben jeweils einen digitalen Ein- und Ausgang. Somit kann man relativ einfach viele LED's mit nur einem digitalem Pin des Arduino ansteuern. 
Um zu sehen ob die Idee mit einem Arduino-Board, APA106-8 RGB LED und der Neo-Pixel Bibliothek funktioniert habe ich folgenden Aufbau gemacht:

![Poc Aufbau](ProjektBrutKasten_PoC_Steckplatine.png)

Und es funktionierte auf anhieb. Nun kann man die Leiterplatte bauen.

## Bau der Leiterplatte
Zunächst Portieren wir das ganze mal von einem Arduino Duemilanove auf einen Atmel ATTiny45/85 (je nachdem wieviel Programmspeicher benötitig wird 4kB oder 8 kB). Hier das Schema mit 6 RGB-LED's:

![Schaltplan](ProjektBrutKasten_Schaltplan.png)

Und die entsprechende Leiterplatte:

![Leiterplatte](ProjektBrutKasten_Leiterplatte.png)

Um den ATTiny45/85 zu programmieren verwenden wir den Arduino als Programmier-Gerät ([hier eine Anleitung](http://highlowtech.org/?p=1695)).


## Werkzeuge und Material
* Arduino IDE
* Fritzing.org
* Arduino Duemilanove
* Breadboard
* RGB LED APA106-8
