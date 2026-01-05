# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Marketing website for **Uncorked**, an iOS wine collection app. Hosted on GitHub Pages at `afontcu.github.io/uncorked-mkt`.

## Structure

```
index.html       Landing page with app description and features
privacy.html     Privacy policy (required for App Store)
app-store-copy.md   Reference copy for App Store Connect submission
icon.png         App icon displayed on landing page
```

## Development

**No build step required** — this is a static HTML/CSS site. Open `index.html` directly in a browser or use any local server:

```bash
# Python
python3 -m http.server 8000

# npx
npx serve .
```

## Design Notes

- **Brand color**: `#722F37` (wine burgundy)
- **Font stack**: Apple system fonts (`-apple-system, BlinkMacSystemFont, ...`)
- Shared styling between pages (container, typography, footer) — keep consistent
- Privacy badge and "Made in Barcelona" footer appear on both pages

## Deployment

Push to `main` branch → GitHub Pages auto-deploys.

Live URLs:
- Landing: https://afontcu.github.io/uncorked-mkt/
- Privacy: https://afontcu.github.io/uncorked-mkt/privacy.html
