## Wildcards:
2.1 Erzeugen Sie ein Verzeichnis Docs in ihrem Heimverzeichnis
```bash
mkdir ~/Docs
```
---
2.2 Erstellen Sie die Dateien file1 bis file10 mit touch im Docs-Verzeichnis
```bash
cd ~/Docs
touch file{1..10}
```
---
2.3 Löschen Sie alle Dateien, welche einer 1 im Dateinamen haben
```bash
rm -f ./*1*
```
---
2.4 Löschen Sie file2, file4, file7 mit einem Befehl
```bash
rm file{2,4,7}
```
---
2.5 Löschen Sie alle restlichen Dateien auf einmal
```bash
rm -f ./file*
```
---
2.6 Erzeugen Sie ein Verzeichnis Ordner in ihrem Heimverzeichnis
```bash
mkdir ~/Ordner
```
---
2.7 Erstellen Sie die Dateien file1 bis file10 mit touch im Ordner-Verzeichnis
```bash
touch ~/Ordner/file{1..10}
```
---
2.8 Kopieren Sie das Verzeichnis Ordner mitsamt Inhalt nach Ordner2
```bash
cp -r ~/Ordner ~/Ordner2
```
---
2.9 Kopieren Sie das Verzeichnis Ordner mitsamt Inhalt nach Ordner2/Ordner3
```bash
cp -r ~/Ordner ~/Ordner2/Ordner3
```
---
2.10 Benennen Sie das Verzeichnis Ordner in Ordner1 um
```bash
mv ~/Ordner ~/Ordner1
```
---
2.11 Löschen Sie alle erstellten Verzeichnisse und Dateien wieder
```bash
rm -r ./Ordner*
```
---
