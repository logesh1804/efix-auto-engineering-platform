---
name: Precision Engineering System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3d4a42'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6d7a72'
  outline-variant: '#bccac0'
  surface-tint: '#006c4a'
  primary: '#006948'
  on-primary: '#ffffff'
  primary-container: '#00855d'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dba9'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#00685f'
  on-tertiary: '#ffffff'
  tertiary-container: '#008378'
  on-tertiary-container: '#f4fffc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85f8c4'
  primary-fixed-dim: '#68dba9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
  surface-base: '#FFFFFF'
  surface-subtle: '#F8FAFC'
  surface-muted: '#F1F5F9'
  border-subtle: '#E2E8F0'
  border-strong: '#CBD5E1'
  accent-cyan: '#06B6D4'
  accent-electric-blue: '#2563EB'
  status-active: '#10B981'
  text-primary: '#0F172A'
  text-secondary: '#475569'
  text-muted: '#64748B'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  technical-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
  label-status:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  space-4xl: 6rem
  grid-margin-desktop: 3rem
  grid-margin-mobile: 1.25rem
  grid-gutter-desktop: 1.5rem
  grid-gutter-mobile: 0.75rem
  container-max-width: 1440px
---

## Brand & Style

This design system delivers a clean, high-precision industrial engineering aesthetic tailored for automotive diagnostic, telemetry, and hardware-grade platform interfaces. The visual language conveys institutional trust, forensic diagnostic clarity, and cleanroom lab precision. 

