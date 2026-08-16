---
name: Ancestral Glow
colors:
  surface: '#fff8ef'
  surface-dim: '#e1d9cb'
  surface-bright: '#fff8ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf3e4'
  surface-container: '#f5edde'
  surface-container-high: '#efe7d9'
  surface-container-highest: '#e9e2d3'
  on-surface: '#1e1b13'
  on-surface-variant: '#5a403e'
  inverse-surface: '#343026'
  inverse-on-surface: '#f8f0e1'
  outline: '#8e706d'
  outline-variant: '#e2beba'
  surface-tint: '#b52424'
  primary: '#8f000d'
  on-primary: '#ffffff'
  primary-container: '#b22222'
  on-primary-container: '#ffc8c2'
  inverse-primary: '#ffb4ac'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#802226'
  on-tertiary: '#ffffff'
  tertiary-container: '#9f3a3c'
  on-tertiary-container: '#ffc8c5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#92030f'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#ffb3b0'
  on-tertiary-fixed: '#410006'
  on-tertiary-fixed-variant: '#832428'
  background: '#fff8ef'
  on-background: '#1e1b13'
  surface-variant: '#e9e2d3'
  peruvian-white: '#FFFFFF'
  charcoal-black: '#2D2926'
  deep-wood: '#4A2C2A'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Montserrat
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
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The brand personality is **Authentic, Passionate, and Cozy**. This design system bridges the gap between traditional Peruvian culinary heritage and a modern dining experience. It aims to evoke the warmth of a charcoal grill (*brasas*) and the communal joy of a family meal.

The visual style is **Tactile & Modern**. We utilize high-quality food photography as a core structural element, supported by wood-inspired textures and warm, layered surfaces. The interface should feel "edible" and inviting, using soft shadows and organic shapes to move away from cold, corporate aesthetics.

## Colors
The palette is inspired by the heat of the hearth and natural Peruvian pigments. 
- **Deep Ember Red (#B22222)** serves as the primary brand anchor, used for headers and key brand elements.
- **Warm Orange (#FF8C00)** is the high-contrast action color, reserved for Call-to-Actions (CTAs) like "Order Now" or "Book a Table."
- **Cream/Off-white (#FDF5E6)** replaces pure white for all large background surfaces to maintain a soft, inviting atmosphere and reduce eye strain.
- **Charcoal Black** is used for primary text to ensure high legibility while maintaining the "grilled" thematic connection.

## Typography
The typographic system pairs the elegance of a classic serif with the clarity of a modern geometric sans-serif. 
- **Playfair Display** is used for all headlines to convey a sense of quality, tradition, and culinary excellence. It should be used with slightly tighter letter-spacing for large displays.
- **Montserrat** handles all functional text, menus, and descriptions. Its wide apertures ensure legibility on mobile devices, even in low-light dining environments. 
- All labels and buttons use uppercase Montserrat with increased tracking to differentiate them from body copy.

## Layout & Spacing
This design system follows a **Fluid Grid** model with a mobile-first philosophy.
- **Mobile (< 600px):** Single column layout with 16px side margins. High-use buttons (Order/Menu) are often fixed to the bottom of the viewport.
- **Tablet (600px - 1024px):** 8-column grid. Food menus transition to a 2-column masonry or grid layout.
- **Desktop (> 1024px):** 12-column grid with a maximum content width of 1200px. 
The spacing rhythm is based on an 8px base unit. Generous white (cream) space is used between menu categories to prevent the interface from feeling cluttered.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows**. 
- **Surface Level 0:** The Cream (#FDF5E6) background.
- **Surface Level 1 (Cards):** Peruvian White (#FFFFFF) cards with very soft, diffused shadows (Blur: 15px, Opacity: 5%, Color: Deep Wood).
- **Surface Level 2 (Floating/Nav):** Use of a subtle "Glassmorphism" effect on navigation bars (Semi-transparent Cream with a 10px backdrop blur) to allow food photography to peek through as the user scrolls.
- Overlays and Modals should use a darkened "Charcoal" backdrop with 40% opacity to maintain focus on the menu items.

## Shapes
To reinforce the friendly and welcoming vibe, a **Rounded (0.5rem)** logic is applied globally. 
- **Buttons and Chips:** Use a more aggressive rounding (1rem or "Pill-shaped") to make them feel tactile and "clickable."
- **Food Images:** Always feature rounded corners or, in special featured sections, use an organic, slightly irregular "blob" shape or a circular frame to break the rigidity of the grid.
- **Inputs:** Maintain a soft 0.5rem radius to balance professional structure with an approachable feel.

## Components
- **Buttons:** Primary buttons use a gradient from Deep Ember Red to Warm Orange. They should have a slight "lift" effect (y-offset shadow) on hover.
- **Cards (Menu Items):** Feature a top-aligned image, followed by the item title in Playfair Display and the price in a bold Montserrat. The card background is pure white to contrast against the off-white page background.
- **Chips:** Used for dietary labels (e.g., "Spicy," "Gluten-Free"). These use the Earthy Terracotta (#CD5C5C) with white text.
- **Input Fields:** Outlined style using a light version of the Deep Wood color. On focus, the border transitions to Warm Orange.
- **Lists:** Reservation lists or order history use "Deep Wood" dividers with 10% opacity to maintain a clean, organized hierarchy.
- **Specialty Component - "The Grill Slider":** A custom UI element for selecting portions of Pollo a la Brasa (1/4, 1/2, Whole) using large, illustrative icons instead of standard radio buttons.