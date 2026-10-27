# Mission Teller 2050

Einstiegsprogramm und digitaler Laufzettel für die Biologie-Freiarbeit „Ernährung“, Klasse 7 (Gymnasium Niedersachsen).

Das Programm besteht aus einer einzigen Datei: `index.html`. Es braucht keinen Server, keine Anmeldung und keine Installation.

## Auf GitHub veröffentlichen (GitHub Pages)

1. Bei github.com anmelden und oben rechts auf **+ → New repository** klicken.
2. Einen Namen eingeben, z. B. `mission-teller-2050`, **Public** wählen und **Create repository** klicken.
3. Auf der neuen Seite den Link **uploading an existing file** anklicken.
4. `index.html` und `README.md` in das Fenster ziehen und unten **Commit changes** klicken.
5. Im Repository auf **Settings → Pages** gehen.
6. Unter **Build and deployment** bei **Source** „Deploy from a branch“ wählen, bei **Branch** `main` und `/ (root)` einstellen und **Save** klicken.
7. Nach ein bis zwei Minuten erscheint oben auf der Pages-Seite die Adresse, z. B.
   `https://DEIN-NAME.github.io/mission-teller-2050/`

Diese Adresse können die Schülerinnen und Schüler ohne Anmeldung öffnen, zum Beispiel über einen QR-Code im Freiarbeitsraum.

## Später etwas ändern

Im Repository auf `index.html` klicken, dann auf das Stift-Symbol (**Edit this file**). Nach **Commit changes** ist die neue Version nach etwa einer Minute online.

Leicht anpassbar im Abschnitt `/* ---------- Inhalte ---------- */` der Datei:

- `WAHL`: die Wahlbausteine
- `PACKS`: die Lernpakete mit Aufgaben und Boxen
- `QUIZ`: die Fragen für Vor- und Nachtest (`a` ist die Nummer der richtigen Antwort, gezählt ab 0)

## Datenschutz

Das Programm speichert alle Eingaben nur im Browser des jeweiligen Geräts (localStorage). Es werden keine Daten an GitHub oder andere Server geschickt. Nur die Schriftarten werden von Google Fonts geladen. Wer das Tablet wechselt, nimmt den Fortschrittscode aus dem Bereich „Bericht“ mit. Vor der Weitergabe eines Tablets kann man unter „Bericht → Neu anfangen“ alles löschen.
