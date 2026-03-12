# Design System: DreamSequence (Trieste Archive)
**Project ID:** 3186960889352125021

## 1. Visual Theme & Atmosphere
The design embraces a **warm, analog 1970s archive aesthetic**, capturing the essence of vintage Italian experimental music studios. The mood is **nostalgic, tactile, and immersive**, utilizing "cabinet-style" layouts, worn paper textures (simulated via grain), and glowing indicators that mimic vacuum tube equipment found in the portside studios of Trieste.

## 2. Color Palette & Roles
*   **Mustard Gold (#d69e2e):** The primary brand and action color. Used for headers, key indicators, and "active" states.
*   **Burnt Orange (#b35900):** Secondary accent for technical labels, mono-spaced data, and sub-headings.
*   **Dark Tobacco (#131315):** The primary deep background color.
*   **Cream Tobacco (#f3e5ab / #d4c5a6):** Primary text colors, providing high legibility with an aged paper feel against the dark canvas.

## 3. Typography Rules
*   **Font Family:** `Space Grotesk` (Google Fonts).
*   **Headlines:** Heavy weight (`font-black`), uppercase, with tight tracking for a bold, statement-like presence.
*   **Monospace Elements:** Used for data (years, formats, stats) to evoke typewriter or early terminal labels.

## 4. Component Stylings
*   **Photo Frames:** Images are encased in thin-bordered frames (`photo-frame`) with subtle rotations and sepia/grayscale filters to look like physical archival photos.
*   **Buttons:** Using `btn-vintage` (gradients) or `bandcamp-btn` (branded teal) with smooth scale transitions on hover.
*   **Archive Terminal:** Stats and technical data are presented in a "Console" interface with oscillating pings and shimmer effects.

## 5. Layout Principles
*   **Negative Space:** Large vertical margins (`mb-32`, `mt-48`) create a sense of importance for each archive "segment."
*   **Responsive Grid:** All discography and gallery items use a flexible grid that standardizes sizes across mobile and desktop.
*   **Scroll Reveal:** Elements use an `IntersectionObserver` to fade into view from the bottom, creating a "discovery" experience as the user explores the archive.

## 6. Pro Max Improvements
*   **CRT Scanlines:** A subtle fixed overlay adds the texture of an old monitor.
*   **Analog Noise:** A dynamic SVG grain overlay provides "film grain" texture across the entire experience.
*   **Terminal Dashboards:** Interactive statistics modules for tour data and signal resonance.
