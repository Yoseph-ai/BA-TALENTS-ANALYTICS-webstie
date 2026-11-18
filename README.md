# BA Talent Search & Analytics website

Static single-file site. `index.html` holds all three views (#home, #talent-pool, #privacy).

## Before going live
- Set `FORM_URL` (Google Form embed) and optionally `BOOKING_URL` in the script at the foot of index.html.
- Replace `https://www.yourdomain.com/` in the canonical tag.
- Add og:image (1200x630) and favicon.
- Add GA4 only behind a consent banner.

## Deploy
Import this repo in Vercel. Framework preset: Other. No build command, output directory: root.
Set the www domain as primary in Vercel > Domains so the apex redirects to it. HTTPS is automatic.
