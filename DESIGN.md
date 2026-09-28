---
name: Liquid Specular
colors:
  surface: '#131317'
  surface-dim: '#131317'
  surface-bright: '#39393e'
  surface-container-lowest: '#0e0e12'
  surface-container-low: '#1b1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#2a292e'
  surface-container-highest: '#353439'
  on-surface: '#e4e1e8'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#e4e1e8'
  inverse-on-surface: '#303035'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#131317'
  on-background: '#e4e1e8'
  surface-variant: '#353439'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.035em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.011em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.006em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
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
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-precision industrial glassmorphism tailored for optical-code generation, encrypted payload transfer, and spatial credentialing. The aesthetic fuses Apple’s polished visionOS and macOS architectural principles with high-end optics laboratory equipment.

### Core Character
- **Optical Clarifier**: Every pane of UI behaves like precision optical glass. Elements have tangible refraction, controlled light dispersion, and chromatic transmission.
- **Stealth Luxury**: Grounded in pitch-black void tones rather than muddy grays, allowing specular highlights and luminescent indicators to slice through the canvas with uncompromising clarity.
- **Architectural Rigor**: Clean geometry, strict squircle geometry, tight letterforms, and structural hierarchy counter the softness of blurred backgrounds, ensuring the tool feels enterprise-grade and dependable.

### Target Emotional Response
Users should feel the quiet confidence of holding a solid sapphire crystal prism—frictionless, impervious to error, and technologically advanced.

## Colors

The palette operates on absolute darkness punctuated by chromatic refraction and luminous status anchors.

### Base Canvases
- **Void Space**: `#08080C` anchors the absolute bottom layer of the viewport.
- **Obsidian Substratum**: `#0D0E15` provides structural contrast for canvas viewports, sidebars, and nested control trays.

### Glass Translucencies
- **Vessel Glass (Tier 1)**: `rgba(255, 255, 255, 0.04)` with `backdrop-filter: blur(40px) saturate(190%)`. Used for expansive backing cards and master panes.
- **Specular Glass (Tier 2)**: `rgba(255, 255, 255, 0.07)` with `backdrop-filter: blur(28px) saturate(210%)`. Used for floating inspectors, tool palettes, and modal cards.
- **Pressed Optical Layer (Tier 3)**: `rgba(255, 255, 255, 0.12)` with `backdrop-filter: blur(16px)`. Reserved for hovered pills, segmented controls, and embedded inputs.

### Chromatic Lighting & Accents
- **Electric Violet / Deep Indigo (`#6366F1`)**: Primary interface locus for primary callouts, active focus halos, and scanning beams.
- **Ethereal Cyan (`#06B6D4`)**: Secondary luminance used for telemetry readouts, data metrics, and dynamic code module nodes.
- **Hyper Emerald (`#10B981` / `#34D399`)**: Strictly functional signal reserved exclusively for cryptographic validation, verified redirects, active transmission links, and engine readiness.
- **Muted Titanium Silver (`#94A3B8`, `#64748B`)**: Structural secondary text and inactive icon fills that reject low-contrast muddiness.
- **Pure Specular White (`#FFFFFF`)**: Primary typography and pinpoint reflection dots.

## Typography

Typographic scale relies on the metric precision of Inter, deployed with deliberate optical tracking to match high-resolution Apple interface standards.

- **Display & Headlines**: Rendered in Semi-Bold weights with negative kerning to create dense, unified headline blocks that mimic physical signage engraved behind glass.
- **Body Elements**: Set at standard reading heights with balanced line spacing to offset the light refraction from background glass blurs.
- **Labels & Micro-Data**: Rendered with expanded tracking (`0.02em` to `0.06em`) and uppercase treatment when identifying spatial dimensions, cryptographic hashes, error-correction levels, and file capacities.

## Layout & Spacing

The canvas is constructed as a spatial, fluid grid framed by generous margins that make glass panels appear floating freely over the underlying dark ambient field.

### Grid & Breakpoints
- **Desktop (1200px+)**: 12-column dynamic grid. Outer margin of `3rem` (`48px`), column gutters of `1.5rem` (`24px`). Primary workstation view centers the live optical preview pane flanked by floating glass parameter drawers.
- **Tablet (768px - 1199px)**: 8-column layout. Margin of `2rem` (`32px`), gutters of `1.25rem` (`20px`). Control drawers collapse into bottom sheets or tabbed panels.
- **Mobile (<768px)**: 4-column layout. Margin of `1.25rem` (`20px`), gutters of `1rem` (`16px`). Tool panels become a fluid bottom-docked glass drawer with swipe-to-reveal controls.

### Architectural Rules
- Components float with consistent internal padding scales: `space-lg` for card bodies, `space-sm` to `space-md` for sub-panels and control groupings.
- Never place edge-to-edge opaque dividers; separation is achieved purely through negative spatial voids (`space-md` to `space-xl`) or translucent containment boundaries.

## Elevation & Depth

Depth is physical and refractive. Objects do not cast flat, generic dark drops; they displace light and reflect ambient illumination from background plasma orbs.

