---
name: Organic Shop Design System
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#424844'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#727973'
  outline-variant: '#c2c8c2'
  surface-tint: '#496455'
  primary: '#173124'
  on-primary: '#ffffff'
  primary-container: '#2d4739'
  on-primary-container: '#98b5a3'
  inverse-primary: '#b0cdbb'
  secondary: '#4a654a'
  on-secondary: '#ffffff'
  secondary-container: '#ccebc8'
  on-secondary-container: '#506b50'
  tertiary: '#3f2611'
  on-tertiary: '#ffffff'
  tertiary-container: '#583b25'
  on-tertiary-container: '#cea689'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ccead6'
  primary-fixed-dim: '#b0cdbb'
  on-primary-fixed: '#062014'
  on-primary-fixed-variant: '#324c3e'
  secondary-fixed: '#ccebc8'
  secondary-fixed-dim: '#b0ceae'
  on-secondary-fixed: '#07200b'
  on-secondary-fixed-variant: '#334d34'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#e8bea0'
  on-tertiary-fixed: '#2c1604'
  on-tertiary-fixed-variant: '#5d4029'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system centers on an **Organic Minimalism** aesthetic. It is crafted for an artisanal marketplace that prioritizes sustainability, transparency, and a connection to the earth. The target audience values quality over quantity and seeks a shopping experience that feels calm, grounded, and intentional rather than transactional.

The UI evokes an emotional response of "breathable luxury"—combining the cleanliness of modern SaaS with the warmth of a boutique apothecary. We achieve this through:
- **Heavy Whitespace:** Giving products room to breathe, mimicking high-end gallery layouts.
- **Soft Tactility:** Using subtle depth and natural color transitions rather than harsh dividers.
- **Refined Typography:** Leveraging modern sans-serifs with generous tracking to feel sophisticated yet approachable.

## Colors

The palette is derived from the natural lifecycle of a forest. 
- **Primary (Forest Green):** Used for primary actions, high-level headers, and critical UI states. It represents stability and growth.
- **Secondary (Sage Green):** Used for accents, success states, and decorative elements. It provides a calming contrast to the deep primary green.
- **Tertiary (Wood Brown):** Reserved for textural details, specific icons, and interactive hover states that require warmth.
- **Neutral (Soft Cream):** The "paper" of the interface. This replaces pure white to reduce eye strain and provide a more premium, recycled-stock feel.

## Typography

We use **Plus Jakarta Sans** across all levels to maintain a clean, contemporary rhythm. To align with the organic theme:
- **Weight Strategy:** Headlines use Semi-Bold (600) and Bold (700) to feel established. Body text remains at Regular (400) for maximum legibility against cream backgrounds.
- **Letter Spacing:** Headlines utilize slight negative tracking for a tighter, more "editorial" look. Labels use increased letter spacing and Medium/Semi-Bold weights to ensure they feel like distinct "stamps" or "tags."
- **Scale:** On mobile, display sizes scale down significantly to prevent awkward word wrapping while maintaining the bold hierarchy.

## Layout & Spacing

The design system utilizes a **Fixed Grid** for desktop and a **Fluid Grid** for mobile. 
- **Desktop:** A 12-column grid centered in a 1280px container. Large 48px margins create a frame effect around the content.
- **Mobile:** A 4-column grid with 16px margins, maximizing the small screen real estate while maintaining consistent gutters.
- **Spacing Rhythm:** We use an 8px base unit. Vertical stack spacing (stack-lg) is intentionally generous to prevent the "cluttered shop" feel, emphasizing an curated boutique experience.

## Elevation & Depth

To maintain the grounded, organic feel, we avoid traditional high-contrast shadows. Depth is communicated through:
- **Tonal Layering:** The primary background is the neutral cream. Surfaces like cards or modals use a slightly lighter or darker tint (Accent Cream) to distinguish themselves.
- **Soft Ambient Shadows:** Where elevation is necessary (e.g., floating action buttons), use very diffused, low-opacity shadows with a hint of the secondary Sage Green in the shadow color to avoid a "grey/dirty" look.
- **Inner Borders:** Subtle 1px borders in a shade just slightly darker than the surface are preferred over shadows for input fields and containers.

## Shapes

The shape language is **Rounded (Level 2)**. 
- Standard components (buttons, inputs) use a 0.5rem (8px) radius.
- Large containers and product cards use a 1rem (16px) radius.
- Interactive chips or tags may use 1.5rem (24px) to create a pebble-like appearance.
This level of roundedness feels approachable and natural, echoing the forms found in nature, without the "childlike" feel of full pill-shapes.

## Components

### Buttons
Primary buttons use the Forest Green background with Cream text. Secondary buttons are outlined in Wood Brown with Wood Brown text. The "Artisanal" feel is reinforced by using a slightly wider horizontal padding (24px) for a more elegant silhouette.

### Input Fields
Inputs use a Soft Cream background with a Sage Green bottom-border (2px) when focused. This creates a "writing on a ledger" feel that is less clinical than a full box stroke.

### Cards
Product cards should have no outer border and no shadow. They rely on the color contrast between the Cream background and the Forest Green text. Images should have the standard Level 2 roundedness applied.

### Chips & Tags
Used for product categories (e.g., "Vegan," "Local"). These use the Sage Green at 10% opacity as a background with the full-strength Sage Green for the text, creating a soft, monochromatic look.

### Checkboxes & Radios
Custom-styled to use the Wood Brown color when selected, emphasizing the tactile, earthy theme. The "check" icon should be a simple, hand-drawn style tick if possible.

### Lists
Lists of products or ingredients should feature generous line-height (body-lg) and use small Forest Green leaf icons or simple dots as bullets to reinforce the organic theme.