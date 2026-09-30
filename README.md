# VIP Recon — App Package

Your POS reconciliation tool, packaged as an installable app.

## Option A — Quick use (no install)
Unzip and open **index.html** in any browser. All data stays on the device
(localStorage). Works offline.

## Option B — Install on phone (PWA)
1. Upload this folder to any static host (GitHub Pages, Netlify, Vercel, or your own server).
2. Open the URL in Chrome/Safari on the phone.
3. Tap **Add to Home Screen** / **Install app** → it runs fullscreen like a native app,
   with offline support via the service worker.

## Option C — Desktop app (Windows / Mac / Linux)
Requires Node.js installed:
```
npm install
npm start        # run directly
npm run dist     # build installers into ./dist
```

## Option D — Android APK
Wrap this folder with a free PWA-to-APK tool (e.g. WebIntoApp, Median.co,
or Bubblewrap/TWA for Play Store). Point it at your hosted URL from Option B.

## Notes
- Unlock screen: tap the word "user's" three times quickly, then enter code **123**.
- Export/Import (JSON) in History lets you move records between devices.
