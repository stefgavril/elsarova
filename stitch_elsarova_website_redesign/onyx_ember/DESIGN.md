---
name: Onyx & Ember
colors:
  surface: '#200f0d'
  surface-dim: '#200f0d'
  surface-bright: '#493431'
  surface-container-lowest: '#1a0a08'
  surface-container-low: '#291715'
  surface-container: '#2d1b19'
  surface-container-high: '#392523'
  surface-container-highest: '#45302d'
  on-surface: '#fddbd7'
  on-surface-variant: '#e7bdb8'
  inverse-surface: '#fddbd7'
  inverse-on-surface: '#402b29'
  outline: '#ae8883'
  outline-variant: '#5d3f3c'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690006'
  primary-container: '#e31e24'
  on-primary-container: '#fffafa'
  inverse-primary: '#c00014'
  secondary: '#c7c6cb'
  on-secondary: '#2f3035'
  secondary-container: '#46464b'
  on-secondary-container: '#b5b4ba'
  tertiary: '#8ecdff'
  on-tertiary: '#00344f'
  tertiary-container: '#007bb5'
  on-tertiary-container: '#fbfcff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000d'
  secondary-fixed: '#e3e2e7'
  secondary-fixed-dim: '#c7c6cb'
  on-secondary-fixed: '#1a1b20'
  on-secondary-fixed-variant: '#46464b'
  tertiary-fixed: '#cbe6ff'
  tertiary-fixed-dim: '#8ecdff'
  on-tertiary-fixed: '#001e30'
  on-tertiary-fixed-variant: '#004b71'
  background: '#200f0d'
  on-background: '#fddbd7'
  surface-variant: '#45302d'
  onyx-base: '#121317'
  onyx-surface: '#1C1D21'
  signature-red: '#E31E24'
  crisp-white: '#FFFFFF'
  muted-gray: '#808080'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 90px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 20px
  section-gap: 160px
---

## Brand & Style

The brand identity is "Industrial Luxe"—a marriage of raw architectural strength and high-end elegance. It targets architects, interior designers, and discerning homeowners who view lighting as functional art. The UI must evoke a sense of exclusivity, precision, and nocturnal sophistication.

The design style is **Minimalism** with **High-Contrast** elements. We utilize expansive dark voids (Deep Charcoal/Onyx) to make the crisp white typography and high-quality product photography pop. The "Industrial" aspect is brought forward through razor-sharp edges and structural grids, while the "Luxe" is conveyed through generous whitespace (negative space) and precise, blood-red accents that mimic the filament of a high-end bulb.

## Colors

The palette is strictly controlled to maintain an editorial, high-end feel. 

- **Primary Base:** The background is an immersive Deep Charcoal (#121317), providing a canvas that eliminates glare and highlights the luminosity of the product imagery.
- **Typography:** Crisp White (#FFFFFF) is used for maximum legibility and a stark, modern contrast.
- **Signature Accent:** The Brand Red (#E31E24) is used sparingly and with surgical precision—reserved for active states, vital CTAs, and structural accents like hairline dividers or bullet points.
- **Surface Tones:** A slightly lighter Onyx (#1C1D21) is used for container backgrounds to create subtle depth without breaking the dark-mode immersion.

## Typography

This design system utilizes **Manrope** exclusively to maintain a clean, technical, yet approachable geometric feel.

- **Display & Headlines:** Use heavy weights (700-800) with tight letter-spacing to create a sense of structural mass. Large-scale typography should feel architectural.
- **Body Text:** Set with generous line height (1.6x - 1.8x) to enhance the editorial readability and "breathable" luxury feel.
- **Labels:** Use uppercase with increased letter-spacing for section headers and metadata to provide a technical, "blueprint" aesthetic.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain editorial control over image/text relationships, transitioning to a fluid model for smaller devices.

- **Editorial Rhythm:** Use exceptionally large vertical gaps (`section-gap`) between content blocks to signal luxury and allow the lighting products to be the sole focus of the user's attention.
- **Grid:** A 12-column grid is used for desktop. Imagery should frequently "break" the grid or span 8-10 columns for a high-impact, cinematic feel.
- **Asymmetry:** Pair large, high-detail imagery on one side with minimalist text blocks on the other, utilizing intentional "dead space" to guide the eye.

## Elevation & Depth

In a dark, industrial luxe system, traditional shadows are replaced by **Tonal Layering** and **High-Contrast Outlines**.

- **Surfaces:** Use `#1C1D21` for cards or sections that need to sit "above" the base background.
- **Borders:** Instead of shadows, use 1px solid borders in `#FFFFFF` with low opacity (10-15%) for subtle definition, or `#E31E24` for high-importance focus states.
- **Imagery:** Product images should feel like they are emerging from the shadows. Use subtle vignettes in photography rather than UI-based gradients.
- **Overlays:** Navigation and modals use a heavily blurred "Glassmorphism" effect with a dark tint to maintain the nocturnal atmosphere while providing depth.

## Shapes

The shape language is strictly **Sharp (0px)**. 

Curves are avoided in the UI elements to contrast with the organic or circular shapes often found in the lighting fixtures themselves. Straight lines, right angles, and sharp corners reinforce the "Industrial" and "Architectural" narrative. All buttons, input fields, and containers must maintain 90-degree corners.

## Components

### Buttons
- **Primary:** Sharp corners, solid crisp white background, black text. On hover, background shifts to signature red.
- **Secondary/Outline:** Sharp corners, 1px white border, transparent background. Red border on hover.
- **CTA (Towing):** A distinct "Industrial Strength" block. Solid signature red background, white bold caps typography. This should feel more "utility" than the lighting components.

### Cards
- **Product Cards:** No borders, no background. Large-scale imagery with text labels positioned in the bottom-left. On hover, the image scales slightly (1.05x) and the title shifts to signature red.

### Input Fields
- Underline-only style. 1px white bottom border that turns red on focus. Labels appear in `label-caps` style above the line.

### Towing Service Section
- A full-bleed, high-contrast section. Use a grayscale image of a tow truck with a heavy black overlay. The heading should be "TOWING & RECOVERY" in `display-lg` with a prominent red "tractari.elsarova.ro" link styled as a high-visibility button.

### Navigation
- Minimalist top bar. Links in `label-caps`. The logo should be the primary focus, flanked by generous empty space.