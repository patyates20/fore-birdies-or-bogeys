# Fore Birdies or Bogeys

The website for [forebirdiesorbogeys.com](https://forebirdiesorbogeys.com) — couples golf, resorts, and the long game. Pat & Sandy Yates, married since 1990.

Static HTML. No build step, no dependencies. Open `index.html` in a browser and it works.

## Pages

| File | What it is |
| --- | --- |
| `index.html` | Home — hero, our story, the trips grid, the 2026–27 route, partner pitch, newsletter |
| `poipu-bay.html` | Poipu Bay, Kauai |
| `tpc-sawgrass.html` | TPC Sawgrass, Ponte Vedra Beach — May 2012 |
| `valhalla.html` | Valhalla, Louisville |
| `bali-hai.html` | Bali Hai, Las Vegas — 2013 and since |
| `las-vegas-country-club.html` | Las Vegas Country Club — 2021 |
| `waikoloa.html` | Waikoloa, Big Island — 2005 |
| `wellen-park.html` | Wellen Park, Venice FL — member-guest |
| `ranch-at-laguna-beach.html` | The Ranch at Laguna Beach — short course |
| `turnberry-isle.html` | Turnberry Isle, Miami |
| `tour-championship-2021.html` | Tour Championship, East Lake |
| `brand-kit.html` | Logo system, color, type, voice, imagery rules |
| `404.html` | Lost ball |

## Brand

| Role | Hex |
| --- | --- |
| Fairway Green | `#14462F` |
| Dusk Navy | `#16233F` |
| Golden Hour | `#DFA43C` |
| Ember | `#C9603A` |
| Clubhouse Cream | `#F7EEDD` |

Type: **Kaushan Script** for the name, star ratings and punchlines. **Archivo** for headlines, body and labels. Never set the script below 18px.

Voice: funny first, honest second, sweet at the end — once.

## Adding a new trip

1. Copy an existing course page (`poipu-bay.html` is the fullest example).
2. Drop resized photos into `images/` (max 1800px on the long edge, JPEG ~82% quality).
3. Update the `<title>`, description and Open Graph tags in `<head>`.
4. Add a card to the trips grid in `index.html` and a `<url>` entry to `sitemap.xml`.

## Forms

The newsletter and partner forms currently open the visitor's mail client addressed to `hello@forebirdiesorbogeys.com`. Once a real form provider is in place, swap the `data-mailto` handling at the bottom of each page for that provider's endpoint.

## Hosting

Served by GitHub Pages from the `main` branch. `CNAME` points the site at `forebirdiesorbogeys.com`; `.nojekyll` stops Jekyll from touching the files.
