# Expense Tracker – Android APK via GitHub

1. Create a new empty repository on github.com (e.g. `expense-tracker`).
2. Upload all files from this folder (keep the `.github/workflows` folder).
   Easiest: repository page > Add file > Upload files > drag everything > Commit.
3. Open the **Actions** tab. The "Build Android APK" workflow starts automatically
   (or click it > Run workflow). It takes about 5-8 minutes.
4. When it finishes, open the run and download **ExpenseTracker-APK** from Artifacts.
5. Unzip it, copy `app-debug.apk` to your phone, open it, and allow
   "Install unknown apps" when asked.

To change the app, edit `www/index.html` and commit; a new APK is built each time.
App name and ID: `capacitor.config.json`.
