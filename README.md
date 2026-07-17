# Weather.html

Mobile-friendly weather web app using open data APIs and explicit user-permission flows.

## Features

- Local digital clock with automatic timezone detection
- Current weather data (Open-Meteo)
- Map display and marker (Leaflet + OpenStreetMap)
- Optional nearby places and place photos with graceful fallback behavior
- Live refresh every 2.5 minutes

## File

- `Weather.html`

## PWA + App Store Readiness

This project now includes:

- `manifest.webmanifest`
- `sw.js` (service worker for offline shell caching)
- `icons/icon-192.svg`
- `icons/icon-512.svg`

## Publish As Free Google Play App

1. Host this app on HTTPS (GitHub Pages, Azure Static Web Apps, or similar).
2. Verify the hosted URL loads `Weather.html` and `manifest.webmanifest` correctly.
3. Open Microsoft PWABuilder: https://www.pwabuilder.com
4. Enter your hosted app URL and generate an Android package (TWA).
5. Create or use a Google Play Console account.
6. Upload the generated Android App Bundle (`.aab`) and publish as a free app.

## Access Requirement

- End users only need an internet connection and a modern browser/app runtime.
- Publishing requires a Google account (Play Console).
- Microsoft account is optional if you use Microsoft hosting/services or PWABuilder workflows.

## License

Released under the MIT License for free use, modification, and distribution.
