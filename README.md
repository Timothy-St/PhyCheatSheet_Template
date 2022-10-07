# Cheatsheet Template for Physics

## LaTeX Workflow

Keine Gedanken machen. Einfach alles reinschreiben was einem wichtig erscheint.

Formatierung können wir am Ende machen.

## Git Workflow

(alle Befehle in dem Ordner des Repos ausführen!)

1. ***WICHTIG!!!!:*** Bevor ihr etwas neues hinzufügt macht ihr:
   ```git pull```
   Das bringt euer lokales Repo auf den neusten Stand. (lädt die neusten Änderungen von GitHub herunter)

2. Ihr fügt eure Formel/Hinweise/Tricks/... hinzu.

3. ```git diff```
   um zu sehen was ihr alles geändert habt. Hier seht ihr falls ihr aus Versehen Mist gebaut habt.

4. ```git add *```
   um alle Änderungen zu stagen.

4. ```git commit -m "Hier kurz schreiben was ihr gemacht habt (nicht länger als das hier)"```
   um einen commit mit euren Änderungen zu machen

5. Jetzt seid ihr lokal schon fertig. Aber wir müssen das ja auch mitbekommen. Deshalb darf auf keinen Fall das abschließende
   ```git push```
   fehlen, das eure(n) hinzugefügte(n) commit(s) auf GitHub hochlädt, wo die anderen sie dann mit 1. wieder herunterladen.
