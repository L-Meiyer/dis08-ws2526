# Conflict Resolution Report

## Was ist passiert?
Ich habe die Datei **bio.md** auf zwei verschiedenen Branches (**main** und **feature-facts**) an der gleichen!!! (ansonsten Auto-merged git) Zeile bearbeitet.
- Auf **main** habe ich "hallo" hinzugefügt und geadded.
- Auf **feature-facts** habe ich "hola" hinzugefügt und geadded.

Beim Versuch **git merge feature-facts** auszuführen, entstand ein Merge Conflict.

## Lösung
1. die Datei **bio.md** öffnen.
2. Konflikt-Marker (**<<<<<<<, =======, >>>>>>>**) sowie "hallo" und "hola" entfernen.
3. Mit `git add bio.md` und `git commit` Merge abschließen.
 -> merge abgeschlossen 
