# Web Engineering II, Vorlesung01 vom 17.02.2022

## Übungen

### Erstellen einen Git Accouns und eines Repositories

Am Beispiel von ruhland-we2 wurde ein neuer Git Account erstellt mit einem ersten Repository vorlesung01.
Wir üben die Erstellung einer README.md markdown Datei.

Ein cheat-sheet zu Markdown liegt auch in dem Verzeichnis

### Arbeit mit dem Git Repository

* Herunterladen der Dateien aus dem Git-Repository darf jeder
* Schreiben in das Git-Repository benötigt man einen speziellen Zugriff Username/Password

#### Arbeit mit dem VisualStudioCode

Wenn man nur eine Kopie des GitHub Repositories möchte, nutzt man einfach das Terminal in VisualStudioCode und gibt das Kommando

```batch
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
In unserem Beispiel ist das
```batch
git clone https://github.com/ruhland-we2/vorlesung01
```

Eine Beschreibung finden Sie unter dem Link [https://code.visualstudio.com/docs/editor/github](https://code.visualstudio.com/docs/editor/github)

Beim ersten Aufruf der Git Extension ( Icon in der linken vertikalen Leiste in VSC ), muss man sich authentifizieren.

Wenn man jetzt z.B. die README.md in VSC editiert und abspeichert wird die Änderung angezeigt.
Diese muss man mit einem Commit und einer Commit Meldung bestätigen. Mit einem sync wird die Änderung
auf dem GitHub Repository eingespielt.

Folgende Kommandos muss man vorbereitend im Terminal von VSC eingeben
```
git config --global user.name "ruhland-we2"
git config --global user.email "k.ruhland@hszg.de"
```

Bei Fehlermeldung mit der Berechtigung können folgende Kommandos helfen
```
git config --system --unset credential.helper
git push --force 
```
der Abgleich erzwungen werden.
#### Arbeit mit einem anderen Client Programm sourcetree



