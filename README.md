# Stonybank Community Church website

Static site for Stonybank Community Church, 35 Stoney Bank Road, Glen Mills, PA. Hosted on GitHub Pages.

## Files
- `index.html` — the whole site (one page)
- `assets/chapel.jpg` — banner photo
- `assets/logo-mark.png` — header logo and podcast artwork
- `assets/carroll-family.jpg`, `assets/jim-diana.jpg` — pastor photos
- `assets/favicon-32.png`, `assets/apple-touch-icon.png` — browser and phone icons
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Still to fill in (search index.html for `[`)
- Pastor bio and welcome quote
- Announcements and upcoming events (in the `#news` section)
- Church email
- Contact form: create a free form at formspree.io and replace `YOUR_FORM_ID`

## Custom domain
To serve at www.stonybankchurch.com, add a `CNAME` file containing `www.stonybankchurch.com`, then point the domain's DNS at GitHub Pages.

## Sermon player
The player loads the latest episodes automatically from the church podcast (Apple Podcasts ID 1469152028). Nothing to update each week.
