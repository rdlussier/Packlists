# Packlists

An offline-first packing list web app (installable on a phone home screen).

- Everything is saved on the phone (localStorage), so the app opens and works with no signal.
- Optional sync: the app keeps one `data.json` in the private `Packlists-data` repo, using a GitHub access token pasted into the app once. The token stays on the phone, never in this repo.
- This repo holds only app code and no personal data.

Files: `index.html` (the whole app), `sw.js` (offline cache), `manifest.webmanifest`, icons.
After the app code changes, open the app twice to pick up the new version.
