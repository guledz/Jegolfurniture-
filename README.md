# Jegol Furniture — Website

Single-page showroom website for Jegol Furniture, Harar (open 24 hours).
Plain HTML + CSS, no build step, no dependencies except Google Fonts.

## Files

```
jegol/
├── index.html      # the whole site (HTML + CSS in one file)
├── README.md
└── images/         # showroom photos (keep this folder next to index.html)
```

## Run it

Double-click `index.html`. To publish, upload `index.html` and the `images/`
folder together to any static host (GitHub Pages, Netlify, Cloudflare Pages).

## Sections

Navbar · Hero · Shop by Category · Featured Collection · Showroom gallery ·
Store info (location, phone, hours) · Footer

## Photo map

| File | Used in |
|---|---|
| hero-bed.jpg | Hero |
| bedroom-white-gold.jpg | Category: Bedroom Sets |
| living-sofa.jpg | Category: Living Room |
| office-chair.jpg | Category: Office Furniture |
| kids-car-bed.jpg | Category: Kids' Furniture |
| vanity-hexagon.jpg | Featured: Hexagon LED Vanity |
| dresser-double-arch.jpg | Featured: Double-Arch Dresser |
| bed-black-white.jpg, bed-velvet-geometric.jpg, office-desk.jpg, office-panels.jpg | Showroom gallery |

To swap a photo, replace the file in `images/` with the same name (about
1200px wide, JPG), or change the `src` in `index.html`.

## Common edits

- **Phone / Telegram:** search `0982828233` and `t.me/jegolfurniture`.
- **Prices:** hidden for now. Featured cards show "On request" in `.feat__price`; the hero card line is in `.hero__card-price`.
- **Colours:** `:root` variables at the top of the CSS (`--navy`, `--gold`, ...).
- **Map:** the map card is a static illustration; "Get Directions" opens Google Maps for "Harar 6273 Jegol Furniture". Replace the query with the exact pin location.
- **Add a gallery item:** copy a `<figure>` inside `.gallery`.

## To do

- Add real Instagram / Facebook / TikTok links (icons removed until then).
- Add About, Delivery, Warranty, Privacy pages if wanted.
- Replace phone-screenshot crops with original photos for sharper images.
- Add `<meta property="og:image">` for nicer link previews on Telegram.
