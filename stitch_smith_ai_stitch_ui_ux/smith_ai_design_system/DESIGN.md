---
name: Atlyra Design System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
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
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
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
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  code-md:
    fontFamily: jetbrainsMono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  container-max: 1440px
---

## Brand & Style
The design system is engineered for an enterprise-level technical interview platform where precision, clarity, and authority are paramount. The brand personality is "The Expert Peer"—intelligent, unbiased, and highly efficient. 

The aesthetic follows a **Modern Enterprise** approach: a refined blend of high-end minimalism and functional technicality. It avoids all forms of visual noise, such as gradients or decorative flourishes, to focus entirely on data integrity and candidate performance metrics. The emotional response should be one of absolute trust and professional focus, ensuring that both the interviewer and the candidate feel they are using a high-performance tool rather than a generic HR application.

## Colors
The palette is rooted in a deep "Midnight Slate" (`#0F172A`) which serves as the primary color for high-level navigation and primary headings, providing a sense of stability and institutional gravity. 

- **Primary:** Midnight Slate. Used for core branding, sidebar backgrounds, and high-emphasis text.
- **Action/Accent:** Professional Blue (`#3B82F6`). Reserved strictly for interactive elements, primary buttons, and active states. It provides a sharp contrast against the neutral backdrop.
- **Surface/Neutral:** A sophisticated range of cool grays. Use `#F8FAFC` for page backgrounds and `#FFFFFF` for content cards to create subtle but clear depth.
- **Status:** Use industry-standard semantic colors (Emerald for success, Rose for errors, Amber for warnings) but desaturate them slightly to maintain the professional tone.

## Typography
The system utilizes **Geist** for headings and UI labels to provide a technical, sharp edge that feels modern and developer-centric. **Inter** is used for all body copy and data entry points to ensure maximum readability during long evaluation sessions.

- **Scale:** Maintain a strict hierarchical contrast. Headings should be significantly heavier and tighter in letter-spacing than body text.
- **Technical Content:** For code snippets or technical output, use JetBrains Mono at 14px to ensure alignment and readability in monospaced environments.
- **Data Tables:** Use `body-sm` for tabular data to maximize information density without sacrificing legibility.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to ensure data visualization remains consistent across different monitor sizes, while transitioning to a fluid model for mobile.

- **Grid:** Use a 12-column grid with 24px gutters. 
- **Rhythm:** All spacing must be a multiple of 4px. Use 24px (`md`) for standard padding within cards and 40px (`lg`) for vertical section separation.
- **Density:** Technical dashboards should utilize "Comfortable" density, using whitespace as a separator rather than lines whenever possible to reduce visual clutter.
- **Responsive:** On mobile, margins reduce to 16px and the 12-column grid collapses to a single column, with specific "Candidate View" optimizations for coding environments.

## Elevation & Depth
This design system employs **Tonal Layers** combined with **Low-Contrast Outlines**. We avoid heavy shadows to maintain a "flat-plus" professional aesthetic.

- **Surface 1 (Base):** `#F8FAFC` (Slate 50).
- **Surface 2 (Card):** `#FFFFFF` with a 1px border in `#E2E8F0` (Slate 200). 
- **Elevation:** Only the "Active" or "Hovered" card receives a shadow. The shadow should be a very soft, diffused `#0F172A` at 4% opacity with a 12px blur.
- **Interaction:** Modals and dropdowns use a slightly more pronounced shadow (8% opacity) to distinguish them from the underlying data layer.

## Shapes
The shape language is **Soft (Level 1)**. This ensures the UI feels approachable and modern without losing the "engineered" precision of sharp-cornered professional software.

- **Standard Elements:** 4px (`0.25rem`) radius for buttons, input fields, and small tags.
- **Containers:** 8px (`0.5rem`) radius for main content cards and modals.
- **Selection Indicators:** Use vertical 2px bars for active menu states rather than rounded pills to maintain a more "technical" feel.

## Components
- **Buttons:** Primary buttons are solid `#3B82F6` with white text. Secondary buttons use a 1px border with `#475569` text. All buttons have a height of 40px for standard actions.
- **Input Fields:** Use a subtle `#F1F5F9` background with a 1px `#E2E8F0` border. On focus, the border transitions to Primary Blue with a 2px outer glow (ring).
- **Cards:** White background, 8px radius, 1px Slate-200 border. No shadow by default. Headers within cards should have a subtle bottom border to separate metadata from content.
- **Chips/Badges:** For status (e.g., "Passed", "Senior", "Python"), use a very light tint of the semantic color with high-contrast text. No bold backgrounds for badges unless it's a critical error.
- **Code Editor:** The core component. Must feature a dark-themed syntax highlighter (e.g., Slate/Nord-inspired) even in light mode to reduce eye strain during technical tasks.
- **Data Visualization:** Use clean line charts and progress bars. Avoid 3D effects or complex gauges.