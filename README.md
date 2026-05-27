# Criterion Bids — Website

Static website for [Criterion Bids](https://criterionbids.com), hosted on GitHub Pages.

## About

Criterion Bids provides structured tender drafting support for SMEs bidding on UK public sector contracts, specialising in cleaning, facilities management, and soft FM sectors.

## File Structure

```
criterion-bids/
├── index.html          # Main one-page website
├── 404.html            # Custom 404 error page
├── sitemap.xml         # XML sitemap for search engines
├── robots.txt          # Search engine crawl directives
├── llms.txt            # Machine-readable summary for LLM crawlers
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── assets/
    ├── criterion-logo.png    # Full horizontal logo
    └── criterion-emblem.png  # Icon/emblem only
```

## Deployment

This site is deployed via **GitHub Pages** from the `main` branch root.

### Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `Deploy from a branch` → `main` → `/ (root)`
4. GitHub Pages will serve the site at `https://<username>.github.io/<repo>` or your custom domain

### Custom Domain

To use `criterionbids.com`:

1. Add a `CNAME` file to the repo root containing:
   ```
   criterionbids.com
   ```
2. In your DNS provider, add:
   - `A` records pointing to GitHub Pages IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Or a `CNAME` record: `www` → `<username>.github.io`
3. Enable **Enforce HTTPS** in GitHub Pages settings once DNS propagates

## SEO

- Schema.org `ProfessionalService` structured data
- Open Graph and Twitter Card meta tags
- XML sitemap at `/sitemap.xml`
- `robots.txt` at `/robots.txt`
- `llms.txt` for LLM/AI crawler discovery

## Fonts

Loaded from Google Fonts:
- **Bebas Neue** — display headings
- **Outfit** — body text

## Colours

| Token | Hex | Usage |
|-------|-----|-------|
| Navy | `#1C3A6E` | Primary brand, backgrounds |
| Navy Dark | `#122951` | Footer, dark sections |
| Orange | `#F47920` | Accent, CTAs, highlights |
| White | `#FFFFFF` | Backgrounds, text on dark |

## Contact

criterion.drafting@gmail.com
