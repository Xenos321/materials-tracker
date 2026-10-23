# Anime Zero — Material Farming Tracker

A free static website for tracking Anime Zero evolution materials. **No account, backend, Excel, or macros required.**

## Features
- Add, rename, or delete any material; edit current and required counts.
- Enter new drops and press **Add** to accumulate them permanently.
- Automatic remaining counts, progress bars, and completion totals.
- Search and filter materials.
- Saved per person in their browser using `localStorage`.
- Export and import JSON backups to move between devices.
- Responsive for phones and desktops.

## Publish on GitHub Pages
1. Create a **public GitHub repository**, e.g. `anime-zero-material-tracker`.
2. Upload **index.html**, **styles.css**, and **app.js** to the root of the repository, then commit.
3. In the repository open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then click **Save**.
6. Your site should appear at `https://YOUR_USERNAME.github.io/anime-zero-material-tracker/` after GitHub completes deployment.

## For clan members
Open the GitHub Pages link and enter your own materials. Your browser stores only *your* progress, on *that specific device/browser*. Everyone can share the same link without sharing their numbers. If you clear site data, use another browser, or change phones, progress **will not sync**. Use **Export backup** and **Import backup** to transfer it.

## Run locally
Open `index.html` in your browser. To test with a local development server, run `python -m http.server 8000` in the project directory and visit `http://localhost:8000`.

## Project structure
- `index.html` — page and dialogs
- `styles.css` — responsive styling
- `app.js` — material tracking and browser storage

This is an unofficial fan project, not affiliated with Roblox or the Anime Zero developers.
