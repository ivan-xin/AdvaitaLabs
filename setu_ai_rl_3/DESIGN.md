---
name: Sovereign Protocol
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
  on-surface-variant: '#c0c6d6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8b91a0'
  outline-variant: '#414754'
  surface-tint: '#aac7ff'
  primary: '#aac7ff'
  on-primary: '#003064'
  primary-container: '#3e90ff'
  on-primary-container: '#002957'
  inverse-primary: '#005db8'
  secondary: '#e6feff'
  on-secondary: '#003739'
  secondary-container: '#00f4fe'
  on-secondary-container: '#006c71'
  tertiary: '#ffb868'
  on-tertiary: '#482900'
  tertiary-container: '#ce7f00'
  on-tertiary-container: '#3f2300'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aac7ff'
  on-primary-fixed: '#001b3e'
  on-primary-fixed-variant: '#00468d'
  secondary-fixed: '#63f7ff'
  secondary-fixed-dim: '#00dce5'
  on-secondary-fixed: '#002021'
  on-secondary-fixed-variant: '#004f53'
  tertiary-fixed: '#ffddbb'
  tertiary-fixed-dim: '#ffb868'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#673d00'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The brand personality is authoritative, immutable, and technologically advanced. It is designed for a target audience of protocol engineers, AI researchers, and governance participants who value cryptographic certainty and verifiable execution.

The design system adopts a **Sovereign Tech / Industrial Cyberpunk Lite** aesthetic. It leans into a refined, high-contrast dark mode that balances the raw utility of developer tools with the sophisticated finish of premium enterprise software. The UI should evoke a sense of "observing the machine"—transparent, precise, and absolute. Key stylistic hallmarks include:
- **Precision Engineering:** Sharp lines, monospaced data readouts, and surgical grid alignment.
- **Glassmorphism Lite:** Subtle translucency on high-level containers to suggest depth within a virtualized stack.
- **Functional Luminescence:** Using vibrant accent colors strictly for state signaling (verification, critique, execution) against a muted, obsidian backdrop.

## Colors
The palette is centered on **Obsidian Dark**, creating a non-reflective environment where technical data becomes the focal point.

- **Primary (Deep Tech Blue):** Used for primary actions, focus states, and signifying the core "trusted" path of the network.
- **Success/Finalized (Neon Teal):** Reserved for cryptographic proof, finalized blocks, and verified agent outputs. It should "glow" against the dark background.
- **Challenge/Warning (Electric Orange):** Used for deliberation conflicts, slashed stakes, or pending critiques.
- **Surface (Midnight Grey):** The primary container color, providing enough contrast against the background to define structural layers without breaking the dark immersion.

## Typography
The typography strategy utilizes a dual-font approach to distinguish between human-readable deliberation and machine-executable provenance.

**Geist** is used for all interface elements, headings, and body text. Its geometric precision and wide apertures maintain legibility in low-light environments and reinforce the modern, technical feel.

**JetBrains Mono** is reserved for "System Data." This includes hash values, transaction IDs, logic clocks, and status indicators. Using a monospace font for these elements signals to the user that this data is the result of a deterministic process. All labels and data snippets should be set in monospace to emphasize the underlying protocol execution.

## Layout & Spacing
The layout follows a **Fixed Grid** system for desktop to maintain the structural integrity of complex data visualizations, switching to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for desktop (max-width 1440px) with 24px gutters.
- **Rhythm:** An 8px linear scale governs all padding and margins to ensure a tight, mathematical feel.
- **Data Density:** Use "Compact" spacing for data-heavy views (nodes, logs) and "Spacious" padding for high-level deliberation summaries.
- **Breakpoints:** 
  - Mobile: < 768px (4 columns, 16px margins)
  - Tablet: 768px - 1024px (8 columns, 24px margins)
  - Desktop: > 1024px (12 columns, 64px margins)

## Elevation & Depth
In the Sovereign Protocol, depth is achieved through **Tonal Layering** and **Glassmorphism**, rather than traditional drop shadows.

1.  **Level 0 (Base):** Obsidian Dark (#050505).
2.  **Level 1 (Cards/Containers):** Midnight Grey (#121212) with a 1px stroke of #1F2937.
3.  **Level 2 (Modals/Overlays):** Midnight Grey with 60% opacity, 20px backdrop blur, and a subtle Primary Blue inner glow (0.5px).

Visual hierarchy is reinforced by **Low-contrast outlines**. Components should feel like they are part of a HUD (Heads-Up Display), where borders define the physical limits of a module within the network stack. Shadows, if used, should be restricted to a very subtle, non-blurred 2px offset in a dark blue tint to simulate physical stacking of circuit plates.

## Shapes
The shape language is **Soft (0.25rem)**. This slight rounding prevents the UI from feeling overly aggressive or "retro-brutalist," aligning it instead with modern industrial design. 

- **Standard Elements:** 4px radius (Buttons, Inputs, Small Cards).
- **Structural Elements:** 8px radius (Main Content areas, Large Modals).
- **Status Tags:** 2px radius or sharp, to differentiate them as "hard" system data.

## Components
- **Primary Buttons:** Solid Deep Tech Blue with white text. High-contrast, no gradients.
- **Monospace Tags:** Midnight Grey background with a 1px border colored by state (Teal for success, Orange for warning). Text is always JetBrains Mono.
- **Glass Cards:** Used for deliberation summaries. Features a 1px border (#1F2937) and a subtle background blur.
- **Logic Clock Indicators:** Vertical or horizontal lines (1px) connecting cards, using the Primary Blue color with small 4px "data nodes" at intersection points to represent the DAG structure.
- **Input Fields:** Darker than the surface color (#080808) with a 1px border. Focus state uses a Neon Teal glow.
- **Charts:** Use a "Wireframe" style—no fills, just 1.5px strokes for lines. Grid lines within charts should be at 10% opacity.
- **Status Indicators:** Small, circular "LED" pips that use the Secondary (Teal) or Tertiary (Orange) colors with a subtle outer glow to indicate live network activity.