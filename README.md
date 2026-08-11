# LNRO Intake — iPhone PWA

This folder is a deployment-ready Progressive Web App (PWA).

## Install on iPhone
1. Host these files on an HTTPS web host (GitHub Pages, Netlify, Cloudflare Pages, or your company's web server).
2. Open the HTTPS address in Safari on the iPhone.
3. Tap **Share** → **Add to Home Screen** → **Add**.
4. Launch **LNRO Intake** from the Home Screen. It will open in standalone app mode.

## Files
- `index.html` — optimized LNRO Intake app
- `manifest.webmanifest` — PWA app metadata
- `sw.js` — service worker for app-shell/offline caching
- `icons/` — Home Screen icons

The form continues to use its existing browser storage and external libraries. The service worker caches the app shell and resources after the first successful visit.
