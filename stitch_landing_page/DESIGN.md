---
name: Urban Pulse
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
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#f8f5f5'
  on-tertiary: '#313030'
  tertiary-container: '#dcd9d8'
  on-tertiary-container: '#5f5e5e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 96px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is built on the intersection of raw street culture and high-end recording studio precision. It evokes the atmosphere of a late-night session: dark, focused, and electric. The personality is unapologetically bold, professional yet "street," catering to artists who value both grit and high-fidelity results.

The visual style utilizes a mix of **High-Contrast / Bold** aesthetics and **Brutalism**. It relies on massive typography, a monochromatic foundation, and surgical hits of neon to guide the eye. The interface should feel like a piece of premium audio hardware—tactile, functional, and elite. This design system prioritizes visual impact and clarity, stripping away unnecessary decorations to focus on the artist and the gear.

## Colors

The color palette is dominated by "Absolute Zero" black and deep charcoal to create a sense of infinite depth. Typography is strictly pure white or high-contrast silver to ensure maximum legibility against the dark backgrounds.

The primary accent is an **Electric Cyan (#00F0FF)**, representing the digital signal, the "on" light of a preamp, and the energy of the music industry. Use this color sparingly for critical calls to action, active states, and focus indicators. Secondary surfaces use graphite tones to create a hierarchy of information without breaking the "dark room" atmosphere.

## Typography

Typography is the primary voice of this design system. We use **Space Grotesk** for headlines to provide a technical, slightly futuristic, and aggressive "urban" feel. It should be used in large scales with tight letter-spacing to mimic concert posters and streetwear branding.

For body text, **Inter** provides a clean, neutral, and highly readable counterpoint to the loud headings. Russian Cyrillic characters in Inter maintain excellent clarity even at small sizes. All uppercase labels are used for navigation and technical metadata (like equipment specs) to maintain a professional, organized aesthetic.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is "Structured Chaos"—while elements sit on a strict grid, asymmetrical placements and oversized typography can break the flow to create visual interest.

Rhythm is based on an 8px square grid. Use generous margins on the outer edges of the container to frame the content like a piece of art, while maintaining tighter gutters (24px) between related components to keep the UI feeling "packed" and energetic.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** rather than traditional soft shadows. Since the background is pure black, we stack elements using progressively lighter shades of graphite.

1.  **Level 0 (Background):** Pure Black (#000000) for the main canvas.
2.  **Level 1 (Surface):** Deep Charcoal (#0A0A0A) for cards and sections.
3.  **Level 2 (Elevated):** Graphite (#1A1A1A) for interactive items or hovered states.

To emphasize "Active" elements, use a **1px solid border** of the accent color or white. A subtle "inner glow" or "outer bloom" using the electric blue can be used for buttons to simulate the light of a recording console, but avoid heavy, muddy drop shadows.

## Shapes

The shape language is strictly **Sharp (0px)**. Rectilinear forms reinforce the brutalist, urban aesthetic and suggest a professional, "no-nonsense" studio environment. This applies to buttons, input fields, image containers, and cards.

Occasional circular elements may be used strictly for functional metaphors, such as volume knobs or "Record" indicators, but all structural containers must maintain 90-degree corners to ensure a cohesive, high-impact look.

## Components

### Buttons
Primary buttons are solid white with black text for maximum contrast. Secondary buttons use a 2px white or electric blue stroke with no fill. Hover states should invert the colors or add a glow effect. All buttons are rectangular with sharp corners.

### Service Cards
Cards use a Level 1 surface background (#0A0A0A). They feature large, bold headings and a subtle 1px border that only becomes visible on hover. Images within cards should have a slight dark overlay to keep typography readable at all times.

### Equipment Showcase
Use a technical "spec sheet" look. Pair a high-quality product photo with monospaced-style labels (using Space Grotesk) to list technical details. This creates a "catalog" feel that appeals to gear enthusiasts.

### Forms
Input fields are simplified to a single bottom border (1px white) or a full outline with Level 1 background. Placeholders should be dark gray, and the cursor/active border should use the accent Electric Blue.

### Atmosphere Gallery
Images should use high-contrast, moody photography. Placeholders for loading states use a graphite-to-charcoal gradient animation to maintain the dark-mode aesthetic.