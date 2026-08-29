# Design System: twodo

Public site for Twodo, a to-do list for two people. The visual language follows the App Store marketing frames: clean light gray, teal accents, sentence-case headlines, and a lot of air. It is not a sticker sheet.

## 1. Visual theme

Quiet and private. The product is for two people, so the site stays small: short copy, generous space, one idea per block. Private vs shared is shown with a gray lock or the blue A / orange S avatars — never with badges, cords, or decorative chrome.

## 2. Color palette

| Name | Hex | Role |
|------|-----|------|
| Canvas | `#F2F2F2` | Page background |
| Card | `#FFFFFF` | App surfaces, support card |
| Ink | `#111111` | Headlines and primary text |
| Muted | `#6B6B6B` | Subheads and body |
| Faint | `#9A9A9A` | Inactive tabs, captions |
| Line | `#E6E6E6` | Hairline dividers |
| Teal | `#1AA99C` | Active tab, plus, toggle, links |
| Alex | `#3B7BFF` | First person avatar |
| Sam | `#F07A2A` | Second person avatar |
| Lock | `#B8B8B8` | Private-task icon |
| Phone | `#1A1A1A` | Device bezel |

No hard offset shadows. No ink borders. Elevation on the device mockup is a single soft shadow.

## 3. Typography

- **Display and UI:** Inter 400–700. Sentence-case headlines. Tight tracking on large type (`-0.03em` to `-0.04em`).
- **Wordmark:** lowercase `twodo`.
- No display novelty faces. No monospace eyebrows.

## 4. Components

- **Header:** Sticky, translucent canvas, blur. Wordmark left, text links right. No store button.
- **Device mockups:** Dark iPhone frame, Dynamic Island, white screen, Today / Partner / Me tab bar.
- **Tasks:** Hollow radio, hairline row, lock or overlapping A/S avatars.
- **Legal pages:** Single narrow column. Support contact sits on a white rounded card without a border.

## 5. Layout

Marketing hero is centered copy over one or two device frames, matching the store compositions. Feature copy is a two-column type list, not a card grid. Legal pages use a 42rem measure. Max width for marketing is 1080px with 1.25rem side gutters.

## GitHub Pages URLs

- Marketing: `https://mrkrphl.github.io/tether-site/`
- Privacy: `https://mrkrphl.github.io/tether-site/privacy.html`
- Terms: `https://mrkrphl.github.io/tether-site/terms.html`
- Support: `https://mrkrphl.github.io/tether-site/support.html`
