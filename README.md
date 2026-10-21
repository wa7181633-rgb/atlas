# Atlas — Interactive Map Dashboard

A **single-file** product-grade map explorer. Dark UI, live filters, stats, favorites, detail popups — the kind of screen property, delivery, travel and local-service businesses pay for.

<p align="left">
  <a href="https://wa7181633-rgb.github.io/atlas/"><img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-Open-22d3ee?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <img alt="HTML" src="https://img.shields.io/badge/HTML-single%20file-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="No build" src="https://img.shields.io/badge/build-none-34d399?style=flat-square" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT-22d3ee?style=flat-square" />
</p>

**Live:** https://wa7181633-rgb.github.io/atlas/

---

## What’s new (advanced version)

| Feature | Description |
|---------|-------------|
| **16 places** | Expanded dataset with hours, phone, open/closed status |
| **Live stats** | Total places · average rating · open now |
| **Favorites** | Heart to save · persists in localStorage · “Saved” filter |
| **Richer cards** | Open/closed badge, distance, tags, rating |
| **Detail popup** | Hours, status, tags, Directions + Save |
| **My location** | One-click center on downtown |
| **Empty state** | Clear message when filters return nothing |
| **Toast feedback** | Save / remove / location actions |
| **Keyboard** | ⌘K / Ctrl+K focus search · Esc close popup |
| **Mobile sheet** | Collapsible bottom panel with grabber |

Still **zero dependencies**. One `index.html`. Open and run.

---

## Features

- Interactive SVG map with themed markers + pulse
- Live search + category filters (including Saved)
- Stat cards for headline numbers
- Detail popup with open status, hours, actions
- Favorites with localStorage
- Zoom controls + reset
- Fully responsive (desktop sidebar / mobile bottom sheet)
- Dark product UI with design tokens

---

## Quick start

```bash
git clone https://github.com/wa7181633-rgb/atlas
cd atlas
# just open the file
start index.html      # Windows
open index.html       # macOS
```

## Rebranding (5 minutes)

Colours live in `:root` at the top of the file.

Data is a plain array — swap it for your own records or fetch from an API.

## Good for

| Use case | Why it fits |
|----------|-------------|
| Property / real-estate | Map + filters + detail panel |
| Delivery / fleet | Stats + marker list |
| Travel & tours | Categories + location previews |
| Local directories | Search + categories, no backend |

## Deploy

**GitHub Pages:** Settings → Pages → Source `main` / `/root`  
**Netlify:** drag the folder onto https://app.netlify.com/drop  
**Cloudflare Pages:** connect the repo, no build command

## Need a custom version?

Connected to a real database, live GPS, or your own API? That’s exactly what I do.

→ [WhatsApp](https://wa.me/923122581354) · [Portfolio](https://wa7181633-rgb.github.io/farmoz-site/)

## License

MIT — free for personal and commercial use.
