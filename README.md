# Niswander Tech — 2-product site

Merged hub + SalesVibe marketing pages (static HTML).

## Structure

```
NewSite_2_Products/
  index.html              ← Hub: choose Jobs or SalesVibe
  site-config.js          ← SALESVIBE_APP_URL (hosted app signup)
  jobs/
    index.html            ← Power Job Search landing (multi-board search, hunt management)
  salesvibe/
    index.html            ← Why SalesVibe (from SalesAI/why-salesvibe.html)
    leadership.html
    css/leadership-marketing.css
    SV3.ai.png, SV.AI.png
    Leadership Team/      ← leadership photos
```

## Local preview

Open in browser:

- Hub: `file:///.../NewSite_2_Products/index.html`
- SalesVibe: `.../NewSite_2_Products/salesvibe/index.html`

## Trials / app links

- **SalesVibe** sign-up → `https://salesai-2cd3e.web.app` (override in `site-config.js`)
- **Power Job Search** → `https://jobsearch-e9866.web.app` (override in `site-config.js`)

## Next steps

1. Deploy folder to niswander.tech hosting
2. Expand Jobs page with screenshots when ready
