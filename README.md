# Atlas — interactive map dashboard template

A **single-file** map dashboard you can rebrand in an afternoon. Dark UI, live filtering, stat cards and a detail panel — the kind of screen property, delivery, travel and local-service businesses pay for.

<p align="left">
  <a href="https://wa7181633-rgb.github.io/atlas/"><img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-Open-22d3ee?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <img alt="HTML" src="https://img.shields.io/badge/HTML-single%20file-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="No build" src="https://img.shields.io/badge/build-none-34d399?style=flat-square" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT-22d3ee?style=flat-square" />
</p>

**Live:** https://wa7181633-rgb.github.io/atlas/

## What it is

One `index.html` containing everything: layout, styles and logic. Open it in a browser and it runs. No npm, no bundler, no framework, no API key.

## Features

- **Interactive map area** with themed markers and hover states
- **Live search + category filters** that update results instantly
- **Stat cards** for headline numbers (total, active, average)
- **Detail side panel** for the selected item
- **Dark, product-grade UI** with a proper design-token palette (`--accent`, `--panel`, `--radius`)
- **Responsive** down to mobile widths
- **Zero dependencies** — deploys free on GitHub Pages, Netlify or Cloudflare Pages

## Quick start

```bash
git clone https://github.com/wa7181633-rgb/atlas
cd atlas
# just open the file
start index.html      # Windows
open index.html       # macOS
```

## Rebranding (5 minutes)

All colours sit in one block at the top of the file:

```css
:root{
  --bg:#070d18;
  --panel:rgba(13,20,36,.86);
  --accent:#22d3ee;    /* primary */
  --accent-2:#a78bfa;  /* secondary */
  --green:#34d399;
}
```

Data lives in a plain array — swap it for your own records or fetch it from an API:

```js
const places = [
  { name: 'Sample location', category: 'retail', lat: 24.86, lng: 67.01 },
];
```

## Good for

| Use case | Why it fits |
|---|---|
| Property / real-estate listings | Map + filters + detail panel is the standard pattern |
| Delivery or fleet tracking | Stat cards + marker list |
| Travel and tour operators | Category filters and location previews |
| Local directories | Search + categories, no backend needed |

## Deploy

**GitHub Pages:** push the repo → Settings → Pages → Source `main` / `/root`.
**Netlify:** drag the folder onto https://app.netlify.com/drop.
**Cloudflare Pages:** connect the repo, no build command, output directory `/`.

## Need a custom version?

Want this connected to a real database, live GPS, or your own API? That’s exactly what I do.

→ See my profile or message me on [WhatsApp](https://wa.me/923122581354)

## License

MIT — free for personal and commercial use.
