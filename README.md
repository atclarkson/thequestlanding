# The Quest — landing page

Single static page teaser for *The Quest*. No build step, no dependencies.

## Deploy on Cloudflare

Connect this repo in the Cloudflare dashboard ("Workers & Pages" → Create → import this repo).

- **Build command:** (leave empty)
- **Deploy command:** `npx wrangler deploy`

`wrangler.jsonc` tells Wrangler to serve this directory as static assets — no Worker script needed.
