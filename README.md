# Essential Services — Tile Installation (Bradenton, FL)

Demo site by Wilson Innovations. Single-page static site (`index.html` + `assets/`).

- **Business:** Essential Services (GBP legal name "Essential services llc") — genuine tile installer
- **Owner:** Ryan Bement (owner-operated)
- **Trade:** Tile installation — backsplashes, floor tile, shower & bathroom retiles, lanai/patio tile, custom stone & mosaic
- **Phone (GBP, shown everywhere):** (941) 330-3422
- **Address:** 912 7th Ave E, Bradenton, FL 34208 (Manatee County)
- **Rating:** 5.0 / 18 Google reviews (shown — ≥4.4)
- **Hours:** Mon–Sat 8:30 AM–5:30 PM, Sun closed
- **Fonts:** Zilla Slab (display) + Work Sans (body)
- **Tier:** 1 (Clean Slate)
- **Palette:** warm greige + soft slate + terracotta accent (with sand highlight)
- **Live URL:** https://wilsoninnovations.net/essential-services/
- **Repo:** wilsonramstead/essential-services (Pages, main/root)

## Photos — 100% the business's own GBP photos (NO stock used)

All images pulled via Google Places API from the Essential Services GBP listing, then
PIL re-encoded (EXIF-rotated, resized, progressive JPEG, ≤350KB). **No Unsplash / stock
imagery was used**, so no Unsplash dedup grep or stock phash comparison was required.

| Asset | GBP source photo | Attribution | Use |
|---|---|---|---|
| `hero.jpg` | gbp_00 | Essential services llc | Hero background + og:image + CTA band |
| `why-bath.jpg` | gbp_06 | Essential services llc | Why-section media (master bath) |
| `divider-kitchen.jpg` | gbp_04 | Belinda (customer photo of the work) | Tagline divider bg |
| `g-backsplash.jpg` | gbp_09 | Essential services llc | Gallery — kitchen backsplash |
| `g-floor.jpg` | gbp_07 | David Berglund (reviewer's photo of his 2,000 sq ft floor) | Gallery — whole-home floor tile |
| `g-lanai.jpg` | gbp_01 | Essential services llc | Gallery — screened lanai tile |
| `g-bath-retile.jpg` | gbp_02 | Essential services llc | Gallery — bathroom & shower retile |
| `g-shower-floor.jpg` | gbp_08 | Essential services llc | Gallery — walk-in shower floor |
| `g-niche.jpg` | gbp_03 | Essential services llc | Gallery — custom stone & niche detail |

Every image was visually inspected and matched to its alt text / caption. All show genuine
completed tile work. Painted-phone check: none of the photos contain a phone number.

**Excluded:** gbp_05 (black toilet + Saltillo/Day-of-the-Dead talavera border) — authentic
own work but visually off-palette/quirky for a clean greige site, so left out.

## Content notes / facts intentionally left out
- Generic GBP name "Essential Services" paired with a descriptive tagline
  ("Tile Installation · Bradenton, FL") per manifest guidance so the trade reads clearly.
- Reviews are the 5 real Google reviews, verbatim (light normalization: capitalization,
  "2000"→"2,000", trailing sentence trims on the two longest), attributed first name + last
  initial (Gene F., David B., Scott T., Steve S., Cindy W.).
- No invented facts: no founding year, no license number, no email, no pricing, no
  "years in business" claim. Ryan Bement referenced factually only (no owner-personality section).
- noindex + DEMO comment present; "Website by Wilson Innovations" footer credit; og: absolute
  URLs at https://wilsoninnovations.net/essential-services/ with og:image (hero).
