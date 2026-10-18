# Aya Portfolio

A minimalist academic portfolio built with Astro.

## Run locally

1. Install Node.js (LTS version recommended).
2. In this folder, run:

```bash
npm install
npm run dev
```

Astro will print a local URL, usually `http://localhost:4321`.

## What to edit

Most of the site is in:

- `src/pages/index.astro` — text, publications, links, sections
- `src/styles/global.css` — typography, spacing, colors
- `astro.config.mjs` — replace `https://your-domain.com` once you own a domain

## Before publishing

Replace these placeholders:

- Email address
- Google Scholar link
- GitHub link
- LinkedIn link
- CV link
- Publication titles/details
- Recent-news entries

## Publish for free

The easiest options are Vercel, Netlify, or GitHub Pages. Connect the repository and use `npm run build` as the build command. Astro outputs the static site to `dist/`.

## Add your profile photo

The homepage already includes a profile-photo slot. To use your own picture:

1. Put your image in the `public` folder, for example as `public/profile.jpg`.
2. In `src/pages/index.astro`, change:

```html
<img src="/profile-placeholder.svg" ... />
```

to:

```html
<img src="/profile.jpg" alt="Ayatallah (Aya) Elakhras" />
```

A square or portrait photo works best; the layout crops it neatly on desktop and mobile.
