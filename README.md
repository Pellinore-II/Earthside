# 🌿 Earthside Nursery Inventory

A mobile-first PWA for managing nursery plant inventory.

## Live App

Deploy to GitHub Pages and visit: `https://YOUR_USERNAME.github.io/earthside/`

## Deploy to GitHub Pages (step by step)

1. **Create a new GitHub repo** — go to github.com → New Repository
   - Name it: `earthside` (or anything you want)
   - Set to **Public**
   - Do NOT initialize with README (you already have files)
   - Click **Create repository**

2. **Upload the files** — on the repo page click **"uploading an existing file"**
   - Drag in all 5 files: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
   - Click **Commit changes**

3. **Enable GitHub Pages** — go to repo **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / root (`/`)
   - Click **Save**

4. **Wait ~2 minutes**, then visit: `https://YOUR_USERNAME.github.io/earthside/`

## Add to Home Screen (iOS Safari)

1. Open the live URL in Safari on iPhone
2. Tap the **Share** button (box with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add**

The app icon will appear on your home screen and open full-screen like a native app.

## Add to Home Screen (Android Chrome)

1. Open the live URL in Chrome
2. Tap the **⋮ menu** → **"Add to Home Screen"**
3. Tap **Add**

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — 266 plants, all UI |
| `manifest.json` | PWA metadata (name, icons, display mode) |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (home screen, 192×192) |
| `icon-512.png` | App icon (splash screen, 512×512) |
