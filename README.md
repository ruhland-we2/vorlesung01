# Web Engineering II, Vorlesung01 vom 17.02.2022

## Übungen01 Markdown und Git

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

Um schreibend auf das GitHub Repository zugreifen zu können muss man sich authentifizieren. Hierzu gibt es in VSC das Icon <img src="vsc-user-icon.png" height="24px">.

Wenn man jetzt z.B. die README.md in VSC editiert und abspeichert wird die Änderung  in dem GitHub Icon angezeigt <img src="vsc-git-icon.png" height="24px">. Diese muss man mit einem Commit und einer Commit Meldung bestätigen. Dies erfolgt mit dem Hackchen in der Leiste <img src="vsc-git-bar.png" height="24px">. Mit einem sync wird die Änderung dann auf dem GitHub Repository eingespielt.

Folgende Kommandos sollte man vorbereitend im Terminal von VSC eingeben
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

