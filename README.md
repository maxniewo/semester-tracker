# Semester Tracker

Behalte den Überblick, welche Vorlesungen und Übungen du verpasst hast, was du schon nachgeholt hast und wie weit du mit den Serien bist.

**Zur Seite: https://maxniewo.github.io/semester-tracker/**

## So funktioniert es

- **Vorlesungen:** Jede Semesterwoche zeigt deine Termine. Tippen wechselt zwischen besucht, verpasst und nachgeholt. Oben steht, was noch offen ist.
- **Serien:** Pro Kurs gibt es nummerierte Serien mit den Zuständen noch nicht gemacht, in Bearbeitung und erledigt. Pro Kurs stellst du ein, in welcher Woche Serie 1 kam. Serien können jede Woche oder alle 2 Wochen kommen.
- **Einrichten:** Semesterstart und Anzahl Wochen festlegen, Kurse mit ihren Terminen anlegen, Kurse abwählen, die du nicht belegst.

## Presets

Ein Preset ist ein fertiges Setup aus Semesterdaten und Kursen, zum Beispiel "Maschinenbau · 3. Semester".

- **Übernehmen:** Unter Einrichten → Presets ein Preset aus der Galerie wählen.
- **Teilen:** Unter "Mein Setup teilen" einen Link kopieren und verschicken. Der Link enthält das ganze Preset, es wird nirgends hochgeladen.
- **Veröffentlichen:** "In Galerie veröffentlichen" öffnet hier ein ausgefülltes Issue. Nach dem Absenden erscheint das Preset in der Galerie.

Die Galerie liest alle offenen Issues dieses Repos, die einen Preset-Link enthalten. Ein Issue schliessen entfernt das Preset aus der Galerie. Issues mit dem Label `geprüft` bekommen in der Galerie einen Stempel.

Als Betreiber musst du dafür nicht auf GitHub: Unter Einrichten → Presets → "Galerie verwalten" meldest du dich mit einem Token mit dem Recht `public_repo` an. Danach haben die Community-Karten Knöpfe zum Entfernen und zum Prüfen. Wer ein Preset veröffentlicht hat, kann sein eigenes auf demselben Weg entfernen.

Sortiert wird nach Likes, also nach der Anzahl 👍-Reaktionen auf dem Issue. Die Galerie zeigt zuerst sechs Presets, der Rest kommt über "Mehr anzeigen" oder die Suche.

## Daten und Privatsphäre

- Es gibt keinen Server und kein Konto. Deine Einträge liegen im Browser (localStorage).
- Optional kannst du sie über einen GitHub-Token mit dem Recht `gist` in einem privaten Gist auf deinem eigenen Konto speichern. So bleiben mehrere Geräte synchron.
- Geteilte Presets enthalten nur Semesterdaten und Kurse, keine Einträge.

## Selbst hosten

Die ganze Seite ist die Datei `index.html`. Repo forken, GitHub Pages einschalten, fertig. Galerie und Veröffentlichen zeigen dann automatisch auf den Fork.
