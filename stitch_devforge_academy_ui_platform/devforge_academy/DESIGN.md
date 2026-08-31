---
name: DevForge Academy
colors:
  surface: '#141218'
  surface-dim: '#141218'
  surface-bright: '#3b383e'
  surface-container-lowest: '#0f0d13'
  surface-container-low: '#1d1b20'
  surface-container: '#211f24'
  surface-container-high: '#2b292f'
  surface-container-highest: '#36343a'
  on-surface: '#e6e0e9'
  on-surface-variant: '#cbc4d2'
  inverse-surface: '#e6e0e9'
  inverse-on-surface: '#322f35'
  outline: '#948e9c'
  outline-variant: '#494551'
  surface-tint: '#cfbcff'
  primary: '#cfbcff'
  on-primary: '#381e72'
  primary-container: '#6750a4'
  on-primary-container: '#e0d2ff'
  inverse-primary: '#6750a4'
  secondary: '#cdc0e9'
  on-secondary: '#342b4b'
  secondary-container: '#4d4465'
  on-secondary-container: '#bfb2da'
  tertiary: '#e7c365'
  on-tertiary: '#3e2e00'
  tertiary-container: '#c9a74d'
  on-tertiary-container: '#503d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#cfbcff'
  on-primary-fixed: '#22005d'
  on-primary-fixed-variant: '#4f378a'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#cdc0e9'
  on-secondary-fixed: '#1f1635'
  on-secondary-fixed-variant: '#4b4263'
  tertiary-fixed: '#ffdf93'
  tertiary-fixed-dim: '#e7c365'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#141218'
  on-background: '#e6e0e9'
  surface-variant: '#36343a'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
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
  label-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  code-md:
    fontFamily: JetBrains Mono
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
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 40px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system for this product is rooted in a **Technical Modernist** aesthetic, specifically tailored for frontend developers. It balances the rigor of code with the sleekness of high-end software tools. The personality is authoritative yet inspiring, aiming to evoke a "flow state" emotional response. 

The visual language utilizes elements of **Minimalism** and **Glassmorphism**, emphasizing high-quality typography and subtle translucent layers to represent the modular nature of programming. It rejects unnecessary ornamentation in favor of functional clarity and precise alignment, ensuring that the educational content remains the focal point while maintaining a cutting-edge technical edge.

## Colors
The color strategy employs a "Functional Palette" system, allowing users to select a workspace vibe that suits their coding environment. 

1.  **Cyber Slate:** Electric violet on slate; high energy for creative coding.
2.  **Neo Mint:** Neon mint on obsidian; high contrast for long nights.
3.  **Cobalt Pro:** Cyan on navy; the standard "technical" professional look.
4.  **Amber Sunset:** Amber on charcoal; a warmer, lower-strain alternative.

In **Dark Mode**, surfaces use the `surface` token with a 1px border of 10% opacity white to define edges. In **Light Mode**, the primary colors are darkened by 15% to maintain accessibility (WCAG AA) against white backgrounds. Semantic colors (Success, Error, Warning) remain consistent across all palettes to ensure diagnostic clarity in code feedback.

## Typography
The typographic hierarchy is designed for maximum legibility of complex technical documentation. 

- **Space Grotesk** is used for all headlines and display text, its geometric quirks providing a futuristic, engineered feel.
- **Inter** handles all UI labels and long-form body text, chosen for its exceptional clarity and neutral tone.
- **JetBrains Mono** is reserved strictly for code blocks, terminal outputs, and inline technical references. 

Line heights are generous to prevent eye fatigue during long reading sessions. Use `label-sm` for navigation and metadata to provide a crisp, organized structure.

## Layout & Spacing
This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

The spacing rhythm is based on a **4px baseline grid**. Components should prioritize "Stack" layouts (vertical spacing) using the `stack` tokens to ensure consistent content flow. 

- **Desktop (1024px+):** 12 columns, 24px gutters, 40px side margins.
- **Tablet (768px - 1023px):** 8 columns, 20px gutters, 32px side margins.
- **Mobile (Up to 767px):** 4 columns, 16px gutters, 20px side margins.

Content blocks, such as course modules or code editors, should utilize the `container-max` width to prevent line lengths from becoming unreadable on ultra-wide monitors.

## Elevation & Depth
Hierarchy is established through **Tonal Layering** and **Ambient Shadows**.

1.  **Level 0 (Background):** The base palette `neutral` color.
2.  **Level 1 (Cards/Sidebar):** The `surface` color, slightly elevated.
3.  **Level 2 (Modals/Popovers):** The `surface` color with a soft, diffused shadow (`0px 10px 30px rgba(0,0,0,0.25)`).

Shadows are never pure black; they are tinted with the palette's primary color at 5-10% opacity to maintain a cohesive atmospheric glow. Glassmorphism is applied to fixed navigation bars using a 12px backdrop blur and a semi-transparent version of the surface color to provide context of the content scrolling beneath.

## Shapes
The shape language is **Soft (0.25rem)**. This provides a professional, "tooled" look that isn't as aggressive as sharp corners but avoids the overly consumer-focused feel of heavy rounding.

- **Standard Elements (Buttons, Inputs):** 4px (0.25rem) radius.
- **Containers (Cards, Code Blocks):** 8px (0.5rem) radius.
- **Modals/Large Overlays:** 12px (0.75rem) radius.

Icons should follow a 2px stroke width with rounded ends to match the UI's subtle corner treatment.

## Components

### Buttons
Primary buttons use a solid fill of the palette's `primary` color with white or high-contrast text. Secondary buttons use an outline style (1px) with a subtle hover state that fills the background at 10% opacity.

### Cards
Cards are the primary container for course modules. They feature a 1px border (opacity 0.1) and a very soft ambient shadow on hover. The header of the card should use `headline-md` in Space Grotesk.

### Input Fields
Inputs use the `surface` color for the fill to distinguish them from the page background. On focus, the border transitions to the `primary` color with a 2px outer glow (glow color matches primary at 20% opacity).

### Chips/Tags
Used for language labels (e.g., "React", "TypeScript"). These are small, pill-shaped elements with a subtle background tint and 70% opacity text.

### Code Blocks
Code blocks must use the `code-md` typography. The header of the code block should display the file name and a "Copy" button. Syntax highlighting must be customized to align with the active Functional Palette.

### Micro-interactions
- **Hover:** Buttons and interactive cards should lift slightly (translate -2px) and increase shadow density.
- **Loading:** Use a sleek linear progress bar at the top of the container rather than a spinning wheel.
- **Transitions:** All state changes (hover, focus, modal entry) should use a 200ms `ease-out` transition.