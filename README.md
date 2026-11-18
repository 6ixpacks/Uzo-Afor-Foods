# Uzo-Afo website (static, no build step)

Files: `index.html` (whole site), `assets/` (WebP photos, favicon), `robots.txt`.

## Host it
- **Netlify (easiest):** app.netlify.com/drop, then drag this whole folder in. Add your domain under Domain settings.
- **Vercel / Cloudflare Pages / GitHub Pages:** push the folder to a repo and deploy it as a static site (no build command, publish directory = root).
- **cPanel / shared hosting:** upload everything inside this folder to `public_html`.
It also works by double-clicking `index.html`.

## Edit before launch (search for these in index.html)
- `WHATSAPP_NUMBER`: the restaurant's number, international format, no +.
- `MENU_ITEMS`: names, prices (all prices are placeholders), descriptions, photos.
- Bulk fufu: price per wrap (700), `minQty: 10`, `step: 5` in the `bulk-fufu` item.
- `YOUR-DOMAIN.com`: replace with the real domain (og:image and JSON-LD).
- Social icon links in the footer currently point to instagram.com / x.com / facebook.com.
- Confirm these claims are true, or remove them: table reservations, parking, island/mainland delivery, complimentary packaging, "firewood" cooking.
- Replace the stock-looking photos with the restaurant's own (assets/img/*.webp, about 800px wide).
