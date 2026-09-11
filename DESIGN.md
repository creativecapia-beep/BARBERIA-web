---
name: Haute Grooming & Barber Heritage
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#e9c176'
  primary: '#e9c176'
  on-primary: '#412d00'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#775a19'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#e1c561'
  on-tertiary: '#3b2f00'
  tertiary-container: '#bea443'
  on-tertiary-container: '#473a00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#fee179'
  tertiary-fixed-dim: '#e1c561'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#554500'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Bodoni Moda
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Bodoni Moda
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.18em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.04em
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system channels an elevated haute-parfumerie and bespoke artisanal barbering heritage. Rooted in traditional craftsmanship yet rendered with razor-sharp editorial restraint, the experience evokes the atmosphere of a private members' atelier: rich, quiet confidence, aromatic pomades, warm aged brass, and impeccably tailored precision.

The style merges **Minimalist High Fashion** with **Atelier Craftsmanship**. It avoids cliché vintage distress in favor of sharp, unyielding 90-degree architecture, hairline gold framing, deep charcoal surfaces, and dramatic high-contrast serif typography. The emotional response is refined dignity, exclusivity, and master-level trust.

## Colors

The palette is anchored in an abyss of obsidian and charcoal, energized by warm antique gold and burnished brass accents.

- **Primary (`#C5A059`)**: Muted antique gold representing bespoke luxury, applied to primary CTAs, hairline ornamental frames, and selected status badges.
- **Secondary (`#D4AF37`)**: Radiant artisan gold reserved for interactive hover states, metallic shimmer highlights, and active indicators.
- **Tertiary (`#E6CA65`)**: Pale champagne amber, leveraged sparingly for delicate filigree rules, small badge borders, and fine accents.
- **Neutral Deep (`#0D0D0D`)**: The primary canvas, presenting pure abyssal contrast without pitch-black flatness.
- **Surface Elevation Layers**: `#141414` (Tier 1 Surface / Cards) and `#1E1E1E` (Tier 2 Surface / Interactive Overlays).
- **Text & Editorial Elements**: `#F5F5F7` (High-contrast ivory text) and `#A0A0A0` (Secondary muted parchment grey for metadata and captions).

## Typography

The typography establishes a tension between timeless European atelier editorial and contemporary Swiss legibility. 

- **Bodoni Moda** carries the display weight. Its extreme stroke contrast, delicate serifs, and high-fashion vertical stress bring an air of luxury grooming ritual. Headlines use tight letter spacing and deliberate line-heights.
- **Plus Jakarta Sans** provides pristine functional balance. Used for continuous prose, navigation, and administrative UI, it delivers rapid scanability in mobile appointment booking flows.
- **Uppercase Labels**: All system badges, timestamps, categories, and step markers rely on `label-caps` set in full uppercase with expansive tracking (`0.18em`) to mimic engraved luxury packaging.

## Layout & Spacing

The layout is built upon a mobile-first modular rhythm using an 8-point structural system, scaling into a structured 12-column desktop grid.

- **Mobile Viewport (<768px)**: A 4-column layout with `margin-mobile` (1.25rem) and `gutter-mobile` (0.75rem). Elements span full width or split evenly in dual booking cards.
- **Desktop Viewport (≥1024px)**: A 12-column layout capped at a maximum container width of 1280px, maintaining generous `margin` (3rem) to evoke an uncrowded, curated lookbook.
- **Rhythm & White Space**: Generous vertical section offsets (`space-xl` multiplied for tier separators) allow photography and gold linear accents to breathe without clutter.

## Elevation & Depth

In alignment with the sharp, zero-radius aesthetic, this system strictly avoids diffused dropshadows. Depth is articulated through **tonal stratification** and **hairline metal boundaries**:

1. **Base Layer (`#0D0D0D`)**: The void background.
2. **Surface Tier 1 (`#141414`)**: Service selection cards, schedule matrices, and drawer canvases; differentiated with a 1px border of `rgba(197, 160, 89, 0.18)`.
3. **Surface Tier 2 (`#1E1E1E`)**: Active modal overlays, floating booking trays, and hover states; accented by a crisp 1px border of `rgba(197, 160, 89, 0.45)`.
4. **Subtle Amber Ambient Light**: High-tier active cards utilize an internal golden inset glow (`inset 0 0 16px rgba(197, 160, 89, 0.04)`) evoking the warm backlighting of a boutique grooming mirror.

## Shapes

The interface embraces an architectural, strictly rectilinear geometry (`roundedness: 0`). 

All corners—buttons, text fields, cards, badges, and modals—are constructed at 90 degrees with zero border-radius. This uncompromising geometry references bespoke razor blades, classic leather-strapped steamer trunks, and fine fragrance packaging, delivering a tailored, masculine posture.

## Components

### Buttons
- **Primary Action (Solid Gold)**: Rectangular zero-radius, filled with `#C5A059`, text in `#0D0D0D` set in `label-caps`. Hover triggers a shift to `#D4AF37` with an expanded tracking animation.
- **Secondary Action (Hairline Frame)**: Transparent background, 1px border `#C5A059`, text in `#F5F5F7`. Hover fills with `rgba(197, 160, 89, 0.1)`.
- **Tertiary Action (Understated Link)**: Text in `#C5A059` with a subtle 1px baseline rule positioned 4px beneath the text.

### Cards & Service Folios
- Constructed with `#141414` fill and 1px `#262626` outline.
- Active or highlighted tier displays an ornamental double hairline border at the top and bottom edges using `#C5A059`.
- Typography within service cards highlights duration and price in `label-caps` alongside the ritual title in `headline-sm`.

### Input Fields & Booking Selectors
- Solid `#141414` fill with bottom-border-only emphasis (`1px solid #333333`).
- On focus, bottom border transitions to `#C5A059` with zero corner smoothing. Floating labels shift in `label-caps` formatting.

### Checkboxes & Radios
- Sharp 16px squares.
- Unchecked: 1px border `#333333`, transparent interior.
- Checked: `#C5A059` solid fill with an inset `#0D0D0D` geometric square center indicator.

### Chips & Barber Badges
- Zero-radius tags with 1px border of `rgba(197, 160, 89, 0.3)`. Text rendered in `label-caps` with `#F5F5F7`.

### Bespoke Domain Components
- **Service Ledger**: A menu list featuring dotted brass leaders connecting service names to prices.
- **Artisanal Seal**: A square badge with a 1px border containing year of establishment and monogram iconography, anchoring hero and footer regions.
- **Barber Availability Selector**: Horizontal mobile-swipe day strip, displaying active days highlighted with a solid `#C5A059` upper border tick.