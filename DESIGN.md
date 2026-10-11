---
name: Fracture Editorial
colors:
  surface: '#15130e'
  surface-dim: '#15130e'
  surface-bright: '#3b3933'
  surface-container-lowest: '#0f0e09'
  surface-container-low: '#1d1c16'
  surface-container: '#21201a'
  surface-container-high: '#2c2a24'
  surface-container-highest: '#37352f'
  on-surface: '#e7e2d9'
  on-surface-variant: '#c4caac'
  inverse-surface: '#e7e2d9'
  inverse-on-surface: '#32302a'
  outline: '#8e9479'
  outline-variant: '#434933'
  surface-tint: '#a8d700'
  primary: '#ffffff'
  on-primary: '#273500'
  primary-container: '#c0f500'
  on-primary-container: '#546d00'
  inverse-primary: '#4f6600'
  secondary: '#ffb3b0'
  on-secondary: '#660611'
  secondary-container: '#862024'
  on-secondary-container: '#ff9995'
  tertiary: '#ffffff'
  on-tertiary: '#1f333f'
  tertiary-container: '#d0e5f5'
  on-tertiary-container: '#536774'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c0f500'
  primary-fixed-dim: '#a8d700'
  on-primary-fixed: '#161f00'
  on-primary-fixed-variant: '#3b4d00'
  secondary-fixed: '#ffdad8'
  secondary-fixed-dim: '#ffb3b0'
  on-secondary-fixed: '#410006'
  on-secondary-fixed-variant: '#862024'
  tertiary-fixed: '#d0e5f5'
  tertiary-fixed-dim: '#b5c9d9'
  on-tertiary-fixed: '#081e29'
  on-tertiary-fixed-variant: '#364956'
  background: '#15130e'
  on-background: '#e7e2d9'
  surface-variant: '#37352f'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 96px
    letterSpacing: 0.02em
  display-hero-mobile:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-xl:
    fontFamily: Anton
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 60px
    letterSpacing: 0.02em
  headline-xl-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  editorial-quote:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  meta-mono:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-caps:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.12em
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
  space-xl: 3rem
---

## Brand & Style

This design system embodies editorial brutalism merged with the urgent, tactile materiality of historical protest ephemera and contemporary underground culture. It operates as an uncompromising broadsheet and critical archive: deliberate, confrontational, rigorous, and devoid of cosmetic sheen. 

The aesthetic is characterized by raw structural lines, strict geometric discipline, mechanical metadata stamps, dense modular containers, and stark physical contrast. There are no soft shadows, radial gradients, or decorative micro-radii. Visual impact relies on severe typographic tension, hard division lines, heavy contrast between archival paper and void surfaces, and high-visibility signal accents that evoke terminal readouts and emergency flyers.

## Colors

The palette reproduces the tactile conditions of radical print and digital counter-culture:

- **Void Black (`#111110`)**: The dominant base canvas. A deep, soot-derived black that acts as the primary ground for digital readout and archival storage.
- **Archive Paper (`#F0EDE5`)**: Uncoated, raw document paper. Used for inverted high-impact editorial broadsheets, text placards, and severe contrast blocks.
- **Signal Acid (`#C8FF00`)**: The primary interactive strike. Used strictly for focus indicators, live editorial timestamps, active tab flags, terminal tickers, and hover inversions. Never diluted or feathered.
- **Oxblood (`#7A171D`)**: Secondary accent. Denotes historical contextual markers, critical dossiers, sensitive archival flags, and deep editorial warnings.
- **Neutral Gray (`#AAA69E`)**: Mid-tone functional tone for body metadata, footnote citations, secondary captions, and disabled states.
- **Structural Lines (`#353530` / `#D3CFC5`)**: High-precision boundary markers. `#353530` serves as the dominant grid divider against Void surfaces, while `#D3CFC5` structures white-paper inserts.

## Typography

Typography acts as architecture. The system relies on four typographic roles:

- **Display (`Anton`)**: Set strictly in uppercase with compressed line-heights. Reserved for primary issue titles, manifestos, category stamps, and aggressive editorial headlines.
- **Editorial Headings & Body (`Space Grotesk`)**: Technical, stark, and modern. Balances clinical clarity with geometric tension across running texts and investigative dossiers.
- **Metadata & Dossiers (`Space Mono`)**: Tabular, monospaced notation for source citations, filing codes, timestamps, author dispatches, and technical tables.
- **Expressive Accents (`Bricolage Grotesque`)**: Deployed for pull quotes, investigative sub-commentary, polemical excerpts, and dynamic marginalia.

## Layout & Spacing

The layout is grounded in a modular 12-column architectural broadsheet grid. Every layout boundary is visible or mechanically aligned:

