---
name: UTM Engineering Portfolio
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#584143'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#8b7172'
  outline-variant: '#dfbfc1'
  surface-tint: '#ad2e47'
  primary: '#510016'
  on-primary: '#ffffff'
  primary-container: '#7a0026'
  on-primary-container: '#ff7b8d'
  inverse-primary: '#ffb2b9'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#18272f'
  on-tertiary: '#ffffff'
  tertiary-container: '#2e3d45'
  on-tertiary-container: '#97a7b1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdadc'
  primary-fixed-dim: '#ffb2b9'
  on-primary-fixed: '#400010'
  on-primary-fixed-variant: '#8c1331'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#d5e5ef'
  tertiary-fixed-dim: '#b9c9d3'
  on-tertiary-fixed: '#0e1d25'
  on-tertiary-fixed-variant: '#3a4951'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
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
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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

This design system blends academic prestige with modern engineering precision. Built around Universiti Teknologi Malaysia’s heritage, the interface balances institutional gravitas and forward-thinking technical innovation.

### Target Audience
Engineering recruiters, industry partners, academic committees, research evaluators, and peer engineers seeking evidence of technical rigor, design aptitude, and project execution.

### Emotional Response
The interface evokes authority, disciplined craftsmanship, analytical clarity, and academic prestige. It rejects frivolous decorative trends in favor of structural symmetry, crisp data displays, and purposeful hierarchy.

### Design Movement
**Modern Technical / Academic Precision**: A refined hybrid of corporate-modern structure and architectural brutalist undertones. Visual rhythm relies on strict geometric alignment, crisp 1px hair lines, tactile micro-elevations, restrained warm-gold metallic accents, and high-legibility typography suitable for technical documentation and complex project portfolios.

## Colors

The palette honors Universiti Teknologi Malaysia's visual identity, utilizing UTM Maroon as the primary anchor and engineering Gold for selective technical highlights.

### Functional Roles
- **Primary (`#7A0026`)**: UTM Maroon. Anchors structural navigation, hero elements, primary interactive states, active indicators, and high-level milestones.
- **Secondary (`#D4AF37`)**: Academic Gold. Reserved for honors, high-impact project badges, metric highlights, key KPI values, and focused micro-interactions.
- **Tertiary (`#2B3A42`)**: Technical Slate. Applied to secondary data visualizations, code and schematics blocks, metadata tags, and technical subheadings.
- **Neutral Primary (`#1A1A1A`)**: Deep Charcoal. Primary reading color for all high-contrast typography, structural outlines, and strong icon fills.
- **Neutral Tonal Palette**:
  - Surface Background: `#F8F9FA` (Soft Industrial Light Gray)
  - Card & Container Surface: `#FFFFFF` (Pure White)
  - Surface Muted: `#EEF0F2` (Dividers, data table striping, inactive states)
  - Subtle Border: `#E2E5E8` (Engineered 1px structural grid lines)
  - Secondary Text: `#59656E` (Specifications, metadata, timestamps)
  - Semantic Status: Success `#1B7F49`, Alert `#C05621`, Danger `#A82222`.

### Contrast & Hierarchy
Backgrounds default to pure white or `#F8F9FA`. Maroon is never used behind body copy unless inside high-contrast solid hero elements containing pure white `#FFFFFF` text. Gold is paired with `#1A1A1A` or `#7A0026` to preserve WCAG AAA readability.

## Typography

The typographic pairing reflects engineering discipline:

1. **Display & Headings (Space Grotesk)**: Geometric, structural, and modern. Its mechanical subtleties evoke drafting tools and tech specs while maintaining executive posture.
2. **Body (Hanken Grotesk)**: Crisp, neutral, and readable across long-form research descriptions, project abstracts, and system designs.
3. **Labels & Metadata (JetBrains Mono)**: A monospaced typeface dedicated to project tags, commit hashes, technical specifications, timelines, and quantitative metrics.

### Typographic Rules
- Always render section categorization, chronological timestamps, and telemetry badges in `JetBrains Mono` with uppercase transformation where appropriate.
- Headlines maintain tight negative letter spacing (`-0.01em` to `-0.03em`) to deliver architectural impact.
- Numerical data in project breakdowns should use monospaced figures to ensure columnar scanability.

## Layout & Spacing

The layout is grounded in a 12-column responsive fluid grid designed around clean 4px/8px modular units. It accommodates diverse engineering deliverables including CAD previews, schematic diagrams, timeline sequences, and publication listings.

### Responsive Breakpoints & Columns
- **Desktop (1200px and up)**: 12-column fluid grid, `3rem` section margins, `1.5rem` gutters. Max canvas constraint set to `1280px` for readability.
- **Tablet (768px – 1199px)**: 8-column fluid grid, `2rem` section margins, `1.25rem` gutters.
- **Mobile (below 768px)**: 4-column fluid grid, `1.25rem` section margins, `1rem` gutters. Project cards and timeline entries reflow into full-width single-column blocks.

### Spacing Philosophy
- Use `space-xs` (4px) and `space-sm` (8px) for tightly coupled metadata, inline badges, and button interiors.
- Use `space-md` (16px) for interior component padding, list items, and form elements.
- Use `space-lg` (24px) for card body padding, timeline item offsets, and section sub-groupings.
- Use `space-xl` (40px) for segment separations, grid breaks, and hero container vertical rhythm.

