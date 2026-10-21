# LiftLog for iPhone (web app)

Installable web app (PWA) version of LiftLog for iPhone – no App Store needed.
Open the hosted page in Safari → Share → "Add to Home Screen".

- `index.html` – the whole app (no build step, no dependencies)
- `sw.js` – offline cache; bump `VERSION` after changing files
- Data is stored only in the browser on the device (localStorage); use Settings → Export backup.
- The rest timer rings while the app is open (iOS doesn't allow web apps to schedule
  local alarms); it keeps the screen awake during the rest.
