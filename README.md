# PlaceTrack
Installable web app (PWA) to track job applications and follow a fixed daily prep schedule.

## Features
- Application pipeline with deadlines and stats
- Daily aptitude and coding schedule with reminders and streaks
- Works offline, installable on Android, iOS and desktop
- Calendar (.ics) export for alerts when the app is closed

## Run locally
    python3 -m http.server 8000
Open http://localhost:8000 (service workers need http://localhost or https).

## Deploy free
Push this folder to GitHub, then Settings > Pages > deploy from main branch.
Open the live URL on your phone and choose "Install app" or "Add to Home Screen".

## Tech
HTML5, CSS3, JavaScript (ES6), Service Worker, Web App Manifest, Notification API, localStorage.
