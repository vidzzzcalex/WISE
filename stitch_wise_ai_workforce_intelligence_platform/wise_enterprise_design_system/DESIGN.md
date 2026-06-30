---
name: WISE Enterprise Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#47464f'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#787680'
  outline-variant: '#c8c5d0'
  surface-tint: '#5b598c'
  primary: '#070235'
  on-primary: '#ffffff'
  primary-container: '#1e1b4b'
  on-primary-container: '#8683ba'
  inverse-primary: '#c4c1fb'
  secondary: '#00687a'
  on-secondary: '#ffffff'
  secondary-container: '#57dffe'
  on-secondary-container: '#006172'
  tertiary: '#000f07'
  on-tertiary: '#ffffff'
  tertiary-container: '#002819'
  on-tertiary-container: '#009d6c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c4c1fb'
  on-primary-fixed: '#181445'
  on-primary-fixed-variant: '#444173'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
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
    lineHeight: '1.5'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
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
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-xs: 4px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
  stack-xl: 48px
---

## Brand & Style
The design system embodies the "Billion-dollar SaaS" aesthetic: a synthesis of high-utility minimalism and futuristic polish. It is designed for Workforce Intelligence & Smart Enterprise (WISE), prioritizing clarity, scalability, and a sense of high-fidelity precision. 

The visual direction blends **Minimalism** with subtle **Glassmorphism**. Key characteristics include:
- **High-Density Utility:** Information-dense layouts that remain breathable through rigorous whitespace application.
- **Micro-Refinements:** Use of subtle 1px inner borders (rim lights) and multi-layered soft shadows to create a tactile, premium feel.
- **Technological Intelligence:** A futuristic vibe achieved through sharp typography, a deep indigo core, and vibrant cyan accents that suggest data flow and connectivity.

## Colors
The palette is rooted in a "Deep Indigo" primary to establish enterprise authority, balanced by "Electric Cyan" for interactive elements and "Emerald Green" for growth-oriented accents.

**Theming Logic:**
- **Light Mode:** Uses a slate-tinted white (`#F8FAFC`) for the base canvas. Surfaces use pure white with 1px borders in `slate-200`.
- **Dark Mode:** Transitions to "Deep Charcoal" (`#0F172A`) and "Pitch Black" (`#020617`). Background blurs (glassmorphism) should use a `white / 3%` overlay in dark mode to maintain depth.
- **Status Colors:** Success, Warning, and Critical colors are highly saturated to stand out against the professional neutral backdrop. Use these sparingly for data visualization and system feedback.

## Typography
The system utilizes a dual-font approach. **Geist** provides a technical, precise feel for headings and data labels, while **Inter** ensures maximum readability for body text and enterprise documentation.

**Hierarchy Guidelines:**
- **Display & Headlines:** Use tight letter-spacing (`-0.02em` to `-0.04em`) for a modern, "Apple-like" editorial look.
- **Labels:** Use Geist Medium or SemiBold for UI controls and table headers to distinguish them from content.
- **Color Contrast:** Secondary information (like timestamps or descriptions) should use `slate-500` in light mode or `slate-400` in dark mode.

## Layout & Spacing
This design system employs a **Fixed-Fluid Hybrid** grid. While the main content container caps at 1440px to ensure readability, internal dashboard components utilize a fluid 12-column system.

**Spacing Rhythm:**
- A strict 4px base unit (0.25rem) governs all padding and margins.
- **Enterprise Density:** For data-heavy views (tables, lists), use `stack-sm` (8px) for vertical padding. For marketing or landing pages, increase to `stack-lg` (24px) or higher.
- **Breakpoints:**
  - **Mobile:** < 768px (4 columns, 16px margins)
  - **Tablet:** 768px - 1024px (8 columns, 24px margins)
  - **Desktop:** > 1024px (12 columns, 40px margins)

## Elevation & Depth
Depth is created through "Tonal Stacking" and "Subtle Glassmorphism" rather than heavy shadows.

**Elevation Levels:**
- **Level 0 (Base):** The main background (`#F8FAFC` or `#0F172A`).
- **Level 1 (Cards):** Pure white (light) or `slate-900` (dark). Features a 1px border (`slate-200` / `white-10%`) and a soft 4px blur shadow.
- **Level 2 (Dropdowns/Modals):** Elements that float. These use **Glassmorphism**: 80% opacity with a 12px backdrop blur and a 10% white inner stroke to catch the light.
- **Shadows:** Use extremely low-opacity Indigo-tinted shadows (`rgba(30, 27, 75, 0.04)`) to keep the UI feeling "light" despite the professional tone.

## Shapes
The shape language is sophisticated and approachable. The standard radius for primary UI elements (buttons, inputs, cards) is **14px** (rounded-lg).

- **Standard Elements:** 14px (Cards, Modals, Large Buttons).
- **Small Elements:** 8px (Small buttons, input fields, tags).
- **Full Rounding:** Used exclusively for user avatars and "Status Pills" to provide visual variety against the structured grid.

## Components
Consistent implementation of these core components ensures the premium SaaS feel:

- **Buttons:** 
  - *Primary:* Deep Indigo background, white text, subtle 1px top-inner-border for a "pressed" look.
  - *Ghost:* No border, slate text, becomes Cyan-tinted on hover.
- **Cards:** Use a 14px radius. Apply a subtle 1px border. In dark mode, add a very faint gradient from top-left to bottom-right to simulate light hitting the surface.
- **Input Fields:** 1px border with a 0.5rem radius. Focus state should use a 2px Electric Cyan glow (`ring`).
- **Chips/Badges:** Small, caps-lock Geist font. Use a low-opacity background of the status color (e.g., Success badge has 10% Emerald background with 100% Emerald text).
- **Glass Sidebar:** Use a semi-transparent background with a 20px backdrop blur to separate the navigation from the main workspace while maintaining the "futuristic" aesthetic.
- **Data Tables:** Remove all vertical borders. Use 1px horizontal dividers. Header row should be `label-sm` with a light slate background.