The aesthetic synthesizes modern technical minimalism with deliberate hardware instrumentation cues:
- **Cleanroom Brightness:** Pure white (#FFFFFF) and architectural off-white (#F8FAFC) canvas foundations provide clinical clarity and high contrast.
- **Instrument Precision:** Crisp hair-thin structural borders, precise geometric alignments, and subtle PCB circuit trace motifs anchor interactive containers.
- **Controlled Chromatic Energy:** Diagnostic emerald greens, cyan-teal spectrums, and rich telemetry blues serve strictly as functional indicators, status monitors, and intentional directional gradients—avoiding neon saturation or cyberpunk styling in favor of authentic industrial lab technology.
- **Target Audience:** Automotive electrical engineers, diagnostic specialists, fleet technical directors, and hardware integration developers who require instant legibility, deterministic status signals, and zero visual friction.

## Colors

The color palette is built upon a deterministic chromatic scale optimized for clinical contrast and automotive telematics:

- **Primary Diagnostic Emerald (`#059669` / `#10B981`):** Represents verified systems, pass states, primary command buttons, and active diagnostic integrity.
- **Secondary Telematics Blue (`#0284C7` / `#2563EB`):** Applied to core navigational systems, primary interactive states, data bus readouts, and engineering infrastructure.
- **Tertiary Bus Teal (`#0D9488` / `#06B6D4`):** Bridges green and blue channels for secondary telemetry, data protocols, sensor groupings, and auxiliary status monitors.
- **Neutral Navy Slate (`#0F172A` / `#1E293B`):** Anchors all typographic hierarchies, high-contrast structural data tables, and crisp visual demarcations. Never use pure black (`#000000`) for text; deep navy slate preserves optical density while maintaining formal sophistication.
- **Surfaces & Borders:** Default backgrounds rely strictly on cleanroom white (`#FFFFFF`) layered over structured off-white panes (`#F8FAFC`, `#F1F5F9`). Structural borders use crisp cool grays (`#E2E8F0`, `#CBD5E1`) at 1px thickness.
- **Linear Gradient Accents:** Hardware headers, primary metric cards, and key promotional telemetry bars leverage an analytical 135-degree linear gradient running from Emerald (`#059669`) through Cyan-Teal (`#0D9488`) into Rich Blue (`#0284C7`). Gradients must never be used as text fills; they are reserved for 2px-to-4px structural indicator lines, border strokes, and primary hero accents.

## Typography

The typographic hierarchy balances structural engineering geometry, rapid text scanning, and hardware-grade data density:

- **Display & Headlines (`Space Grotesk`):** Provides sharp, mechanical sans-serif forms with geometric character terminals. Used for page banners, section titles, and high-level platform modules. Tight negative letter spacing reinforces engineering cohesion.
- **Body Text (`Hanken Grotesk`):** A modern, neutral grotesk that guarantees optimal legibility across documentation, fault reports, instructions, and user controls.
- **Technical Specs & Hardware Telemetry (`JetBrains Mono`):** Deployed for all VINs, OBD-II error codes, memory register addresses, firmware checksums, chip revisions, and micro-metrics. 
- **Uppercase Labels (`label-caps`):** Rendered strictly with `JetBrains Mono` at 11px with `0.08em` letter tracking to indicate sensor channels, state modes, and industrial categories.

## Layout & Spacing

The layout system is founded upon an exact 8px base rhythm (with 4px half-steps for micro-components), reflecting high-precision engineering schematics.

- **Grid Framework:**
  - **Desktop (>=1280px):** 12-column fluid system within a max-width envelope of `1440px`. Gutters sit at `24px` (`1.5rem`), outer margins at `48px` (`3rem`).
  - **Tablet (768px - 1279px):** 8-column layout with `16px` (`1rem`) gutters and `24px` margins.
  - **Mobile (<768px):** 4-column layout with `12px` (`0.75rem`) gutters and `20px` (`1.25rem`) side margins.
- **Density & Alignment:**
  - Diagnostic dashboards and device telemetry screens prioritize high-density layout modes: compact vertical paddings (`space-sm` to `space-md`) prevent paging during critical hardware analysis.
  - Informational, marketing, and institutional pages transition into expanded vertical section spacing (`space-3xl` to `space-4xl`), framing precision cards against airy cleanroom backdrops.

## Elevation & Depth

Visual hierarchy uses crisp clinical layering, subtle surface tonal differences, and multi-stop ambient diffusion rather than heavy dark drop shadows:

- **Surface Tonal Stacking:**
  - `Level 0 (Canvas):` Deep cleanroom background (`#F8FAFC`).
  - `Level 1 (Card & Module Foundation):` Pure solid white (`#FFFFFF`) with a 1px perimeter border (`#E2E8F0`).
  - `Level 2 (Active Panels / Flyouts / Dropdowns):` Pure white surface elevated with an ambient shadow: `0 4px 16px -2px rgba(15, 23, 42, 0.05), 0 2px 6px -1px rgba(15, 23, 42, 0.03)` paired with border `#CBD5E1`.
  - `Level 3 (Diagnostic Modals / Floating Telemetry Bars):` High-clarity elevation with `0 16px 36px -4px rgba(15, 23, 42, 0.08), 0 4px 12px -2px rgba(15, 23, 42, 0.04)`.
- **PCB Trace Overlay Details:**
  - Specialized diagnostic cards feature an ultra-faint structural circuit trace: a fine 1px linear stroke (`#E2E8F0` at 60% opacity) running horizontally with a 45-degree chamfered lead-in, simulating printed circuit board traces across module headers.
- **Interactive State Elevation:**
  - On hover, interactive cards do not move upward excessively; they elevate by 1px while the perimeter border transitions to an active emerald or blue gradient accent border, signaling precision electrical continuity.

## Shapes

The design system employs a calibrated modern radius standard, matching high-end automotive test hardware and precision CNC-machined enclosures:

- **Base Radii:**
  - Core container modules, equipment display cards, and data groupings use `rounded-xl` (`1rem` / `16px`) and `rounded-2xl` (`1.5rem` / `24px`).
  - Interactive controls (buttons, inputs, select fields) use `rounded-lg` (`0.5rem` / `8px`) for immediate ergonomic affordance.
  - Badges, technical register tags, and status dots leverage fully pill-shaped contours (`9999px`) to juxtapose against the structured box grid.
- **Chamfers & Cut-Corner Accents:**
  - Hardware status badges and firmware version banners may feature micro 45-degree industrial chamfer cutoffs on the upper-right corner (4px) to accentuate electronic lab aesthetics.

## Components

### Buttons
- **Primary Technical Button:**
  - Solid Emerald fill (`#059669`) transitioning to `#047857` on hover.
  - Text: `#FFFFFF`, weight 600, `Hanken Grotesk`.
  - Border radius: `8px`. Padding: `10px 20px`.
  - Optional subtle gradient overlay: `linear-gradient(180deg, rgba(255, 255, 255, 0.12) 0%, rgba(0, 0, 0, 0.04) 100%)`.
- **Secondary Telemetry Button:**
  - Surface: `#FFFFFF`.
  - Border: 1px solid `#CBD5E1`. On hover: 1px solid `#0284C7`, text `#0284C7`, background `#F0F9FF`.
  - Text: `#0F172A`, weight 600.
- **Hardware Action Button (Ghost / Monospace):**
  - Text: `JetBrains Mono` 12px, tracking `0.04em`, uppercase.
  - Border: 1px dashed `#CBD5E1`.

### Cards & Telemetry Containers
- Background: `#FFFFFF`.
- Border: 1px solid `#E2E8F0`.
- Border radius: `16px` (`rounded-xl`).
- Internal padding: `24px`.
- Hardware Header Bar: A top border accent of 2px height using the brand gradient (`linear-gradient(90deg, #059669 0%, #06B6D4 50%, #0284C7 100%)`) for primary analytical panels.

### Status Chips & Badges
- Format: Inline pill badges (`rounded-full`) with an internal active ping or solid dot (6px).
- **Pass / Active:** Background `#ECFDF5`, border 1px solid `#A7F3D0`, text `#065F46`, font `JetBrains Mono` 11px.
- **Telemetry Processing:** Background `#F0F9FF`, border 1px solid `#BAE6FD`, text `#075985`, font `JetBrains Mono` 11px.
- **Diagnostic Alert:** Background `#FEF2F2`, border 1px solid `#FECACA`, text `#991B1B`, font `JetBrains Mono` 11px.

### Inputs & Hardware Selectors
- Background: `#FFFFFF`.
- Height: `44px`.
- Border: 1px solid `#CBD5E1`. Radius: `8px`.
- Typographic style: `Hanken Grotesk` 14px for inputs; numeric/register fields default to `JetBrains Mono`.
- Active Focus State: 1px solid `#059669` accompanied by a crisp 3px outer ring: `0 0 0 3px rgba(5, 150, 105, 0.15)`.

### Checkboxes & Radio Controls
- Base: 18px x 18px square (checkbox: 4px radius; radio: circular).
- Inactive: 1.5px border `#94A3B8`, background `#FFFFFF`.
- Active: Background `#059669`, border `#059669`, with pure white high-contrast tick or center pip.

### Lists & Data Tables
- Header Row: Background `#F8FAFC`, border-bottom 1px solid `#E2E8F0`, uppercase `JetBrains Mono` 11px text in `#64748B`.
- Content Rows: Alternating zebra striping avoided in favor of crisp 1px `#F1F5F9` bottom divider lines. Hover row triggers `#F8FAFC` background shift with active left indicator bar (2px `#0284C7`).
- Numbers and hex codes always right-aligned and rendered in `JetBrains Mono`.

### Specialized Hardware Component: Diagnostic Bus Readout
- Encapsulated component simulating real-time ECU/OBD-II stream.
- Background: `#F8FAFC` recessed box with 1px inset border `#E2E8F0`.
- Includes live heartbeat status pulse (`#10B981`), port spec (`OBD-II / CAN-FD`), and high-density hex output styling.