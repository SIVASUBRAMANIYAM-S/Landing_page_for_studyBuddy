# Study Buddy

A responsive, dependency-free starter for the Study Buddy B2B landing page.
Project documentation is kept in this `docs/` directory.

## Project structure

```text
.
├── .gitignore
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── fonts/
│   │   └── .gitkeep
│   ├── images/
│   │   └── .gitkeep
│   └── js/
│       └── main.js
└── docs/
    └── README.md
```

## Run locally

Open `index.html` in a browser, or use the Live Server extension in VS Code.
There is no build step or package installation required.

## Customize

- Update page content and metadata in `index.html`.
- Add visual assets to `assets/images/` and reference them with relative paths.
- Add custom fonts to `assets/fonts/` and declare them in `assets/css/style.css`.
- Keep page styling and interaction code in `assets/css/style.css` and
  `assets/js/main.js`, respectively.
- Keep project and implementation documentation in `docs/`.

## Phase 1: floating navigation

The sticky navigation uses the configured Tailwind brand colors, a translucent
blurred surface, a blue gradient demo button, and a responsive hamburger menu.
The mobile menu supports keyboard dismissal with Escape and closes after a
navigation link is selected.

The contact link currently uses a reserved `.example` email address. Replace it
with your team's approved contact address before publishing the page.
