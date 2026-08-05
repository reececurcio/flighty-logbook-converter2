FLIGHTY IPHONE LOGBOOK CONVERTER — VERSION 5.0

WHAT CHANGED
- Block time is calculated only after converting airport-local OUT and IN times to UTC.
- Uses the iPhone/Safari built-in IANA time-zone engine; Luxon is no longer used.
- Airport time zones are bundled in airports.js, so there is no airports.csv upload problem.
- Preview shows departure/arrival time zones and OUT UTC / IN UTC values.

INSTALL / UPDATE ON GITHUB PAGES
1. Delete the old app files from your repository.
2. Upload every file in this folder.
3. Commit the changes and wait for GitHub Pages to deploy.
4. Delete the old Home Screen icon.
5. In iPhone Settings, clear Safari website data for your GitHub Pages site.
6. Open the site in Safari and confirm it says VERSION 5.0 NATIVE UTC ENGINE.
7. Test SAMPLE-FlightyExport.csv. The first MIA–EIS flight diverted to SJU must show 3:38.
8. The preview UTC check for that flight should show 2026-02-03 18:09Z → 2026-02-03 21:47Z.
9. Add the site back to the Home Screen.

FILES REQUIRED
index.html, app.js, airports.js, styles.css, manifest.webmanifest, icon.svg, service-worker.js
