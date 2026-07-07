# Design System: Tether
**Project ID:** tether (GitHub Pages + iOS app)

## 1. Visual Theme & Atmosphere

Tether feels warm, calm, and intentionally small-scale. The product is for two people, not a social network, so the visual language favors soft cream backgrounds, sticker-like cards with crisp ink borders, and playful display type without feeling childish. Density is relaxed: generous padding, short copy blocks, and one clear action per screen region. The braided cord metaphor (two partner colors meeting at a violet knot) is the central brand image.

## 2. Color Palette & Roles

| Name | Hex | Role |
|------|-----|------|
| Warm Canvas | `#FFFBF3` | Primary page background |
| Ink Plum | `#241F3D` | Headlines, borders, primary text |
| Muted Lilac Gray | `#8A84A6` | Secondary text, eyebrows |
| Coral Pop | `#FF6B4A` | Primary CTA, cord strand, energy |
| Coral Pressed | `#DE4A28` | Link hover, pressed states |
| Knot Violet | `#8C5CFF` | Shared-state accent, cord center |
| Sky Strand | `#3E8EFF` | Secondary cord color in UI previews |
| Lavender Wash | `#F1EEFC` | Section strips, soft panels |
| Card White | `#FFFFFF` | Elevated surfaces |
| Hairline Lilac | `#D8D3EE` | Dividers, subtle borders |

## 3. Typography Rules

- **Display:** Baloo 2 (700-800) for product name, hero headlines, and section titles. Tight line-height on large type.
- **Body:** Inter (400-600) for paragraphs, buttons, and settings rows. Comfortable 1.5-1.6 line-height.
- **Mono labels:** Space Mono for small uppercase section labels in app settings. Use sparingly on marketing pages (one eyebrow max in hero).

## 4. Component Stylings

* **Buttons:** Pill-shaped with 2px ink border and offset hard shadow (`3px 3px 0`). Primary fill is coral; ghost variant is white card.
* **Cards/Containers:** 14-16px corner radius, 2px ink border, hard shadow. Shared tasks use violet border accent.
* **Inputs/Forms:** Rounded rectangles on card white with visible ink border. No placeholder-only labels in product UI.

## 5. Layout Principles

Mobile-first on the app; marketing site uses a max width of 1080px with 1rem side gutters on small screens. Hero is split text + product preview on desktop, stacked on mobile. Legal pages use a single readable column. Section rhythm alternates open canvas with lavender strip for emphasis. Sticky header with light blur for navigation continuity.

## GitHub Pages URLs

- Marketing: `https://mrkrphl.github.io/tether-site/`
- Privacy: `https://mrkrphl.github.io/tether-site/privacy.html`
- Terms: `https://mrkrphl.github.io/tether-site/terms.html`
- Support: `https://mrkrphl.github.io/tether-site/support.html`
