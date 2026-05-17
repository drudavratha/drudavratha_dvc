---
name: Noir Precision
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
  on-surface-variant: '#bac9cd'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#859397'
  outline-variant: '#3b494c'
  surface-tint: '#00daf8'
  primary: '#baf2ff'
  on-primary: '#00363f'
  primary-container: '#00e0ff'
  on-primary-container: '#005f6d'
  inverse-primary: '#006877'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#ffe6b6'
  on-tertiary: '#3f2e00'
  tertiary-container: '#fec42e'
  on-tertiary-container: '#6f5200'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#a5eeff'
  primary-fixed-dim: '#00daf8'
  on-primary-fixed: '#001f25'
  on-primary-fixed-variant: '#004e5a'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdf9d'
  tertiary-fixed-dim: '#f7be27'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
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
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 160px
---

## Brand & Style
This design system is built for a high-end cinematic post-production environment. The personality is authoritative, technical, and premium, mirroring the precision of a color grading suite or an edit bay. 

The aesthetic follows a **Dark Minimalist** movement with **High-Contrast** accents. It prioritizes content (film frames and reels) by utilizing deep obsidian backgrounds and expansive whitespace (or "blackspace"). The emotional response should be one of "exclusive craft"—where the UI disappears to let the artistry of the moving image take center stage. Sharp edges and a rigid grid reflect a commitment to technical excellence.

## Colors
The palette is dominated by **Absolute Black (#0A0A0A)** to ensure infinite depth on OLED displays, mimicking a cinema blackout. **Charcoal Grey (#1A1A1A)** is used sparingly for UI containers and surface elevation to maintain a flat, sophisticated look.

The primary accent is **Electric Cyan (#00E0FF)**, representing the digital light of post-production tools. It is used for critical action points and active states. A secondary **Luxury Gold** may be used exclusively for "Award" or "Featured" designations. All text is pure white or high-purity grey to maintain a high-contrast ratio that ensures legibility against the dark void.

## Typography
The typography system uses a hierarchical mix of **Montserrat** for impactful, geometric headlines and **Inter** for neutral, utilitarian body text. **Geist** is introduced for labels and technical metadata to provide a monospaced, "studio-tool" feel.

Display type should be used with extreme tracking (letter-spacing) adjustments: tight for massive headlines to feel cinematic, and wide for uppercase labels to feel premium. Avoid italics; keep the type-face upright and structural.

## Layout & Spacing
The layout follows a **Fixed 12-Column Grid** for desktop and a **4-Column Grid** for mobile. The philosophy is "Exhibitionism": large-scale imagery and video players should often break the grid to go Full-Width, while text content remains strictly aligned to the inner columns.

Spacing is aggressive. Section gaps are intentionally large (160px+) to isolate different projects or case studies, preventing the UI from feeling "cluttered." Use a strict 8px base unit for all component internal spacing.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Sharp Outlines** rather than shadows. In this design system, shadows are almost never used; instead, surfaces are separated by a 1px border of #2A2A2A (for subtle separation) or #FFFFFF (for high-intent focus).

For overlays and modals, a high-intensity **Backdrop Blur** (60px+) is applied to the deep black background to create a "smoke and mirrors" effect that maintains the dark atmosphere while indicating a new layer of interaction.

## Shapes
The shape language is strictly **Sharp (0px)**. Every button, card, and image container must have 90-degree corners. This evokes a sense of architectural precision and professional-grade software. Circular elements are only permitted for play buttons or progress indicators to provide a functional contrast to the rigid rectangular grid.

## Components
- **Buttons:** Primary buttons are solid Electric Cyan with black text, no border. Secondary buttons are transparent with a 1px white border and white text. All hover states involve a 100% color inversion or a subtle scale-up of the content.
- **Input Fields:** Minimalist underlines or 1px charcoal borders. Backgrounds stay #0A0A0A. Focus state changes the border to Electric Cyan.
- **Cards:** No background color by default; use 1px charcoal borders. On hover, the background shifts to #1A1A1A and images should slightly zoom.
- **Lists:** Technical data lists (e.g., credit blocks) should use the Geist label font. Each row is separated by a 1px hairline #2A2A2A.
- **Video Player:** Custom UI controls using thin 1px lines. The scrubber is Electric Cyan.
- **Chips/Tags:** Small, rectangular, uppercase Geist font. Used for "4K," "VFX," or "Color" metadata.