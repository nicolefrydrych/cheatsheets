# Shell Cheatsheet

## Navigation
Command | Description
--------|-----------
ls      | list all items
pwd     | Aktueller Pfad
cd      | change directory
mkdir ordnername  | make directory
touch filename  | creates new file in directory

## Manipulation

Command | Description
--------|-----------
ls -a         | list all items + hidden
ls -l         | list all items in long
ls -t         | list all items by time
ls -alt       | list all items hidden + long + time
cp            | copy files
mv            | move and rename
rm            | remove files
rm-r          | remove directory

# Cheat Sheet für **Shell Befehle**

#### Wechseln zu anderen Ordnern / Inhalt anzeigen etc.:

- `cd [Ordnername]` change directory
- `..` Weiterleitung in übergeordnete Ordner
- `z neu` = `cd ~/neuefische` z lernt oft benutzte Ordner und bietet so Abkürzung
- `ls` Liste aller Dateien und Unterordner eines Ordners
- `ls -la` Liste mit Details `l` (=long; untereinander auflisten) und durch `a` (=all) werden auch versteckte Dateien angezeigt
- `tree` Verzeichnisbaum anzeigen
- `curl` lädt Objekt über eine URL
- `cat` zeigt den Inhalt einer Datei

#### Neu, verschieben, kopieren, löschen, öffnen:

- `mkdir` Ordner erstellen
- `mkdir [Ordner/Unterordner]` Unterordner erstellen
- `mkdir -p [Ordner/Unterordner/Unterunterordner/...]` Ordnerpfad wird erzeugt
- `touch [Dateiname]` Datei erstellen
- `mv [alter Name] [neuer Name]` Ordner/Datei umbenennen
- `mv [alter Pfad] [neuer Pfad]` Ordner/Datei verschieben
- `mv [Ordner] *` verschieben des Ordners in den aktuellen Ordner
- `cp -R [src-directory] [target-directory]` kopiert alles aus dem Quellverzeichnis in das Zielverzeichnis
- `pbcopy` speichert Eingabe in die Zwischenablage (Bsp.: `cat ~/.ssh/id_rsa.pub | pbcopy`)
- `rm` remove (geht nur bei Dateien)
- `rm -rf` Ordner löschen; `r` = rekursiv (alles in allen Unterordnern); `f` = force (nicht jede Datei einzeln bestätigen); uch **Rimraf** genannt
- `rm -rf *` löschen aller Ordner und Dateien im aktuellen Ordner
- `code .` aktueller Ordner wird bei VS Code aufgerufen
- `open [Datei]` öffnet Datei mit dem Standardprogramm eines Betriebssystems
- `open .` öffnet Ordner im Finder/Explorer