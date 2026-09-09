# Tampa Retirement Live — artwork needed

For the landing page at `tampa-summit.html`. Everything below is currently a
grey placeholder or a stand-in. Sizes are the pixel dimensions the page will
actually display at, doubled for retina — supply at the "Supply at" size.

**House rules for all of it**

- Palette is the brand standards guide: navy `#1A4364`, deep navy `#0C2945`,
  teal `#037182`, mint `#9AD1C9`, red `#F05238`, brick `#BE412A`,
  orange `#F4792A`, bone `#E3DAC6`.
- The guide leans on **flat illustrated skylines**, not photography. Where a
  photo and an illustration would both work, the illustration is more on-brand.
- Deliver JPG for photographic content (quality ~80), PNG-24 for anything with
  transparency, WebP alongside if easy.
- No baked-in text unless noted. Headlines are live HTML so they stay
  responsive and translatable.

---

## 1. Hero background — DONE

Supplied as `Walser Wealth Management_design elements_Tampa Retirement Summit - WEB HEADER-rev.ai`.
Page 3 of that file — the artboard with no baked-in text — is now the hero
background, exported at 2880 × 1620 as `Brand Assets/Hero Background v2.webp`.

**One thing to fix at source:** the `.svg` version of the same file is not usable
on its own. Its gradient background is a **linked** image
(`../backgrounds/Walser_design element_ TRL - full spectrum 8741303.jpg`) that was
not included, so the sky renders as an empty hole. The `.ai` has it embedded, so
that is what the export came from. If the SVG is meant to be the deliverable,
it needs the background embedded rather than linked.

The other two artboards are on file and unused for now: page 1 is the full
lockup (Tampa Retirement Live + OCT 17 + BOLD MOVES + OWN WHAT'S NEXT +
LAUNCHED BY), page 2 is the same without the lockup. Page 1 is the obvious
starting point for the social share card in section 7.

## 2. Speaker portraits

Three needed, same treatment so they read as a set.

| | |
|---|---|
| **Supply at** | 1200 × 1500 px (4:5 portrait) |
| **Displays at** | 300 × 375 in the guest card, 420 × 560 for the keynote |
| **Format** | JPG |

- **Charles Payne** — a headshot is in place now, but it is a press photo.
  If his booking agent supplies an official one with usage rights, use it.
- **Rebecca Walser** — currently the existing Walser Wealth portrait. Fine, but
  a shot matching Charles's crop and lighting would make the pair look
  deliberate.
- **Tom** — nothing yet. Need the portrait plus his surname and a one-line credit.

Shoot or crop with the head in the upper third; the bottom of the frame gets a
gradient and the name plate.

## 3. Agenda section background

| | |
|---|---|
| **Supply at** | 2400 × 1400 px |
| **Displays at** | full-bleed behind the six topic cards |
| **Format** | JPG or PNG |

Sits under a heavy teal overlay, so it only needs to read as texture. A wide
shot of the Sheraton Tampa Brandon ballroom, or an abstract brand pattern from
the standards guide, both work. Low contrast is a feature here.

## 4. "Who this day is built for" image

| | |
|---|---|
| **Supply at** | 1800 × 1360 px (4:3) |
| **Displays at** | roughly 560 × 420 |
| **Format** | JPG |

Audience or room shot. If there is no library of past-event photography, an
illustrated scene or a venue photo works instead.

## 5. Closing banner background

| | |
|---|---|
| **Supply at** | 2400 × 1200 px |
| **Displays at** | full-bleed behind "BOLD MOVES" |
| **Format** | JPG or PNG |

Currently a pure brand gradient, which honestly looks good as-is. Only replace
it if there is a strong illustrated skyline to use. Same rule as the hero:
quiet in the centre, type sits there.

## 6. Favicon

| | |
|---|---|
| **Supply at** | 512 × 512 px, plus 180 × 180 for Apple touch icon |
| **Format** | PNG with transparency, plus `.ico` if easy |

The sunburst mark from inside the "V" of LIVE, on navy or transparent. The full
lockup will not read at 32 px.

## 7. Social share card

| | |
|---|---|
| **Supply at** | 1200 × 630 px |
| **Format** | JPG or PNG |

For Facebook, LinkedIn and iMessage previews. This one **does** carry baked-in
text: the event lockup, `OCT 17 · 2026`, `SHERATON TAMPA BRANDON HOTEL`, and
`LAUNCHED BY WALSER WEALTH MANAGEMENT`. Keep everything inside a 60 px safe
margin — the edges get cropped differently on each platform.

## 8. Event logo as vector — nice to have

The logo on the page was extracted from the brand standards PDF as a 418 px
PNG. It is clean, but it is a raster. If the agency can send the original
**SVG or EPS**, it will stay sharp on large screens and cut page weight.

Both colourways are in use: white (reversed, for dark grounds) and navy.

---

## Also outstanding, not artwork

1. **Checkout URLs** for all four ticket products. This is the blocking item —
   the buttons currently go nowhere.
2. **Hosting decision**: `walserwealth.com/tamparetirementlive` or ClickFunnels.
   Changes how asset paths are written.
3. **Session titles** for sessions one, two, four and five.
4. **Tom's** surname and credit.
5. **Seat counts** — 200 total seats is confirmed (venue capacity). The
   "Only 40 VIP places" figure is still a guess and needs confirming.
6. **Transat and Dunbar webfont files**, if the licence covers web embedding.
   Archivo and Figtree are standing in.
