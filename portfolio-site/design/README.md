---
name: Deep Navy Premium Portfolio
colors:
  surface: '#081425'
  surface-dim: '#081425'
  surface-bright: '#2f3a4c'
  surface-container-lowest: '#040e1f'
  surface-container-low: '#111c2d'
  surface-container: '#152031'
  surface-container-high: '#1f2a3c'
  surface-container-highest: '#2a3548'
  on-surface: '#d8e3fb'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d8e3fb'
  inverse-on-surface: '#263143'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#b9c7e0'
  on-secondary: '#233144'
  secondary-container: '#3c4a5e'
  on-secondary-container: '#abb9d2'
  tertiary: '#c4c7c9'
  on-tertiary: '#2d3133'
  tertiary-container: '#15181a'
  on-tertiary-container: '#7e8183'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#081425'
  on-background: '#d8e3fb'
  surface-variant: '#2a3548'
typography:
  h1:
    fontFamily: Inter
    fontSize: 4rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Manrope
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  button:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 2rem
  section-padding: 8rem
  stack-sm: 1rem
  stack-md: 2rem
  stack-lg: 4rem
---

## Brand & Style
The design system is built to evoke a sense of technical mastery, reliability, and high-end craftsmanship. It targets high-value clients and technical recruiters who prioritize clarity and precision. 

The style is a synthesis of **Minimalism** and **Corporate Modernism**. It leverages expansive whitespace to provide breathing room for complex technical content, while using deep tonal backgrounds to anchor the visual hierarchy. The emotional response should be one of "quiet confidence"—professional and polished without being loud or distracting.

## Colors
The palette is dominated by **Deep Navy (#0f172a)**, which serves as the primary canvas color to establish a premium "dark mode" foundation. 

- **Primary Canvas**: #0f172a (Deep Navy) for backgrounds.
- **Secondary/Surface**: #1e293b (Slate) for card backgrounds and navigation surfaces.
- **Crisp White**: #f8fafc (Slate 50) used for primary typography and high-contrast elements.
- **Subtle Accents**: #334155 (Slate 700) for borders and decorative dividers.
- **Interaction Accent**: #38bdf8 (Sky) used sparingly for hover states or status indicators to maintain the professional aesthetic.

## Typography
This design system utilizes **Inter** for headlines to convey a systematic, engineering-focused personality. Its bold weights at large scales create a strong visual anchor. 

For body copy, **Manrope** is selected for its refined geometric qualities and exceptional legibility, ensuring long-form case studies remain readable. Use tight letter-spacing for large headlines and generous line-heights (1.6x-1.7x) for body text to maintain the minimalist feel.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a 12-column structure. Spacing is governed by a 4px base unit to ensure mathematical harmony. 

Key principles:
- **Generous Verticality**: Use 8rem to 10rem of vertical padding between major sections to emphasize the minimalist aesthetic.
- **Flexible Grid**: Columns should collapse gracefully from 12 to 4 on mobile devices.
- **Safe Areas**: Maintain a minimum horizontal margin of 1.5rem on mobile, scaling to 4rem on desktop displays before hitting the container max-width.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Ambient Shadows**. Instead of heavy blacks, shadows use a tinted Navy (#020617) with high diffusion and low opacity (10-15%).

- **Level 0 (Background)**: #0f172a.
- **Level 1 (Cards/Nav)**: #1e293b with a 1px border of #334155.
- **Floating State**: Elements use a 24px blur shadow with a 0px Y-offset to appear as if they are glowing softly rather than casting a traditional shadow.
- **Glassmorphism**: Apply a subtle backdrop-blur (12px) to the sticky navigation bar for a high-end, layered feel.

## Shapes
The design system utilizes **Rounded** geometry to soften the technical nature of the content. 
- **Standard Radius**: 12px for small components like inputs and chips.
- **Large Radius (rounded-lg)**: 16px for project cards and main containers.
- **Full Radius**: Reserved exclusively for status indicators and pill-shaped tags.
- **Borders**: 1px width is standard; avoid thick borders to maintain a lightweight, modern feel.

## Components
- **Sticky Navigation**: A slim, semi-transparent bar with a `backdrop-filter: blur(16px)`. It should feature a subtle bottom border (#334155) that appears only on scroll.
- **Project Cards**: Use a "lift-on-hover" effect where the card moves 4px upward and the shadow deepens. Imagery should have a slight zoom-in transition (0.4s ease-out).
- **CTA Buttons**: High-contrast White (#f8fafc) background with Navy (#0f172a) text for primary actions. Transitions should be smooth (0.2s) and include a subtle horizontal scale on hover.
- **Chips/Tags**: Small, low-contrast Slate (#1e293b) backgrounds with #94a3b8 text for technical skills or categories.
- **Input Fields**: Ghost-style with a subtle border. Focus states should use a 1px solid Sky (#38bdf8) border and a soft glow.
- **Code Snippets**: Specialized containers using #020617 background to provide a clear distinction from the standard UI cards.