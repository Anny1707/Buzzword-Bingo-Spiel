# Buzzword Bingo

Buzzword Bingo ist ein unterhaltsames Spiel, bei dem Spieler versuchen, bestimmte Buzzwords zu erraten, während sie an Meetings oder Präsentationen teilnehmen. Dieses Projekt implementiert die Grundfunktionen für das Spiel, einschließlich der Erstellung von Bingo-Boards, der Verwaltung von Spielerinformationen und der Verwaltung des Spielflusses.

## Projektstruktur

Das Projekt besteht aus folgenden Dateien:

- **bingo_helpers.py**: Hilfsfunktionen zur Bearbeitung von Wörterlisten und zum Erstellen von Bingo-Boards.
- **buzzword_bingo.py**: Hauptskript zur Verwaltung der Spiellogik und zur Bearbeitung von Befehlen über die Kommandozeile.
- **game_utils.py**: Zusätzliche Utility-Funktionen zur Verwaltung von Spielrunden und Spieleraktionen.
- **player.py**: Definiert die Spielerklasse und deren Verhalten im Spiel.

## Installation

### Python3 auf Linux installieren

**Python3 installieren**

   Öffnen Sie das Terminal und führen Sie folgende Befehle aus:

   sudo apt update
   
   sudo apt install python3 python3-pip
   

Überprüfen der Installation mit:

python3 --version
pip3 --version
Spiel installieren


## Klonen Sie das Repository:

git clone https://github.com/Anny1707/BuzzwordBingo.git

cd BuzzwordBingo

## Verwendung

Erstellen Sie eine neue Spielrunde mit folgendem Befehl:

python3 buzzword_bingo.py newround -roundfile runde.json -xaxis 5 -yaxis 5 -wordfile buzzwords.txt -maxplayers 4 -player "IhrName"
Spieler zur Runde hinzufügen

Fügen Sie einen Spieler hinzu:

python3 buzzword_bingo.py joinround -roundfile runde.json -player "NeuerSpieler"

Starten Sie das Spiel:

python3 buzzword_bingo.py startgame -roundfile runde.json
Log-Dateien

Jeder Spiellog wird in einer separaten Datei gespeichert. Die Logdatei wird beim Start des Spiels erstellt.
Weiterentwicklung

Zusätzliche Features: Sie können zusätzliche Funktionen wie Benachrichtigungen, Punktesysteme oder eine Benutzeroberfläche hinzufügen.

## Code verbessern: Beiträge und Pull Requests sind willkommen!

Viel Spaß beim Spielen von Buzzword Bingo!
