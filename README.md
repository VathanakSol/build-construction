# BuildPro Construction - Static Websites

Modern static company website for a construction business, organized using a modular and standard folder structure.

## Project Structures

```
build-pro-construction/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   ├── base.css
│   │   ├── layout.css
│   │   ├── components.css
│   │   ├── sections.css
│   │   ├── responsive.css
│   │   └── main.css
│   └── js/
│       └── projects-filter.js
└── pages/
    ├── about.html
    ├── services.html
    ├── projects.html
    └── contact.html
```

## Pages

- `index.html` - Home page
- `pages/about.html` - Company history, mission, vision, team
- `pages/services.html` - Service details
- `pages/projects.html` - Projects grid with category filter
- `pages/contact.html` - Contact form, map, office hours

## CSS Modules

- `assets/css/base.css` - Variables, reset, typography, form elements
- `assets/css/layout.css` - Header, nav, footer, grid and container layout
- `assets/css/components.css` - Buttons, cards, checklist, reusable blocks
- `assets/css/sections.css` - Hero, gallery, page hero, filters, section-specific UI
- `assets/css/responsive.css` - Breakpoints and responsive behavior
- `assets/css/main.css` - Single stylesheet entrypoint using `@import`

## JavaScript

- `assets/js/projects-filter.js` - Filter logic for `pages/projects.html` (`All`, `Residential`, `Commercial`)

## Run Locally

This is a static site. You can run it in either way:

1. Open `index.html` directly in a browser, or
2. Use VS Code Live Server extension for local hosting.

## Customization

### 1) Update brand details

Search and replace in all pages:

- Company name
- Phone number
- Email address
- Office address

### 2) Update form endpoint

In `index.html` and `pages/contact.html`, replace:

`https://formspree.io/f/your-form-id`

with your real Formspree endpoint.

### 3) Update theme colors

Edit variables in `assets/css/base.css`:

- `--primary`
- `--secondary`
- `--bg`
- `--text`

### 4) Replace images

Current demo images use external Unsplash URLs. Replace with your own image URLs or local assets.

## Notes

- The site uses semantic HTML and responsive CSS.
- The structure is modular and ready for further scaling.
