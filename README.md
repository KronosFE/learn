# Kronos /learn — knowledge base (404 pages)

Served at **kronosfusionenergy.com/learn/** — this repo's root IS /learn/.
Matches the live site: navy #232C39 / gold #D4AD5C, with the site's fonts (Newsreader, Space Grotesk, Space Mono
via Google Fonts). Refined editorial style — hairlines, no boxes. Includes a /learn/videos.html Watch page and
YouTube embeds (privacy-nocookie) on matching topic pages.

## Deploy
1. **GitHub (you):** copy the contents of this folder into the `KronosFE/learn` repo root
   (alongside LICENSE), commit + push. Hub serves at `/learn/`, pages at `/learn/<slug>.html`.
2. **Lovable (paste Claude's wiring prompt):** add "Learn" to nav + footer, merge `sitemap_learn.xml`
   into the main site sitemap, append `llms_learn.txt` to `/llms.txt`, add cross-links from /science + /metro-volt.

## Contents
- `index.html` + `<slug>.html` — the 404 pages (hub + articles)
- `sitemap_learn.xml` — URL fragment to merge into the main site sitemap
- `llms_learn.txt` — fragment to append to /llms.txt

Every number is canon (MetroVolt design point; DOI 10.5281/zenodo.21248916).
Do not hand-edit pages — regenerate from `build_kb.py`.
