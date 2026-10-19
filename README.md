# Ammily Prain — Portfolio 2026

Personal graphic design portfolio built from the Portfolio 2026 Figma designs.

Live site: https://ammily-portfolio-2026.socialgoose1.chatgpt.site

## Files

- `dist/index.html`: Work Index, category filters, newest-first ordering and formatted captions.
- `dist/work/silpacheep/index.html`: Silpacheep project page.
- `dist/assets/`: Project artwork, the four animated states for 13 (un) BELIEF, and fonts.
- `.openai/hosting.json`: Existing Sites deployment configuration.

## Run locally

No dependency installation or build step is needed. Serve `dist` as the website root:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. Serving from `dist` preserves the absolute asset and project URLs.

## Included behavior

- Category filters with projects belonging to multiple categories.
- Projects ordered from 2026 to 2022.
- Caption text and selective bold formatting from the work-status spreadsheet.
- Hover animation for 13 (un) BELIEF using four Figma states.
- Automatic entrance animations and scroll reveals, with reduced-motion support.
- Index-to-Silpacheep navigation and return links.
- GT Ultra Median and Athiti typography on the Silpacheep page.

Spreadsheet edits are not synchronized automatically. Current content is stored in the HTML.

## Deploy

Use any static hosting service with `dist` as the published directory. The existing Sites configuration is retained for the current site.
