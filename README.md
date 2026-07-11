# Scholars Space — v1 (Homepage)

A premium, academic-styled homepage for Scholars Space, built with plain HTML, CSS and JavaScript only — no frameworks, no backend, no login.

## What's included
- `index.html` — the homepage
- `css/style.css` — full design system (navy / white / gold)
- `js/main.js` — mobile nav, welcome popup + Local Storage name capture, toast notifications, search UI
- `netlify.toml` — ready-to-deploy Netlify config

## Features on this page
- Hero section with headline, stats and a search bar (UI only for now)
- Welcome popup asking for the visitor's first name, saved to `localStorage`
  - Returning visitors see a "Welcome back, [Name] 👋" toast instead of the popup
- Four quick-access cards: University Explorer, Find My Chances, Student Services, Daily Quiz
  (these link to pages that will be built in the next version)
- Floating WhatsApp button
- Full responsive footer

## Deploying to Netlify
**Option A — drag & drop**
1. Unzip this folder.
2. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
3. Drag the unzipped folder onto the page. Done — your site is live.

**Option B — Netlify CLI**
```
npm install -g netlify-cli   # (only if you don't already have it)
cd scholars-space
netlify deploy --prod
```

No build step is required — this is a static site.

## Notes
- Update the WhatsApp number in `index.html` (search for `wa.me`) with your real number.
- Update social links and contact details in the footer.
- Nav links to other pages (University Explorer, Find My Chances, etc.) are already in place and will work automatically once those pages are added in the next version.
