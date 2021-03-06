# Projekt Brut-Kasten

![Der Brut-Kasten](ProjektBrutKasten_03.jpg)

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

## Programmierung des ATtiny85
Um den ATTiny45/85 zu programmieren verwenden wir den Arduino als Programmier-Gerät ([hier eine Anleitung](http://highlowtech.org/?p=1695)).
![Der Brut-Kasten](ProjektBrutKasten_02.jpg)

## Das bemahlen der Eier
Das bemahlen der Eier habe ich mit einen [Egg-Bot](http://egg-bot.com) durchgeführt:
![Der Brut-Kasten](ProjektBrutKasten_01.jpg)

## Werkzeuge und Material
* [Arduino IDE](http://www.arduino.cc/)
* [Fritzing.org EDA](http://www.fritzing.org/)
* Vektor Grafik Editor [Inkscape](https://inkscape.org/)
* [Arduino Duemilanove](https://www.arduino.cc/en/Main/arduinoBoardDuemilanove) oder Ähnlich
* Steckplatine
* RGB LED [APA106-F8](https://cdn.sparkfun.com/datasheets/Components/LED/COM-12877.pdf)
* Mikrokontroller [ATTiny85 (oder ATTiny45)](http://www.atmel.com/images/atmel-2586-avr-8-bit-microcontroller-attiny25-attiny45-attiny85_datasheet.pdf)
* Spannungsregler [7805](https://www.sparkfun.com/datasheets/Components/LM7805.pdf)
* [CNC Fräse](https://aliexpress.com/item/CNC-2418-GRBL-control-Diy-CNC-machine-working-area-24x18x4-5cm-3-Axis-Pcb-Pvc-Milling/32704119622.html) 
* [PCB milling cutter](https://aliexpress.com/item/High-quality-10pcs-lot-Titanium-Nitride-Coated-Carbide-PCB-CNC-milling-cutter-0-8mm-3/32719367945.html)
* [Engraving bits](https://aliexpress.com/item/New-10pcs-New-Mini-PCB-wood-drill-Bits-Tungsten-Steel-Carbide-PCB-CNC-drill-Bit-Milling/32702792947.html)
* [Egg-Bot](http://egg-bot.com) (weitere Informationen sind im [WiKi](http://wiki.evilmadscientist.com/The_Original_Egg-Bot_Kit) zu finden)
* Rayher [Holz-Schatulle](https://rayher-hobby-shop.de/Basteltrends-Aktuelles/Saisonthemen/Hochzeit-Liebe/Accessoires/Boxen-Schachteln/Holz-Schatulle-FSC-Mix-Credit-1.html)
* Rayher [Plastik Eier 4,5 cm](https://rayher-hobby-shop.de/Brands-Aktuelles/Ostern/Deko-Artikel-O1/Aug-13/Plastik-Eier-oxid-2.html) und [Plastik Eier 3,8 cm](https://rayher-hobby-shop.de/Brands-Aktuelles/Ostern/Deko-Artikel-O1/Aug-13/Mini-Plastik-Eier-weiss-Beutel-5.html)

## Video
Ein kurzes Video kann man sich bei [YouTube](https://www.youtube.com/watch?v=r_lHXrtwGJQ) ansehen.
