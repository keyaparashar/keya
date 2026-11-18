---
name: KEYA'S दिल Editorial Architecture
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c9c6c5'
  secondary: '#0028c2'
  on-secondary: '#ffffff'
  secondary-container: '#0138ff'
  on-secondary-container: '#c8ceff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#3e001f'
  on-tertiary-container: '#fc0d91'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#dee0ff'
  secondary-fixed-dim: '#bbc3ff'
  on-secondary-fixed: '#000e5e'
  on-secondary-fixed-variant: '#002cce'
  tertiary-fixed: '#ffd9e3'
  tertiary-fixed-dim: '#ffb0ca'
  on-tertiary-fixed: '#3e001f'
  on-tertiary-fixed-variant: '#8d004e'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 112px
    fontWeight: '800'
    lineHeight: 96px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 68px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Work Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lead:
    fontFamily: Work Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: -0.005em
  body-default:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 25px
    letterSpacing: 0em
  body-sm:
    fontFamily: Work Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 19px
    letterSpacing: 0.01em
  mono-annotation:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
  mono-label:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.04em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 4rem
---

## Brand & Style

This design system establishes an avant-garde digital publishing apparatus operating at the intersection of high-fashion print editorial, Swiss typographic discipline, and Tokyo brutalist visual culture. Built for a bilingual, transcultural contemporary art and cultural publication, the interface rejects modern SaaS homogenization—dispensing with soft pill shapes, cheerful illustrations, and decorative shadows—in favor of authoritative typographic cadence, deliberate structural tension, and razor-sharp planar hierarchy.

### Aesthetic Principles
- **Editorial Monumentality:** Massive display type treats language as architecture. Scaled glyphs collide with razor-thin structural dividers and precise micro-annotations.
- **Asymmetric Grid Dynamic:** Strict underlying column mechanics disrupted by off-axis placements, overlapping typographic boundaries, and stark white space voids.
- **Micro-Technical Cataloging:** Archival taxonomy inspired by Japanese art books—running volume indices, geographic coordinates, frame anchors, bilingual metadata, and issue datelines.
- **Dual-Script Typographic Equilibrium:** Intentional integration of Latin grotesque letterforms with authentic Devanagari script weights, respecting the distinct vertical rhythm and headline bar of each script without synthetic distortion.

## Colors

The palette operates on stark, museum-grade binary contrast energized by two laser-grade accent pigments. Surfaces evoke heavy-weight uncoated archival paper, never sterile digital gray.

### Functional Palette Logic
- **Canvas / Paper (`#FCFBF9`):** Archival warm white base. Acts as the physical substrate across light mode.
- **Ink Primary (`#0a0a0a`):** Dense carbon black. Applied to structural rules, monumental typography, and primary interactive solids.
- **Electric Ultramarine (`#0038FF`):** Pure optical blue used for active editorial indexes, metadata stamps, navigational pivots, and dynamic focus states.
- **Electric Hot Pink (`#FF1493`):** High-tension punctuation. Reserved for issue markers, critical callouts, Devanagari ligature highlights, and live exhibition alerts.
- **Hairline Rule (`rgba(10, 10, 10, 0.15)`):** Ultra-fine structural boundaries defining the layout grid.

## Typography

The typographic hierarchy establishes tension between the monumental sculptural presence of **Syne**, the rationalist editorial neutrality of **Work Sans**, and the calibrated technical rigor of **JetBrains Mono**.

### Typographic Directives
- **Script Handling:** The Devanagari mark **दिल** sits beside Latin typography at matching optical stem-weights. In headline configurations, the shirorekha (top hanging line) provides a rigid horizontal baseline reference for adjacent Latin caps.
- **Case Discipline:** Technical annotations (`mono-annotation`, `mono-label`) are universally uppercase, rendered with strict tabular numerals and expanded tracking.
- **Editorial Micro-Index:** Essays, photo spreads, and critiques must feature a running mono marker containing issue volume, catalog index, and reading duration (e.g., `VOL.04 // ESSAY.12 // 28.6139° N, 77.2090° E`).

## Layout & Spacing

The system enforces an asymmetric 12-column editorial grid on desktop and an unyielding 4-column system on mobile devices, characterized by deliberate column voids and unaligned margins.

### Grid & Composition Rules
- **Breakpoints:**
  - **Mobile:** `< 768px` (4 columns, `1.25rem` outer margins, `1rem` gutters)
  - **Tablet:** `768px – 1199px` (8 columns, `2rem` outer margins, `1.5rem` gutters)
  - **Desktop:** `≥ 1200px` (12 columns, `3.5rem` outer margins, `2.5rem` gutters)