### Specular Edge Architecture
Every elevated glass panel is bounded by a directional 1px highlight:
- **Top / Light-Facing Edge**: `rgba(255, 255, 255, 0.16)` to `rgba(255, 255, 255, 0.24)`.
- **Bottom / Shadowed Edge**: `rgba(255, 255, 255, 0.03)` to `rgba(255, 255, 255, 0.0)`.
- **Implementation**: Applied via linear gradient stroke or `box-shadow: inset 0 1px 1px 0 rgba(255, 255, 255, 0.2)`.

### Tiered Elevation Stack
1. **Canvas Surface (0dp)**: Pure `#08080C` void space host to slowly shifting radial light orbs (Indigo: `rgba(99, 102, 241, 0.15)`, Cyan: `rgba(6, 182, 212, 0.10)`).
2. **Backdrop Card (Level 1)**: `rgba(255, 255, 255, 0.03)` background, 32px squircle radius, 40px backdrop blur, soft shadow `0 24px 48px -12px rgba(0, 0, 0, 0.6)`.
3. **Floating Palettes & Controls (Level 2)**: `rgba(255, 255, 255, 0.06)` background, 24px squircle radius, 28px backdrop blur, layered drop shadow `0 12px 32px -4px rgba(0, 0, 0, 0.5)`, inner glow `inset 0 0 12px rgba(255, 255, 255, 0.03)`.
4. **Active Overlays & Modals (Level 3)**: `rgba(255, 255, 255, 0.09)` background, 32px squircle radius, multi-layer shadow `0 32px 64px -8px rgba(0, 0, 0, 0.8), 0 0 40px rgba(99, 102, 241, 0.12)`.

## Shapes

The design system uses squircle radii that echo modern device hardware and optical lenses.

### Corner Radius System
- **Master Cards & Main Containers**: 24px to 32px (`1.5rem` - `2rem`). These wide curves preserve the illusion of a molded liquid glass slab.
- **Controls, Input Fields & Panels**: 12px to 16px (`0.75rem` - `1rem`). Balanced curvature for high-density functional controls.
- **Badges, Status Chips & Interactive Micro-pills**: Fully rounded pill shapes (`9999px`) to visually differentiate metadata from structural surfaces.
- **QR Alignment Blocks & Code Matrix Nodes**: Configurable optical squircle curves with an internal corner curvature matching the parent enclosure.

## Components

### Buttons
- **Primary Specular Action**: Pill or 14px squircle container filled with pure white `#FFFFFF` text against an ultra-subtle chromatic shift (`rgba(255, 255, 255, 0.92)` hover to full white). Top specular highlight `inset 0 1px 1px rgba(255, 255, 255, 0.8)`. Outer glow `0 0 24px rgba(99, 102, 241, 0.3)`.
- **Glass Secondary**: Transparent glass background (`rgba(255, 255, 255, 0.05)`), border `1px solid rgba(255, 255, 255, 0.12)`, text `#FFFFFF`. On hover, background elevates to `rgba(255, 255, 255, 0.10)` with border transitioning to cyan/indigo specular accent.
- **Destructive / Alert**: Translucent deep crimson wash `rgba(239, 68, 68, 0.12)` bounded by a directional red-tinted 1px edge highlight.

### Input Fields
- **Container**: 14px rounded squircle, background `rgba(255, 255, 255, 0.03)`, top-lit border `rgba(255, 255, 255, 0.10)`.
- **Text & Placeholder**: Value is crisp `#FFFFFF`, placeholder is muted titanium `#64748B`.
- **Focus State**: Ambient ring halo `0 0 0 1px #6366F1, 0 0 16px rgba(99, 102, 241, 0.35)`, background darkens slightly to `rgba(0, 0, 0, 0.4)` to heighten text legibility through the glass.

### Chips & Badges
- **Status Indicator**: Strict capsule pill (`9999px`), internal padding `4px 10px`. 
- **Live / Validated State**: Background `rgba(16, 185, 129, 0.08)`, border `1px solid rgba(52, 211, 153, 0.25)`, text `#34D399`. Contains a 6px breathing emerald light dot with pulse animation.
- **Telemetry Pill**: Background `rgba(255, 255, 255, 0.04)`, border `1px solid rgba(255, 255, 255, 0.08)`, text `#94A3B8`.

### Cards & Glass Stage
- **Primary Generator Viewport**: A centered 32px squircle floating slab with 48px blur backdrop. Houses the generated dynamic code vector. The perimeter carries an active 1px gradient stroke running from electric indigo at the top-left to translucent white at the bottom-right.
- **Embedded Inner Trays**: Contrast inset areas inside main cards using `rgba(0, 0, 0, 0.25)` to seat technical controls and data keys securely.

### Checkboxes & Segmented Controls
- **Segmented Control**: Encapsulated pill shell (`rgba(0, 0, 0, 0.35)`) containing a smooth sliding glass pill thumbnail (`rgba(255, 255, 255, 0.14)`) with specular edge highlight.
- **Checkboxes & Radios**: 8px rounded squares or circles with `rgba(255, 255, 255, 0.06)` base. Active state illuminates with solid `#6366F1` or `#10B981` core and subtle atmospheric bloom.