---
name: Serene Sky Glass
colors:
  surface: '#f5faff'
  surface-dim: '#d4dbe1'
  surface-bright: '#f5faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#edf4fa'
  surface-container: '#e8eff5'
  surface-container-high: '#e2e9ef'
  surface-container-highest: '#dce3e9'
  on-surface: '#151d21'
  on-surface-variant: '#3f4850'
  inverse-surface: '#2a3136'
  inverse-on-surface: '#ebf2f8'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006387'
  on-tertiary: '#ffffff'
  tertiary-container: '#007da9'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f5faff'
  on-background: '#151d21'
  surface-variant: '#dce3e9'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-badge:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system conveys an aura of technical mastery, mindfulness, and crisp clarity for a software engineering portfolio. Drawing direct inspiration from expansive, bright azure skies punctuated by translucent cumulus clouds, the aesthetic unites modern minimalism with delicate frosted glassmorphism.

The target audience comprises tech leads, recruiters, engineering executives, and collaborative clients seeking precision, calm reliability, and refined craftsmanship. The emotional response is one of cognitive ease, spaciousness, and trusted authority—countering developer portfolio clichés of dark terminal screens with an airy, elevated perspective.

## Colors
The palette balances serene atmosphere with deep contrast for high legibility:
- **Primary (`#0284C7` - Cerulean Sky):** Anchor for calls-to-action, active indicators, and interactive links.
- **Secondary (`#0F172A` - Midnight Slate):** Grounded deep navy used for headlines, key body copy, and high-emphasis structure, ensuring WCAG AAA legibility over light frosted surfaces.
- **Tertiary (`#38BDF8` - Soft Electric Azure):** Highlights, ambient glows, focus borders, and interactive hover states.
- **Neutral (`#F0F7FD` - Cloud Mist):** Soft cool-tinted canvas background, avoiding stark sterile white and enabling translucent white glass elements to stand out naturally.
- **Surface Translucency:** Glass layers leverage white at `65%` to `80%` opacity (`rgba(255, 255, 255, 0.7)`) backed by backdrop filters.

## Typography
Plus Jakarta Sans provides geometric balance, friendly terminals, and contemporary software product polish. JetBrains Mono is paired selectively for technical callouts, commit metrics, stack labels, and code snippets, instantly signaling developer identity without clashing with the serene tone.

Headings leverage tight tracking (`-0.02em` to `-0.03em`) to anchor attention against airy backgrounds. Body text maintains open line heights (`1.5` to `1.6`) to maximize comfort when scanning project case studies and architectural overviews.

## Layout & Spacing
A fluid 12-column grid structure anchored to a maximum width of `1280px` defines the desktop view, scaling down gracefully to an 8-column layout on tablets and 4 columns on mobile devices.

Generous vertical pacing reinforces the relaxed, uncluttered philosophy:
- Section gaps follow `space-xl` scaled dynamically (often doubled to `5rem` for major portfolio dividers).
- Outer margins compress on mobile screens to `1.25rem`, allowing project screenshots and code cards to maximize horizontal fidelity.
- Internal component rhythm follows an 8pt modular scale (`space-xs` through `space-xl`), ensuring predictable alignment between technical badges, media grids, and descriptive text.

## Elevation & Depth
Depth relies on translucent glass planes and tinted atmospheric drop shadows rather than heavy opaque layers:
- **Base Glass (Level 1):** `backdrop-filter: blur(16px)`, background `rgba(255, 255, 255, 0.65)`, rimmed by a micro-border of `rgba(255, 255, 255, 0.8)` on top/left edges and `rgba(2, 132, 199, 0.12)` on bottom/right edges.
- **Floating Hover (Level 2):** Applied to active project cards and dialogs: `backdrop-filter: blur(24px)`, background `rgba(255, 255, 255, 0.82)`, paired with a tinted ambient shadow `0 16px 36px -10px rgba(15, 23, 42, 0.08), 0 0 20px 2px rgba(56, 189, 248, 0.15)`.
- **Background Ambiance:** Soft, fixed gradient orbs in deep sky blue and soft electric azure drift slowly beneath the frosted layers to highlight real-time blur dispersion.

## Shapes
A consistent `roundedness: 2` (base `0.5rem` / `8px`) sets a clean, balanced geometry that complements the fluid translucency of glass surfaces. Large project cards, modal overlays, and code sandboxes use `rounded-xl` (`1.5rem` / `24px`) to emulate soft, cloud-like panels without veering into overly playful bubble forms.

## Components

### Buttons
- **Primary:** Gradient fill from Cerulean Sky (`#0284C7`) to Soft Electric Azure (`#38BDF8`), solid white text, subtle specular top inset shadow (`inset 0 1px 0 rgba(255, 255, 255, 0.3)`), `rounded-lg` geometry. Hover introduces an azure back-glow.
- **Secondary / Glass:** Background `rgba(255, 255, 255, 0.6)`, text in Midnight Slate (`#0F172A`), border `1px solid rgba(255, 255, 255, 0.7)`, with `backdrop-filter: blur(12px)`.

### Chips & Tech Stack Badges
- Pill-shaped tags (`rounded-full`) utilizing `label-code` typography. Background tinted `rgba(2, 132, 199, 0.08)` with a faint border of `rgba(2, 132, 199, 0.2)`. Text renders in Cerulean Sky.

### Cards (Project & Experience)
- Frosted glass finish with `1.5rem` internal padding (`space-lg`), soft rounded corners (`rounded-xl`), and delicate hairline white borders. Hover triggers a subtle upward lift (`translateY(-4px)`) and intensifies the electric azure edge illumination.

### Input Fields & Contact Elements
- Inputs feature `rgba(255, 255, 255, 0.5)` background, `backdrop-filter: blur(8px)`, and border `1px solid rgba(15, 23, 42, 0.1)`. Focus states smoothly transition border color to `#38BDF8` with an ambient glow (`box-shadow: 0 0 0 3px rgba(56, 189, 248, 0.25)`).

### Code Snippets & Terminal Windows
- Semi-translucent dark slate card (`rgba(15, 23, 42, 0.85)`) embedded with macOS-style window controls (soft azure, cerulean, and neutral grey dots). Syntax highlighted in serene ice blues, teals, and soft whites.