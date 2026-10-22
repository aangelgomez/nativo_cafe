---
name: Warm Artisanal Minimal
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4e4540'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#80756f'
  outline-variant: '#d2c4bd'
  surface-tint: '#6c5b51'
  primary: '#110703'
  on-primary: '#ffffff'
  primary-container: '#2b1e16'
  on-primary-container: '#988479'
  inverse-primary: '#d9c2b5'
  secondary: '#536441'
  on-secondary: '#ffffff'
  secondary-container: '#d3e6bb'
  on-secondary-container: '#576845'
  tertiary: '#150500'
  on-tertiary: '#ffffff'
  tertiary-container: '#321b0a'
  on-tertiary-container: '#a58169'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f6ded1'
  primary-fixed-dim: '#d9c2b5'
  on-primary-fixed: '#251911'
  on-primary-fixed-variant: '#54433a'
  secondary-fixed: '#d6e9be'
  secondary-fixed-dim: '#bacda3'
  on-secondary-fixed: '#111f05'
  on-secondary-fixed-variant: '#3c4c2b'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#e8bea4'
  on-tertiary-fixed: '#2c1606'
  on-tertiary-fixed-variant: '#5d402d'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 3.5rem
    fontWeight: '600'
    lineHeight: 4rem
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 2.5rem
    fontWeight: '500'
    lineHeight: 3rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.65rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.35rem
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the sensory warmth, quiet craftsmanship, and social ritual of an Argentine specialty coffee house. It pairs architectural minimalism with organic earthiness, evoking the aroma of slow-roasted single-origin beans, warm ceramic mugs, and late afternoon sun casting long shadows across linen and polished walnut.

The visual style is **Warm Minimalist Tactile**: expansive breathing room, layered warm neutral surfaces, tactile hairline dividers, and graceful editorial typography. The interface should feel collected, hospitable, and composed—eschewing clinical tech sterility in favor of buttery surfaces, deliberate pacing, and subtle earthy accents that suggest botanical origin and craftsmanship.

## Colors

The palette draws inspiration directly from the roastery and botanical coffee terroir:

- **Primary (`#2B1E16`)**: Deep roast espresso. Used for primary typography, authoritative buttons, and grounded structural frames. A secondary dark tone (`#3E2B20`) provides subtle contrast for hovered elements and active states.
- **Secondary (`#5A6B48`)**: Earthy olive leaf. Used sparingly for organic accents, sustainability certifications, seasonal origin indicators, and focused CTA highlights. Its deeper shade (`#4D5E3B`) secures AA-level text accessibility against pale backdrops.
- **Tertiary (`#8C6A54`)**: Steamed mocha and roasted husk. Used for supporting iconography, metadata, secondary tags, and subtle warm illustrations.
- **Neutral Surface Hierarchy**:
  - `Base Canvas`: Creamy Ivory (`#FDFBF7`)
  - `Card / Surface Container`: Steamed Latte (`#F5EFEB`)
  - `Elevated Surface / Inset Well`: Toasted Oat (`#EFE8DF`)
  - `Border / Hairline Outline`: Soft Warm Clay (`#E5DCD0`)

Avoid stark pitch black (`#000000`) or sterile cold whites (`#FFFFFF`). Maintain a strictly warm color temperature across all UI states and overlays.

## Typography

The typographic hierarchy balances literary grace with high-performance legibility:

- **Headlines (Playfair Display)**: Infuses editorial sophistication, artisanal pedigree, and warmth. Display and headline weights remain moderate (`500` to `600`) to preserve delicate serif hairline details without becoming visually aggressive.
- **Body & Functional UI (Plus Jakarta Sans)**: A contemporary humanist sans-serif with friendly geometric curves and open counters. It renders legibly on digital menus, ingredient lists, bean provenance profiles, and bag weight selections.
- **Micro-labels & Badges**: Set in `Plus Jakarta Sans` with slightly tracked upper or title-case styling (`letter-spacing: 0.04em` to `0.06em`) for tasting notes, roast levels, and processing methods.

## Layout & Spacing

This design system uses a responsive 12-column grid system built on an 8pt baseline rhythm, shifting to 8 columns on tablet and 4 columns on mobile:

- **Desktop (>= 1024px)**: Max container width of `1280px` with `margin: 3rem` and `gutter: 1.5rem`. Generous negative space between editorial bean showcases and tasting narratives.
- **Tablet (768px - 1023px)**: 8-column layout with `margin-tablet: 2rem` and `gutter: 1.25rem`. Two-column product cards and flexible side-by-side spec sheets.
- **Mobile (<= 767px)**: 4-column layout with `margin-mobile: 1.25rem` and `gutter-mobile: 1rem`. Full-width modular cards, sticky bottom order drawers, and horizontal swipe carousels for tasting tags and roast selections.

