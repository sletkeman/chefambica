# Chef Ambica

An editorial, single-page Astro chef portfolio designed for Cloudflare Pages.

## Develop locally

1. Install Node.js 22 or later.
2. Run `npm install` once.
3. Run `npm run dev` and open the local URL shown in the terminal.

Use `npm run build` to make the production site in `dist/`, and `npm run preview` to view that production build locally.

## Deploy with Cloudflare Pages

Connect this GitHub repository to a Cloudflare Pages project. Set the build command to `npm run build` and the output directory to `dist`.

Cloudflare will deploy the `main` branch to production and provide preview URLs for pull requests. The GitHub Action in `.github/workflows/build.yml` independently verifies that the site builds, but does not deploy it.

## Before publishing

- Replace the Unsplash placeholder photography in `index.html` with Ambica's photography.
- Replace `919000000000` in the WhatsApp link with Ambica's number in international format.
- Update the placeholder email address and all copy.

The current contact link opens WhatsApp; no backend or personal data collection is involved yet.