## Elevation & Depth

To match modern engineering precision, depth is conveyed through layered tonal borders, crisp surface contrasts, and subtle ambient shadows rather than diffuse skeuomorphism.

### Depth Layers
- **Base Canvas (`#F8F9FA`)**: Resting background for the overall application frame.
- **Surface Level 0 (`#FFFFFF`)**: Standard cards, project containers, and documentation surfaces. Outlined with `1px solid #E2E5E8`.
- **Surface Level 1 (Raised)**: Interactive states, hovering project cards, and active timeline indicators.
  - Box Shadow: `0px 4px 12px -2px rgba(26, 26, 26, 0.06), 0px 1px 3px 0px rgba(122, 0, 38, 0.04)`
  - Border transition: Shifts from `#E2E5E8` to `#7A0026` (UTM Maroon) at 30% opacity.
- **Surface Level 2 (Floating & Modals)**: Schematics lightboxes, PDF viewers, and navigation overlays.
  - Box Shadow: `0px 12px 28px -4px rgba(26, 26, 26, 0.12), 0px 4px 8px -2px rgba(26, 26, 26, 0.04)`
  - Border: `1px solid #D4AF37` (Subtle Gold highlight) or `#E2E5E8`.

### Engineering Accent Line
Cards and timeline milestones feature an optional structural accent: a 2px top or left border rendered in UTM Maroon (`#7A0026`) or Gold (`#D4AF37`) to indicate project status, patent achievements, or primary focus areas.

## Shapes

The design system uses a strict **Soft (Level 1)** geometric standard. Engineering blueprints and CAD software rely on disciplined geometry; rounded corners are restrained to maintain technical sharpness.

### Corner Radius Standards
- Base radius: `0.25rem` (4px) applied to primary buttons, input fields, code blocks, technical chips, and inner containers.
- Medium/Large radius: `0.5rem` (8px) for main project cards, timeline wrapper panels, and interactive dialogue boxes.
- Circular elements (`rounded-full`): Strictly restricted to user avatar portraits, status light nodes, and timeline connector dots.

## Components

### Buttons
- **Primary**: Solid UTM Maroon (`#7A0026`) background, `#FFFFFF` text, `0.25rem` radius. Left or right icons (e.g., download thesis, view schematic). Hover state darkens background to `#5E001D`.
- **Secondary / Technical**: Pure white surface, `1px solid #7A0026` border, `#7A0026` text. Hover state introduces `#7A0026` at 5% tint.
- **Accent (Honors / Demo)**: Solid Gold (`#D4AF37`) background with dark `#1A1A1A` text. Hover state brightens gold to `#E2BF4D`.
- **Ghost / Code**: JetBrains Mono label, `#1A1A1A` text, transparent background. Hover gives light `#EEF0F2` fill.

### Badges & Chips
- **Engineering Tag**: `#EEF0F2` background, `#2B3A42` text, `0.25rem` border-radius, `label-sm` monospaced font.
- **Gold Merit Badge**: `#FFFDF0` surface, `1px solid #D4AF37` outline, `#8F7317` text. Displays awards, dean's list mentions, and patents.
- **UTM Maroon Pill**: High-contrast identifier for department, discipline (e.g., "B.Eng Electrical", "MJIIT"), with Maroon fill and white mono text.

### Timeline
- **Milestone Line**: Continuous vertical or horizontal `2px` track in `#E2E5E8`.
- **Node**: Dual-ring marker: outer ring `12px` solid `#FFFFFF` with `2px solid #7A0026`; inner center `4px` dot in `#D4AF37` for major career milestones.
- **Content Block**: White surface card with `1px solid #E2E5E8`, displaying timestamp (`label-md`), milestone title (`headline-sm`), and concise descriptive bullet points.

### Project Cards
- **Structure**: High-contrast white box with a `2px` top hairline in UTM Maroon.
- **Visual Zone**: Fixed aspect ratio (16:9) engineering asset preview (renders, hardware photos, circuit blueprints) with subtle inner border.
- **Meta Bar**: Monospaced status line indicating tools/technologies used (e.g., `MATLAB // SOLIDWORKS // C++`).
- **Body**: Space Grotesk headline, two-sentence impact abstract, and embedded metric readout (e.g., "Efficiency: +24%").

### Form Fields & Inputs
- **Base Input**: `#FFFFFF` background, `1px solid #E2E5E8` border, `15px` Hanken Grotesk text, `0.25rem` border radius.
- **Active / Focused**: Border shifts to `#7A0026` with a crisp `2px` ring in `rgba(122, 0, 38, 0.15)`. No fuzzy glow.
- **Labels**: JetBrains Mono uppercase (`label-sm`), `#59656E` tone.

### Checkboxes & Radio Controls
- **Square / Circle Form**: `18px` boundary with `1.5px solid #59656E`.
- **Checked State**: Solid `#7A0026` fill with crisp white checkmark or inner dot.

### Data Metrics & KPI Displays
- Large numerical readouts rendered in Space Grotesk Bold paired with JetBrains Mono unit indicators (e.g., `98.4` `kHz`).
- Underlined with a thin gold accent separator (`#D4AF37`) to signify engineering validation.