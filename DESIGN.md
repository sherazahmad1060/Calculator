---
name: Aura Horizon
colors:
  surface: '#161311'
  surface-dim: '#161311'
  surface-bright: '#3c3836'
  surface-container-lowest: '#100e0c'
  surface-container-low: '#1e1b19'
  surface-container: '#221f1d'
  surface-container-high: '#2d2927'
  surface-container-highest: '#383432'
  on-surface: '#e9e1dd'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#e9e1dd'
  inverse-on-surface: '#33302d'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#ffbe9d'
  on-tertiary: '#552100'
  tertiary-container: '#ff965b'
  on-tertiary-container: '#732f00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783200'
  background: '#161311'
  on-background: '#e9e1dd'
  surface-variant: '#383432'
  surface-glass-amber: '#574a2e9f'
  surface-glass-light: rgba(255, 255, 255, 0.08)
  surface-glass-active: rgba(255, 255, 255, 0.18)
  key-number-fill: rgba(41, 37, 36, 0.65)
  key-action-fill: rgba(87, 74, 46, 0.85)
  key-accent-fill: '#f59e0b'
  text-primary: '#fef3c7'
  text-secondary: '#d6d3d1'
  text-accent: '#38bdf8'
  border-glass: rgba(251, 191, 36, 0.25)
  border-glass-specular: rgba(255, 255, 255, 0.35)
typography:
  display-lg:
    fontFamily: Roboto Flex
    fontSize: 56px
    fontWeight: '300'
    lineHeight: 64px
    letterSpacing: -1px
  display-lg-mobile:
    fontFamily: Roboto Flex
    fontSize: 42px
    fontWeight: '300'
    lineHeight: 48px
    letterSpacing: -0.5px
  display-md:
    fontFamily: Roboto Flex
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
  display-md-mobile:
    fontFamily: Roboto Flex
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 34px
  headline-sm:
    fontFamily: Roboto Flex
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
  title-md:
    fontFamily: Roboto Flex
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0.15px
  body-lg:
    fontFamily: Roboto Flex
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Roboto Flex
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-keypad:
    fontFamily: Roboto Flex
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 28px
  label-keypad-sm:
    fontFamily: Roboto Flex
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 22px
  label-sm:
    fontFamily: Roboto Flex
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.5px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 0.75rem
  gutter-tablet: 1rem
  margin: 1rem
  margin-tablet: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system blends Android Material 3 design principles with cinematic glassmorphism. Rooted in naturalistic warmth, it pairs the deep golden-hour tones of sunset alpine vistas with frosted, semi-translucent surfaces.

The emotional signature is grounded, tactile, and serene. It caters to users who value polished micro-interactions and refined modern Android utilities over flat, lifeless tools. By leveraging soft-specular ambient backdrops, warm-amber translucent layers, and crisp mathematical glyphs, the UI elevates utilitarian calculation into a calm, tactile experience.

## Colors

The palette is derived from twilight alpine reflections: glowing golden-amber summits fading into dusk-tinted slate waters.

- **Primary (`#f59e0b`)**: Warm glowing amber used for primary evaluation keys (`=`), active operators, and key visual focal points.
- **Secondary (`#38bdf8`)**: Crisp glacial cyan inspired by lake reflections, utilized for functional clear controls (`AC`, `DEL`, memory states) and focus outlines.
- **Tertiary (`#f97316`)**: Rich dusk orange reserved for secondary operational toggles or status tags.
- **Neutral (`#1c1917`)**: Deep stone black anchor providing contrast behind translucent layers.
- **Surface Glass Amber (`#574a2e9f`)**: The foundational translucent acrylic tint across calculation modules, harmonizing with natural photographic backplates.

## Typography

Typography relies on **Roboto Flex**, emphasizing the clean, calibrated geometry native to modern Android Material 3 interfaces.

