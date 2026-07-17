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

## Free GitHub PWA

1. Host this app on HTTPS using GitHub Pages.
2. Install it from the browser as a PWA.
3. Keep the app updated by pushing changes to this repository.

## Android Release Without Play Store

If you want Android distribution without paying the Google Play registration fee, use a GitHub Release or direct download page.

Recommended path:

1. Build an Android APK from the PWABuilder package already generated for this project.
2. Upload the APK to a GitHub Release.
3. Share the GitHub Releases page with users so they can download and install it manually.

This keeps the project free for end users and avoids Play Console registration costs.

## Access Requirement

- End users only need an internet connection and a modern browser/app runtime.
- Publishing to Google Play still requires a Google Play Console account and the one-time registration fee.
- GitHub Pages and GitHub Releases are free for public distribution.

## License

Released under the MIT License for free use, modification, and distribution.
