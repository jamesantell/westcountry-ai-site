# Westcountry AI

The marketing website for **Westcountry AI** — practical AI consulting for SMEs in the South West of England.

Live at [westcountry.ai](https://westcountry.ai).

## Stack

Static HTML and CSS, no build step. Deployed to Cloudflare Pages with auto-deploy from this repo's `main` branch.

## Files

- `index.html` — Home
- `opportunities-survey.html` — The AI Opportunities Survey (product page)
- `contact.html` — Contact
- `styles.css` — Single CSS file with palette, type, components
- `wyvern.svg` — Logo and favicon

## Local preview

Open `index.html` directly in a browser. For live reload during edits:

```powershell
python -m http.server 8000
```

Then visit http://localhost:8000

## Design tokens

All in `styles.css` under `:root`:

- Background: warm off-white `#FAF7F2`
- Primary: deep eucalyptus green `#2D5040`
- Accent: burnt ochre `#C25B1E`
- Headings: Lora (Google Fonts)
- Body: Inter (Google Fonts)
- Logo: wordmark "Westcountry AI" with the wyvern icon (Wessex heraldic beast)

## Editing copy

Each page is a self-contained HTML file. Find the text, edit it, save, refresh the browser. No build step.

For changes that affect every page (header, footer, nav), edit each HTML file individually.

## Deploy

Push to `main` → Cloudflare Pages auto-builds and publishes within ~30 seconds.
