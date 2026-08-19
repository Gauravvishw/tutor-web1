---
name: Academic Professionalism
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1e'
  on-tertiary-container: '#818486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
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
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Inter
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is built on a foundation of **Modern Corporate** aesthetics, blending the reliability of traditional academic institutions with the agility of contemporary tech platforms. The primary goal is to foster mutual trust between school administrators and educators.

The visual language focuses on clarity, high-quality whitespace, and a structured hierarchy. It avoids unnecessary decorative elements, opting instead for functional elegance. The emotional response should be one of "calm confidence"—reassuring the user that the platform is organized, professional, and purpose-driven.

## Colors

The palette is anchored by **Deep Slate Blue** (#0F172A), used for primary text and structural elements to convey authority and stability. The background relies on **Soft White** and cool grays (#F8FAFC) to maintain a crisp, airy environment that reduces cognitive load during long periods of reading resumes or job descriptions.

**Vibrant Teal** (#0D9488) serves as the primary action color. It is chosen for its balance of professional calm and energetic "go" signals, providing high contrast against the deep blues without being as aggressive as traditional reds or oranges. Semantic colors for success, warning, and error should be desaturated to match the professional tone.

## Typography

This design system utilizes **Inter** exclusively to ensure maximum readability and a systematic, clean appearance. The typeface is a "workhorse" that maintains its character across various weights, making it ideal for information-dense applications like hiring platforms.

- **Headlines:** Use tighter letter spacing and heavier weights (600-700) to create a strong visual anchor.
- **Body Text:** Standard weight (400) with generous line heights to ensure long-form job descriptions and educator bios are easy to scan.
- **Micro-copy:** Use the `label-caps` style for section headers and category tags to differentiate them from interactive content.

## Layout & Spacing

The design system employs a **Fixed Grid** philosophy for desktop layouts to ensure consistency across large monitors, centering content within a 1280px container. On mobile, it transitions to a fluid, single-column layout.

- **Rhythm:** All spacing must be a multiple of 8px. 
- **Grids:** A 12-column grid is used for desktop. Components like "Teacher Profile Cards" should span 4 columns (3 per row), while "Job Lists" should span 8 columns to accommodate a side-bar filter.
- **Margins:** Generous outer margins (40px) are required to create the "Contemporary" feel and prevent the UI from feeling cramped.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and subtle tonal shifts. Surfaces are layered to indicate importance:

1.  **Level 0 (Base):** The primary background (#F8FAFC).
2.  **Level 1 (Cards/Surface):** Pure white (#FFFFFF) with a very soft, diffused shadow (15% opacity, 20px blur, 4px Y-offset). This is the primary container for content.
3.  **Level 2 (Interaction/Hover):** When a card is hovered, the shadow should deepen slightly and the element should lift by 2px to provide tactile feedback.
4.  **Overlays:** Modals and dropdowns use a stronger shadow with a backdrop blur (8px) to isolate the user's focus.

## Shapes

The shape language is consistently **Rounded**, reflecting a modern and approachable brand personality. 

- **Standard Elements:** Buttons, input fields, and small tags use a 0.5rem (8px) radius.
- **Large Containers:** Content cards and profile headers use a `rounded-lg` 1rem (16px) radius to create a soft, friendly container for professional information.
- **Interactive Icons:** Small utility icons (like a "bookmark" or "close" button) should be contained within a circular background if a background is present.

## Components

### Buttons
Primary buttons use the Teal accent with white text. Secondary buttons use a Slate Blue outline with no fill. State changes (Hover/Active) should be represented by a 10% darkening of the background color.

### Cards
Cards are the primary vehicle for information. They must have a white background, the Level 1 shadow, and a 1px stroke in a light gray (#E2E8F0) to ensure definition on all screens. Padding inside cards should be at least 24px (`stack-lg`).

### Input Fields
Inputs should be clean with a 1px border. When focused, the border changes to Teal with a soft 2px Teal outer glow. Labels always sit above the field in the `label-sm` style.

### Chips & Badges
Used for teacher certifications or subjects (e.g., "Math", "Special Ed"). These should be pill-shaped with a light tint of the primary color (e.g., 10% opacity Slate Blue) and dark text to remain legible but secondary to the main content.

### Candidate Lists
Lists should use a "Divided" pattern—thin gray lines separating rows—rather than individual cards to maximize vertical space when a recruiter is scanning 50+ applications.