# Kinco HMI DTools Beispiel Messwertanzeige 4 - 20 mA mit Skalierung (Beispielwert CO<sub>2</sub>)

![](assets/a2b37ed7a0bf85e566c1479f95221d2ba8566eec.png)

Example program of CO<sub>2</sub> Display for 4 - 20 mA Sensor in Kinco HMI made with DTools

Dieses Beispielprogramm für ein Kinco GT070HE zeigt, wie man leicht einen 4 - 20 mA-**Messwert** auf dem HMI skalieren und darstellen kann. Ein simulierter Temperatursensor (LW0) mit einem 4 - 20 mA-Messwert wird in einen Wert mit Einheit skaliert. 



## Das ist im Beispielprogramm enthalten



* **Zahlenanzeige** für CO2 mit Skalierung im Anzeigeelement und Einheit als Label (ppm)
* **Rechtsbündige Ausrichtung** des Werts für bessere Darstellung
* Anpassung aller **Schriftarten** auf Arial Nova für attraktive Darstellung
* Beispiel **Grafische Schrift** (Bitmap-Schrift) zur Darstellung von Sonderzeichen (tiefergestellte 2 in CO<sub>2</sub>)
* Abgerundetes Rechteck, Überschrift für Messwert und Icon als statisches Bitmap (importiertes PNG)
* Komponente **Balkendiagramm** rechts zur Darstellung des Wertes als Balken
* Simulation eines unskalierten Rohwertes als 4-20-mA-Messwert (wie im Analogmodul für KS-SPS)
* Eigene Button (selbst erstellte VG-Vektorgrafik) für Buttons für Wertänderung (Hoch / Runter) mit **Jog-Funktion (Multizustandschalter)**
* Anpassung der **Zifferntastatur** mit passender Farbdarstellung und Arial Nova als Tastaturschriftart
* Anpassung der **Systemmeldung** für falsche Eingabe des Rohwertes - Sprache und Schriftart der Meldung
* Timer rechts unten, der beim Aufruf des Fensters (Start des HMI) den simulierten Messwert auf 5500 setzt

Das Projekt wurde für das Kinco HMI GT070HE mit einer Auflösung von 1.024 x 600 Pixeln erstellt. Die Kinco HMI der GL100E und GT100E-Serie sowie das GT070E2 haben eine gleiche Auflösung. Das Projekt kann für diese Modelle einfach per Rechtsklick auf das HMI in DTools konvertiert werden. 
Für HMI mit anderer Auflösung ist eine Konvertierung über diesen Weg ebenfalls möglich, es werden aber wahrscheinlich Nacharbeiten notwendig, um die Darstellung an das HMI anzupassen.

Das Programm wurde in der Entwicklungssoftware Kinco DTools 4.4.0.3 erstellt.



## So ladet ihr das Programm herunter

### Variante 1:

Unter "<> Code" findet ihr einen Link zum "Download ZIP"

### Variante 2:

Wenn ihr euch in Github registriert und Github Desktop installiert, könnt ihr das Programm **klonen** und so als lokale Kopie auf eure Festplatte holen.



![](assets/b47bc804ef28f7127134dc0258e53d83dcb08fac.png)
