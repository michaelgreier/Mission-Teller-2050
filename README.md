# Mission Teller 2050

Einstiegsprogramm und digitaler Laufzettel für die Biologie-Freiarbeit „Ernährung“, Klasse 7 (Gymnasium Niedersachsen).

Das Programm braucht keinen Server, keine Anmeldung und keine Installation. Alle Dateien werden direkt aus dem Repository geladen, es gibt keine Verbindungen zu Google Fonts oder anderen fremden Servern.

## Inhalt des Ordners

- `index.html` – das Programm
- `fonts/` – die Schriften (Atkinson Hyperlegible, Bricolage Grotesque, SIL Open Font License)

Lade immer **alle** Dateien und den Ordner `fonts` hoch, sonst fehlt die Schrift. Die PDF-Funktion steckt direkt in `index.html`.

## Auf GitHub veröffentlichen (GitHub Pages)

1. Bei github.com anmelden und oben rechts auf **+ → New repository** klicken.
2. Einen Namen eingeben, z. B. `mission-teller-2050`, **Public** wählen und **Create repository** klicken.
3. Auf der neuen Seite den Link **uploading an existing file** anklicken.
4. Den Inhalt des entpackten Ordners (`index.html`, `README.md`, `fonts`) in das Fenster ziehen und unten **Commit changes** klicken.
5. Im Repository auf **Settings → Pages** gehen.
6. Unter **Build and deployment** bei **Source** „Deploy from a branch“ wählen, bei **Branch** `main` und `/ (root)` einstellen und **Save** klicken.
7. Nach ein bis zwei Minuten erscheint oben auf der Pages-Seite die Adresse, z. B.
   `https://DEIN-NAME.github.io/mission-teller-2050/`

Diese Adresse können die Schülerinnen und Schüler ohne Anmeldung öffnen, zum Beispiel über einen QR-Code im Freiarbeitsraum.

## Später etwas ändern

Im Repository auf `index.html` klicken, dann auf das Stift-Symbol (**Edit this file**). Nach **Commit changes** ist die neue Version nach etwa einer Minute online. Gespeicherte Fortschritte der Schülerinnen und Schüler bleiben dabei erhalten, solange Repository-Name und Adresse gleich bleiben.

Leicht anpassbar im Abschnitt `/* ---------- Inhalte ---------- */` der Datei:

- `WAHL`: die Wahlbausteine
- `PACKS`: die Lernpakete mit Aufgaben und Boxen
- `QUIZ`: die Fragen des Vortests (`a` ist die Nummer der richtigen Antwort, gezählt ab 0)

## Speicherung und Datenschutz

- Alle Eingaben bleiben im Browser des jeweiligen Geräts (localStorage). Sie werden nicht an GitHub oder andere Server geschickt.
- Beim Aufruf der Seite sieht GitHub als Betreiber von GitHub Pages die IP-Adresse des Geräts. Ob das an eurer Schule zulässig ist, sollte die oder der Datenschutzbeauftragte bestätigen. Alternativ kann der Ordner unverändert auf einem Schulserver liegen.
- Die Daten gehen verloren, wenn Browserdaten gelöscht werden, im privaten Modus, bei einem anderen Browser oder Gerät oder wenn sich die Adresse der Seite ändert.
- **Safari auf iPad und iPhone** löscht solche Daten, wenn die Seite 7 Tage lang nicht geöffnet wurde. Tipp: Die Seite über **Teilen → Zum Home-Bildschirm** als Symbol ablegen und die Schülerinnen und Schüler regelmäßig den Bericht als PDF sichern lassen.
- Wer das Tablet wechselt, nimmt den Fortschrittscode aus „Bericht“ mit. Vor der Weitergabe eines Tablets kann man unter „Bericht → Neu anfangen“ alles löschen.
