---
name: Pitch Precision Dark
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#4ae176'
  on-secondary: '#003915'
  secondary-container: '#00b954'
  on-secondary-container: '#004119'
  tertiary: '#ffb3ad'
  on-tertiary: '#68000a'
  tertiary-container: '#ff7a73'
  on-tertiary-container: '#79000e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#6bff8f'
  secondary-fixed-dim: '#4ae176'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#005321'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#930013'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  display-hero:
    fontFamily: Chivo
    fontSize: 56px
    fontWeight: '900'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Chivo
    fontSize: 36px
    fontWeight: '900'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Chivo
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  headline-xl-mobile:
    fontFamily: Chivo
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 36px
  headline-lg:
    fontFamily: Chivo
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Chivo
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Chivo
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Chivo
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-xl:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Chivo
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Chivo
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Chivo
    fontSize: 10px
    fontWeight: '800'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system embodies high-octane Egyptian football passion through an elite athletic lens. It blends pitch-side stadium lights with street-level fan fervor. The emotional tone is energetic, authentic, premium, and intensely competitive. 

The aesthetic is Modern Kinetic Brutalism softened by refined athletic editorial cues: deep midnight pitch backgrounds, ultra-crisp high-contrast cards, razor-sharp status indicators, and luminous pitch-volt accents. Elements feel technical, responsive, and tactile—reminiscent of high-tech sportswear fibers, stadium architecture, and matchday countdown boards.

## Colors
The palette balances immersive nighttime match atmospheres with electric field indicators:

- **Primary (`#10B981`) & Secondary (`#22C55E`):** Pitch Green and Electric Volt drive primary action loops, selection states, active tab highlights, and in-stock inventory indicators.
- **Tertiary (`#EF4444`):** Match Alert Red, dedicated to flash sales, hot drops, live score tags, limited editions, and clearance badges. Gold (`#F59E0B`) serves as an accent tier for Player Issue and Authentic Match jersey tiers.
- **Background Tiers:** The canvas defaults to Deep Stadium Pitch (`#0B0F19`), rising into elevated surface containers (`#111827` and `#1F2937`).
- **Surface Contrast:** High-impact product cards utilize either hyper-clean Dark Graphite (`#111827`) with micro-borders or crisp High-Contrast Stark Cards (`#FFFFFF` with inverted typography `#0B0F19`) for sponsored drops and special kits.

## Typography
Typography is tuned for bilingual performance, with full Right-to-Left (RTL) baseline matching. In Arabic interfaces, typography maps to IBM Plex Sans Arabic to retain identical technical precision and legible counter-forms on both digital numbers and Arabic ligatures. 

Display headlines project intense energy via heavy weights (`800` and `900`), slightly condensed tracking, and urgent line heights. Body copy favors rhythmic reading comfort with generous line heights to accommodate Arabic diacritics and complex letter curves. Tactical labels (kit badges, sizing chips, numbers, and squad prints) employ upper-register tabular numerals and bold letterforms.

## Layout & Spacing
The layout follows a fluid-responsive column system structured for RTL visual priority, driving user eyes naturally from top-right navigation hubs down through the match product grids:

- **Mobile (< 768px):** 4 fluid columns, `1rem` margin, `1rem` gutters. Product cards snap edge-to-edge horizontally with peek-ahead carousels.
- **Tablet (768px – 1024px):** 8 columns, `2rem` outer margin, `1rem` gutters.
- **Desktop (> 1024px):** 12 columns with max layout container pinned to `1440px`, flanked by dynamic outer gutters and `1.5rem` internal gutters.

Spacing enforces clear athletic intervals: tight grouping (`space-xs` and `space-sm`) binds badges, kit attributes, and prices directly to product names; wide gaps (`space-lg` and `space-xl`) separate distinct stadium collection sections and club kits.

## Elevation & Depth
Depth avoids heavy diffuse drop shadows, opting instead for crisp light-leak boundaries, sharp tonal shifts, and stadium-grade edge luminescence:

