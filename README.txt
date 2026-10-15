VETDOSE CALCULATOR BY DS — iPhone Home Screen Web App

CONTENTS
- index.html: your existing Dog & Cat calculator with embedded original logo and iOS/PWA setup
- manifest.json: web app metadata
- service-worker.js: offline cache for the app shell
- apple-touch-icon.png / icon-192.png / icon-512.png: generated from the embedded logo

IMPORTANT
This package is prepared, but it is not yet a live website. iPhone Home Screen installation and service-worker offline support require HTTPS hosting.

DEPLOY USING AN ANDROID PHONE (one possible route)
1. Extract this ZIP on your Android phone, or upload the ZIP through a static-site hosting provider that supports ZIP/direct asset uploads.
2. Create a static site and upload the CONTENTS of this folder (index.html, manifest.json, service-worker.js and all three PNG icons). The files must be at the site root, not inside an extra nested folder.
3. Open the HTTPS website URL on the iPhone in Safari.
4. Tap Share, then Add to Home Screen. If shown, enable Open as Web App, then tap Add.
5. Open it from the new Home Screen icon once while online; then test offline mode.

DOSE SAFETY
This calculator performs arithmetic using a dose rate you enter. It does NOT contain a verified automatic BSAVA drug-dose database. Check every drug, indication, route, interval, formulation, and dose with the full trusted monograph and a supervising veterinarian.
