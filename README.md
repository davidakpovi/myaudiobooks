# HTL Audiobook Landing (GitHub Pages)

This repository hosts the tracking/redirect landing page for the audiobook
**"How To Launch A Successful Print-On-Demand Business"**.

## Quick Deploy (GitHub UI)
1. Create a new repo (public): `htl-landing` (or any name).
2. Click **Add file → Upload files** and upload:
   - `index.html`
   - `404.html` (optional)
   - `README.md` (this file)
3. Go to **Settings → Pages**.
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` (or `master`) and **/ (root)** folder
   - Save.
4. Wait ~1–2 minutes until GitHub shows a green banner with your site URL.
   - It will look like: `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Note on URLs
- The page is served at the **repository** URL, NOT your user root unless your repo is named `YOUR-USERNAME.github.io`.
- If the repo is named `YOUR-USERNAME.github.io`, the site root is: `https://YOUR-USERNAME.github.io/`

## Common 404 causes
- No `index.html` at the repo root on the published branch/folder.
- GitHub Pages not enabled or wrong branch/folder selected.
- Case mismatch in file name (`Index.html` ≠ `index.html`).

## Customization
Open `index.html` and update these constants with your product URLs:

```js
const APPLE_URL = "https://books.apple.com/your-product-link";
const KOBO_URL  = "https://www.kobo.com/your-product-link";
```

(Optional) add your GA4 snippet after the GA4 comment in `<head>`.
