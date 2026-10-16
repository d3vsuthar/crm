# CRM portfolio pages

Two static pages with no build step, styled as a Think with Google–style article (Google Sans, sticky table of contents on the left). Fonts load from Google Fonts. Everything else is inline.

Live at https://d3vsuthar.github.io/crm-port/

- `index.html`: Selected CRM work, the main page
- `journeys.html`: Journey maps, including the lifecycle blueprint (linked from index)

## Before publishing
- Both pages carry `<meta name="robots" content="noindex">` so they stay out of search results. Delete it if you want them indexed.

## Deploy
Put this folder on your static host under the path you want, for example `yourdomain.com/crm/`:
- **Vercel / Netlify / Cloudflare Pages:** add the folder to your site repo (e.g. `crm/`) and push, or drag-and-drop the folder in the dashboard.
- **GitHub Pages:** commit the folder into the Pages repo, e.g. `crm/index.html`.

The pages link to each other with relative paths, so keep both files in the same folder.
