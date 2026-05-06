# Captain's Choice LLC — Website Preview

A static marketing site for Captain's Choice LLC, a family-owned marine construction and general contracting company in Bridgman, Michigan.

**Live preview:** [captainschoice.momentumarketing.io](https://captainschoice.momentumarketing.io) *(set up after deploy)*

## What's here

A full multi-page site built as plain HTML/CSS/JS — no build step, no framework, no dependencies. Open `index.html` in any browser to view locally.

```
index.html              Homepage with cinematic video hero
permanent-docks.html    Service deep-dive
seasonal-docks.html     Service deep-dive
boat-lifts.html         Service deep-dive
seawalls.html           Service deep-dive
diving-services.html    Service deep-dive
renovations.html        Renovations & general construction
library-hotel.html      Featured restoration project page
hero-bg.mp4             Homepage hero video (9.5MB, H.264)
hero-poster.jpg         Video fallback poster
assets/
  ├── library/          Library Historic Hotel project photos
  ├── creatives/        Project portfolio photos
  ├── services/         Service-specific hero images
  └── logo/             Captain's Choice brand logo (navy + white variants)
```

## Stack

- Vanilla HTML5, CSS3 (custom properties), minimal JS
- Google Fonts: Fraunces (display) + Inter (body)
- Schema.org JSON-LD on every page for local SEO
- Fully responsive — desktop, tablet, mobile burger menu
- Single MP4 source for the hero (with auto-loop, muted, playsinline)

## Local development

No tooling required. Open `index.html` directly in a browser, or for full asset paths:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Deployed via Vercel as a static site. No build step needed — Vercel auto-detects the static HTML and serves the directory as-is.

## Brand notes

- Primary navy: `#1e3548`
- Accent (sandstone): `#b8a37c`
- Cream background: `#f8f5ee`
- Phone: (269) 422-7246
- Email: info@captainschoicellc.com
- Service area: SW Michigan (Berrien, Cass, Van Buren, St. Joseph counties) + NW Indiana

---

Built by [Momentum Marketing](https://momentummarketing.io).
