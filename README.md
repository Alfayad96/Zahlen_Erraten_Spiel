# Zahlen Erraten Spiel

Das "Zahlen Erraten" Spiel ist ein einfaches Python-Spiel, bei dem der Spieler drei Zahlen zwischen 1 und 15 erraten muss. Das Spiel generiert zufällige Gewinnzahlen und vergleicht diese mit den geratenen Zahlen des Spielers. Wenn die geratenen Zahlen mit den Gewinnzahlen übereinstimmen, gewinnt der Spieler. Andernfalls ist das Spiel vorbei.

## Funktionen

- **Willkommensnachricht:** Begrüßt den Spieler und gibt an, dass das Spiel in 5 Sekunden beginnt.
- **Generierung von Gewinnzahlen:** Das Spiel generiert drei zufällige Zahlen zwischen 1 und 15.
- **Eingabe der geratenen Zahlen:** Der Spieler gibt nacheinander drei Zahlen zwischen 1 und 15 ein.
- **Vergleich der Zahlen:** Das Spiel vergleicht die geratenen Zahlen mit den Gewinnzahlen und gibt das Ergebnis aus (Gewonnen oder Game Over).
- **Neustart des Spiels:** Der Spieler kann das Spiel neu starten, indem er die Zahl `1` eingibt.

## Voraussetzungen

- Python 3.x
- Bibliotheken: `colorama` (für farbige Konsolenausgabe)

## Installation

1. Klonen Sie das Repository:

```bash
git clone https://github.com/Alfayad96/Zahlen-Erraten-Spiel.git
```

2. Navigieren Sie in das Verzeichnis des Projekts:

```bash
cd Zahlen-Erraten-Spiel
```

3. Installieren Sie die erforderlichen Bibliotheken:

```bash
pip install colorama
```

## Verwendung

1. Führen Sie das Skript aus:

```bash
python zahlen_erraten.py
```

2. Folgen Sie den Anweisungen im Terminal, um drei Zahlen zwischen 1 und 15 einzugeben.

3. Das Spiel vergleicht Ihre geratenen Zahlen mit den zufällig generierten Gewinnzahlen und gibt das Ergebnis aus.

4. Um das Spiel neu zu starten, drücken Sie die Zahl `1`, um das Programm zu beenden, drücken Sie eine andere Zahl.

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Weitere Informationen finden Sie in der `LICENSE`-Datei.
