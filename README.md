# perkbridge.github.io

Landing site for the **PerkBridge** GitHub organization — open-source projects built on Solana infrastructure.

🔗 Org: https://github.com/perkbridge

## Structure

```
index.html               # the whole site (single file, no build step)
assets/logo.png          # original PB mark on white (used for social/OG image)
assets/logo-mark-t.png   # same mark, background removed (nav, hero, favicon)
```

## Publishing with GitHub Pages

1. Push this repo to `https://github.com/perkbridge/perkbridge.github.io`.
2. In the repo: **Settings → Pages → Build and deployment**.
3. Set **Source = Deploy from a branch**, **Branch = `main` / `root`**, then Save.
4. The site goes live at **https://perkbridge.github.io** within a minute or two.

## Editing

- All content, styling, and the project list live in `index.html`.
- The design is a light, monochrome theme built around the logo's charcoal — no third-party colors.
- Update the three cards under the **Projects** section as repos ship —
  point each `href` at the specific repository URL, and set each badge to
  `open` (Open Source) or `closed` (Proprietary).
