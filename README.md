# Responsive Vehicle Web Catalog

Interactive, responsive vehicle catalog web app inspired by the Porsche car configurator. Built with HTML, CSS and vanilla JavaScript, and deployed on Netlify.

**Live demo:** https://assignment4-diegofiz-porsche.netlify.app/

## Objective

Design and build a responsive, multi-page vehicle catalog where users browse car models as cards and open a dynamic detail page that loads each model's information and technical specifications on the fly, replicating the look and feel of a premium car configurator.

## Technologies and methods

- **HTML5** for the semantic structure of the catalog and detail pages.
- **CSS3**: design tokens with CSS custom properties (`:root` variables), responsive layout with Flexbox (`flex-wrap`), Google Fonts, and keyframe animations (hover pulse, slide-down, entrance transitions).
- **JavaScript (vanilla)**: reads each model's data from URL query parameters (`URLSearchParams`), builds the technical-specifications list dynamically, manipulates the DOM, and handles the show/hide specifications toggle through event listeners.
- **Netlify** for continuous deployment and hosting.

## Key features

- Catalog of car models presented as responsive cards that reflow according to screen width.
- Dynamic detail page: model name, image, description and specifications are passed through URL parameters, so a single `detail.html` serves every model.
- Expandable technical-specifications panel with a smooth slide-down animation.
- Consistent design system driven by CSS variables (colors and typography).
- Hover and entrance animations for a polished, configurator-like experience.

## Project structure

```
├── index.html            # Catalog page (model cards)
├── detail.html           # Dynamic model detail page
└── assets/
    ├── stylesheets/
    │   ├── general.css    # Base styles and font import
    │   ├── config.css     # Design tokens (CSS variables)
    │   ├── index.css      # Catalog layout
    │   └── detail.css     # Detail layout and animations
    └── images/            # Vehicle photos and logos
```
