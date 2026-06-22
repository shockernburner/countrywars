# World History Country Explorer — PWA

This folder is ready for GitHub Pages.

## Publish

1. Upload **all files and the `icons` folder** to the root of your GitHub Pages repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your publishing branch (usually `main`) and `/ (root)`, then save.
5. Open the HTTPS Pages URL once while online. The app will cache itself for offline use.

The manifest and service-worker paths are relative, so the app works both at `username.github.io` and `username.github.io/repository-name/`.

## Install on Android

Open the Pages URL in Chrome. Use the in-app **Install app** button when shown, or Chrome menu → **Add to Home screen / Install app**.

## Install on iPad

Open the Pages URL in Safari. Tap **Share** → **Add to Home Screen** → **Add**.

## Updating

Replace files in the repository. For a guaranteed cache refresh after a substantial release, change `CACHE_NAME` in `service-worker.js` (for example, from `v1.0.0` to `v1.0.1`). The app shows a refresh notice when a new service worker is ready.

## Important

The news checker only surfaces possible conflict mentions. It does not automatically modify the historical dataset.
