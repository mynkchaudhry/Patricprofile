# Mayank Chaudhary — Portfolio

Brutalist AI engineer portfolio. Single static `index.html` — no build step.

## Local

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

### Vercel
```bash
npx vercel --prod
```

### Netlify
```bash
npx netlify deploy --prod --dir=.
```

### GitHub Pages
Push to a repo, enable Pages → Source: root of `main`.

### Any static host
Upload the folder. Entry: `index.html`.

## Files
- `index.html` — the site
- `favicon.svg` — mark
- `og-image.svg` — social preview (1200×630)
- `vercel.json` / `netlify.toml` — security headers + SVG caching
- `robots.txt` — allow all crawlers

## Contact form
Wired to Formspree `meqyeqlk`. Update the `action` on `#contact-form` to change endpoint.
