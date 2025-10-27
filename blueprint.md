# Arantxa's Portfolio Blueprint

## Overview

This document outlines the structure, design, and features of Arantxa's personal portfolio website. The site is built with Astro.js and showcases her skills and projects as a web developer.

## Implemented Features

*   **Project Structure:** The project is organized with a clear separation of concerns, using layouts, components, and pages.
*   **Styling:** Tailwind CSS is used for utility-first styling, with a custom color palette defined in `src/styles/global.css`.
*   **Animated Splash Screen:** A full-screen entry point with a title and a button to enter the main portfolio.
*   **Header:** A simple, elegant header with the name "Arantxa" and a "Contacto" button.
*   **Hero Section:** A full-screen hero section with:
    *   A brief introduction to Arantxa and her skills.
    *   An interactive 3D model from Spline.
    *   A responsive design that adapts to different screen sizes.
*   **Projects Section:** A placeholder for future projects.
*   **Parallax Effect:** The hero section remains sticky while scrolling, creating a parallax effect with the projects section.

## Current Task: Enhance the Home/Splash Screen

### Plan

1.  **Integrate an interactive particle background:**
    *   Use a lightweight JavaScript library for particle animations.
    *   The particles will subtly move in the background and react to mouse movement.
2.  **Add a descriptive subtitle:**
    *   Include a subtitle below the main title to provide more context (e.g., "Desarrolladora Web & Creativa Digital").
    *   Animate the subtitle to appear after the main title.
3.  **Create a "glow" effect for the button:**
    *   Use CSS to add a glow effect to the "Ver Portfolio" button on hover, making it more engaging.
4.  **Refine animations and timing:** Ensure all animations are smooth and the timing feels natural.
