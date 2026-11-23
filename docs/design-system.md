---
name: Obsidian Kinetic
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#c1cab1'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#8c947d'
  outline-variant: '#424937'
  surface-tint: '#94da3a'
  primary: '#ffffff'
  on-primary: '#1f3700'
  primary-container: '#aff755'
  on-primary-container: '#447000'
  inverse-primary: '#406900'
  secondary: '#cebdff'
  on-secondary: '#381385'
  secondary-container: '#4f319c'
  on-secondary-container: '#bea8ff'
  tertiary: '#ffffff'
  on-tertiary: '#31312c'
  tertiary-container: '#e5e2db'
  on-tertiary-container: '#65645f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#aff755'
  primary-fixed-dim: '#94da3a'
  on-primary-fixed: '#102000'
  on-primary-fixed-variant: '#2f4f00'
  secondary-fixed: '#e8ddff'
  secondary-fixed-dim: '#cebdff'
  on-secondary-fixed: '#21005e'
  on-secondary-fixed-variant: '#4f319c'
  tertiary-fixed: '#e5e2db'
  tertiary-fixed-dim: '#c9c6c0'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#474742'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 5rem
    fontWeight: '700'
    lineHeight: 5rem
    letterSpacing: -0.04em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: 3.125rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: 3.75rem
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.025em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.025em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0em
  code:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.375rem
    letterSpacing: 0em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.08em
  stat-lg:
    fontFamily: JetBrains Mono
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system establishes an authentic, experimental, yet disciplined digital platform for a student-led creative technology collective. Drawing directly from Gen Z digital subcultures, post-digital brutalism, and avant-garde editorial publications, the aesthetic rejects the homogenizing tropes of modern software design: there are zero amorphous purple blurs, no generic drop shadows, and no decorative skeuomorphic bloat.

### Visual Philosophy
- **Neo-Brutalist Precision:** Structural honesty where structural dividers, hair-thin technical borders, coordinate stamps, and monospaced diagnostic markers double as ornamentation.
- **Editorial Contrast:** Extreme scale shifts between gargantuan headlines set with aggressive negative tracking and compact, scannable technical metadata.
- **Controlled Friction:** Intentional asymmetric layouts, dense content grids, and deliberate physical-print nods (index cards, catalog markers, ticket stamps) that invite exploration rather than passive consumption.
- **Tone:** Radical, intellectually rigorous, street-smart, and uncompromisingly technical.

## Colors

The color architecture is built for pure dark mode, prioritizing extreme contrast and high-efficiency visual hierarchy.

### Core Architecture
- **Canvas Base (`#0B0B0D`):** An obsidian backdrop that provides void-level contrast without clipping absolute black.
- **Surface Elevation (`#141419`):** A dense ink layer used to structure modules, inspectable panels, and card matrices.
- **High-Impact Accent — Acid Lime (`#B6FF5C`):** Deployed with surgical discipline. Used strictly for focus states, interactive triggers, terminal badges, status pings, and critical anchors. Never flooded across wide backgrounds.
- **Sub-Accent — Soft Lavender (`#A78BFA`):** Used to delineate conceptual tags, secondary metadata branches, and generative project stamps.
- **Typographic Tiers:** 
  - Primary: Warm Cream (`#F4F1EA`) at 100% opacity for maximum readability and physical-print warmth.
  - Secondary: Muted Concrete (`#A4A1AA`) for descriptive runs, auxiliary keys, and supporting copy.
- **Structural Lines:**
  - Ambient Divider: `#222228` (1px structure and subtle compartmentalization).
  - High-Contrast Border: `#33333D` (active frames, focal interactive boundaries, and pinned containers).

## Typography

Typography acts as the primary visual architecture of the collective. The combination of three contrasting typefaces creates a high-tension balance between raw power, clarity, and computational logic.

### Typeface Roles
- **Headlines (`Space Grotesk`):** Dense, kinetic, bold. Display sizes must use strict negative tracking (`-0.03em` to `-0.04em`) with tight leading to produce solid typographic blocks reminiscent of Swiss brutalist posters.
- **Reading Body (`Inter`):** Neutral, crisp, and invisible. Used to balance experimental headline treatments with friction-free legibility in essays, case studies, and descriptions.
- **Telemetry & Labels (`JetBrains Mono`):** Applied to indices, catalog numbers, dates, tags, and data readouts. Rendered uppercase with expanded tracking (`0.08em`) to enforce technical veracity.

## Layout & Spacing

The layout model combines an asymmetrical 12-column editorial grid on desktop with a disciplined 4-column system on mobile devices.

