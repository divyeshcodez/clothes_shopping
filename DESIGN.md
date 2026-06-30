---
name: Friendary
colors:
  surface: '#fff7ff'
  surface-dim: '#e7d2ff'
  surface-bright: '#fff7ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf0ff'
  surface-container: '#f6e9ff'
  surface-container-high: '#f1e3ff'
  surface-container-highest: '#eddcff'
  on-surface: '#24123c'
  on-surface-variant: '#4d4634'
  inverse-surface: '#3a2852'
  inverse-on-surface: '#f8edff'
  outline: '#7f7661'
  outline-variant: '#d1c5ad'
  surface-tint: '#745c00'
  primary: '#745c00'
  on-primary: '#ffffff'
  primary-container: '#ffd23f'
  on-primary-container: '#725a00'
  inverse-primary: '#edc22e'
  secondary: '#a53360'
  on-secondary: '#ffffff'
  secondary-container: '#ff7aa8'
  on-secondary-container: '#76093d'
  tertiary: '#3c692b'
  on-tertiary: '#ffffff'
  tertiary-container: '#b1e598'
  on-tertiary-container: '#3b682a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe089'
  primary-fixed-dim: '#edc22e'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffd9e2'
  secondary-fixed-dim: '#ffb1c7'
  on-secondary-fixed: '#3e001c'
  on-secondary-fixed-variant: '#861948'
  tertiary-fixed: '#bdf1a3'
  tertiary-fixed-dim: '#a1d489'
  on-tertiary-fixed: '#052100'
  on-tertiary-fixed-variant: '#255015'
  background: '#fff7ff'
  on-background: '#24123c'
  surface-variant: '#eddcff'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
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
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The design system is built on a foundation of "Digital Craftmanship." It rejects the cold, sterile efficiency of typical SaaS platforms in favor of a warm, tactile experience that feels like a neighborhood print shop. The brand personality is optimistic, supportive, and unpretentious.

The design style is a blend of **Minimalism** and **Tactile/Skeuomorphism**. We use plenty of whitespace (using Warm Cream instead of white) to let products shine, but we apply physical metaphors—stickers, paper textures, and organic edges—to make the interface feel tangible and "handmade." Every interaction should evoke the feeling of picking up a freshly printed shirt or sticking a decal onto a notebook.

## Colors
The palette is grounded in a "Sun-Drenched Studio" aesthetic. 

- **Sunshine Yellow (#FFD23F)** is the hero color, used for primary actions and to draw the eye to creative possibilities.
- **Warm Cream (#FFF8EC)** replaces pure white as the global background to reduce eye strain and provide a "paper" feel.
- **Deep Blueberry (#3D2B56)** provides necessary contrast and weight for typography, ensuring the playful palette remains professional and trustworthy.
- **Bubblegum Pink (#FF7AA8)** serves as the energetic spark for secondary highlights and interactive hover states.
- **Soft Sage (#7FB069)** is used for success states and "Free" tags, offering an organic, eco-friendly vibe that feels more "craft" than "corporate."

## Typography
The typography strategy pairs the soft, rounded geometry of **Plus Jakarta Sans** for headlines with the warm, humanist legibility of **Nunito Sans** for body text. 

Headlines should be set with tight tracking to feel like bold headers on a storefront window. Use "Deep Blueberry" for almost all text to maintain a soft but high-contrast readability. For special emphasis or "Sale" items, use a wobbly strikethrough decoration in Sunshine Yellow or Bubblegum Pink.

## Layout & Spacing
This design system utilizes a **Fluid Grid** with generous margins to create a relaxed, breathable atmosphere. 

- **Desktop:** 12-column grid with 24px gutters. Content should be centered with a maximum width of 1280px.
- **Mobile:** 4-column grid with 16px gutters and 16px side margins.
- **Spacing Rhythm:** Use 8px increments. Large sections should be separated by 80px or 120px to maintain the "minimalist craft" aesthetic.

Instead of hard horizontal rules, use SVG-based **wavy dividers** to separate major page sections (e.g., Hero to Features). This reinforces the "organic" and "handmade" narrative.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Sticker Effects** rather than traditional drop shadows.

- **Level 0 (Base):** Warm Cream background.
- **Level 1 (Cards):** Flat White background with a 2px solid Deep Blueberry border, offset by 4px to the bottom-right to create a "printed card" look.
- **Level 2 (Active/Hover):** A subtle "peel" effect where one corner of a card lifts slightly using a small, high-blur shadow (0px 10px 20px rgba(61, 43, 86, 0.08)).
- **Overlays:** Use semi-transparent Deep Blueberry (20% opacity) for backdrops to keep the focus on the vibrant modals.

## Shapes
Shapes are unapologetically soft and friendly. All primary containers use a 16px (rounded-lg) or 24px (rounded-xl) radius. 

Avoid sharp 90-degree angles entirely. Buttons, input fields, and tags should feel "squishy" and approachable. Icons should feature rounded caps and slightly imperfect, hand-drawn strokes to match the craft aesthetic.

## Components
### Buttons
Primary buttons are Sunshine Yellow with Deep Blueberry text. They use a "3D Press" effect: a 4px solid bottom border that disappears on click, simulating a physical button press.

### Chips & Tags
"Free" tags use Soft Sage background with a thin, dashed border to look like a sewn-on garment label. Use Bubblegum Pink for "New" or "Hot" items.

### Cards
Cards feature the "peeling" effect on hover. Product images within cards should have a slight 2-degree random rotation to appear like they were hand-placed on a table.

### Inputs
Search bars and form fields use a 2px solid border in Deep Blueberry. When focused, the background shifts from White to a very pale version of Sunshine Yellow.

### Icons & Illustrations
Use "doodle-style" iconography. Lines should not be perfectly straight; they should have a slight variable width to mimic a felt-tip pen.