LANCE PHOTO v0.4 — INSTALLABLE PWA

WHAT THIS CHANGES
- Lance Photo now has a web-app manifest.
- It can be installed to the home screen when served over HTTPS.
- It launches in its own standalone app window.
- A service worker caches the app for offline use after the first successful load.
- The cache is versioned so future releases can replace the old cached app.

IMPORTANT
Opening index.html directly from the Downloads/Files app is still useful for testing the editor, but Android browsers do not allow a true installable PWA/service worker from a local file:// address.

TO INSTALL IT LIKE A NORMAL APP
The folder must be hosted on an HTTPS website. Once hosted:
1. Open its HTTPS address in Samsung Internet or Chrome.
2. Use the browser's Install/Add to Home screen option (or the in-app Install button when offered).
3. Lance Photo will appear as an app icon and open standalone.

FUTURE UPDATES
Keep the same hosted address. Replace the hosted files with the new Lance Photo release. The service worker/cache version is changed with releases so the installed app can receive the newer build.

This package contains the full v0.3 editor plus the v0.4 PWA/install/update layer.
