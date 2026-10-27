# FLOOSY (فلوسي)
Static, backend-free personal finance app. Single file: `index.html` (HTML + CSS + vanilla JS).

## Run
Open `index.html` in a browser, or serve the folder: `python3 -m http.server`.

## Deploy
Upload the folder to GitHub Pages (Settings → Pages → deploy from branch) or drag it into Netlify. No build step, no server.

## Data
Everything is saved automatically in this browser's localStorage (key `floosy.v1`) on this device only. No sync between devices.
Clearing browser data can erase it, so use Settings → Export Backup (JSON) regularly and Import Backup to restore (full replacement, with confirmation).
Amounts are stored as integer piastres. Savings-goal contributions are tracked separately and do not change the balance.
