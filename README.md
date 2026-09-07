# Banner Forge

Static site: `index.html` plus assets. No build step, no server code.

## Deploy
- **GitHub Pages / Netlify / Vercel / Cloudflare Pages:** upload this folder as-is.
- Before publishing, replace `https://bannerforge.app/` with your real domain in
  `index.html` (canonical, og:url, og:image, twitter:image, JSON-LD), `robots.txt` and `sitemap.xml`.
- Update the "Source" link in the footer or remove it.

## After deploy
1. Google Search Console → add the domain → submit `https://your-domain/sitemap.xml`.
2. Bing Webmaster Tools → same.
3. Check https://your-domain/robots.txt is reachable.

## Files
- `index.html` – the app (SEO meta, Open Graph, JSON-LD included)
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `icon-512.png`, `og-image.png` – icons and share image
- `site.webmanifest` – PWA / install metadata
- `robots.txt`, `sitemap.xml` – crawler files
