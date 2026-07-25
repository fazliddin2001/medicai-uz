---
name: Glacier Intelligence
colors:
  surface: '#f9f9ff'
  surface-dim: '#c9dbfb'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee9ff'
  surface-container-highest: '#d5e3ff'
  on-surface: '#091c34'
  on-surface-variant: '#44474c'
  inverse-surface: '#20314a'
  inverse-on-surface: '#ebf1ff'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#525f71'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0f1c2c'
  on-primary-container: '#778598'
  inverse-primary: '#bac8dc'
  secondary: '#006688'
  on-secondary: '#ffffff'
  secondary-container: '#76d1ff'
  on-secondary-container: '#005978'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#141d21'
  on-tertiary-container: '#7c858b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#c2e8ff'
  secondary-fixed-dim: '#76d1ff'
  on-secondary-fixed: '#001e2b'
  on-secondary-fixed-variant: '#004d67'
  tertiary-fixed: '#dbe4ea'
  tertiary-fixed-dim: '#bfc8ce'
  on-tertiary-fixed: '#141d21'
  on-tertiary-fixed-variant: '#3f484d'
  background: '#f9f9ff'
  on-background: '#091c34'
  surface-variant: '#d5e3ff'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 40px
---

## Brand & Style

The brand personality is clinical, precise, and technologically advanced. It aims to evoke a sense of "Light Glacier"—an atmosphere that is crisp, sterile yet welcoming, and incredibly clear. The target audience includes healthcare professionals and medical administrators who require high-reliability tools that feel calm under pressure.

The design style is **Corporate / Modern** with a strong infusion of **Minimalism**. It utilizes expansive white space to reduce cognitive load, paired with cool-toned gradients and soft, diffused shadows that suggest depth and intelligence. The interface should feel "breathable," prioritizing legibility and a sense of calm authority.

## Colors

The palette is anchored in a deep, authoritative primary navy for text and critical brand elements, contrasted against a vibrant "Glacier Blue" for accents and interactive states. 

- **Primary:** Deep charcoal-navy for maximum contrast and readability.
- **Secondary:** A bright, energetic sky blue used for active icons, progress indicators, and primary actions.
- **Tertiary:** A very soft, translucent ice-blue used for card backgrounds and large surface areas to soften the transition from pure white.
- **Neutral:** A muted slate-blue for secondary text and borders, ensuring the interface feels cohesive rather than purely grayscale.

Backgrounds should primarily use a subtle gradient from pure white (`#FFFFFF`) to a faint blue tint (`#F0F7FF`) to mimic the reflective quality of ice.

## Typography

This design system uses **Manrope** across all levels to maintain a modern, geometric, and highly legible aesthetic. The typeface bridges the gap between technical precision and human friendliness.

Headlines use tighter letter-spacing and heavier weights to project confidence and structure. Body text is set with generous line-heights to ensure clarity in dense medical data environments. Labels and small metadata utilize increased letter-spacing and semi-bold weights for rapid scanning.

## Layout & Spacing

The design system employs a **Fluid Grid** with fixed maximum widths for desktop environments to maintain optimal line lengths. 

- **Desktop:** 12-column grid with 24px gutters. Content is typically centered in a 1280px container.
- **Tablet:** 8-column grid with 20px gutters. 
- **Mobile:** 4-column grid with 16px gutters and 20px side margins.

Spacing follows an 8px linear scale. Generous internal padding (32px to 48px) within cards is required to maintain the "Glacier" feel of openness and clarity. Section vertical spacing should be aggressive (80px+) to clearly demarcate different functional areas.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**. Surfaces do not use heavy dark shadows; instead, they use wide, low-opacity shadows with a slight blue tint (`rgba(90, 107, 135, 0.08)`).

- **Level 0 (Background):** Pure white or ultra-light blue gradient.
- **Level 1 (Cards):** Tertiary blue background (`#F0F9FF`) with a 1px solid border in a slightly darker shade.
- **Level 2 (Floating/Active):** Raised elements use a white background with a soft, diffused shadow to appear as if floating just above the surface.

Avoid harsh black shadows. The goal is to make components feel like they are carved from or resting on soft snow.

## Shapes

The shape language is consistently **Rounded**, signifying approachability and safety. 

Standard components (buttons, inputs) use a 0.5rem (8px) radius. Larger container elements like cards use `rounded-xl` (1.5rem / 24px) to create a soft, friendly framing for technical data. Circular shapes are reserved exclusively for icons and status indicators to provide a distinct visual language for "active" or "system" states.

## Components

### Buttons
Primary buttons use the secondary blue background with white text. Secondary buttons use a ghost style (transparent background, blue border) or a light-blue fill with deep navy text. Hover states should involve a subtle scale increase (1.02x) rather than a dramatic color shift.

### Cards
Cards are the primary container. They feature a `rounded-xl` radius, a subtle 1px border (`#E1EFFE`), and a very soft blue-tinted shadow. Content inside cards should be padded at 32px minimum.

### Input Fields
Inputs are clean with a 1px border. On focus, the border transitions to the secondary blue, accompanied by a soft blue outer glow (3px spread).

### Chips & Status Badges
Chips use a pill-shape (`rounded-full`). For statuses like "Connected" or "Ready," use a white background with a thin border and a small leading icon. The text should be `label-sm` weight for professional precision.

### Icons
Icons should be thin-stroke (2pt) and linear, utilizing the secondary blue color. Enclose primary action icons in a soft-blue circular container to create a "hub" visual.