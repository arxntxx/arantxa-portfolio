# Portfolio Blueprint

## Overview

This document outlines the plan for creating a personal portfolio website using Astro.js and Tailwind CSS. The portfolio is designed with a mobile-first approach, ensuring it is responsive and accessible. It will showcase projects, skills, and professional background with a modern, bold, and interactive design.

## Implemented Features

*   **Project Setup:** Astro.js project initialized with Tailwind CSS.
*   **Layout & Global Styles:** Consistent page structure with a dark theme, custom fonts, and a defined color palette.
*   **Header Component:** A sticky, responsive header with desktop and mobile navigation.
*   **Hero Component:** A responsive hero section with an animated gradient headline and different visuals for desktop (3D) and mobile (image).
*   **Particle Background v1 (`src/components/Particles.astro`):**
    *   Started with a floating constellation effect.
    *   Evolved into a "snow" effect.
    *   **v2:** Transformed into an interactive "Matrix-style" code rain effect with mouse interaction.

## Current Plan

**Objective:** Refine the background into a highly stylized and unique "Pink Code Heart" effect.

**Steps:**
1.  **Change Color Palette:** Switch the entire particle animation from green to a palette of pinks. The particles near the mouse will glow with a brighter, more intense pink.
2.  **Implement Heart Shape Mask:** The falling code characters will now only be rendered within the boundaries of a large, centered heart shape. This will create the illusion that the code rain is forming a heart.