## Elevation & Depth

Visual hierarchy uses tonal surface layering and ambient espresso-tinted shadows, avoiding stark drop shadows or cold grey blurs:

- **Layering Principle**: Depth is primarily established by contrast between surfaces: `#FDFBF7` (Canvas) supports `#F5EFEB` (Cards), which in turn hold `#EFE8DF` (Input wells, chip backgrounds).
- **Ambient Shadow Character**: When elevation is required (such as sticky navigation bars, floating cart triggers, or elevated modal sheets), shadows use ultra-diffused, warm-tinted alpha values:
  - `Elevation-1 (Cards on hover)`: `0px 6px 20px -4px rgba(43, 30, 22, 0.06)`
  - `Elevation-2 (Dropdowns, Dialogs)`: `0px 14px 34px -6px rgba(43, 30, 22, 0.10)`
  - `Elevation-3 (Bottom sheets, Cart drawers)`: `0px 20px 48px -10px rgba(43, 30, 22, 0.16)`
- **Hairline Borders**: Surfaces are anchored with delicate `1px` borders in `#E5DCD0` to keep edges defined against ivory backdrops without creating visual heaviness.

## Shapes

The shape system blends generous organic curves with pill contours, evoking polished river stones and handcrafted ceramics:

- **Cards & Surface Modules**: Styled with `rounded-2xl` (`1rem` / `16px`) to produce a soft, approachable frame for imagery and content blocks.
- **Interactive Controls & Tags**: Buttons, form inputs, status chips, and origin badges utilize full pill contours (`rounded-full` / `9999px`), reinforcing the smooth, tactile coffee house aesthetic.
- **Imagery**: Product photographs, farm landscape shots, and brewing guides feature continuous rounded corners with inner borders (`inset 0 0 0 1px rgba(43, 30, 22, 0.05)`) to preserve clean silhouettes.

## Components

### Buttons
- **Primary**: Pill-shaped (`rounded-full`), deep espresso background (`#2B1E16`), creamy ivory text (`#FDFBF7`), padding `0.875rem 1.75rem`. On hover, transitions smoothly to `#3E2B20`.
- **Secondary / Accent**: Pill-shaped, olive green background (`#5A6B48`), ivory text (`#FDFBF7`). Used for primary actions with botanical context (e.g., "Subscribe to Origin Series").
- **Outline**: Pill-shaped, 1.5px border in `#2B1E16`, transparent fill, `#2B1E16` text. On hover, fills with `#F5EFEB`.
- **Ghost**: Pill-shaped, no border, `#2B1E16` text, subtle `#F5EFEB` background fill on hover.

### Chips & Badges
- **Tasting Note Chips**: Pill-shaped, background `#EFE8DF`, text `#3E2B20`, border `1px solid #E5DCD0`, padding `0.375rem 0.875rem`, font `label-md`.
- **Origin & Roast Badges**: Compact pill, olive tint (`background: rgba(90, 107, 72, 0.12)`, text `#4D5E3B`), uppercase font `label-sm`.

### Input Fields
- Filled style with pill-to-rounded transition: `rounded-xl` (`0.75rem`), background `#F5EFEB`, border `1px solid #E5DCD0`, text `#2B1E16`.
- **Focus State**: Border transitions to `#5A6B48` with a soft outer ring: `0 0 0 3px rgba(90, 107, 72, 0.18)`. Background shifts to pure `#FDFBF7`.

### Selection Controls (Checkboxes & Radios)
- **Checkboxes**: `rounded-md` (`6px`), border `1.5px solid #8C6A54`. When checked, filled with `#2B1E16` containing a crisp cream checkmark.
- **Radio Buttons (Grind & Bag Size)**: Circular, outer ring in `#8C6A54`. When selected, filled with an inner pill indicator in `#2B1E16`. Also supported as interactive pill-toggle selectors.

### Cards
- **Product Card**: Background `#F5EFEB`, border `1px solid #E5DCD0`, corner radius `1rem` (`rounded-2xl`), padding `1.25rem`. Subtle lift on hover (`Elevation-1`).
- **Story / Editorial Card**: Cream ivory background (`#FDFBF7`), subtle divider hairline, asymmetric image placement, Playfair Display headers.

### Product-Specific Components
- **Roast Level Meter**: A 5-point organic pill step-indicator tracking roast depth from Cinnamon to Dark Roast using graduated tones of `#8C6A54` and `#2B1E16`.
- **Flavor Profile Radar / Tags**: Grouped clusters of tasting tags (e.g., "Dulce de Leche", "Jasmine", "Bergamot") featuring warm beige fills with espresso typography.
- **Grind Selector Bar**: Segmented horizontal pill control allowing seamless switching between Whole Bean, French Press, Pour Over, and Espresso.