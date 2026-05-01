---
name: Interview Intelligence
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
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#4e565b'
  on-tertiary: '#ffffff'
  tertiary-container: '#666f74'
  on-tertiary-container: '#e9f2f8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dbe4ea'
  tertiary-fixed-dim: '#bfc8ce'
  on-tertiary-fixed: '#141d21'
  on-tertiary-fixed-variant: '#3f484d'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
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
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  container-margin: 20px
  gutter: 16px
---

## Brand & Style

The design system is built on the narrative of "Empathetic Technology." It balances the precision of artificial intelligence with the warmth of human coaching. The aesthetic is **Modern Corporate with a Futuristic Edge**, utilizing heavy whitespace to reduce user anxiety during high-stakes interview preparation. 

The style draws from **Minimalism** for clarity and **Glassmorphism** for its high-tech, layered feel. Surfaces are clean and breathable, ensuring the user feels supported rather than overwhelmed. The interface should feel like a premium, quiet lounge—professional, focused, and high-end.

## Colors

The palette is anchored by a "Deep Trust Blue," a primary color that signals stability and professional competence. This is supported by a "Midnight Navy" for high-contrast text and a "Vapor Blue" (tertiary) used for subtle background accents and AI-interaction zones. 

The background is a very light "Slate White" (#F8FAFC) to provide more depth than pure white, allowing white surface cards to pop with subtle elevation. Success states should use a muted emerald, while cautionary states use a soft amber, maintaining the system's calm demeanor.

## Typography

This design system utilizes a dual-font strategy. **Space Grotesk** is used for headlines to provide a technical, futuristic flair that mirrors the AI's capabilities. Its geometric quirks add personality without sacrificing readability.

**Manrope** is used for all functional body text and labels. It was chosen for its exceptional legibility on mobile screens and its balanced, professional tone. Maintain generous paragraph spacing (1.5x font size) to ensure the educational content is digestible. Use weight variations (Semibold vs. Regular) rather than color changes to establish hierarchy.

## Layout & Spacing

The design system employs a **Fluid Grid** model optimized for mobile viewport constraints. The layout rhythm is based on a 4px baseline grid to ensure mathematical harmony between elements.

Standard lateral margins are set to 20px to allow content to breathe. Vertical rhythm should be generous; use 'xl' (40px) spacing between major sections to emphasize the minimal, spacious feel. Elements within a card or component should stick to 'sm' and 'md' increments to maintain a tight, functional relationship.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. Unlike traditional material design, shadows here are extra-diffused and slightly tinted with the Primary Blue color (e.g., 10% opacity, 20px blur, 4px vertical offset). This creates a "floating" effect rather than a "heavy" one.

Glassmorphism is applied to fixed navigation elements and AI-feedback overlays, using a `backdrop-filter: blur(12px)` and a thin 1px white border (20% opacity) to simulate frosted glass. This adds a sense of technological sophistication and depth without cluttering the UI with lines.

## Shapes

The shape language is defined by **large, friendly radii**. This softens the "high-tech" aspect, making the AI feel approachable rather than intimidating. 

- **Standard Cards/Buttons:** 16px (rounded-lg)
- **Feature Containers:** 24px (rounded-xl)
- **Input Fields:** 12px
- **Icons:** Set within circular or soft-square housings.

Avoid sharp corners entirely. Even hard-edged images should be clipped to at least the 'soft' (4px) radius to maintain system consistency.

## Components

**Buttons:** Primary buttons use a solid Deep Trust Blue with white text and a subtle glow-shadow. Secondary buttons should be ghost-style with a thin 1px border or a light blue tonal background.

**Cards:** Cards are the primary container. They should have a white background, no border, and a soft ambient shadow. Use internal padding of 24px to ensure content doesn't feel cramped.

**Input Fields:** Utilize "Floating Labels" to keep the UI clean. On focus, the border should transition to the Primary Blue with a soft outer glow.

**AI Interaction Chips:** Small, pill-shaped elements used for suggested answers or tags. These should use the Tertiary Blue (#F0F9FF) with Primary Blue text to indicate interactivity.

**Progress Indicators:** Use thick, rounded-cap lines for progress bars. For "Interview Readiness" scores, use circular gauges with a gradient stroke to reinforce the futuristic theme.

**Voice Visualization:** A unique component for this system. Use a smooth, generative waveform animation when the AI is "listening" or "thinking," utilizing the Primary and Tertiary blue shades.