# Hype Shop — DESIGN.md

Direction: dark "night product launch" — a near-black stage, the product lit like on a showcase, one hot orange for action. Built from the existing brand (logo HYPE + orange NEW price tag, Instagram posters). Not based on UXKIN references (not connected).

## Color (dark only — the brand is dark everywhere)
| Token | Value | Role |
|---|---|---|
| --bg | #0b0d17 | page background |
| --bg-2 | #11142a | alternate section background |
| --surface | #161a33 | cards, panels |
| --line | rgba(255,255,255,.10) | borders, dividers |
| --ink | #f4f5fb | headings, body text (17:1 on bg) |
| --muted | #a3a8c3 | secondary text (8:1 on bg) |
| --primary | #ff5a1f | primary buttons, links, key word in headings |
| --primary-hover | #ff7a45 | primary hover |
| --on-primary | #0b0d17 | text on primary (6.4:1) |
| --wa | #25d366 | WhatsApp actions only |
| --ok | #2ecc71 | "in stock" |
| --burgundy | #8e2a4f | product glow, 18 Pro Max only |
| --orange-case | #ff6a2e | product glow, 17 Pro Max only |

No gradients on text. Glow only behind products.

## Typography
Inter (Google Fonts), weights 400/500/700/800/900.
Scale: 13 / 15 / 17 / 20 / 26 / 40 / clamp(44–88) hero. Line height 1.55 body, 1.05 headings, letter-spacing −0.03em on 40+.
Body ≥ 16px, lines ≤ 70ch. Eyebrows: 12px 800 uppercase +0.16em, primary color.

## Spacing
8-based: 4, 8, 12, 16, 24, 32, 48, 64, 96. Sections 96px desktop / 64px mobile. Content width 1160px, 20px side gutter.

## Shape & depth
Radius: 10 (chips), 18 (buttons pill = 999), 24 (cards). One shadow: 0 30px 60px rgba(0,0,0,.5) for product images and video frame only.

## Components
- Button primary: --primary bg, --on-primary text, pill, 15/700, hover --primary-hover + lift 2px, focus 3px outline --primary offset 3px.
- Button WhatsApp: --wa bg, dark text, WhatsApp glyph.
- Button secondary: transparent, 1px --line border, --ink text.
- Chip: 10 radius, --surface bg, 13/600.
- Card: --surface, 1px --line, radius 24, padding 28.
- Nav: sticky, blurred --bg at 80%, logo left, language switch + WhatsApp right.
- Footer: thin line on top, muted 14px.

## Imagery & icons
Product renders on transparent background with LED glow, never on white. Real product video in a phone frame. Icons: inline stroke SVG, 2px, 24px, primary color on a 12%-primary tile. No emoji, no stock photos.
