# kazakhsouvenirs.kz Website Mapping

## Sitemap

- `/index.html`
- `#collections`
- `#products`
- `#gallery`
- `#about`
- `#contact`

## Wireframe Structure

- Sticky navigation
- Full-viewport editorial hero with brand name, source boundary, Instagram CTA, and product image
- Source-boundary band for unavailable Instagram fields
- Collection grid based on visible categories
- Product card grid using captioned facts or placeholders
- About/editorial section sourced from an older Instagram caption
- Gallery section using selected public Instagram images
- Contact section with Instagram URL and placeholders for unavailable details
- Footer with mapping document link

## UI Layout

- Desktop: two-column hero, four-column collections, three-column product grid, four-image gallery.
- Tablet: two-column cards and stacked editorial sections.
- Mobile: single-column cards, collapsed navigation, full-width imagery.

## Design System

- Colors extracted from the Instagram images:
  - Canvas `#f7f4ee`
  - Surface `#fffdf8`
  - Ink `#202020`
  - Felt gray `#c0c0b0`
  - Mountain blue `#608090`
  - Leather brown `#806040`
  - Saddle `#b09070`
  - Oxblood `#801010`
  - Red accent `#c01020`
- Typography:
  - Display: Georgia / Times New Roman serif stack for editorial, premium headings.
  - Body: Inter/system sans stack for clean navigation and product information.
- Spacing:
  - Scale from `.5rem` to `7rem`, with generous section padding.
- Buttons:
  - Pill buttons, one filled and one outline, with focus/hover movement.
- Cards:
  - 8px radius, quiet borders, image-first product cards.
- Icons:
  - No unsupported icon set was added. Navigation uses text; mobile menu uses simple accessible lines.

## Instagram Source Analysis

Primary account URL: `https://www.instagram.com/kazakhsouvenirs.kz`

Observed public profile data:
- Username: `kazakhsouvenirs.kz`
- Public mirrored user id from Imginn: `4025387461`
- Bio: unavailable in accessible public snapshot.
- Highlights: unavailable in accessible public snapshot.
- Contact details: Instagram URL only.
- Testimonials and FAQ: not found in accessible public snapshot.

Mirrored source used because Instagram direct profile/API fetches returned app shells or rate limits:
- `imginn.html`
- `instagram-parsed-items.json`
- `assets/instagram/all/*`

## Product Categories Identified

- Magnets
- Felt dolls
- Jewelry and accessories
- Textile bags
- Wallets / cardholders
- Keychains
- Neckwear / pendants
- Ornamental cuffs / bracelets
- Cognac sets

## Content And Asset Mapping

| Website section | Local asset | Instagram post/source | Content used |
| --- | --- | --- | --- |
| Hero | `assets/site/DaiOvZzDD5k-04.webp` | Post `DaiOvZzDD5k`, uncaptioned carousel, 8 days ago | Brand name and placeholder for unavailable bio |
| Collections / Magnets | `assets/site/DZ95L8pjFOz-03.webp` | Post `DZ95L8pjFOz`, 22 days ago | Caption says magnets, materials, and price from 1000 tenge |
| Collections / Felt dolls | `assets/site/DZ9ke2tDGRN-01.webp` | Post `DZ9ke2tDGRN`, 22 days ago | Caption says felt dolls, handmade |
| Collections / Jewelry and accessories | `assets/site/DaINtRIjKqB-01.webp` | Post `DaINtRIjKqB`, uncaptioned carousel, 18 days ago | Category inferred from visible earrings/bracelet imagery |
| Collections / Textile bags | `assets/site/DaICXqZDA7I-15.webp` | Post `DaICXqZDA7I`, uncaptioned carousel, 18 days ago | Category inferred from visible bag imagery |
| Product / Wallets | `assets/site/DaiOvZzDD5k-03.webp` | Post `DaiOvZzDD5k`, uncaptioned carousel | Caption unavailable placeholder |
| Product / Cuffs | `assets/site/DaI-aznjKgy-05.webp` | Post `DaI-aznjKgy`, uncaptioned carousel | Caption unavailable placeholder |
| Product / Keychains | `assets/site/DaIB-XfjOBH-01.webp` | Post `DaIB-XfjOBH`, uncaptioned carousel | Caption unavailable placeholder |
| Product / Pendants | `assets/site/DaAXS7NjCrC-01.webp` | Post `DaAXS7NjCrC`, uncaptioned carousel | Caption unavailable placeholder |
| Product / Han set | `assets/site/BTtfn4NBj9H-01.webp` | Post `BTtfn4NBj9H`, 9 years ago | Captioned product name, 3 positions, 500 ml, 2 cups, handmade/hand-painted, 22 cm |
| Product / Karakoz set | `assets/site/BTtfiiOhEqn-01.webp` | Post `BTtfiiOhEqn`, 9 years ago | Captioned product name, 5 items, 500 ml, 4 cups, handmade, decaling technique, 22 cm |
| About | `assets/site/DZ7L-pvjJaF-01.webp` | Post `BqcMcQwlV2Q`, 8 years ago, and visible carousel imagery | Short paraphrase of caption mentioning ASTA TRAVEL, craftspeople from Kazakhstan regions, handmade souvenirs/accessories/interior objects |
| Gallery | Four selected `assets/site/*.webp` files | Public mirrored carousel images | Visual feed only |

## Performance And Accessibility Notes

- Images were downloaded from public mirrored Instagram media and converted to local WebP assets.
- Images use explicit dimensions, `loading="lazy"` where appropriate, and descriptive alt text.
- The hero image uses `fetchpriority="high"`.
- Semantic regions, skip link, accessible mobile nav, and dialog labels are included.
- Motion respects `prefers-reduced-motion`.

## Unsupported Sections

- Testimonials were not generated because no testimonials were visible.
- FAQ was not generated because no FAQ content was visible.
- Handmade process details were not expanded beyond captions mentioning handmade work.
- Prices were not invented; only the magnets price from the observed caption is included.
