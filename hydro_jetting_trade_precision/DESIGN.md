---
name: Hydro Jetting Trade Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#c2dcff'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e5efff'
  surface-container-high: '#dbe9ff'
  surface-container-highest: '#d1e4ff'
  on-surface: '#001d36'
  on-surface-variant: '#44474c'
  inverse-surface: '#17324d'
  inverse-on-surface: '#e9f1ff'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#525f71'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0f1c2c'
  on-primary-container: '#778598'
  inverse-primary: '#bac8dc'
  secondary: '#a33e00'
  on-secondary: '#ffffff'
  secondary-container: '#ff742d'
  on-secondary-container: '#602100'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001c39'
  on-tertiary-container: '#3c86d7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#ffdbcd'
  secondary-fixed-dim: '#ffb596'
  on-secondary-fixed: '#360f00'
  on-secondary-fixed-variant: '#7c2e00'
  tertiary-fixed: '#d3e3ff'
  tertiary-fixed-dim: '#a3c9ff'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#004883'
  background: '#f8f9ff'
  on-background: '#001d36'
  surface-variant: '#d1e4ff'
  technical-blue-bright: '#2B8FE8'
  surface-cream: '#F8FAFC'
  surface-panel: '#E2E8F0'
  warning-amber: '#F59E0B'
  success-teal: '#0D9488'
  pipe-dark: '#070E17'
typography:
  headline-xl:
    fontFamily: Oswald
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Oswald
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Oswald
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Oswald
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: 0em
  headline-md:
    fontFamily: Oswald
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Oswald
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-technical:
    fontFamily: Oswald
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.12em
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

This design system embodies high-stakes commercial and municipal infrastructure maintenance. It blends industrial durability, precision engineering, and responsive trade dispatch. Designed for commercial facility managers, municipal water superintendents, and homeowners facing plumbing emergencies, the interface evokes immediate reliability, rugged competence, and operational authority.

The aesthetic fuses **Modern High-Contrast Trade UI** with **Technical Industrial Brutalism**:
- **Tactile Grid Clarity:** Structural paneling, pronounced technical lines, and clear geometric zoning mimic industrial control consoles and architectural schematics.
- **Safety-Critical Hierarchy:** Mission-critical elements (e.g., 24/7 emergency dispatch, PSI telemetry, flow rate indicators) use high-visibility industrial orange and sharp geometric badges.
- **Zero Ambiguity:** Crisp borders, crisp typographic contrasts, and structured data layouts replace decorative visual noise.

## Colors

The palette directly reflects high-pressure water machinery and infrastructure work:
- **Primary Navy (`#0D1B2A`):** The structural core of the platform. Used for dense headers, structural frames, navigation bars, and primary authority text.
- **Industrial Safety Orange (`#E8631A`):** Reserved strictly for immediate action cues, emergency dispatch triggers, high-priority notifications, and key phone conversions. Never diluted or used for extensive background fills.
- **Technical Blue (`#1A6FBF`) & Technical Blue Bright (`#2B8FE8`):** Represents water jet pressure dynamics, active system telemetry, secondary verification badges, and interactive focus states.
- **Neutral Blue-Slate (`#415A77`):** Bridges heavy structure with readable content, providing calibrated contrast for subtext, table borders, and metadata.
- **Surface Layering:** Neutral backgrounds sit between pristine white (`#FFFFFF`) for primary data canvases and structured panel tone (`#F8FAFC` and `#E2E8F0`) for mechanical framing.

## Typography

The type system balances industrial condensation with utilitarian legibility:
- **Headings (Oswald):** Condensed, punchy, and confident. Transforms titles into bold trade statements reminiscent of equipment branding, architectural callouts, and industrial signage. Always set in uppercase for operational alerts, metrics, and top-level page banners.
- **Body & Data (DM Sans):** Neutral, highly legible grotesque sans-serif that withstands rapid scanning under harsh outdoor lighting or field-mobile conditions.
- **Technical Labels (`label-technical`):** Rendered in Oswald uppercase with expanded tracking (`0.12em`) to denote equipment specs (e.g., `4000 PSI / 18 GPM`), pipe diameters, certification codes, and real-time status monitors.

## Layout & Spacing

