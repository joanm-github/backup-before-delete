# Design System: DreamSequence
**Project ID:** 3186960889352125021

## 1. Visual Theme & Atmosphere
The design embraces a **retro-futuristic, 70s analog aesthetic**, capturing the essence of vintage synthesizer hardware and early science-fiction film interfaces. The atmosphere is **atmospheric, technological, and immersive**, utilizing a modular "synth panel" grid and glowing elements on a deep, dark expanse to create a sense of mystery and late-night studio vibes.

## 2. Color Palette & Roles
*   **Cosmic Canvas (#121214):** An ultra-dark, desaturated blue-grey used as the primary background.
*   **Panel Surface (#242429):** A slightly lighter blue-grey used for cards, modules, and surface elements.
*   **Luminous Teal (#29B6B6):** A vibrant, saturated teal used for primary CTAs, active states, and technical indicators.
*   **CRT Amber (#FFC107):** A glowing amber used sparingly for highlights, warnings, and decorative phosphor effects.
*   **Mustard Highlight (#d69e2e):** A warm, vintage mustard color used for branding and key header elements.

## 3. Typography Rules
*   **Font Family:** `Space Grotesk` is used throughout.
*   **Headlines:** Bold, uppercase, and set with generous letter-spacing to mimic technical documentation and hardware labels.
*   **Body Text:** Regular weight with ample line-height for readability against dark backgrounds.
*   **Technical Text:** Monospace-style arrangements for numeric data and specific "signal" information.

## 4. Component Stylings
*   **Buttons:** Subtly rounded (8px radius). Primary buttons feature the Luminous Teal background with dark text. Secondary buttons are outlined with teal or mustard borders.
*   **Cards/Containers:** Modular "synth panels" with 8px corner rounding. Instead of heavy shadows, they use whisper-thin, illuminated borders in the primary teal to indicate an "active" or "on" state.
*   **Navigation:** Styled as a sophisticated synthesizer display. The header is a persistent bar with a primary color glow on active links.
*   **Images:** Grainy, ethereal photography with subtle sepia or color overlays, often held in "photo frame" containers with thin borders.

## 5. Layout Principles
*   **Whitespace:** Generous spacing within and between modules to prevent visual fatigue and enhance the deep-space vibe.
*   **Grid:** A modular hierarchy that mimics physical control surfaces, allowing for a structured yet dynamic arrangement of content.
*   **Responsivity:** Fluid adaptation from desktop "panels" to mobile "control strips," maintaining the tactile, hardware feel.

## 6. Design System Notes for Stitch Generation
When generating new screens for DreamSequence, follow these rules:
- Always use a **dark theme** with the Cosmic Canvas background (#121214).
- Use **Luminous Teal (#29B6B6)** for all primary interactions and glowing accents.
- Frame everything as if it were part of an **analog synthesizer panel**.
- Use **Space Grotesk** with uppercase, wide-tracked styling for headings.
- Avoid traditional drop shadows; use **thin glows** (#29B6B6) for elevation and focus.
- Incorporate **CRT-style grainy overlays** or noise textures for texture.
