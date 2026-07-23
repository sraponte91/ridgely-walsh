# Ridgely Walsh — Design Directions

Design explorations for the **Ridgely Walsh** website (a public affairs advisory
firm partnering with transformational companies and causes).

Published with **GitHub Pages** → https://sraponte91.github.io/ridgely-walsh/

## Directions

| # | Name | Path | Status |
|---|------|------|--------|
| 01 | Editorial | [`v1-editorial/`](v1-editorial/) | Live |
| 02 | Modern | [`v2-modern/`](v2-modern/) | Live |
| 03 | Press | [`v3-press/`](v3-press/) | Live |
| 04 | Petrol | [`v4-petrol/`](v4-petrol/) | Live |

Each direction is a single self-contained `index.html` — fonts and artwork are
embedded, no build step and no external dependencies.

### 01 · Editorial
Full-bleed typographic hero in a bold condensed serif with a rotating sector
word, an antique-gold accent (#B8975A) and a curtain intro sequence.

### 02 · Modern
Typographic hero in Manrope with a live, cursor-reactive contour field, and a
hand-drawn intro that resolves into the hero image.

### 03 · Press
Stacked colour panels on newsprint cream — Instrument Sans display over Manrope
text, a live team roster and press list, and a panel-peel loading sequence.
Content is pulled from the current site: the full team, selected coverage, the
About copy and the direct email.

### 04 · Petrol
The same stacked layout as Press, carried into cool papers — petrol green and
muted steel blue in place of the warm tones.

## Local preview
Open any direction's `index.html` in a browser, or serve the root:

```bash
python3 -m http.server
```

then visit http://localhost:8000/
