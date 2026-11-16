SPROUTS BUSINESS – Android Offline App

FILES
- index.html: complete app
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icon-192.png / icon-512.png: app icons

INSTALL ON ANDROID
This is an installable PWA, not a native APK and not currently published on Google Play.
1. Upload all files (keep the file names) to the ROOT of a GitHub repository.
2. In GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.
3. Wait for the HTTPS Pages URL.
4. Open that URL in Chrome on Android, allow it to load once while online.
5. Chrome menu ⋮ > Install app (or Add to Home screen).
6. Open installed app once online; then test in Airplane mode.

DATA & BACKUP
- Records are stored locally in this phone's browser/app storage (localStorage).
- No automatic cloud sync or multi-device sync.
- Use Backup > Download backup regularly. Keep JSON file somewhere safe.
- Before uninstalling/clearing Chrome data, export a backup.
- Monthly outstanding balance is calculated as all recorded deliveries/sales minus all recorded customer payments through the selected date.
- Profit shown is recorded sales minus recorded expenses; it is an estimate and excludes any costs not entered.

APP USE
1. Add each customer and their rate per kg.
2. Daily Entry: choose date/customer, enter quantity in grams, status and save.
3. Payments: record every amount received against the customer.
4. Expenses: record business costs.
5. Monthly Report: choose month to see sales, receipts, expenses, estimated profit, opening and closing receivables, and customer-wise balances.
6. Backup: download JSON and CSV.

IMPORTANT
For a truly native APK or Google Play release, the web app must be wrapped/built and signed through an Android build workflow (for example Capacitor/Android Studio). This ZIP does not itself contain an APK.
