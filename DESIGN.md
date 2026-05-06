---
name: Premium Artist Executive
colors:
  surface: '#121318'
  surface-dim: '#121318'
  surface-bright: '#38393f'
  surface-container-lowest: '#0d0e13'
  surface-container-low: '#1a1b21'
  surface-container: '#1e1f25'
  surface-container-high: '#282a2f'
  surface-container-highest: '#33343a'
  on-surface: '#e2e2e9'
  on-surface-variant: '#e5bdbb'
  inverse-surface: '#e2e2e9'
  inverse-on-surface: '#2f3036'
  outline: '#ac8887'
  outline-variant: '#5c403f'
  surface-tint: '#ffb3b1'
  primary: '#ffb3b1'
  on-primary: '#680011'
  primary-container: '#c8102e'
  on-primary-container: '#ffdad8'
  inverse-primary: '#bf0229'
  secondary: '#c5c6ca'
  on-secondary: '#2e3134'
  secondary-container: '#494c4f'
  on-secondary-container: '#babcbf'
  tertiary: '#c3c7cb'
  on-tertiary: '#2d3135'
  tertiary-container: '#616569'
  on-tertiary-container: '#e0e3e8'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#e1e2e6'
  secondary-fixed-dim: '#c5c6ca'
  on-secondary-fixed: '#191c1f'
  on-secondary-fixed-variant: '#44474a'
  tertiary-fixed: '#e0e3e8'
  tertiary-fixed-dim: '#c3c7cb'
  on-tertiary-fixed: '#181c20'
  on-tertiary-fixed-variant: '#43474b'
  background: '#121318'
  on-background: '#e2e2e9'
  surface-variant: '#33343a'
typography:
  h1:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  h3:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 32px
  gutter: 24px
  margin-sm: 12px
  margin-md: 24px
  margin-lg: 48px
---

## Brand & Style

This design system is tailored for high-level music industry executives and premium artists who require a sophisticated, data-rich environment that feels authoritative yet modern. The aesthetic moves away from pure black into a refined charcoal-grey space, creating a softer but equally prestigious atmosphere.

The style is **Corporate / Modern** with a focus on high-end editorial clarity. It utilizes deep tonal layering rather than aggressive shadows to define hierarchy. The emotional response is one of "controlled power"—a workspace that feels expensive, focused, and operationally superior.

## Colors

The palette is anchored by a foundational charcoal base (#2a2d30). This specific grey provides a low-strain reading environment while maintaining a premium "Executive Dark Mode" feel. 

- **Primary Accent:** Brand Red (#C8102E) is used sparingly for critical actions, key performance indicators, and brand touchpoints.
- **Surface Hierarchy:** To maintain depth against the #2a2d30 background, containers use subtly lighter increments. Level 1 surfaces use #323539, while interactive or hovering states elevate to #3d4044.
- **Functional Greys:** Text utilizes high-contrast white for headings and a muted silver-grey (#ced4da) for secondary metadata to ensure a clear information hierarchy.

## Typography

The design system exclusively utilizes **Manrope** to bridge the gap between geometric modernism and functional legibility. 

- **Headlines:** Set with tight letter-spacing and heavy weights (700-800) to project confidence.
- **Body:** Set with generous line height (1.6) to ensure readability against the dark charcoal backgrounds.
- **Labels:** Always set in Semi-Bold or Bold to ensure functional UI elements are easily scannable. Capitalization should be used for section headers to evoke an editorial feel.

## Layout & Spacing

The system employs a **Fixed Grid** philosophy for dashboard views and a **Fluid Grid** for content-heavy lists. The base spacing unit is 8px.

- **Layout Model:** A 12-column grid with 24px gutters. Content is typically housed in "Executive Modules" (cards) that span 3, 4, 6, or 12 columns.
- **Rhythm:** Generous internal padding (32px) within containers is required to maintain the "Premium" feel, preventing the density often found in standard enterprise software.

## Elevation & Depth

In this design system, depth is communicated through **Tonal Layering** and **Soft Inner Strokes** rather than heavy drop shadows.

- **Background:** #2a2d30 (The floor).
- **Raised Surfaces:** #323539 with a 1px top-edge highlight of #404347 to simulate physical thickness.
- **Floating Elements:** Modals and menus use the #3d4044 surface with a very subtle, large-radius ambient shadow (Black, 25% opacity, 30px blur) to separate from the primary canvas.
- **Active State:** Elements being interacted with should utilize a subtle Brand Red (#C8102E) glow or a border-left accent.

## Shapes

The design system uses **Soft** geometry. This provides a professional, "tailored" appearance that is more approachable than sharp corners but more serious than fully rounded mobile-first designs.

- **Standard Components:** 0.25rem (4px) corner radius for small inputs and buttons.
- **Modules/Cards:** 0.5rem (8px) corner radius for primary layout containers.
- **Media/Avatars:** Circular (pill) shapes are reserved exclusively for artist profile images to contrast against the structured rectangular layout.

## Components

- **Buttons:** Primary buttons are solid Brand Red (#C8102E) with white text. Secondary buttons use a ghost style with a #4a4d51 border and white text.
- **Inputs:** Fields use a darker inset background (#222528) with a 1px border (#404347). On focus, the border transitions to Brand Red.
- **Cards/Modules:** These are the workhorses of the system. They must use the #323539 surface color. Titles within cards should always be Manrope Semi-Bold.
- **Chips/Badges:** Small, low-saturation backgrounds (e.g., #3d4044) with high-contrast text. For status indicators (Active/Pending), use a small 8px colored dot alongside the text.
- **Lists:** Rows should be separated by 1px dividers (#3a3e42). Hover states for list items should shift the background color to #3d4044.
- **Navigation:** Side navigation uses a slightly darker shade than the main background to anchor the layout, with active icons highlighted in Brand Red.