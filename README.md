# Anthony Monaghan – GitHub Pages site, v7

## What changed

- Desktop geometry remains unchanged from v6.
- Ordinary portrait phones keep the 36 px text and 150 px portrait.
- The text now reflows against the real device width instead of scaling the
  whole composition with container-query units.
- Mobile spacing is tightened so the text, portrait and name fit within the
  normal phone viewport.
- Very narrow legacy screens receive a modest scale reduction.
- Short landscape phones use a compact two-column layout.
- Horizontal overflow is prevented; vertical scrolling remains available if
  browser accessibility settings enlarge the text.

## Domain-transition code included

- Production indexing is enabled in `index.html`.
- `robots.txt` allows crawling and declares the sitemap.
- `sitemap.xml` lists the canonical production URL.
- `CNAME` contains `anthonymonaghan.com`.
- Canonical, Open Graph, Twitter-card and structured-data URLs all use the
  production domain.
- `site.webmanifest` now uses root-relative paths suitable for the custom domain.

## Update the cloned repository

Replace these files in the local clone:

- `index.html`
- `robots.txt`
- `sitemap.xml`
- `site.webmanifest`
- `README.md`

Add:

- `CNAME`

Then commit and push. Suggested commit message:

`Make mobile layout responsive and prepare custom domain`

After GitHub Pages rebuilds, check **Settings → Pages**. The custom-domain field
should show `anthonymonaghan.com`; enter and save it there if it does not.

Do not change the WordPress DNS records until the GitHub test deployment has
rebuilt successfully with this version.
