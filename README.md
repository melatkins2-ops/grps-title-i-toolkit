# GRPS Title I Toolkit

Static site for GitHub Pages. No build step and no server code.

- `index.html` – landing page with the four tools and the 2026–27 templates
- `meeting/` – Annual Title I Meeting Builder
- `compact/` – Compact and Family Engagement Plan Builder
- `program/` – Title I Program Requirements Guide

## Publish on GitHub Pages
1. Create a repository (for example `grps-title-i-toolkit`) under your GitHub account.
2. Upload everything in this folder to the repository's main branch, keeping the folders.
3. Go to Settings → Pages, choose "Deploy from a branch," select `main` and `/ (root)`, and save.
4. The site is live in about a minute at `https://<account>.github.io/grps-title-i-toolkit/`.

## How it works
- Work saves in each person's browser on that device. Nothing is sent to a server.
- Word downloads are built in the browser with JSZip, loaded from cdnjs.
- Fonts load from Google Fonts. Template links open in Google Drive and need a GRPS account.
- The Translate and "Make it plainer" buttons work only inside Claude. They stay hidden here.

## Suggested commit message
Add GRPS Title I Toolkit (2026–27)

- Landing page linking three Title I tools and the 2026–27 templates
- Annual Title I Meeting Builder, Compact and Family Engagement Plan Builder,
  and Title I Program Requirements Guide
- Current entry and exit criteria (2026–27 state tests, College Board benchmarks)
- Links to updated English and Spanish agenda, compact and presentation templates