- **Asymmetric Spans:** Standard reading text spans 6 to 7 columns off-center (e.g., Columns 4–10). Columns 1–3 are reserved for floating metadata, footnotes, and Devanagari pull-glyphs.
- **Edge-to-Edge Collisions:** Visuals break the margin boundary into absolute bleeding edges, juxtaposed immediately with ultra-dense typographic blocks.

## Elevation & Depth

This system strictly rejects drop shadows, blurs, and pseudo-skeuomorphic depth. Depth is articulated purely through tonal planes, overlapping geometry, and hard-edged graphic contrast.

### Elevation Principles
- **No Diffusion:** Shadow blur radii are globally prohibited (`box-shadow: none`).
- **Hard Tonal Layering:** Layering is achieved by stacking absolute high-contrast fields—e.g., a solid Ink Black panel overlaid directly against Paper Cream, separated only by a 1px solid hairline or zero-gap perimeter.
- **Planar Stacking:** Elevated or modal elements (such as audio essays, issue drawer overlays, or glossary terms) slice into the canvas as absolute geometric cut-outs framed by `1px solid #0a0a0a`.
- **Text Layering:** Monumental Syne display type may underlap or overlap visual frames with a CSS mix-blend mode (`difference`), prioritizing compositional tension over conventional web layering.

## Shapes

The shape system is strictly non-rounded (`0px` corner radius throughout). No curved corners, rounded container outlines, or pill badges may be introduced. 

### Geometric Rules
- **Zero Radius:** Every button, card, image frame, modal window, tag, and text input features razor 90-degree corners.
- **Structural Lines:** Dividers and box frames use a standard `1px` thickness. Heavy divider accents expand to `4px` or `8px` solid black bars to anchor section shifts.
- **Framing Indicators:** Corner crop marks (e.g., `+` or right-angle ticks `⌐`) may be placed at container bounds to echo physical printing plates and editorial layout software.

## Components

Components embody physical editorial layouts: stark, tactile, high-contrast, and monospaced-driven.

### Buttons & Interactive Links
- **Primary Action:** Solid `#0a0a0a` rectangle with `#FCFBF9` typography in `JetBrains Mono` (uppercase, tracked). Hover reverses instantaneously to solid `#0038FF` background or inverted stroke without transition delays.
- **Editorial Action:** Text-only link with an unpadded bottom border (`1px solid #0a0a0a`). On hover, the border shifts to `#FF1493` with an immediate upward 1px typographic nudge.
- **Never Use:** Floating action buttons, curved corners, pill shapes, or gradient fills.

### Chips, Tags & Volume Indexes
- **Structure:** Hard rectangular framing (`1px solid #0a0a0a`), zero border-radius.
- **Typographic Treatment:** `mono-annotation` font style.
- **Active State:** Solid fill in `#0038FF` with white text, or solid `#FF1493` for live/critical issue tags. Prefix every index with a hash or bracket notation (e.g., `[ISSUE_04]` or `// ARCHIVE`).

### Lists & Content Indexes
- **Editorial Index:** Grid-aligned, horizontal tabular rows. Left column houses the index count (`001`, `002`), center column displays the article title in `Syne` or `Work Sans`, right column shows category and page number in `JetBrains Mono`.
- **Dividers:** Each row is segregated by a `1px solid rgba(10, 10, 10, 0.15)` hairline. Hovering over a row highlights the index numeral in `#0038FF`.

### Input Fields & Controls
- **Inputs:** Minimalist bottom-border-only (`2px solid #0a0a0a`) or strict 4-sided `1px` rectangular boxes with `#FCFBF9` ground. No placeholder text that disappears ambiguously; static micro-labels sit permanently pinned outside the input perimeter in `JetBrains Mono`.
- **Checkboxes & Radios:** Custom square checkmarks (`14px x 14px`) with sharp 90-degree corners. Checked state is marked with a centered solid black square or an electric hot pink crosshair.

### Cards & Editorial Modules
- **Editorial Frame:** Flat white or cream canvas with a distinct `1px solid #0a0a0a` boundary. Imagery within cards adheres strictly to zero border radius and contains caption stamps directly within the lower edge of the image frame.
- **Meta Header:** Cards feature a running top header bar separating the category, catalog coordinates, and date before the headline block begins.