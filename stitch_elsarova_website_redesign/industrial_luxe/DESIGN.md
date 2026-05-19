---
name: Industrial Luxe
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393e'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343439'
  on-surface: '#e3e2e8'
  on-surface-variant: '#e7bdb8'
  inverse-surface: '#e3e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#ae8883'
  outline-variant: '#5d3f3c'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690006'
  primary-container: '#e31e24'
  on-primary-container: '#fffafa'
  inverse-primary: '#c00014'
  secondary: '#9acbff'
  on-secondary: '#003355'
  secondary-container: '#3a96e2'
  on-secondary-container: '#002c4b'
  tertiary: '#e9c176'
  on-tertiary: '#412d00'
  tertiary-container: '#8f6f2d'
  on-tertiary-container: '#fffaf9'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000d'
  secondary-fixed: '#cfe4ff'
  secondary-fixed-dim: '#9acbff'
  on-secondary-fixed: '#001d34'
  on-secondary-fixed-variant: '#004a79'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#121317'
  on-background: '#e3e2e8'
  surface-variant: '#343439'
  surface-ebony: '#0B0C10'
  surface-onyx: '#1F2124'
  accent-gold: '#C5A059'
  towing-blue: '#007BC5'
  brand-red: '#E31E24'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
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
  technical-label:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The design system embodies a premium, high-end showroom aesthetic that bridges the gap between sophisticated interior lighting and heavy-duty technical services. The brand personality is authoritative yet refined, targeting high-value clients who seek both aesthetic excellence in lighting and absolute reliability in towing services.

The chosen style is **Minimalism with a Technical Edge**. This approach utilizes heavy whitespace and precise, structured layouts to evoke the feeling of a modern gallery. High-quality product imagery is treated as the focal point, framed by thin, purposeful borders and a sophisticated dark palette. By removing traditional e-commerce clutter, the UI transitions from a "store" to a "curated showcase," emphasizing craftsmanship and professional service.

## Colors

The palette is anchored in a deep, sophisticated dark-mode environment to make lighting products and technical graphics "glow" against the interface. 

- **Primary Red:** Derived from the brand logo, used sparingly for critical actions and brand identity.
- **Secondary Blue:** Reserved for the towing and industrial service sectors of the business, providing a clear visual distinction between service types.
- **Tertiary Gold:** A metallic accent color used to highlight premium lighting attributes and high-end materials.
- **Neutral/Surface:** The "Surface-Ebony" acts as the primary background, with "Surface-Onyx" used for card elements and containers to create subtle depth without relying on traditional shadows.

## Typography

The typography strategy focuses on a hierarchy that balances editorial elegance with technical precision.

- **Headlines:** Uses **Manrope** for its modern, balanced, and premium geometric character. Large display headings should use tighter letter-spacing for a high-fashion look.
- **Body:** Uses **Inter** for maximum legibility. It is neutral and functional, ensuring that long technical descriptions remain readable.
- **Technical Labels:** Uses **JetBrains Mono** for specifications (e.g., Kelvin, Wattage, IP ratings). This monospaced choice reinforces the professional, technical nature of the product catalog and services.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** on desktop to maintain a structured, gallery-like presentation. 

- **Showroom Spacing:** Vertical rhythm is intentionally generous. Significant gaps between sections (120px+) create a sense of luxury and allow the products to breathe.
- **Technical Grid:** Product grids and service details use a tighter 24px gutter to feel organized and precise.
- **Responsive Behavior:** On mobile, margins reduce to 16px and the grid collapses to a single column, with section gaps reduced to 64px to maintain momentum while scrolling.

## Elevation & Depth

To maintain a premium, modern feel, this system avoids heavy, traditional shadows. Instead, it uses **Tonal Layering** and **Thin Outlines**.

- **Surface Levels:** The primary background is the darkest value. Cards and containers sit one level higher with a slightly lighter gray (#1F2124).
- **Glassmorphism:** Navigation bars and floating overlays use a high-blur (20px) backdrop filter with a subtle 1px border (#FFFFFF10) to create a sense of light-diffusing glass.
- **Technical Strokes:** Elements are often defined by 1px solid borders in low-opacity white or brand-blue/red rather than shadows, reinforcing the industrial precision of the brand.

## Shapes

The shape language is **Soft (0.25rem)**. This near-sharp approach maintains an architectural, professional look while being just approachable enough for a modern consumer brand. 

- **Strictness:** Containers and large image wrappers should stick to a 4px (Soft) radius to feel like high-end frames.
- **Interaction:** Buttons may occasionally use a "Pill" shape to distinguish them as high-priority interactive elements, but the general layout remains grounded in precise, subtle rounding.

## Components

- **Buttons:** Primary buttons are solid brand-red or brand-blue with no roundedness (sharp) or minimal 4px rounding. Secondary buttons use a "ghost" style with a 1px border and monospaced text labels.
- **Technical Chips:** Used for lighting specs (e.g., "3000K", "IP44"). These are styled with a dark background and a thin accent-gold border, using monospaced typography.
- **Service Cards:** Feature high-contrast photography. Text is overlaid on a subtle dark gradient at the bottom. No shadows are used; depth is achieved via 1px border highlights on hover.
- **Input Fields:** Minimalist design with only a bottom border that animates to a full brand-color stroke on focus.
- **Navigation:** A floating, translucent top bar that uses a backdrop-blur effect. Links are uppercase with wide letter spacing.
- **Lists:** Information-heavy specification lists should use a "Data-Grid" style with thin dividers and alternating subtle background tints for row clarity.