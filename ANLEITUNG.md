# Nebenjob-App: Hochladen und auf dem iPhone installieren

## 1. Auf GitHub hochladen (am PC)

1. ZIP-Datei entpacken.
2. Auf github.com einloggen, oben rechts auf **+** und dann **New repository**.
3. Name: `nebenjob`, Sichtbarkeit **Public** (GitHub Pages ist im kostenlosen Konto nur für öffentliche Repositories verfügbar), dann **Create repository**.
4. Auf der leeren Repository-Seite auf **uploading an existing file** klicken.
5. Alle Dateien aus dem entpackten Ordner hineinziehen (nicht den Ordner selbst, sondern seinen Inhalt) und **Commit changes** klicken.
6. **Settings** öffnen, links **Pages** wählen.
7. Unter „Branch" **main** und **/ (root)** auswählen, dann **Save**.
8. Etwa 1 bis 2 Minuten warten. Oben auf der Pages-Seite erscheint die Adresse, zum Beispiel
   `https://DEIN-BENUTZERNAME.github.io/nebenjob/`

Im Repository liegt nur der Programmcode. Deine Arbeitszeiten werden nie hochgeladen, sie bleiben auf dem iPhone.

## 2. Auf dem iPhone installieren

1. Die Adresse in **Safari** öffnen.
2. Unten auf **Teilen** tippen (Quadrat mit Pfeil nach oben).
3. **Zum Home-Bildschirm** wählen, dann **Hinzufügen**.
4. Die App ab jetzt immer über das Icon „Nebenjob" starten, nicht über Safari. Nur die installierte App hat deine Daten.

Nach dem ersten Start funktioniert die App ohne Internet.

## 3. Erste Schritte

1. Zahnrad oben rechts: Name und Stundenlohn eintragen.
2. Mit **+** einen Abend eintragen.
3. Monatsende: **Stundenzettel erstellen**, dann im Teilen-Menü Mail, WhatsApp oder „In Dateien sichern" wählen.

## 4. Datensicherung (wichtig)

Die Daten liegen nur auf dem iPhone. Wenn du die App vom Home-Bildschirm löschst oder das iPhone verlierst, sind sie weg.

- Zahnrad, dann **Sicherung speichern**, dann **In Dateien sichern**, dann **iCloud Drive** wählen.
- Am besten einmal im Monat, zusammen mit dem Stundenzettel. Die App erinnert dich, wenn die letzte Sicherung länger als 30 Tage her ist.
- Wiederherstellen: Zahnrad, dann **Sicherung laden** und die Datei auswählen.

## 5. Spätere Änderungen an der App

Neue Dateien auf GitHub hochladen (gleiche Namen überschreiben). In `sw.js` die Zeile `const CACHE = 'nebenjob-v1';` auf `v2` usw. erhöhen, sonst lädt das iPhone weiter die alte Version. Die App zweimal öffnen und schließen, dann ist die neue Version aktiv. Deine Daten bleiben dabei erhalten.
