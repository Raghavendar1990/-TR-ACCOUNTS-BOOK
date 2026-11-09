TR-ACCOUNTS-BOOK app project. Dark Navy + Neon Teal/Cyan, person ledgers, PDF statements, Cash/UPI/Card, Credit/Debit, local storage, PIN and JSON backup. GitHub Actions workflow builds debug APK.

## Offline / Privacy
TR-ACCOUNTS-BOOK stores transactions, persons, business investments, and settings locally in the app's WebView LocalStorage. The build workflow removes Android's INTERNET permission; the APK cannot connect to a server or send app data online. Keep JSON backups somewhere safe because clearing app data/uninstalling can erase local records.