The layout is grounded in a disciplined 12-column modular grid designed for trade service presentation:
- **Desktop (1024px+):** 12-column fixed grid with a max-width of 1280px, `3rem` canvas margins, and `1.5rem` gutters. Splits cleanly into 8/4 splits for primary content vs. live dispatch cards, or 4/4/4 splits for service capabilities.
- **Tablet (768px - 1023px):** 8-column layout with `2rem` outer margins and `1.25rem` gutters. Technical specification sidebars collapse below hero panels.
- **Mobile (< 768px):** 4-column layout with `1.25rem` outer margins and `1rem` gutters. High-impact emergency dispatch strips dock to the viewport base with strict vertical stacking.
- **Grid Structure:** Grid intersections employ 1px hairline divider strokes in `#E2E8F0` or `#0D1B2A` rather than excessive empty whitespace, reinforcing the architectural draftsmanship aesthetic.

## Elevation & Depth

Visual hierarchy prioritizes crisp tactile separation over diffuse shadows:
- **Structural Planar Tiers:** Depth is established primarily via high-contrast border definition and contrasting background planes (e.g., `#0D1B2A` containers nested against `#F8FAFC` base floors).
- **Crisp Cut Borders:** Cards, inputs, and modular panels feature crisp `1px` or `2px` solid borders (`#0D1B2A` for primary emphasis; `#E2E8F0` for secondary structural containment).
- **Hard Technical Shadows:** Elevated surfaces (e.g., floating dispatch action bars, sticky estimation summary cards) utilize directional, non-diffused offset drop shadows:
  - `elevation-low`: `0 2px 0 0 #0D1B2A`
  - `elevation-high`: `4px 4px 0 0 #0D1B2A`
- **Emergency Inset Glow:** Dedicated critical alert banners leverage a focused internal highlight: `inset 0 0 0 2px #E8631A`.

## Shapes

The shape system is strictly **Sharp (0)**.
- Precision engineering leaves no room for soft curves. Buttons, container corners, input fields, and tags utilize `0px` radius.
- Angled cuts (45-degree chamfers of 8px) may be applied via CSS clip-path to top-right corners of primary action cards and status badges to evoke sheet-metal fabrication and industrial warning labels.
- Structural borders use consistent 1px and 2px stroke weights to ensure visual cohesion across data panels.

## Components

### Buttons & Action Bars
- **Primary Dispatch Button:** Solid `#E8631A` background, `#FFFFFF` text, `0px` border radius, uppercase Oswald typography, `1.25rem` horizontal padding, paired with a `4px 4px 0 0 #0D1B2A` hard offset shadow. Active state depresses `2px` down and right.
- **Technical Secondary Button:** Ghost style with a `2px` solid `#0D1B2A` border, transparent background, text in `#0D1B2A`. Hover transitions immediately to solid `#0D1B2A` with `#FFFFFF` text.
- **Phone / Emergency Hotline Button:** Deep `#0D1B2A` fill with `#E8631A` left-border accent bar (6px thick) and live pulse indicator badge.

### Badges & Technical Indicators
- **Spec Badges:** Compact rectangular tags with `1px` solid borders, uppercase `label-technical` tracking, and tinted fills:
  - Hydro Jetting Specs: `#1A6FBF` text over `#1A6FBF1A` background.
  - Emergency/Active Status: `#E8631A` text over `#E8631A15` background with a solid `1px` `#E8631A` border.
  - Certified/Licensed: `#0D9488` text over `#0D948815` background.

### Input Fields & Selectors
- Background is `#FFFFFF` with a rigid `2px` solid `#0D1B2A` border.
- Label sits directly above in `label-md` uppercase DM Sans.
- Placeholder text set in `#415A77` at 60% opacity.
- Focus state switches the border to `#1A6FBF` with a `2px` offset outline, maintaining zero corner rounding.

### Service & Telemetry Cards
- **Base Card:** Clean white `#FFFFFF` surface bordered by a crisp `1px` `#E2E8F0` stroke. Header zone features a solid `#0D1B2A` title block with white Oswald text.
- **High-Trust Feature Card:** Heavy left boundary marked by a 4px solid `#E8631A` stroke, containing structured metadata tables (pipe diameter range, PSI capacity, pricing transparency guarantee).

### Checkboxes & Segmented Controls
- Checkboxes are square (`18px x 18px`), `2px` solid `#0D1B2A` borders, with solid `#E8631A` fill and white checkmark when active.
- Segmented switches feature industrial mechanical toggles with hard borders and no pill shapes.