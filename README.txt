AttendEase PWA files

Upload these files/folders into the ROOT of your GitHub repository:
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

Your current index.html already links to ./manifest.json, uses the icon paths above,
and registers ./service-worker.js. Do not replace index.html.

After committing:
1. Wait for GitHub Pages to publish.
2. Open https://himatirumani-debug.github.io/AttendEASE/ in Chrome.
3. Refresh the page, then close and reopen the tab.
4. Open Chrome menu (three dots) and look for Install app.
5. If it still does not appear, clear the site's cached data or wait a little and retry.

Note: Chrome decides when to show installation. The files meet the common PWA
manifest/service-worker setup, but the exact menu wording and availability depend
on the browser version and its installability checks.
