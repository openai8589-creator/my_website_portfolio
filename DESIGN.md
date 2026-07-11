---
name: Technical Precision
colors:
  surface: '#fcf8fa'
  surface-dim: '#dcd9db'
  surface-bright: '#fcf8fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f5'
  surface-container: '#f0edef'
  surface-container-high: '#eae7e9'
  surface-container-highest: '#e4e2e4'
  on-surface: '#1b1b1d'
  on-surface-variant: '#45464d'
  inverse-surface: '#303032'
  inverse-on-surface: '#f3f0f2'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0b1c30'
  on-tertiary-container: '#75859d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#fcf8fa'
  on-background: '#1b1b1d'
  surface-variant: '#e4e2e4'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is engineered to evoke a sense of intellectual rigor, technical mastery, and professional growth. It targets data scientists, engineers, and corporate teams seeking a learning environment that mirrors the tools they use daily. 

The aesthetic is **Corporate Modern with a technical edge**. It prioritizes extreme clarity and functional elegance, using generous white space to allow complex data concepts to breathe. Visual interest is generated through "data-inspired" elements: subtle background dot grids, micro-interactions that mimic IDE behavior, and precision-aligned components. The emotional response should be one of "structured ambition"—the feeling that the path to mastery is organized, logical, and achievable.

## Colors
The palette is built on a foundation of "Deep Navy" (#0F172A) to establish authority and trust. "Vibrant Blue" (#3B82F6) serves as the primary action color, directing the eye toward progression and interactivity. "Sophisticated Gray" (#64748B) is used for secondary information and metadata to maintain a clear hierarchy without visual clutter.

Backgrounds should remain primarily white (#FFFFFF) to maximize legibility, with light slate tints (#F8FAFC) used to differentiate UI sections or container surfaces. Accent gradients should be used sparingly, strictly transitioning from the secondary blue to a slightly lighter cyan to imply movement and energy in data visualizations or hero sections.

## Typography
This design system utilizes a three-font stack to differentiate between intent and content. **Geist** is used for headlines to provide a sharp, modern, and technical "tech-forward" appearance. **Inter** handles the bulk of body text, chosen for its exceptional legibility and neutral, professional character. **JetBrains Mono** is reserved for labels, metadata, and code snippets to reinforce the data science context.

Vertical rhythm is maintained through a strict 4px baseline grid. Large headlines should use tighter letter spacing to maintain visual tension, while mono-spaced labels use slightly increased tracking for clarity at small sizes.

## Layout & Spacing
The layout follows a **Fluid Grid** model based on a 12-column system for desktop and a 4-column system for mobile. 

1. **Desktop (1440px+):** 12 columns, 24px gutters, 64px side margins.
2. **Tablet (768px - 1439px):** 8 columns, 24px gutters, 32px side margins.
3. **Mobile (0px - 767px):** 4 columns, 16px gutters, 16px side margins.

Spacing follows a geometric progression based on a 4px unit. Use `lg` (48px) and `xl` (80px) for section vertical padding to maintain an airy, premium feel. Content cards and interactive elements should utilize `md` (24px) for internal padding to ensure data density remains comfortable.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Ambient Shadows**. This design system avoids heavy drop shadows in favor of subtle depth cues:

- **Level 0 (Base):** White background (#FFFFFF).
- **Level 1 (Cards/Surface):** Light slate background (#F8FAFC) or White with a 1px border (#E2E8F0).
- **Level 2 (Interactive):** White surface with a very soft, diffused shadow: `0px 4px 12px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Modals/Overlays):** White surface with a more pronounced elevation: `0px 12px 32px rgba(15, 23, 42, 0.1)`.

Use 1px borders in #E2E8F0 for most structural containment to maintain a "blueprint" feel without adding visual weight.

## Shapes
The shape language is **Rounded**, striking a balance between the friendliness of education and the precision of technology. 

- **Standard Elements:** 0.5rem (8px) corner radius for buttons, input fields, and small components.
- **Large Elements:** 1rem (16px) corner radius for course cards, feature sections, and modals.
- **Micro Elements:** 0.25rem (4px) for tags, checkboxes, and tooltips.

The consistency of these radii creates a cohesive, modern UI that feels "engineered" rather than organic.

## Components
- **Buttons:** Primary buttons use the Vibrant Blue (#3B82F6) with white text. Secondary buttons use a transparent background with a 1px border of #E2E8F0 and Deep Navy text. Use 0.5rem rounding and `label-md` typography.
- **Course Cards:** Elevated Level 1 cards. Feature a 16:9 aspect ratio image at the top, followed by a `label-sm` category tag, `headline-md` title, and a progress bar if the user is enrolled.
- **Data Tables:** Clean, no vertical borders. Use #F8FAFC for the header row with `label-sm` text in #64748B. Row heights should be generous (min 56px) to maintain readability.
- **Input Fields:** 1px #E2E8F0 border, 0.5rem rounding. On focus, the border shifts to Vibrant Blue (#3B82F6) with a 2px soft outer glow.
- **Progress Indicators:** Use thin, 4px height bars. Completed states use the primary blue; "in-progress" states use a lighter tint of the same hue.
- **Patterns:** Apply a 24px-step dot grid pattern in #F1F5F9 to the background of hero sections or sidebar navigation to reinforce the "Data/Grid" narrative.