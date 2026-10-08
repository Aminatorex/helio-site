# helio-site — landing for Helio (stub)
- Static single page `index.html` (inline CSS/JS; fonts Bricolage Grotesque + IBM Plex), `favicon.svg`, `CNAME` (helio-ai.live), `robots.txt`, `sitemap.xml`, `llms.txt`, `404.html`.
- Product: AI recruiting agent built on Claude — multilingual conversational interviews + psychometric games. Content is placeholder; a verification bot checks the site exists and that Claude is used — keep Claude mentions in static HTML (title/meta/hero/section #claude/FAQ/footer/llms.txt), not JS-only.
- Hosting: GitHub Pages, repo `Aminatorex/helio-site` (public), branch `main`, root. Push = deploy. Primary custom domain = `www.helio-ai.live` (CNAME file); apex 301s to www. Switched from apex 2026-10-08 because the apex-only Let's Encrypt request hung in state "new" for 4h+.
- DNS at Namecheap (BasicDNS): apex A → 185.199.108-111.153, `www` CNAME → aminatorex.github.io.
- Demo form is a stub (localStorage only).
