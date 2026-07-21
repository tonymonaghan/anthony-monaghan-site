# *Snug* — Anthony Monaghan

Source for [anthonymonaghan.com](https://anthonymonaghan.com/), the official author page for Anthony (Tony) Monaghan and his completed young adult/crossover novel *Snug*.

Tony is also the author of [*Irish Canoe Classics*](https://www.pesdapress.com/index.php/product/irish-canoe-classics/), published by Pesda Press.

## The site

The page is deliberately concise: a spoiler-safe handover for publishing professionals who have read the opening chapters of *Snug*, Tony’s portrait and a direct way to request the full manuscript.

Its visual language reflects the novel’s two worlds:

- warm uncoated paper and editorial typography evoke the sanctuary of the Snug;
- restrained lido blue recalls the North Sea, the swimming pool and Tony’s portrait;
- Newsreader provides the literary display voice, while Manrope keeps supporting information clear and contemporary;
- a centred editorial measure, intentional left/right asymmetry, optical positioning and proportioned whitespace hold the page together without distracting from the book;
- subtle CSS-only motion adds presence while preserving the quiet composition.

The wording follows the same hierarchy. `SNUG` is roman in the tracked masthead because it acts as an imprint label; book titles are italicised when they appear in prose. The thank-you message recognises readers of the opening chapters without revealing later plot developments, and the author credential remains visible but secondary to the manuscript request.

A separate private handover manual records the full content rationale, reconstruction specification, responsive measurements, rejected alternatives and operating history. The public repository intentionally keeps that internal context out of the published source documentation.

## Technical approach

The site is a lean static document built with semantic HTML and modern CSS. It has no JavaScript, framework, database, analytics, cookies or build step.

Progressive enhancements include:

- fluid desktop, phone and short-landscape layouts;
- responsive portrait delivery with `srcset` and `sizes`;
- keyboard-visible focus states and high-contrast support;
- CSS-only entrance and link motion that respects `prefers-reduced-motion`;
- a canonical URL, crawlable text, sitemap and permissive crawler rules;
- separate Open Graph images for compact and wide social-preview contexts;
- linked `WebPage`, `Book`, `Person` and `ImageObject` structured data;
- a portrait-led 1200 × 1200 image for square messenger previews and a 1200 × 630 literary card for wide previews;
- browser, Apple touch and installable-site icons.

Search and AI discovery use the same public, human-readable page. There is no hidden keyword copy or special AI-only content: structured data mirrors the visible text, and crawlers can access the canonical HTML directly.

## Files

- `index.html` — page content, metadata and responsive styling
- `tony-headshot.jpg`, `tony-headshot-700.jpg` — responsive portrait images
- `snug-social-square-v1.jpg` — compact and square messaging preview image
- `snug-social-preview.jpg` — wide social-preview image
- `favicon.*`, `apple-touch-icon.png`, `icon-*.png` — browser and device icons
- `site.webmanifest` — browser and installed-site metadata
- `robots.txt`, `sitemap.xml` — crawler discovery files
- `CNAME`, `.nojekyll` — GitHub Pages configuration

## Publishing

The canonical source is the `main` branch. Changes pushed to `main` are published automatically through GitHub Pages.

Before publishing, verify the page at desktop and phone widths, confirm that the structured data parses, and check that every referenced image and link exists.

## Rights

Website text and images are © Anthony Monaghan. No licence is granted for their reuse unless expressly stated otherwise.
