# Island 2027 — Familien-Roadbook

Neun Tage Island in den Osterferien 2027 (Karfreitag 26.3. bis Samstag 3.4.).
Route: Snæfellsnes → Borgarfjörður → Golden Circle → Südküste → Vatnajökull.

Eine einzelne statische HTML-Seite, keine Abhängigkeiten außer Google Fonts
und Bildern von Wikimedia Commons.

## Auf GitHub Pages veröffentlichen

1. Neues Repository anlegen, z.B. `island-2027` (öffentlich, damit Pages
   ohne kostenpflichtigen Plan funktioniert).
2. `index.html` und diese `README.md` hochladen — entweder per Drag & Drop
   im Browser ("Add file" → "Upload files") oder per Kommandozeile:

   ```bash
   git init
   git add .
   git commit -m "Island-Roadbook 2027"
   git branch -M main
   git remote add origin https://github.com/Fozz2026/island-2027.git
   git push -u origin main
   ```

3. Im Repository: **Settings → Pages**.
4. Bei "Source" **Deploy from a branch** wählen, Branch `main`, Ordner `/ (root)`,
   dann **Save**.
5. Nach ein bis zwei Minuten ist die Seite erreichbar unter:

   ```
   https://Fozz2026.github.io/island-2027/
   ```

Der Link lässt sich direkt teilen und funktioniert auf Handy und Tablet.

## Wenn die Seite privat bleiben soll

GitHub Pages aus privaten Repos gibt es nur mit bezahltem Plan. Alternativen:

- **Netlify Drop** (app.netlify.com/drop): Ordner ins Browserfenster ziehen,
  fertig. Erzeugt eine zufällige, nicht auffindbare URL.
- **Lokal**: `index.html` einfach per AirDrop oder Mail verschicken und im
  Browser öffnen. Funktioniert offline, außer den Bildern und Fonts.

## Anpassen

- Alles steckt in `index.html`: Struktur, CSS und ein kleines Skript für
  Fortschrittsbalken und Scroll-Animationen.
- Farbpalette und Abstände sitzen ganz oben in `:root` als CSS-Variablen.
- Bilder kommen über `Special:FilePath` direkt von Wikimedia Commons. Ein
  Bild ersetzen: Dateiname in der URL austauschen. Bilder, die nicht laden,
  werden automatisch ausgeblendet.
- Fahrzeiten und Übernachtungsorte stehen jeweils im `.spine`- und
  `.sleep`-Block des betreffenden Tages.

## Offene Punkte

- [ ] Flüge FRA–KEF für 26.3. und 3.4.2027 buchen
- [ ] Mietwagen 4×4 mit Winterreifen, zweiter Fahrer, Sand-/Ascheversicherung
- [ ] **Eishöhlentour für Do 1.4. buchen** — Saisonende, Plätze knapp,
      Mindestalter schriftlich bestätigen lassen
- [ ] Blue Lagoon (26.3.) und Sky Lagoon (3.4.) Zeitfenster reservieren
- [ ] Unterkünfte: Borgarnes, Hellissandur, Laugarvatn, Hella, Vík,
      Hof (2 Nächte), Hvolsvöllur
- [ ] Reiten optional: Hof bei Flúðir/Hella oder Hvolsvöllur
- [ ] Öffnungszeiten Krauma und Secret Lagoon an Ostern prüfen
