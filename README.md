# Gym Log

Offline-first workout logger (PWA). Data is stored on your phone in IndexedDB.

## Put it on your phone (GitHub Pages, free)
1. Create a new public GitHub repo, e.g. `gym-log`.
2. Upload these 5 files to the repo root: index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png.
3. Repo Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After about a minute, open `https://<your-username>.github.io/gym-log/` in Chrome on Android.
5. Chrome menu (three dots) > "Add to Home screen" > "Install".
6. Open the installed app > Settings > check "Protected storage" is on.

## Updating
Edit the files and push. The app fetches the new version the next time you open it online.
If you change icons or the manifest, bump `CACHE` in sw.js (e.g. `gymlog-v2`).

## Backups
Settings > Export backup saves a JSON file. Import merges a backup in without duplicating sets.
Do this before changing phones or clearing Chrome data.
