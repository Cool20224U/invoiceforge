# 📇 LeadClean — Scraper Data Cleaner & Normalizer

A zero-dependency, single-file tool that turns messy scraped leads into clean, deduplicated, validated contact lists. Paste data from any scraper (2GIS, Google Maps, directories), get a clean CSV out. **100% client-side — nothing uploads, so there are no data-residency worries for buyers.**

## Why this sells

- **Same buyer, second product**: anyone running scrapers (lead-gen agencies, recruiters, real-estate agents) drowns in dirty data. Lead-cleaning SaaS charges $30–100/month; this costs them once.
- **The privacy claim is the pitch**: "your leads never leave your device" — impossible for cloud competitors to match.
- **Zero infrastructure**: one `index.html`, free hosting, nothing to maintain.

## Features

- **Auto-detects delimiter** (CSV, TSV, semicolon, pipe) and **auto-classifies columns** (email / phone / name / company) by content — no setup
- **Deduplication** by email, phone, or both
- **Email validation** with syntax checks, trimmed & lowercased
- **Phone normalization** to international format (+971 UAE, +1, +44, +91, +49, +61)
- **Name normalization** (title-case, whitespace collapse) and company-name detection
- **Live stats**: rows in / valid / duplicates removed / flagged invalid / rows out
- **Export** clean CSV via copy or download — duplicates and flagged rows handled your way (keep & flag, or drop)
- Everything in-browser; works offline

## Run it

Open `index.html` in any modern browser. Host free via [Netlify Drop](https://app.netlify.com/drop) or GitHub Pages.

## Suggested pricing

| Tier | Price |
|---|---|
| LeadClean alone | $29 |
| Pro resale/white-label license | $79 |

## License

MIT — see the repository's [LICENSE](../LICENSE).
