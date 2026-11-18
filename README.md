# NMapUI website

The marketing site for NMapUI, a vulnerability scanning tool. This repo holds only the website, not the app.

**Live site:** https://techmore.github.io/TM-NMapUI-www/

## Run locally

The site is plain HTML with no build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

GitHub Pages serves the root of `main`.

## Layout

| Path | What it is |
|---|---|
| `index.html` | Landing page: overview, setup, sample reports, pricing |
| `scanner-pricing.html` | Vulnerability scanner pricing comparison |
| `recommended-tools.html` | Recommended network tools with pricing |
| `screenshots/` | App screenshots used on the pages |

Part of [Techmore](https://techmore.github.io/pages/repos/).
