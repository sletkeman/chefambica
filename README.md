# Chef Ambica

An editorial, single-page Astro chef portfolio designed for Cloudflare Pages.

## Develop locally

1. Install Node.js 22 or later.
2. Run `npm install` once.
3. Run `npm run dev` and open the local URL shown in the terminal.

Use `npm run build` to make the production site in `dist/`, and `npm run preview` to view that production build locally.

## Deploy with Cloudflare Workers Builds

Connect this GitHub repository to a Cloudflare Worker through the Cloudflare dashboard. Set the build command to `npm run build` and the deploy command to `npx wrangler deploy`.

Cloudflare will deploy the `main` branch to production and provide preview deployments for other branches. The `wrangler.jsonc` file tells Cloudflare to serve Astro's built `dist/` folder as static assets.

To deploy manually after authenticating with Cloudflare, run `npm run deploy`.

## Before publishing

- Replace the Unsplash placeholder photography in `index.html` with Ambica's photography.
- Replace `919000000000` in the WhatsApp link with Ambica's number in international format.
- Update the placeholder email address and all copy.

The current contact link opens WhatsApp; no backend or personal data collection is involved yet.
