# markup.teo

A minimal digital business card with a markup/terminal aesthetic — pure HTML, no frameworks, no nonsense.
Vibe-coded (Gemini 3 + Claude Sonnet 4.6) like it's 2026.

Live at [matteo.cavalleri.eu](https://matteo.cavalleri.eu/)

## What it is

A single-page personal site that doubles as an e-business card. Links out to scientific identity (ORCID, Authorea), side projects, and the occasional overshare on Instagram.

Built with IBM Plex Mono and vibes. Vibe-coded in 2026.

## Stack

- Plain HTML/CSS
- IBM Plex Mono (Google Fonts)
- GitHub Pages

## Changelog

### 2026-04-02
- Fixed right column (`.link-meta`) alignment — was shifting horizontally based on left label length due to `::after` pseudo-element (⏎ symbol) acting as a third flex child under `justify-content: space-between`. Replaced with `margin-left: auto` on `.link-meta` so the right column is consistently positioned.
- Added `text-align: right` and `white-space: nowrap` to `.link-meta` to prevent text wrapping.
- Replaced `transition: all` on `.link-item` and `::after` with explicit property transitions for better rendering performance.
- Added Akanaba profile QR code to the header, vertically centered alongside the name/title text and sized to match the two text rows height.

## License

MIT
