---
name: Architectural Precision
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#424656'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#727687'
  outline-variant: '#c2c6d8'
  surface-tint: '#0054d6'
  primary: '#0050cb'
  on-primary: '#ffffff'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#b3c5ff'
  secondary: '#8c4f10'
  on-secondary: '#ffffff'
  secondary-container: '#fdad67'
  on-secondary-container: '#763f00'
  tertiary: '#a33200'
  on-tertiary: '#ffffff'
  tertiary-container: '#cc4204'
  on-tertiary-container: '#fff6f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#ffdcc2'
  secondary-fixed-dim: '#ffb77b'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#6d3a00'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832600'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  slate-gray: '#1E293B'
  off-white: '#F8FAFC'
  teal-accent: '#226D7A'
  sky-tint: '#B0E0E9'
typography:
  display-lg:
    fontFamily: Syne
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is engineered for a premium architectural and luxury real estate aesthetic, specifically tailored for high-end roofing and exterior services. The brand personality is authoritative, precise, and sophisticated, targeting discerning homeowners and commercial property managers who value structural integrity as much as visual excellence.

The design style follows a **Modern Architectural Minimalism**. It utilizes high-contrast transitions between deep, obsidian-like surfaces and crisp, gallery-white spaces. The visual language is defined by structural rigidity, generous whitespace to allow high-resolution project photography to breathe, and surgical precision in detail. It rejects "soft" or "playful" trends in favor of a powerful, institutional presence that evokes the permanence of high-quality construction.

## Colors

The palette is rooted in architectural materials: charcoal, slate, and metal. 

- **Primary & CTA:** Electric Blue (#0066FF) serves as the primary action color, providing a modern, high-tech contrast against dark backgrounds. Metallic Copper (#B87333) is used as a sophisticated secondary accent for "Premium" or "Heritage" service tiers.
- **Surface Strategy:** Use Deep Charcoal (#121212) for hero sections and footers to establish gravity. Off-White (#F8FAFC) is the primary background for content-heavy sections to ensure maximum readability and a "studio" feel.
- **Legacy Accents:** Subtle implementations of Teal (#226D7A) can be used for secondary informative icons, acknowledging the brand's established identity while elevating it within the new high-contrast framework.

## Typography

The typography strategy balances the avant-garde geometry of **Syne** with the utilitarian clarity of **Inter**.

- **Headlines:** Syne is used for all major headings. Its unique, wide proportions and bold weights create an immediate architectural "statement." Display sizes should use tight tracking to emphasize the structural interlocking of characters.
- **Body & Technical Info:** Inter provides a neutral, highly legible counterpoint. It is used for all long-form text, technical specifications, and navigational elements.
- **Hierarchy:** Use `label-caps` for section overlines (e.g., "COMMERCIAL SERVICES") to create an organized, blueprint-inspired rhythm.

## Layout & Spacing

This design system employs a **Fixed-Fluid Hybrid Grid**. Content is housed within a 1280px max-width container for desktop, centered with significant side margins to create an upscale "editorial" feel.

- **Rhythm:** Spacing follows an 8px base unit. Section gaps are intentionally large (120px+) to distinguish different service areas and prevent visual clutter.
- **Breakpoints:** 
    - **Desktop (1280px+):** 12-column grid, 24px gutters.
    - **Tablet (768px - 1279px):** 6-column grid, 32px margins.
    - **Mobile (Under 768px):** 2-column grid, 20px margins, reduced section gaps (80px).
- **Reflow:** Cards and service blocks should transition from 3-column layouts on desktop to single-column vertical stacks on mobile to preserve image aspect ratios.

## Elevation & Depth

To maintain the architectural aesthetic, depth is conveyed through **Structural Layering** rather than heavy drop shadows.

- **Tonal Layers:** Use the transition between `#121212` and `#1E293B` to define depth. Darker surfaces sit "further back," while slightly lighter slate surfaces represent interactive cards or modals.
- **Ghost Outlines:** Use 1px solid borders in low-opacity white (10-15%) on dark backgrounds or light gray on light backgrounds. This mimics architectural drafting lines.
- **Subtle Elevation:** When shadows are necessary for utility (e.g., dropdowns), use a "Long-Soft" shadow: `0 20px 40px rgba(0,0,0,0.1)`. This avoids a "muddy" look and maintains the crispness of the UI.

## Shapes

The shape language is strictly **Sharp (0px roundedness)**. 

This decision reinforces the themes of construction, slate roofing tiles, and architectural beams. Every button, input field, and image container must feature hard 90-degree angles. This lack of "softness" differentiates the brand as a serious, professional engineering and exterior firm. 

**Exceptions:** Circular icons may be used for social media links or status indicators, but all structural containers must remain rectangular.

## Components

- **Buttons:** Primary buttons use a solid Electric Blue fill with white text, no border, and sharp corners. Hover states should involve a color shift to a slightly deeper blue or a fill-to-outline transition. Secondary buttons use a "Ghost" style: 1px border with no fill.
- **Input Fields:** Bottom-border only (1px solid) to mimic a formal architectural contract style. Active states highlight the border in Electric Blue.
- **Cards:** No background fill or shadow by default; instead, use 1px solid borders (`#E2E8F0`) and high-resolution imagery. On hover, the border thickness may increase or the image may slightly scale.
- **Service Chips:** Small, rectangular tags with `label-caps` typography. Background should be `#1E293B` with white text for high contrast.
- **Image Treatment:** All project photography should use high-contrast filters with a slight desaturation to ensure they sit harmoniously within the Charcoal/Slate/Off-White theme.
- **Navigation:** A minimal top bar with "mega-menu" capabilities for service categories, utilizing the full width of the container.