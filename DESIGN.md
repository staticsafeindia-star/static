---
name: Industrial Precision
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#424752'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#727784'
  outline-variant: '#c2c6d4'
  surface-tint: '#0d5bbc'
  primary: '#00408b'
  on-primary: '#ffffff'
  primary-container: '#0057b8'
  on-primary-container: '#bfd2ff'
  inverse-primary: '#adc7ff'
  secondary: '#00658d'
  on-secondary: '#ffffff'
  secondary-container: '#2dbcfe'
  on-secondary-container: '#004866'
  tertiary: '#324360'
  on-tertiary: '#ffffff'
  tertiary-container: '#495b79'
  on-tertiary-container: '#c1d3f6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc7ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#c6e7ff'
  secondary-fixed-dim: '#82cfff'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6b'
  tertiary-fixed: '#d6e3ff'
  tertiary-fixed-dim: '#b5c7ea'
  on-tertiary-fixed: '#071c36'
  on-tertiary-fixed-variant: '#364764'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
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
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The design system embodies a fusion of consumer-grade refinement and heavy industrial reliability. It targets enterprise decision-makers and technical engineers who value precision and safety. The aesthetic combines the sleek minimalism of modern tech hardware with the structured authority of high-end engineering firms.

The visual narrative is built on "Industrial Clarity"—a philosophy of extreme whitespace, disciplined alignment, and high-tech materiality. It utilizes a refined **Minimalist** foundation augmented with **Glassmorphism** to signify transparency and advanced technology. The emotional response is one of absolute trust, sophisticated expertise, and forward-thinking innovation.

## Colors
The palette is rooted in professional trust and technological advancement. 
- **Industrial Blue (#0057B8):** The primary anchor, used for core branding and high-priority actions.
- **Tech Blue (#00AEEF):** An energetic highlight used for secondary interactions, data visualizations, and accents.
- **Navy (#0B1F3A):** Provides depth and contrast, primarily for high-level headings and structural footers.
- **Surface (#F5F7FA):** A clinical light gray used to define sections and provide a soft alternative to pure white.
- **Support Colors:** Success (Emerald), Warning (Amber), and Danger (Crimson) should be desaturated to maintain the professional industrial aesthetic.

## Typography
The system uses **Inter** for all primary communication to ensure maximum legibility and a contemporary, "Apple-esque" feel. Hierarchy is established through significant size deltas and weight shifts. 

**JetBrains Mono** is introduced as a secondary label font for technical specifications, product codes, and data points, reinforcing the engineering and high-tech nature of the brand. Use generous line heights for body text to maintain the feeling of openness and premium quality.

## Layout & Spacing
The layout follows a strict 12-column grid system with a "Content-First" philosophy. Horizontal rhythm is governed by an 8px base unit. 

- **Desktop:** Large 64px outer margins to create a "framed" look. Section vertical spacing is intentionally aggressive (120px+) to allow the eye to rest and emphasize the premium nature of the brand.
- **Mobile:** Transition to a 4-column grid with 20px margins. Section gaps reduce to 64px.
- **Alignment:** All content should align to the left for readability, with the exception of hero headers or specialized "Statement" cards which may be centered.

## Elevation & Depth
Depth is used sparingly and purposefully to denote interaction.
- **Glassmorphism:** Navigation bars and floating controls use a 20px backdrop blur with a 10% white tint and a subtle 1px border (#FFFFFF 20%).
- **Shadows:** Avoid heavy black shadows. Use "Ambient Glows" — soft, diffused shadows with a subtle primary color tint (e.g., 10% #0057B8 at 40px blur) to suggest the "static-free" and high-tech nature of the products.
- **Hover States:** Elements should "lift" using a combination of a slight upward translation (-4px) and an increased shadow spread.

## Shapes
The shape language is "Soft Industrial." Corners are noticeably rounded to feel approachable and modern, but not so circular as to lose professional rigor. 
- **Standard Elements:** 8px (0.5rem) for buttons and input fields.
- **Large Cards:** 16px (1rem) for product and feature cards.
- **Inner Elements:** Nested elements (like images inside cards) should have a radius 4px smaller than their container to maintain visual harmony.

## Components
- **Buttons:** Primary buttons are solid #0057B8 with white text, using a subtle inner glow on top. Secondary buttons use a 1px Industrial Blue border with a transparent background.
- **Cards:** Premium Product Cards use a white background, a 1px border (#E2E8F0), and a soft shadow. On hover, the border shifts to #00AEEF and the shadow expands.
- **Glass Headers:** Navigation should be pinned to the top, utilizing a frosted glass effect that allows the high-tech product photography to bleed through subtly as the user scrolls.
- **Technical Badges:** Use JetBrains Mono for badges indicating ESD compliance or technical certifications, using the #F5F7FA surface color with a Navy text label.
- **Input Fields:** Minimalist design with a bottom-only border that transforms into a full 1px #0057B8 stroke on focus.
- **Data Tables:** High-density, clean rows with #F5F7FA zebra striping and Navy headers to emphasize technical accuracy.