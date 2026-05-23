---
name: Pinta Constrói Design System
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#010101'
  on-primary: '#ffffff'
  primary-container: '#1c1c1c'
  on-primary-container: '#858484'
  inverse-primary: '#c8c6c5'
  secondary: '#a53c00'
  on-secondary: '#ffffff'
  secondary-container: '#fe702c'
  on-secondary-container: '#5d1e00'
  tertiary: '#010101'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1c19'
  on-tertiary-container: '#878480'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb598'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7e2c00'
  tertiary-fixed: '#e6e2dd'
  tertiary-fixed-dim: '#cac6c1'
  on-tertiary-fixed: '#1d1b19'
  on-tertiary-fixed-variant: '#484643'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-lg: 48px
  stack-md: 32px
  stack-sm: 16px
---

## Brand & Style

This design system embodies the intersection of architectural precision and artisanal craftsmanship. It is built for a professional Portuguese construction and painting firm, targeting clients who value structural integrity and aesthetic refinement.

The visual style is **Rugged Modernism**. It blends the raw, unyielding nature of construction materials—concrete, steel, and timber—with the sophisticated finish of a master painter. The UI should feel "built" rather than merely "rendered," utilizing heavy weight, structural alignment, and a tactile sense of permanence. The emotional response is one of absolute reliability, heritage, and deliberate execution.

**Key Aesthetic Pillars:**
- **Structural Integrity:** Elements are grounded and purposeful, avoiding unnecessary fluff.
- **Craftsmanship:** High-contrast typography and generous whitespace reflect an eye for detail.
- **Tactility:** Subtle grain and monochromatic layering suggest the physical materials of the trade.

## Colors

The palette is rooted in the materials of the construction site and the vibrancy of fresh paint.

- **Deep Charcoal (#1C1C1C):** The primary structural color. Used for high-impact typography, primary buttons, and architectural framing. It represents steel and stone.
- **Burnt Orange (#E8601C):** The "Action" color. Inspired by safety equipment and clay tiles. It is used sparingly for calls to action, highlights, and critical indicators to ensure they pop against the neutral base.
- **Warm White (#F5F0EB):** The primary surface color. A "bone" or "plaster" white that is easier on the eyes than pure white and provides a premium, gallery-like backdrop for project photography.
- **Granite (#4A4A4A):** The secondary neutral for borders, secondary text, and iconography.

## Typography

The typography strategy leverages a high-contrast pairing to distinguish between "The Brand" and "The Detail."

- **Headlines (Playfair Display):** Should be used for all major section titles and branding moments. The serif nature conveys a sense of history and established expertise. Use bold weights for "Display" roles to create a striking visual impact.
- **Body & Interface (Inter):** A utilitarian, highly legible sans-serif for technical details, descriptions, and functional UI elements. It provides a necessary modern balance to the traditional serif.
- **Labels:** Use Inter in All-Caps with slight letter spacing to denote categories, status badges, and small technical specifications. This mimics architectural blueprint labeling.

## Layout & Spacing

The layout philosophy is a **Structured Fixed Grid**. Like a well-built wall, every element must align to a rigorous 8px spatial rhythm.

- **Desktop:** 12-column grid with a 1280px max-width container. Large 64px margins create a "framed" look, emphasizing the professional, gallery-style presentation.
- **Tablet:** 8-column grid with 32px margins. 
- **Mobile:** 4-column grid with 20px margins.
- **Spacing Logic:** Use larger "Stack" values between major sections to allow the design to breathe. Vertical rhythm is critical; maintain consistent padding inside components to reinforce the "built" feel. Elements should be grouped tightly if they are part of the same structural unit.

## Elevation & Depth

To maintain the rugged, physical feel, this design system avoids soft, floating shadows. Instead, it uses **Tonal Layering and Sharp Offsets**.

- **Surfaces:** Use the Warm White (#F5F0EB) as the base. Secondary containers or "inset" areas use a slightly darker tint or a very subtle 2% noise overlay to simulate concrete or paper texture.
- **Borders:** Use solid, 1px or 2px Deep Charcoal borders to define boundaries. This replaces shadows as the primary method of separation.
- **High Elevation:** For cards or modals that must appear "above" the page, use a **Hard Shadow** (6px offset, 0 blur, Deep Charcoal at 15% opacity) to create a mechanical, architectural depth rather than a digital glow.
- **Interactive States:** On hover, elements should shift physically—either via a border-weight increase or a slight 2px positional offset—rather than a blur change.

## Shapes

The shape language is **Sharp and Rigid**. 

In construction, precision is found in straight lines and 90-degree angles. All buttons, input fields, cards, and containers must have **0px corner radius**. This reinforces the "solid" and "unyielding" brand personality. 

The only exception to this rule is for purely organic elements like circular profile avatars or specific iconography where a circle is technically required. All structural UI remains strictly rectangular.

## Components

- **Buttons:** Large, blocky, and high-contrast. The primary button is Deep Charcoal with White text. On hover, it fills with Burnt Orange. Use a 2px border for "ghost" buttons.
- **Input Fields:** Thick 2px bottom borders or full boxes in Deep Charcoal. Labels should sit above the field in the `label-sm` style. Focus states use a Burnt Orange border.
- **Cards:** Defined by a 1px Deep Charcoal border. Use the Warm White background. Headers inside cards should use Playfair Display for a premium feel. 
- **Chips/Badges:** Rectangular with `label-sm` text. Use Burnt Orange for "Active" or "In Progress" status and Deep Charcoal for "Completed."
- **Lists:** Separated by thin 1px horizontal lines. High-density information is prioritized, using Inter for all technical list data.
- **Progress Indicators:** Use a thick, solid Burnt Orange bar to show construction or project completion phases. It should look like a physical measurement tool.
- **Textures:** Apply a very light SVG grain texture to the Warm White background to give the digital interface a tactile, physical quality resembling plaster or high-end stationery.