### Grid & Composition Rules
- **Desktop (12 Columns):** Breakpoint `1024px+`. Spans operate on deliberate tension—e.g., pairing a massive 7-column project title with an offset 5-column technical spec block. Margins set to `3rem` with `1.5rem` gutters.
- **Tablet (8 Columns):** Breakpoint `768px - 1023px`. Fluid adaptations where column spans snap into balanced halves or thirds. Margins set to `2rem`.
- **Mobile (4 Columns):** Breakpoint `<768px`. Content reflows vertically into structured stacked index tiers. Canvas margins compress to `1.25rem` with `1rem` gutters.
- **Rule Dividers:** Grid boundaries are explicitly marked using visible `1px` lines (`#222228`) running continuously across columns and rows, avoiding floating whitespace gaps in favor of concrete structural framing.

## Elevation & Depth

This system discards conventional soft box-shadows and blurred depth layers entirely. Spatial hierarchy is communicated through high-contrast boundary definition, surface shifts, and physical-inspired offsets.

### Depth Mechanics
- **Zero-Shadow Default:** Components rest directly on the surface plane. Visual separation is accomplished using explicit `1px` borders (`#222228` ambient, `#33333D` foreground) or color contrast shifts between `#0B0B0D` and `#141419`.
- **Hard-Edge Neo-Brutalist Offset:** For elevated interactive elements, floating action banners, or triggered state dialogs, use sharp 2px or 4px hard offsets without blur:
  - `box-shadow: 4px 4px 0px 0px #B6FF5C;` (Accent state)
  - `box-shadow: 3px 3px 0px 0px #33333D;` (Neutral active state)
- **Overlay Panels:** Modals and flyout drawers utilize a flat `#141419` fill framed by a crisp `#33333D` border, backed by a darkened canvas mask (`rgba(11, 11, 13, 0.85)`) without soft blurs.

## Shapes

The shape system is strictly **Sharp (0px)** across all foundational modules, panels, buttons, cards, and input fields. 

### Geometry Rules
- **Pure Angles:** Every corner is an unyielding 90-degree angle. This reinforces mechanical authority and digital craftsmanship.
- **Notched & Ticket Corners (Controlled Variation):** For special artifacts—such as project badges, conference pass tickets, or experimental tags—components may feature geometric 45-degree corner cutouts (chamfers) using CSS clip paths (`4px` to `8px`), maintaining angular integrity without soft radiuses.
- **Full Radius Exception:** Circular elements are strictly reserved for functional status indicators (e.g., active pulsing server pings) or avatar cutouts. Chips, buttons, and structural containers must never have pill-shaped corners.

## Components

### Buttons
- **Primary Action:** Solid Acid Lime fill (`#B6FF5C`), pure black text (`#0B0B0D`), font `JetBrains Mono` semi-bold uppercase, 0px border radius. Hover triggers an inverted state (`#F4F1EA` fill with `#0B0B0D` text) or a hard offset shadow (`3px 3px 0px #F4F1EA`).
- **Secondary Action:** Transparent background, `1px solid #33333D`, text `#F4F1EA`. On hover: border transitions to `#B6FF5C` and text shifts to `#B6FF5C`.
- **Tertiary Action:** Raw text link styled with monospaced brackets (e.g., `[ EXPLORE ARCHIVE ]`), shifting to `#B6FF5C` on hover.

### Chips & Metadata Badges
- **Editorial Stamp / Tag:** Framed in `1px solid #222228`, filled with `#141419`. Uses `label-caps` in `JetBrains Mono` (`0.75rem`, tracked out).
- **Status Indicator:** Prepends a mini square or monospace glyph (`[•] LIVE`) in `#B6FF5C` or `#A78BFA`.

### Input Fields & Controls
- **Input Fields:** Flat `#141419` surface with `1px solid #222228` border, zero border-radius, font `Inter` (`0.9375rem`), text `#F4F1EA`. On focus: border shifts instantly to `#B6FF5C` with no outer glow.
- **Checkboxes & Radios:** Sharp square indicators (`16px x 16px`) with `1px solid #33333D`. Active selection fills with `#B6FF5C` displaying an obsidian interior check or solid inner square.

### Cards & Project Frames
- **Modular Project Tile:** Built using `#141419` surface and surrounded by `1px solid #222228`. Includes an explicit top metadata strip (e.g., `PROJ_08 // 2025`) rendered in `#A4A1AA` `JetBrains Mono` separated by a horizontal rule before imagery or headline.
- **Hover Interaction:** Card border sharpens to `#33333D`, headline tints to `#B6FF5C`, with an optional `3px 3px 0px #B6FF5C` hard-offset projection.

### Lists & Tables
- **Telemetry Data Rows:** Border-bottom `1px solid #222228`. High-contrast grid distribution with numeric identifiers left-aligned in monospaced muted gray and interactive targets right-aligned. Hover states initiate a subtle background flash to `#141419`.