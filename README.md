# Fast Tracker

An intermittent fasting tracker for iPhone, built as an installable web app (PWA).

- **Timer**: start/end a fast, pick a goal (12:12 – 23:1), live progress ring, edit the start time if you forgot to tap Start.
- **History**: fast count, current streak, average, longest, goal hit rate, hours in the last 7 days, a 7-day chart, and a list of every fast (tap one to edit or delete it).
- **Backup**: export/import your data as JSON.

## Install on iPhone

1. Host it over HTTPS: in the repo go to Settings → Pages, deploy from the `main` branch root, then open https://staynee-hub.github.io/fasting/.
2. Open the URL in Safari → Share → **Add to Home Screen**.
3. Launch it from the home screen icon. It runs full-screen and works offline.

## Limitations

- Data is stored only on the device (`localStorage`). Use **Export** for backups.
- No "goal reached" notification. iOS web apps can't schedule local notifications. That would need a native app or a push server.
