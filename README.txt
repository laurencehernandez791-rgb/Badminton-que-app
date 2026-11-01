BADMINTON QUEUE & COURT MANAGER — OFFLINE EDITION

WHAT THIS DOES
- Responsive layout for phones, tablets, and computers.
- The main app uses browser local storage, so registration, queue, match, and payment records work offline after opening.
- Includes PWA files for installable app-like use and offline caching after the app is first loaded through a supported local web server or HTTPS website.
- Backup/restore and CSV export remain available.

IMPORTANT LIMITATION
Data is stored separately in each browser/device. This version does NOT automatically sync data between multiple devices. To keep records on another device, use Settings > Download Full Backup (JSON), transfer the file, then use Settings > Import Backup on the other device. Do not edit the same system on multiple devices expecting live shared data.

QUICKEST OFFLINE USE
1. Extract this ZIP.
2. Open index.html in a modern browser. The app itself works offline and stores data in that browser.
3. Keep using the same browser on that device. Do not clear browser site data unless you have a backup.

INSTALLABLE PWA MODE
For install prompts and reliable service-worker offline caching, the files must be served from HTTPS or localhost (service workers do not work when opening index.html directly as file://).
1. Upload the extracted folder to an HTTPS static host, or serve it on localhost.
2. Open the page once while online.
3. Use the browser's Install app / Add to Home Screen option.
4. After the first successful load, the app shell can open offline.

DATA SAFETY
- Use Settings > Download Full Backup (JSON) regularly.
- Store backups somewhere safe.
- Importing a backup replaces current data in that browser.
