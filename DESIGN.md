---
name: Gentle Path
colors:
  surface: '#f8f9f9'
  surface-dim: '#d9dada'
  surface-bright: '#f8f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f4'
  surface-container: '#edeeee'
  surface-container-high: '#e7e8e8'
  surface-container-highest: '#e1e3e3'
  on-surface: '#191c1c'
  on-surface-variant: '#40484f'
  inverse-surface: '#2e3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#707880'
  outline-variant: '#bfc7d0'
  surface-tint: '#006491'
  primary: '#006491'
  on-primary: '#ffffff'
  primary-container: '#5dade2'
  on-primary-container: '#003f5d'
  inverse-primary: '#8aceff'
  secondary: '#006d43'
  on-secondary: '#ffffff'
  secondary-container: '#97f6be'
  on-secondary-container: '#007348'
  tertiary: '#6f5d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#bca43d'
  on-tertiary-container: '#463a00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c9e6ff'
  primary-fixed-dim: '#8aceff'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#004b6f'
  secondary-fixed: '#97f6be'
  secondary-fixed-dim: '#7bd9a4'
  on-secondary-fixed: '#002111'
  on-secondary-fixed-variant: '#005231'
  tertiary-fixed: '#fde274'
  tertiary-fixed-dim: '#dfc65b'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#f8f9f9'
  on-background: '#191c1c'
  surface-variant: '#e1e3e3'
typography:
  headline-lg:
    fontFamily: Quicksand
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Quicksand
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Quicksand
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  label-caps:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 14px
    fontWeight: '700'
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
  unit: 8px
  container-padding: 24px
  gutter: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 40px
---

## Brand & Style
The design system is centered on clarity, safety, and emotional regulation for children with autism. The brand personality is supportive and predictable, reducing cognitive load through structured simplicity. 

The design style is **Soft Minimalist** with **Tactile** influences. It prioritizes high-contrast legibility without sensory overload. Every element is designed to feel physically approachable—avoiding sharp corners and aggressive transitions—to create a digital environment that feels like a safe, calming physical space.

## Colors
The palette uses desaturated, soft tones to prevent visual overstimulation while maintaining high contrast ratios for accessibility. 
- **Soft Blue (Primary):** Used for core navigation and stable interface elements.
- **Gentle Green (Secondary):** Used for "Go," success states, and positive reinforcement.
- **Warm Yellow (Tertiary):** Reserved for highlights and attention-grabbing cues that are not urgent.
- **Friendly Coral (Accent):** Used sparingly for interactive elements that require a distinct visual category.
- **Slate Navy (Text):** A softened dark grey for text to provide high contrast against the neutral background without the harshness of pure black.

## Typography
The system uses **Quicksand** for its rounded terminals and open counters, which feel friendly and are easier for children to process. For labels and instructional text where maximum character differentiation is required, **Atkinson Hyperlegible Next** is utilized to ensure "I", "l", and "1" are distinct.

- **Scale:** Type sizes are intentionally large to aid readability. 
- **Spacing:** Increased line height and letter spacing are applied globally to prevent "crowding" of text, which can be a barrier for neurodivergent users.

## Layout & Spacing
The layout follows a **Fluid Grid** with generous "breathing room." A standard 4-column grid is used for mobile to ensure large touch targets.

- **Safe Margins:** A minimum of 24px outer margin is maintained to prevent content from feeling "trapped" against the screen edges.
- **Vertical Rhythm:** Elements are grouped in clear vertical stacks with 24px gaps to define distinct logical sections. 
- **Padding:** Internal padding for cards and containers is never less than 20px, ensuring text never feels cramped.

## Elevation & Depth
This design system avoids complex shadows and skeletal blurs. Depth is conveyed through **Tonal Layering** and **Soft Insets**.

- **Cards:** Use a very subtle, large-radius shadow (0px 4px 20px) with 5% opacity of the text color.
- **Borders:** All interactive containers feature a 2px solid border in a slightly darker shade of the surface color to provide a clear physical boundary.
- **Active States:** Instead of deep shadows, "pressed" states are indicated by a 2px downward shift (mimicking a physical button being pushed) and a subtle darkening of the border.

## Shapes
Shapes are defined by organic, highly rounded corners to evoke safety. 
- **Small Elements:** (Checkboxes, mini-chips) use `rounded-md` (8px).
- **Standard Components:** (Buttons, Input fields) use `rounded-lg` (16px).
- **Large Containers:** (Cards, Modals) use `rounded-xl` (24px).
- **Icons:** Always enclosed in circular or highly rounded containers to maintain a consistent silhouette.

## Components
- **Buttons:** Large format (minimum height 56px). They feature a 3px bottom "border-shadow" to give a tactile 3D feel. Text inside buttons is always Bold and centered.
- **Cards:** Content is broken into "bite-sized" chunks. Every card must have a 2px stroke in `#EAECEE` to define its limits against the background.
- **Input Fields:** Extra-large tap areas with thick 2px borders that turn Blue when focused. Labels always sit outside the field to remain visible.
- **Chips/Selectors:** Used for category filtering. When selected, the background color fills in completely, and the border thickens to 3px for unmistakable visual feedback.
- **Progress Indicators:** Thick, rounded bars with a "soft glow" effect. Avoid percentages; use visual steps or icons to show progress (e.g., a moving star icon).
- **Iconography:** Use thick-stroke (2pt) monoline icons with rounded ends. Never use abstract icons; stick to representational pictograms that represent the literal object or action.