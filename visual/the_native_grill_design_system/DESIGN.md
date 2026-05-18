---
name: The Native Grill Design System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e4beba'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ab8985'
  outline-variant: '#5b403d'
  surface-tint: '#ffb3ac'
  primary: '#ffb3ac'
  on-primary: '#680008'
  primary-container: '#d32f2f'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ba1a20'
  secondary: '#ffb59a'
  on-secondary: '#5b1b00'
  secondary-container: '#f95e14'
  on-secondary-container: '#4f1700'
  tertiary: '#7bd1f8'
  on-tertiary: '#003546'
  tertiary-container: '#00799c'
  on-tertiary-container: '#e9f7ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930010'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59a'
  on-secondary-fixed: '#380d00'
  on-secondary-fixed-variant: '#802a00'
  tertiary-fixed: '#bee9ff'
  tertiary-fixed-dim: '#7bd1f8'
  on-tertiary-fixed: '#001f2a'
  on-tertiary-fixed-variant: '#004d65'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
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
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  container-max-width: 1200px
---

## Brand & Style

This design system is built on the concept of **"Refined Embers."** It elevates the raw, visceral energy of Nigerian street food—specifically the Suya grill—into a sophisticated, lounge-like digital experience. The aesthetic is moody, cinematic, and premium, avoiding any visual cues associated with fast-food or budget dining.

The style is a blend of **Minimalism** and **Glassmorphism**. We use expansive dark space to represent the heat and depth of the grill, while thin strokes and translucent surfaces evoke a sense of high-end hospitality and curated atmosphere. The target audience is the discerning diner looking for an authentic yet elevated cultural experience.

The UI should feel like a dimly lit, high-end restaurant: intimate, warm, and exclusive.

## Colors

The palette is anchored by the **Charcoal Base (#121212)**, which provides a deep, non-distracting canvas. The accent colors are heat-derived: 
- **Suya Red (#D32F2F):** Used for primary actions and to signal heat/spice.
- **Burnt Orange (#E65100):** Used for secondary highlights and decorative elements.
- **Cream (#F5F5F1):** Replaces pure white to reduce eye strain in dark environments and add a touch of organic, parchment-like warmth.

Layering is achieved through a "Surface" tier (#1E1E1E), which is slightly lighter than the base to create subtle visual separation for cards and containers.

## Typography

Typography follows an editorial hierarchy. **Playfair Display** provides the premium, "menu-style" authority for all headings. It should be used with generous leading to feel spacious.

**Inter** is the utilitarian counterpart, ensuring that menu descriptions, prices, and functional labels remain legible against dark backgrounds. We use a high contrast between the serif headlines and the sans-serif body copy to reinforce the "Upscale Casual" positioning. Labels are frequently set in all-caps with increased letter spacing to mimic high-fashion or luxury brand labeling.

## Layout & Spacing

The layout uses a **Fixed Grid** model on desktop to maintain an editorial, magazine-like feel. 
- **Desktop:** 12-column grid with a 1200px max-width. Margins are intentionally wide (80px) to create an "isolated" and focused content area.
- **Mobile:** Single column with 20px margins.

Spacing follows a strict 8px rhythmic scale. We favor large vertical gaps (64px+) between sections to allow food photography to "breathe." Content should never feel cramped; the luxury is in the empty space.

## Elevation & Depth

Hierarchy in this dark-mode system is established through **Tonal Layering** and **Glassmorphism**, rather than traditional shadows.

1.  **Level 0 (Base):** #121212. The ground layer.
2.  **Level 1 (Cards/Sections):** #1E1E1E with a 1px border of #F5F5F1 at 10% opacity.
3.  **Level 2 (Modals/Overlays):** A semi-transparent blur (Backdrop Filter: 12px) using a dark tint. This creates a "smoky glass" effect, keeping the user grounded in the restaurant's atmosphere.

Shadows, when used, are deep and diffused: `0 20px 40px rgba(0,0,0,0.5)`. This adds weight to floating elements like "Order Now" buttons.

## Shapes

The shape language is **Architectural and Soft**. We avoid the playfulness of fully rounded "pills" and the harshness of pure sharp corners.

A subtle **0.25rem (4px)** base radius is applied to buttons and inputs. Large containers and menu cards use **0.5rem (8px)**. This slight rounding suggests quality and craftsmanship without losing the sophisticated edge of the brand. Lines should be thin (1px) and used sparingly to divide menu sections.

## Components

### Buttons
- **Primary:** Solid #D32F2F (Suya Red) with Cream text. Sharp-ish corners. No gradients.
- **Secondary:** Outline button with 1px Cream border at 30% opacity. Text in Cream.

### Input Fields
- Underlined style or subtle dark fill (#1E1E1E). Focus state transitions the border to Suya Red. Labels are always small, uppercase, and placed above the field.

### Cards
- Use for menu items. Featured items should have a "smoky" glass overlay at the bottom for the title and price. Images should be high-contrast with dark shadows to blend into the background.

### Lists
- Menu lists use thin dividers (1px) in #F5F5F1 at 10% opacity. Prices are emphasized in Playfair Display, while descriptions are in Inter (Body-md).

### Chips
- Used for dietary tags (e.g., "Spicy," "Vegan"). Dark background (#1E1E1E) with a 1px Burnt Orange border.

### Navigation
- Top-tier navigation uses high letter spacing and a "low-profile" appearance. The active state is indicated by a simple dot or a 2px Suya Red underline.