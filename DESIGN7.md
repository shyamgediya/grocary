---
name: Warm Editorial Craft
colors:
  surface: '#f9f9fc'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#55433e'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#88726c'
  outline-variant: '#dbc1ba'
  surface-tint: '#97472e'
  primary: '#94452c'
  on-primary: '#ffffff'
  primary-container: '#b35c41'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59f'
  secondary: '#536256'
  on-secondary: '#ffffff'
  secondary-container: '#d6e7d7'
  on-secondary-container: '#58685c'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59f'
  on-primary-fixed: '#3a0a00'
  on-primary-fixed-variant: '#793019'
  secondary-fixed: '#d6e7d7'
  secondary-fixed-dim: '#bacbbc'
  on-secondary-fixed: '#101f15'
  on-secondary-fixed-variant: '#3b4a3f'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 3.5rem
    fontWeight: '400'
    lineHeight: 4.25rem
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 2.5rem
    fontWeight: '400'
    lineHeight: 3rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 2.5rem
    fontWeight: '400'
    lineHeight: 3.25rem
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 1.875rem
    fontWeight: '400'
    lineHeight: 2.5rem
  headline-md:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.25rem
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.8125rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 2rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system embodies an intersection of Scandinavian functionalism and Japanese wabi-sabi ceramics. Built for an artisan tableware atelier, the interface emphasizes quiet luxury, tactile mindfulness, and editorial breathing room.

The emotional resonance is deliberate, grounding, and calm—analogous to holding an unglazed, wood-fired stoneware vessel. Interactions must feel measured rather than hurried. Visual weight relies heavily on expansive whitespace, poetic asymmetrical layouts, and earthy material honesty.

## Colors

The palette draws directly from studio raw materials: wet slip, mineral glazes, kiln flame, and raw clay bodies.

- **Primary (`#C86D51`)**: Terracotta Clay. Applied purposefully for primary calls to action, active navigation markers, and focal indicators.
- **Secondary (`#6B7B6E`)**: Muted Sage Olive. Reflects celadon reduction glazes; utilized for secondary accents, badges, tags, and supportive iconography.
- **Tertiary (`#D4AF37`)**: Antique Kiln Gold. Reserved for subtle highlights, awards, certifications, and limited edition flourishes.
- **Neutral (`#1E2022`)**: Deep Charcoal Slate. Replaces pure black to preserve organic softness across high-contrast typography and structural hairline dividers.
- **Background Tones**: Base canvas rests on warm ivory (`#FAF8F5`), with secondary content planes and cards set on warm sand (`#F3EFEA`).

## Typography

The type system balances the literary elegance of Playfair Display with the clean geometry and high legibility of Plus Jakarta Sans.

- Headings use Playfair Display with generous line heights and tight tracking on large scales, lending an editorial curation tone reminiscent of art monographs.
- Body copy uses Plus Jakarta Sans at regular weights (`400`), prioritizing open tracking and relaxed vertical rhythm to ensure comfortable reading across production descriptions, provenance notes, and care guides.
- Micro-labels, category tags, and action buttons employ Plus Jakarta Sans uppercase tracking (`0.06em` to `0.08em`) at weights `600` for clear hierarchy without visual heaviness.

## Layout & Spacing

A 12-column responsive fluid grid enforces structure while accommodating asymmetrical, gallery-style editorial arrangements.

- **Desktop (≥ 1024px)**: 12 columns, 64px (`4rem`) outer margins, 32px (`2rem`) gutters. Content is allowed room to breathe with broad vertical spacing (`space-xl` and above) between curated sections.
- **Tablet (768px - 1023px)**: 8 columns, 32px (`2rem`) outer margins, 24px gutters.
- **Mobile (< 768px)**: 4 columns, 20px (`1.25rem`) outer margins, 16px (`1rem`) gutters. Full-bleed imagery alternates with padded textual passages to maintain editorial pacing.

## Elevation & Depth

Visual depth eschews harsh artificial drop shadows in favor of material warmth and diffused illumination:

- **Ambient Stratification**: Surfaces stack naturally using hue variations (Warm Ivory base `#FAF8F5` against Warm Sand panels `#F3EFEA`).
- **Diffused Earth Shadows**: When floating overlays, drawers, or modal sheets require elevation, use an ultra-soft clay-tinted shadow: `0 12px 32px -4px rgba(30, 32, 34, 0.06), 0 4px 12px -2px rgba(200, 109, 81, 0.04)`.
- **Refined Borders**: Structural boundaries rely on single-pixel hairline strokes using `#E8E2D9` (Warm Sand stroke) rather than dark dividing lines, emulating architectural joins and parchment framing.

## Shapes

The shape system adopts subtle softening (`roundedness: 1`), honoring hand-thrown pottery edges that are neither razor-sharp nor overly synthetic:

- Base interactive items (inputs, buttons, select fields) implement `0.25rem` (4px) corner radii.
- Media tiles, cards, and modal sheets scale to `0.5rem` (8px) using `rounded-lg`.
- Floating chips and pill-style status pills explicitly permit full border-radius caps to balance the subtle exterior geometry.

## Components

### Buttons
- **Primary**: Solid Terracotta (`#C86D51`) background, warm ivory text, subtle `0.25rem` radius. Padding: `0.75rem 1.75rem`. Hover transitions to a darkened earthenware tone (`#B45E44`) with no elevation shift.
- **Secondary**: Transparent background, 1px solid stroke in Deep Charcoal Slate (`#1E2022`), Charcoal text. Hover fills with `#F3EFEA`.
- **Text / Editorial Action**: Raw text with an animated bottom border offset by `4px`, set in `label-md` tracking.

### Cards
- **Product & Editorial Cards**: Flat background (`#FAF8F5` or `#F3EFEA`), hairline border (`1px solid #E8E2D9`). No drop shadow in default state; hover introduces a faint ambient shadow and smooth image scale (1.02x). Product photography is framed with a standard 4:5 aspect ratio.

### Input Fields
- Understated rectangular forms with a `1px` stroke in `#DCD6CD`, filling with `#FAF8F5`. Text set in `body-md`. Focus transitions the stroke to Primary Terracotta (`#C86D51`) without an outer glow. Helper text utilizes `body-sm` in a softened charcoal tint.

### Chips & Badges
- Glaze/material attributes (e.g., "Unglazed Stoneware", "Celadon Glaze") utilize small pill shapes with muted backgrounds: Sage Olive background (`#EBEFEA`) with dark green text (`#3B463E`), or Sand background (`#EFEBE5`) with charcoal text.

### Selection Controls (Checkboxes & Radios)
- Custom minimal checkboxes with delicate `1px` borders. Checked states fill with `#C86D51` using a warm ivory custom check glyph. Radio buttons retain concentric rings with a 4px gap between indicator and rim.

### Atelier Additions
- **Material Swatch Pickers**: Circular 28px diameter clay and glaze swatches with a floating 2px ring offset on selection.
- **Provenance Accordion**: Clean border-bottom dividers (`#E8E2D9`) featuring `headline-sm` headers with quiet `+` / `−` indicators, providing space for craftsman notes and kiln batch details.