Key typographic rules:
- **Numerical Output (`display-lg` / `display-lg-mobile`)**: Thin, highly legible figures with tabular numerals enabled (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during rapid calculations.
- **Secondary Expression Row (`body-lg`)**: Low-emphasis running history displayed directly above the active calculation buffer.
- **Keypad Glyphs (`label-keypad`)**: Centered arithmetic signs and digits balanced visually with optical line heights to maintain uniform centering inside rounded key boundaries.

## Layout & Spacing

The layout is built for hand-held ergonomics and one-handed thumb reach:

- **Keypad Matrix**: Strict 4-column balanced grid with a persistent `0.75rem` (`12px`) gap.
- **Vertical Hierarchy**: Top-pinned formula history, middle-anchored primary calculation output with fluid auto-shrinking text, and bottom-anchored 5-row button pad.
- **Responsive Adaptability**:
  - **Mobile (<600px)**: Edge-to-edge floating card docking towards the bottom viewport, bounded by `margin: 1rem` with safe-area padding for Android system gestures.
  - **Tablet & Landscape (>=600px)**: Centered glass monolith with fixed width (`380px` to `420px`) floating over the full-bleed landscape canvas.

## Elevation & Depth

Visual depth is achieved through layered frosted glass and inner specular borders rather than opaque drop shadows:

- **Main Shell Backdrop**: Multi-layered backdrop blur (`backdrop-filter: blur(28px) saturate(180%)`) combined with `#574a2e9f` amber-gold tinting.
- **Specular Bordering**: 1px perimeter border with top-down directional opacity (`linear-gradient(180deg, rgba(255,255,255,0.35) 0%, rgba(251,191,36,0.15) 100%)`), mimicking angled sunlight catching glass edges.
- **Elevation Layers**:
  - **Level 0 (Canvas)**: Full-bleed landscape photographic background.
  - **Level 1 (Card Shell)**: `box-shadow: 0 20px 50px rgba(0, 0, 0, 0.45), 0 0 0 1px rgba(255, 255, 255, 0.1) inset`.
  - **Level 2 (Interactive Keys)**: Semi-translucent keycaps hovering with soft ambient depth (`box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15), inset 0 1px 1px rgba(255, 255, 255, 0.2)`).
  - **Level 3 (Pressed / Active)**: `transform: scale(0.94)` with collapsed shadows, giving immediate physical feedback.

## Shapes

The shape vocabulary uses smooth, continuous curves inspired by Material 3 squircles and pills:

- **Main Calculator Frame**: `rounded-2xl` (`1.75rem` / `28px`) for a soft handheld posture.
- **Standard Keypads**: Near-pill / squircle radius (`1.25rem` / `20px`) to maximize touch target area while maintaining comfortable finger separation.
- **Display Output Container**: `rounded-lg` (`1rem` / `16px`) inset within the parent frame.
- **Special Action Keys (Equals / Clear)**: Full pill (`9999px`) styling when occupying extended spans.

## Components

### Calculator Shell
- Bounded glass container housing the visual stack.
- Uses `backdrop-filter: blur(24px) saturate(180%)`, filled with `surface-glass-amber` (`#574a2e9f`).
- Top edge rimmed with 1px `border-glass-specular` to replicate refracted light.

### Display Panel
- Flush or subtly recessed dark-tinted glass field (`rgba(0, 0, 0, 0.25)`).
- Two-line data presentation:
  - Upper: Previous equation history in `text-secondary`, right-aligned, `body-md`.
  - Lower: Active running value in `text-primary`, right-aligned, `display-lg-mobile`.

### Keypad Buttons
- **Numeric Keys (`0–9`, `.`)**:
  - Background: `key-number-fill` (`rgba(41, 37, 36, 0.65)`).
  - Text: `text-primary` (`#fef3c7`).
  - Font: `label-keypad`.
- **Operator Keys (`+`, `−`, `×`, `÷`)**:
  - Background: `key-action-fill` (`rgba(87, 74, 46, 0.85)`).
  - Text: `primary_color_hex` (`#f59e0b`).
  - Active state: Inverts to solid amber fill with dark stone glyph.
- **Functional Reset & Erase (`AC`, `DEL`, `%`)**:
  - Background: Subtle frost (`rgba(255, 255, 255, 0.1)`).
  - Text: `text-accent` (`#38bdf8`).
  - Font: `label-keypad-sm`.
- **Evaluation Key (`=`)**:
  - Background: Solid accent `key-accent-fill` (`#f59e0b`).
  - Text: Deep charcoal (`#1c1917`), font weight `600`.
  - Ambient glow: `box-shadow: 0 4px 20px rgba(245, 158, 11, 0.4)`.

### Tactile Feedback & Micro-Interactions
- Every key incorporates a `100ms` cubic-bezier compression curve (`transform: scale(0.94)`) upon touch or click.
- Ripples inherit an Android Material 3 bounded radial highlight with 20% opacity.