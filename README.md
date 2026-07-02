# NoBuy — public web pages (GitHub Pages)

These are the four public pages your App Store / Google Play listing needs, ready to host **for free** on GitHub Pages.

## What's here

```
site/
├── index.html          → https://melihtoksari.github.io/nobuy/          (Marketing URL)
├── privacy/index.html  → https://melihtoksari.github.io/nobuy/privacy   (Privacy Policy URL)
├── terms/index.html    → https://melihtoksari.github.io/nobuy/terms     (Terms of Use)
├── support/index.html  → https://melihtoksari.github.io/nobuy/support   (Support URL)
└── .nojekyll           (tells GitHub Pages to serve the files as-is)
```

Each page is a single self-contained HTML file (no build step, light + dark aware). The folder-per-page layout is what produces the clean `/privacy` URLs — no `.html` needed.

## Deploy in ~5 minutes

1. Create a GitHub account (if you don't have one) at github.com. Your username is **`MelihTOKSARI`** — GitHub Pages lowercases it in the URL, which is why the pages live at `melihtoksari.github.io` (not `MelihTOKSARI.github.io`). Both spellings work in the browser; the URLs above use the canonical lowercase form to paste into the stores.
2. Create a new **public** repository named exactly **`nobuy`**.
3. Upload the **contents of this `site/` folder** to the repo root (drag the files into GitHub's "Add file → Upload files", or push with git). The repo root should directly contain `index.html`, the `privacy/` `terms/` `support/` folders, and `.nojekyll`.
4. In the repo: **Settings → Pages**. Under "Build and deployment", set **Source = Deploy from a branch**, **Branch = `main`**, **folder = `/ (root)`**, then Save.
5. Wait 1–2 minutes. Your pages go live at `https://melihtoksari.github.io/nobuy/`.
6. Open all four URLs in a browser to confirm they load, then paste them into App Store Connect / Google Play Console.

## Before you submit — checklist

- [ ] All four URLs load.
- [ ] Governing law in Terms is set to US / Delaware (change if you want a different state or country).
- [x] Privacy Policy reflects **no analytics / no data collection** (v1.0). App Store privacy label = **"Data Not Collected"**.
- [ ] Contact email `smtoksari@gmail.com` is correct everywhere.
- [ ] GitHub repo is named exactly `nobuy` and set to **public**, so the URLs resolve.

## Updating later

Edit the HTML, commit/upload again — GitHub Pages redeploys automatically in a minute or two. Bump the "Last updated" date at the top of Privacy/Terms when you make material changes.
