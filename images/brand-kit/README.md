# Magic City — logo assets (concept 1A, diamond badge)

## Geometry
Single even-odd path on a 100×100 grid. The star is negative space, not a separate shape.

```
viewBox="0 0 100 100" fill-rule="evenodd"
M50 3 L97 50 L50 97 L3 50 Z M50 17 L56.5 43.5 L83 50 L56.5 56.5 L50 83 L43.5 56.5 L17 50 L43.5 43.5 Z
```

## Colour
- `#0B2545` primary navy
- `#1D63D1` accent blue (tagline only, used sparingly)
- `#EDF3FA` light ground

## Type
- Wordmark: Manrope ExtraBold (800), all caps, 0.22em tracking
- Tagline: Manrope Bold (700), 0.4em tracking, accent blue
- Clear space: half the badge width on all sides

## Files
Vector (scale to any size):
- `magic-city-icon-navy.svg` — transparent background
- `magic-city-icon-white.svg` — transparent background
- `magic-city-icon-navy-on-white.svg`
- `magic-city-icon-white-on-navy.svg`
- `magic-city-lockup-stacked-navy.svg` / `-white.svg`
- `magic-city-lockup-horizontal-navy.svg` / `-white.svg`

Raster icons (`png/`, 2048 / 1024 / 512 px — app icon, favicon, avatar):
- `magic-city-icon-navy-{size}.png` — transparent background
- `magic-city-icon-white-{size}.png` — transparent background
- `magic-city-icon-white-on-navy-{size}.png`

Lockup rasters aren't included: the wordmark is type, so export it from the SVG
(or from the design sheet) with Manrope loaded, at whatever size you need.

## Note on text in the SVG lockups
The wordmark is live `<text>` with Manrope, not outlines. For print or a client handoff,
convert text to outlines in Illustrator/Figma, or load Manrope where the SVG is rendered.
The icon-only SVGs are pure path data and need no fonts.
