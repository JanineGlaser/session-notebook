//shell basics

command and functionality
ls list the content of the current directory
cd <foldername> change directory into a folder
cd .. change into the parent folder
cd ~ change into your home directory
pwd print the current directory path
touch example.md create a file called "example.md"
mkdir newFolder create a folder called "newFolder"
mv <oldname> <newname> move or rename a file
rm <filename> delete a file permanently (there is no trash bin to recover files!)
open . open the current folder in the finder
cat <filename> prints the content of a specific file
curl <url> prints the received content from the specified url. (try curl ipinfo.io)

// Git basics

Order anlegen die man in VsCode öffnen und bearbeiten möchte und mit Code . öffnen um danach in die cloud (github) zu pushen

1: git init // eine git datei in dem Ordner erstellen //
2: git status // prüfen //
3: git add . // alle änderungen speichern //
4: git commit -m " folder name" // Datei anlegen und gleichzeitig wechseln //
5: -- Github öffnen, neu anlegen + 3 Sätze kopieren + in Terminal einfügen (branch name ändern).
6: git add .
7: Ordner im VsCode anlegen: .gitignore - .DS_Store
8: git commit -m "folder name"
9: git push

Nachdem wir alles geändert haben müssen wir jetzt die einzelnen dinge speichern indem wir ein commit erstellen und das ganze an unseren "boss" senden zum kontrollieren.

10: git add .
11: git commit -m "allles aufzeigen was geändert wurde"
12: git status
13: git push -u orgin + // name des branch //

commit wurde erstellt und ist nun im Github hochgeladen

- nun wird der alte branch also unsere kopie auf unserem pc gelöscht, wir brauchen es nicht mehr, es ist jetzt online.

14: git switch main ( auf den hauptmain zurück kehren um jetzt lokal zu speichern)
15: git branch -d + // branch name //