- **Level 0 (Pitch Baseline):** Ground canvas `#0B0F19`. Flat, non-interactive.
- **Level 1 (Card & Section Surfaces):** Elevated surface `#111827` framed with a subtle 1px border of `rgba(255, 255, 255, 0.08)`.
- **Level 2 (Active Cards & Floating Drawers):** High-tier containers `#1F2937` with an ambient rim light: `0px 4px 20px rgba(0, 0, 0, 0.5)`. On hover, interactive cards trigger a border bloom: `1px solid rgba(16, 185, 129, 0.4)`.
- **Level 3 (Modals, Overlays & Sticky Nav):** Surface `rgba(11, 15, 25, 0.85)` treated with `backdrop-filter: blur(16px)` and grounded by a hard divider line at the baseline.
- **Stark Drop Cards:** Select limited-edition jerseys feature a stark `#FFFFFF` card body with a razor-thin `#000000` rim and zero blur, delivering maximum pop against the dark canvas.

## Shapes
The visual architecture emphasizes discipline, modern speed, and athletic sharpness. Geometry relies on compact bevels and subtle soft radii (`0.25rem` to `0.5rem`), keeping silhouette contours firm and engineered. Sizing badges, club crest housings, and jersey preview frames avoid pillowy curves in favor of crisp rectangular surfaces with structural corner integrity.

## Components

### Buttons
- **Primary Action (Add to Bag / Buy Now):** Electric Volt (`#22C55E`) or Pitch Green (`#10B981`) solid fill with bold midnight ink (`#0B0F19`). Angular `rounded` corners (0.25rem), capitalized or high-weight Arabic typography, micro-scale press effect.
- **Secondary (Custom Squad Name & Number):** Transparent background with a 1.5px solid border in Pitch Green, shifting to full fill on hover.
- **Ghost/Tertiary:** High-contrast neutral text with subtle underline or background wash (`rgba(255,255,255,0.06)`).

### Product & Kit Cards
- **Dark Stadium Card:** Matte `#111827` body with 1px border (`rgba(255, 255, 255, 0.08)`). High-res cutout jersey imagery centered. Top-right accommodates promotional and fabric badges; top-left houses heart/wishlist toggle. Price displays prominently in bold numerals followed by currency in Arabic (ج.م).
- **Stark Showcase Card:** Crisp white surface with high-contrast pitch-black text, used to spotlight Matchday Derbies (e.g., Ahly vs Zamalek match specials).

### Badges & Tags
- **Discount & Flash Drop:** Tertiary Red (`#EF4444`) with white typography. Compact padding (`0.125rem 0.5rem`), strictly rectangular or `rounded` (0.25rem).
- **Fabric & Technology Badges:** Translucent dark container (`rgba(255, 255, 255, 0.1)`) with crisp typography detailing fabric tech: `Dry Fit`, `Player Issue`, `Recycled Aero`, `100% Polyester`.
- **Authenticity Seal:** Gold tone (`#F59E0B`) with metallic micro-border.

### Fabric & Size Selectors (Chips)
- **Size Selector:** Crisp square tiles (S, M, L, XL, 2XL, 3XL). Unselected: dark tile (`#111827`) with faint outline. Selected: Pitch Green (`#10B981`) text, bright volt border, subtle inner glow. Out-of-stock sizes show a clean diagonal slash with muted opacity (`0.35`).
- **Kit Customization Input:** Clean numeric step-form allowing customized Arabic/English fan names and back numbers, styled with monospaced tabular digits.

### Form Inputs & Checkboxes
- **Text Inputs:** Dark base (`#0E1422`) with `1px solid rgba(255, 255, 255, 0.15)`. Text sits right-aligned for RTL script. Focus state shifts border to Pitch Green (`#10B981`) with no blurry ring.
- **Checkboxes & Radios:** Sharp square indicators with 0.125rem radius. Check mark fills with energetic volt.