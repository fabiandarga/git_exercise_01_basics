# Übungsaufgabe: Erstellen und Commiten einer einfachen Textdatei

Diese Übung sollte dir ein grundlegendes Verständnis für die Verwendung von git add, git status und git commit geben, um Änderungen in deinem Arbeitsverzeichnis zu verfolgen und zu bestätigen. Du kannst diese Übung beliebig oft wiederholen, um dich weiter mit diesen grundlegenden Git-Befehlen vertraut zu machen.

## Schritt 1
Initialisiere ein neues Git-Repository in einem leeren Verzeichnis. Verwende dazu den Befehl:
```bash
git init
```

## Schritt 2
Erstelle eine neue Textdatei mit einem Texteditor oder der Befehlszeile.
Nenne die Datei example.txt und füge einen beliebigen Textinhalt hinzu.

## Schritt 3
Überprüfe den Status deines Git-Repositories, um festzustellen, welche Änderungen erfasst werden können. 
Verwende dazu den Befehl:
```bash
git status
```

## Schritt 4
Füge die neue Textdatei dem Staging-Bereich hinzu, um sie für den nächsten Commit vorzubereiten.
Verwende dazu den Befehl:

```bash
git add example.txt
```

# Schritt 5
Überprüfe erneut den Status deines Git-Repositories, um zu sehen,
dass die Datei example.txt jetzt für den Commit bereit ist.

## Schritt 6
Mache einen Commit mit einer aussagekräftigen Commit-Nachricht. Verwende dazu den Befehl:

```bash
git commit -m "Added example.txt with initial content"
```

# Schritt 7
Überprüfe abschließend den Status deines Git-Repositories, um sicherzustellen, dass dein Arbeitsverzeichnis sauber ist und keine ausstehenden Änderungen mehr vorhanden sind.

