
Vedant's Timetable - Static PWA
--------------------------------
Files:
 - index.html
 - manifest.json
 - service-worker.js
 - icon-192.png, icon-512.png

How to host (Vercel, Netlify, or any static host):
 1) Unzip the folder and deploy the folder root.
 2) On Vercel: `vercel deploy` or drag-and-drop to Vercel dashboard.
 3) After deployment open the site in your phone browser and tap "Add to Home Screen".
 4) The app works offline (service worker caches core files).

Notes:
 - This is a minimal PWA. Icons are placeholders.
 - If you want Play Store APK we can wrap this with Capacitor later.