- **Desktop (1024px+)**: 12 columns with 1.5rem (`gutter-desktop`) gutters and 3rem (`margin-desktop`) margins. Components lock into strict grid units (1, 2, 3, 4, 6, 8, or 12 columns).
- **Tablet (768px – 1023px)**: 6 or 8 columns with 1rem gutters and 2rem outer margins.
- **Mobile (320px – 767px)**: 2 or 4 columns with 1rem gutters and 1rem outer margin. Content flows vertically with explicit 1px horizontal rule divisions.

Surfaces use zero offset spacing between contiguous modules; adjacent cards and panels share structural line borders instead of floating with outer margins. Content padding inside elements follows strict steps: `space-xs` (tags/badges), `space-sm` (dense table cells), `space-md` (standard modular containers), `space-lg` (article headers), and `space-xl` (section breaks).

## Elevation & Depth

This system rejects simulated three-dimensional light sources. Visual hierarchy is established entirely through structural borders, tonal inversion, and planar layering:

- **Bold Outlines & Grid Borders**: Depth is communicated via 1px and 2px solid lines (`#353530` on dark canvas, `#D3CFC5` on light paper). Content boxes snap together as contiguous cells.
- **Tonal Contrast & Inversion**: High-priority modules break the dark void canvas by switching directly to `#F0EDE5` (Archive Paper) with `#111110` text, reading as physical broadsheet sheets pasted onto digital structures.
- **Physical Overlays**: Overlays, dialogs, and dossiers do not employ soft backdrop blurs or diffuse shadows. They feature hard 2px solid borders, solid opaque backgrounds, or high-contrast diagonal cross-hatch scrims.

## Shapes

All shapes across the system are absolutely sharp:

- All buttons, input fields, containers, modals, images, tags, and tabs feature `0px` border-radius (`roundedness: 0`).
- Cropping of photographs, diagrams, and video embeds must be strictly rectangular or square. No circular avatars or pill containers are permitted under any circumstance; user and contributor identifiers are displayed as rectangular photo crops or bracketed monospaced alphanumeric indices.

## Components

### Buttons & Interactive Controls
- **Primary Button**: Solid `#C8FF00` background, `#111110` text, `0px` radius, 1px solid `#C8FF00`. Font is `Space Mono` uppercase bold (`label-caps`). On hover, inverts to `#111110` background with `#C8FF00` text and 1px border.
- **Secondary Button**: `#111110` surface, 1px solid `#353530`, text in `#F0EDE5`. On hover, the border changes to `#C8FF00` with text colored `#C8FF00`.
- **Destructive / Archive Button**: Deep `#7A171D` background with `#F0EDE5` monospaced text and 1px `#7A171D` border.

### Chips, Tags & Badges
- Displayed as bracketed or hard-bordered modules (e.g., `[ DISPATCH ]` or bordered rectangle).
- Padding: `space-xs` vertically, `space-sm` horizontally.
- Typeset in `meta-mono`. In active or live states, prefixed with a solid square glyph (`■`) rendered in `#C8FF00`.

### Lists & Modular Dossiers
- Structured with continuous horizontal dividers (`1px solid #353530`).
- Left-hand column features tabular index numbering (`001`, `002`, `003`) in `#AAA69E` (`Space Mono`).
- Hovering a list row highlights the row’s left-hand border with a 3px accent in `#C8FF00`.

### Form Elements (Inputs, Checkboxes, Radios)
- **Inputs**: Flat `#111110` background, 1px solid `#353530`, text `#F0EDE5` in `Space Grotesk`. Focus state applies a 1px solid `#C8FF00` ring with zero offset and zero blur.
- **Checkboxes**: Hard 16x16px square, 1px solid `#AAA69E`. Checked state fills the box completely with `#C8FF00` containing a solid void black inner square.
- **Radio Buttons**: Hard 16x16px square (no circular radios). Selected state contains a centered, non-rounded inner square marker in `#C8FF00`.

### Editorial Cards
- Framed by 1px solid borders (`#353530`).
- Card headers feature an explicit metadata strip containing category, timestamp, and issue code set in `meta-mono`.
- Imagery inside cards sits flush against the container borders without internal margin or curved clipping.
- Selected or featured cards alternate with an inverted ground of `#F0EDE5` paper canvas with `#111110` typography.

### Bespoke Elements
- **Terminal Ticker**: Edge-to-edge marquis bar bounded by top and bottom 1px lines, streaming archival briefs and status updates in `label-caps`.
- **Dossier Header**: High-density editorial metadata block containing classification level, clearance tag, and coordinates rendered in Oxblood (`#7A171D`) and Signal Acid (`#C8FF00`).