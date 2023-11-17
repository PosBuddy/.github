
## Architektur
* * *

![drawio](https://github.com/PosBuddy/.github/blob/main/profile/drawio?raw=true)

* * *
## Komponenten des PosBuddy Systems

### Kasse
An dem Kassensystem kann ein alter Laptop installiert werden.
Der Laptop sollte über eine Kamera verfügen. 
Alternativ kann hier eine USB Kamera verwendet werden

#### Kassenfunktionen
- Aufladen des Kontos
- Auszahlung vom Konto
- Sonderbuchungen
- Beleg Drucken

### Server
Als Server kann ein Raspberry Pi eingesetzt werden.

#### Funktionen
- Hosten der Datenbank in einem Container
- Hosten der PosBuddy Software in einem Container

### Router
Als Router fungiert z.b. eine alte Fritzbox

#### Funktionen
- bereitstellen des POSBuddy WLAN's
- Kabelgebundenes Netzwerk zwischen PosBuddy Server und Kasse / Admin

### Smartphones an Stationen
Hier können "alte" Smartphones genutzt werden
auf den Smartphones werden **X509 Zertifikate** installiert.

### Funktion
- Buchen von Positionen durch Auswahl der für diese Station angeboten Artikel
z.b. 2 x Bier 0,3
- Stornieren von Buchungen

Der Buchungsvorgang wird ausgelöst durch.
1. Anwahl der Artikel
2. Scannen des **PosBuddy Tokens**
