# Github project for Mezuza hosting static website 

## How to create Github static page 
So gehst du vor, um die Webseite bei GitHub zu hosten:

Erstelle einen neuen Ordner auf deinem Computer: Nenne ihn zum Beispiel mesusot_website.
1. Speichere die Dateien:
Öffne einen Texteditor (wie Notepad auf Windows, TextEdit auf Mac oder VS Code).
Kopiere den gesamten HTML-Code und speichere ihn als index.html im mesusot_website-Ordner.
Kopiere den gesamten CSS-Code und speichere ihn als style.css im selben Ordner.
1. Füge deine Bilder hinzu:
Erstelle im mesusot_website-Ordner einen neuen Unterordner namens images.
Platziere deine Mezuzah-Bilder in diesem images-Ordner.
Ganz wichtig: Benenne die Platzhalter in index.html um, sodass sie den Namen deiner Bilder entsprechen. Zum Beispiel, wenn dein Bild meine_mesusa_1.jpg heißt, ändere <img src="placeholder1.jpg" alt="Mesusa Design 1"> zu <img src="images/meine_mesusa_1.jpg" alt="Mesusa Design 1">. Wiederhole dies für alle Bilder.
1. Lade die Webseite auf GitHub hoch:
Erstelle ein GitHub-Konto: Falls du noch keins hast, registriere dich kostenlos auf github.com.
Erstelle ein neues Repository: Klicke auf das "+" Symbol in der oberen rechten Ecke und wähle "New repository".
Gib einen Repository-Namen ein (z.B. meine-mesusot).
Wähle "Public".
Wichtig: Aktiviere nicht die Option "Add a README file" oder ".gitignore" oder "Choose a license" in diesem Schritt, da wir die Dateien manuell hochladen.
Klicke auf "Create repository".
Auf der nächsten Seite siehst du Anweisungen. Wähle die Option "uploading an existing file" (meist ein kleiner Link unter den Kommandozeilen-Anweisungen).
Ziehe deinen gesamten mesusot_website-Ordner (oder alle Dateien einzeln, aber der Ordner ist einfacher) in das Upload-Feld oder wähle die Dateien manuell aus. Stelle sicher, dass index.html, style.css und der images-Ordner mit deinen Bildern hochgeladen werden.
Scrolle nach unten und klicke auf "Commit changes".
1. Aktiviere GitHub Pages:
Gehe in deinem Repository auf den Tab "Settings".
Scrolle nach unten zum Bereich "Pages".
Unter "Build and deployment", wähle bei "Source" die Option "Deploy from a branch".
Bei "Branch" wähle "main" (oder "master", je nachdem, wie dein Hauptzweig heißt) und dann / (root).
Klicke auf "Save".
Es kann ein paar Minuten dauern, aber danach siehst du über den Einstellungen den Link zu deiner veröffentlichten Webseite (z.B. deinbenutzername.github.io/meine-mesusot).
