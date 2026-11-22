# Steady

A budgeting app that works out how much is safe to spend today, with a wait list for impulse buys. It installs on your phone like a normal app and works offline. Your data stays on your phone.

## Put it online (one time, free)

1. Create a free account at github.com.
2. Create a new **public** repository, for example `steady`.
3. Upload these files to it: `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` and the `icons` folder.
4. In the repository go to **Settings → Pages**. Under "Branch" choose `main` and `/ (root)`, then click **Save**.
5. About a minute later the app is live at `https://YOUR-USERNAME.github.io/steady/`.

## Install it on your phone

- **iPhone:** open the link in **Safari** → Share → **Add to Home Screen**.
- **Android:** open the link in **Chrome** → ⋮ menu → **Install app** (or **Add to Home screen**).

## Updating the app

Change the files, then change `VERSION` in `sw.js` (for example `steady-v1` to `steady-v2`) and upload again. Your phone gets the new version the next time you open the app. Sometimes it takes closing and reopening it once. Your budget data isn't affected.

## Backups

Your data is stored only on your phone. Use **Settings → Save backup file** now and then (email it to yourself or save it to Files or Google Drive). Use **Restore from a backup** to load it again on a new phone.
