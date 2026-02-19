# CardMaxx – Credit Card Benefits Manager

A **Progressive Web App (PWA)** for tracking, optimizing, and maximizing your credit card benefits, credits, and rewards.

## Features

- 📇 **My Cards** — Add and manage your credit cards with earning rates and benefits
- ✅ **Benefits Checklist** — Annual/semi-annual/monthly/quarterly benefit tracker with fold-by-month grouping
- 🔍 **Best Card Search** — Find the best card for any spend category, ranked by effective cpp
- ⚙️ **Settings** — Customize point valuations (MR, UR, TYP, etc. in cents-per-point)

## Default Cards Included

| Card | Issuer | Points |
|------|--------|--------|
| Amex Delta Gold | American Express | SkyMiles |
| Hawaiian Airlines Mastercard | Barclays | HawaiianMiles |
| Chase IHG Premier | Chase | IHG Points |
| Chase Hyatt | Chase | Hyatt Points |
| Chase Freedom Flex | Chase | UR |
| Chase Ritz-Carlton Visa | Chase | Bonvoy |
| Discover it Cash Back | Discover | Cash |

## Setup & Deploy

### Local Development
Just open `index.html` in a browser — no build step required.

### GitHub Pages Deployment
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source: main branch / root**
3. Your app will be live at `https://yourusername.github.io/cardmaxx/`

The PWA will be installable on iOS (Safari → Share → Add to Home Screen) and Android (Chrome → Install App).

### File Structure
```
cardmaxx/
├── index.html       ← Main app (single file)
├── manifest.json    ← PWA manifest
├── sw.js            ← Service Worker (offline support)
├── icons/           ← Place 192x192 and 512x512 PNG icons here
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

### Icons
Generate icons at [realfavicongenerator.net](https://realfavicongenerator.net) or any PWA icon generator, then place them in the `icons/` folder.

## Data Storage
All data is stored in **localStorage** — nothing leaves your device.

Use **Export Data** in Settings to back up your data as JSON, and **Import Data** to restore it.

## License
MIT
