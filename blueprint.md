# Portfolio Blueprint

## Overview

This document outlines the plan for creating a personal portfolio website using Astro.js and Tailwind CSS. The portfolio is designed with a mobile-first approach, ensuring it is responsive and accessible. It will showcase projects, skills, and professional background with a modern, bold, and interactive design.

## Implemented Features

*   **Project Setup:**
    *   Astro.js project initialized.
    *   Tailwind CSS integrated for styling.
*   **Layout & Global Styles:**
    *   A main `Layout.astro` file has been created to provide a consistent page structure.
    *   Global styles, including a dark theme, custom fonts (Poppins), and a custom color palette, are defined in `src/styles/global.css`.
    *   The Tailwind config (`tailwind.config.mjs`) is synchronized with the custom color palette.
*   **Header Component (`src/components/Header.astro`):**
    *   A sticky, responsive header component has been created.
    *   **Desktop:** Features a centered logo and navigation links ("Sobre Mí", "Proyectos", "Contacto") with increased letter spacing (`tracking-widest`).
    *   **Mobile:** Features a logo, a hamburger menu icon, and a slide-out menu.
    *   **Interactivity:** Links have hover effects (scaling and color change).
*   **Hero Component (`src/components/Hero.astro`):**
    *   The hero section was created as a separate, reusable component.
    *   Features a responsive, two-column layout.
    *   **Text Content:** Includes an animated gradient for the main headline.
    *   **Visual Content:**
        *   **Desktop:** Displays an interactive 3D scene using `<spline-viewer>`.
        *   **Mobile:** Displays a static fallback image.

## Current Plan

Ready for the next feature implementation.
