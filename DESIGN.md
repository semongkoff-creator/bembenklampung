---
name: Industrial Excellence
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#514535'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#837563'
  outline-variant: '#d5c4af'
  surface-tint: '#815500'
  primary: '#815500'
  on-primary: '#ffffff'
  primary-container: '#f5b041'
  on-primary-container: '#694500'
  inverse-primary: '#ffb94c'
  secondary: '#5f5e5f'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfe0'
  on-secondary-container: '#636263'
  tertiary: '#5f5e5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#bebdba'
  on-tertiary-container: '#4c4c4a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffddb2'
  primary-fixed-dim: '#ffb94c'
  on-primary-fixed: '#291800'
  on-primary-fixed-variant: '#624000'
  secondary-fixed: '#e5e2e3'
  secondary-fixed-dim: '#c8c6c7'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474647'
  tertiary-fixed: '#e4e2df'
  tertiary-fixed-dim: '#c8c6c3'
  on-tertiary-fixed: '#1b1c1a'
  on-tertiary-fixed-variant: '#474745'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The brand personality is rugged, dependable, and high-performance. It balances the "heavy-duty" nature of industrial machinery with a "premium service" aesthetic. The goal is to evoke a sense of structural integrity, safety, and modern efficiency. 

The design style is **Modern Corporate** with an industrial edge. It utilizes generous whitespace to ensure clarity—reflecting a well-organized warehouse—while employing bold accents to mirror safety markings. The UI is intentionally clean and "uncluttered," projecting a sense of professional reliability and ease of use for logistics managers and construction foremen.

## Colors

The palette is rooted in functional industrialism. 

*   **Primary (Safety Yellow):** Used for critical actions, highlights, and primary branding. It demands attention without being aggressive.
*   **Secondary (Charcoal Black):** Provides a strong, grounded foundation for text and headers, ensuring high contrast and readability.
*   **Tertiary (Industrial Gray):** Used for borders, disabled states, and secondary information to maintain a professional, metallic feel.
*   **Surface (Clean White):** The primary canvas color, creating a "clean shop floor" atmosphere that feels modern and spacious.

Success, Error, and Warning states should be handled with standard semantic colors, but with a slight desaturation to match the industrial palette.

## Typography

This design system uses a dual-font strategy to balance impact with utility. 

**Montserrat** is utilized for all headlines. Its geometric, bold structure reflects the strength of heavy machinery and provides a clear visual hierarchy. **Public Sans** is used for body text and labels; it is an institutional, highly legible typeface that ensures technical specifications and rental terms are easy to digest. 

All headings should favor a heavier weight (600-700) to maintain the "Bold Industrial" feel. Labels and small metadata should utilize uppercase styling with slight letter spacing to mimic industrial stamping and labeling.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a maximum container width of 1280px to prevent excessive line lengths on ultra-wide monitors. 

*   **Desktop:** 12-column grid with 24px gutters. Use 64px outer margins to provide the "generous whitespace" required for a premium feel.
*   **Tablet:** 8-column grid with 20px gutters and 32px margins.
*   **Mobile:** 4-column grid with 16px gutters and 16px margins.

Spacing increments are strictly based on an 8px rhythm. Content blocks (cards, sections) should use larger vertical gaps (48px to 80px) to allow the UI to "breathe," ensuring the heavy industrial imagery doesn't feel cramped.

## Elevation & Depth

Visual hierarchy is established through **Ambient Shadows** and **Tonal Layers**. 

Flat surfaces use a subtle light gray border (`#E1E1E1`) by default. When an element requires elevation (like a card), apply a soft, highly diffused shadow with a slight Charcoal tint: `0px 10px 30px rgba(26, 26, 27, 0.08)`.

For interactive elements like buttons and cards, a "hover lift" effect is used: the shadow becomes more pronounced (`0px 15px 40px rgba(26, 26, 27, 0.12)`) and the element translates -4px on the Y-axis. This gives a "premium" tactile feel, as if the components are physically responsive.

## Shapes

The shape language is defined by modern accessibility. While the industry is "hard" and "metallic," the digital interface uses **Rounded (Level 2)** shapes to feel approachable and high-end. 

Standard components like input fields use a 0.5rem (8px) radius. Larger containers, such as product cards and informational modals, utilize the `rounded-xl` (1.5rem / 24px) scale to create the "2xl" rounded look requested. This softness contrasts against the bold, sharp typography to create a balanced, modern aesthetic.

## Components

### Buttons
*   **Primary:** Solid Primary Yellow (#F5B041) background with Charcoal Black text. Bold weight.
*   **Secondary:** Solid Charcoal Black background with White text.
*   **Ghost:** Transparent background with an Industrial Gray border.

### Cards
Cards are the primary content vessel. They feature a White background, the `rounded-xl` corner radius, and a subtle ambient shadow. On hover, they should scale slightly (1.02x) and increase shadow depth.

### Input Fields
Inputs use a thick 2px Industrial Gray border that transitions to Primary Yellow on focus. The label font (Public Sans) should be used for placeholders to maintain a clean, technical look.

### Industrial Icons
Icons should be thick-stroked (2px minimum) and geometric. Use "Industrial Gray" for standard icons and "Primary Yellow" for icons representing active features or safety alerts.

### Progress & Status
Status indicators (e.g., "Available", "In Maintenance") should use pill-shaped (Level 3) backgrounds with high-contrast text to mimic physical industrial status lights.