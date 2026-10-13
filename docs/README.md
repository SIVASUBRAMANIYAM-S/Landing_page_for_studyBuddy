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

## Phase 2: immersive hero

The hero presents an institute-focused message on a deep blue gradient, with
responsive partner/demo actions and a CSS-built glass analytics dashboard.
The dashboard floats gently on desktop and respects reduced-motion preferences.

## Phase 3: ecosystem features

The platform section includes responsive analytics, 24/7 AI tutor, and
automated grading cards. Each card combines a lift/scale hover treatment with
CSS-built mini dashboard visuals that remain legible on smaller screens.

## Phase 4: impact metrics and testimonial

The proof-of-impact section presents the supplied student, pass-rate, and test
metrics in responsive floating cards, followed by a glass testimonial over a
blue abstract backdrop.

The contact link currently uses a reserved `.example` email address. Replace it
with your team's approved contact address before publishing the page.
