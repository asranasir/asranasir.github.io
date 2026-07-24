---
name: Academic Precision
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001e2c'
  on-tertiary-container: '#008ebf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Source Serif 4
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1120px
  gutter: 24px
  margin-mobile: 20px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is engineered for high-level academic and technical presentation. It targets recruiters, researchers, and peers in the Computer Science field. The visual narrative balances the rigorous structure of academic research with the modern, streamlined efficiency of high-end software development. 

The style adopts a **Modern Corporate** aesthetic with **Minimalist** leanings. It prioritizes clarity, systematic organization, and intellectual authority. Every element serves a functional purpose, utilizing generous whitespace to ensure that complex technical projects and research papers remain digestible and prominent.

## Colors
The palette is built on a foundation of "Academic Navy" and "Slate," conveying stability and depth.

- **Primary (#0F172A):** A deep navy used for primary headings, navigation bars, and high-impact UI elements. It establishes an authoritative tone.
- **Secondary (#475569):** A muted slate used for subheaders, icons, and descriptive text. It provides a softer contrast against the primary navy.
- **Tertiary (#38BDF8):** A vibrant sky blue reserved strictly for interactive highlights, code syntax highlighting, and progress indicators.
- **Neutral (#F8FAFC):** A clean, cool-tinted white for page backgrounds, providing a crisp canvas for technical content.
- **Surface:** Use a subtle gray (#F1F5F9) for code blocks and secondary layout containers to differentiate from the main background.

## Typography
The typography strategy employs a "Technical-Academic" pairing. 

**Headings (Geist):** A clean, high-precision sans-serif that reflects a modern developer aesthetic. It is used for all structural navigation, project titles, and section headers.

**Body (Source Serif 4):** A professional serif font optimized for long-form reading. It is used for research abstracts, project descriptions, and personal statements, providing a sophisticated academic feel that contrasts the technical sans-serif headings.

**Labels & Code (Geist / JetBrains Mono):** Smaller labels use Geist in medium weights for metadata. Code snippets should utilize JetBrains Mono to reinforce technical expertise.

## Layout & Spacing
The design system utilizes a **Fixed Grid** approach for desktop to maintain a structured, editorial feel. 

- **Grid:** A 12-column grid with a 1120px max-width container. 
- **Sectioning:** Large vertical gaps (120px) separate major sections (e.g., Education, Research, Projects) to prevent visual clutter and give the content room to "breathe."
- **Stacking:** Use an 8px base unit for internal component spacing.
- **Mobile Adaptivity:** On mobile devices, the grid collapses to a single column with 20px side margins. Large display headings should scale down to ensure no overflow and maintain readability.

## Elevation & Depth
This design system avoids heavy shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Use flat colors to define hierarchy. The primary surface is pure white, while secondary surfaces (like project cards or code blocks) use a light slate-gray tint (#F1F5F9).
- **Borders:** Instead of shadows, use 1px solid borders in a very light slate (#E2E8F0) to define card boundaries and input fields.
- **Interactions:** Subtle elevation can be achieved on hover via a very soft, diffused shadow (0px 4px 20px rgba(15, 23, 42, 0.05)) to suggest interactivity without breaking the clean, flat aesthetic.

## Shapes
The shape language is conservative and professional. 

- **Radius:** A "Soft" approach is used throughout the system. Standard UI elements like buttons and input fields use a 0.25rem radius.
- **Cards:** Larger containers like project cards or profile images use a 0.5rem (rounded-lg) radius to provide a modern but disciplined appearance.
- **Consistency:** Avoid pill-shapes or fully circular elements except for status indicators or small avatars, as they can appear too casual for an academic context.

## Components
- **Buttons:** Primary buttons use the Primary Navy background with White text. Secondary buttons use a Slate-Gray outline. High-precision 0.25rem corner radius.
- **Project Cards:** Features a subtle 1px border (#E2E8F0). On hover, the border color shifts to Tertiary Blue and a slight lift is applied.
- **Research Tags/Chips:** Use a light-gray background (#F1F5F9) with Slate-Gray text in the `label-md` style. No icons inside tags to maintain a clean look.
- **Input Fields:** Minimalist design with a 1px border. On focus, the border changes to Tertiary Blue.
- **Code Blocks:** Dark-themed using a specific "Midnight" background (#1E293B) to provide a high-contrast break from the light-themed academic text. 
- **Timeline (Education/Work):** A vertical 2px line in Slate-Gray with small circular nodes to anchor chronological entries.
- **Data Visualizations:** Charts and graphs should utilize the Primary Navy and Tertiary Blue to maintain brand consistency.