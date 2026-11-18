# Snooker Scorer

Offline snooker scoring app. Score matches shot by shot, keep match history, and track stats for every player.

Open the GitHub Pages link on a phone or tablet, then add it to the home screen. After the first visit it works with no internet. Data is stored on each device. Use **Back up** / **Restore** on the home screen to keep a copy or move data between devices.

When you change any file, bump `VERSION` in `sw.js` so devices pick up the update.

## Sync (optional)

Groups sync players and matches through Firebase (Firestore + anonymous auth). Put the project's web config in `firebase-config.js`. `firebase-bundle.js` is the Firebase JS SDK (v11) bundled locally so the app works offline.
