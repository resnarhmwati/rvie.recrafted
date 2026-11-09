# RVie Recrafted — Astro

Editorial-style responsive landing page focused only on reworked ties (no preloved clothing section).

## Run locally
```bash
npm install
npm run dev
```
Open the local URL Astro prints (usually http://localhost:4321).

## Add your own assets
Place your logo and photos in `public/images/`:
- `logo.svg` — your RVie Recrafted logo (SVG preferred; PNG also works if you change the path)
- `hero.jpg` — hero editorial/model photo
- `bound.jpg` — product 01, Bound
- `model-02.jpg` — product 02
- `model-03.jpg` — product 03
- `model-04.jpg` — product 04

Image slots are intentional: replace these files with your own product photography. The product labels and descriptions are in `src/pages/index.astro`.

## Replace external links
In `src/pages/index.astro`, replace:
- `https://shopee.co.id/` with your shop or product Shopee URL
- `https://wa.me/6281234567890` with your WhatsApp link (country code, no plus or spaces)
- `https://www.tiktok.com/@yourusername` with your TikTok profile

## Build
```bash
npm run build
npm run preview
```
