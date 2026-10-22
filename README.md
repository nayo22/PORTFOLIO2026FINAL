# Nayo — Interactive Media Designer

A complete, buildless portfolio: HTML, CSS and JavaScript. No package installation or build step is needed. The production output and full application source are in `dist/`.

## Run locally

From this folder: `python3 -m http.server 8080 --directory dist`
Open http://localhost:8080.

## Deploy to Vercel

Import this repository into Vercel. Choose Framework Preset: Other. Set Root Directory to `dist`, leave the Build Command empty, and use `.` as the Output Directory. Deploy. No environment variables are required.

Alternatively, run `npx vercel --prod` from `dist/` and follow Vercel's account/project prompts.

## Files

- dist/index.html: content, navigation, metadata and sections
- dist/style.css: responsive layout, two themes, motion and accessibility
- dist/app.js: projects, gallery, theme persistence, skill tabs, tools and drawing board
- dist/assets/: authentic supplied photographs/project covers optimized to WebP

## Asset mapping

03_03_57: Solar Lens; 03_04_06: ¿Dónde comemos hoy?; 03_04_14: NutriDog; 03_04_21: RideVibe; 03_04_28: Saltín Noel; 03_04_35: Nayo's black-and-white portrait.
Only six files were supplied; no color portrait was available. No artificial color reconstruction was used.

## Content and verification limitations

The external references and case studies were not readable through the research tools. Project descriptions are intentionally limited to supplied information and visible covers. Responsibilities and results are not invented. Outbound URLs match the user's brief; external availability cannot be guaranteed. All supplied project titles retain their original spelling. Body copy is English.

Google Fonts provides the optional display and body fonts; system fallbacks remain available offline. Theme preference is stored in browser local storage. No analytics, server storage, cookies, forms, or external messages are used.

Motion honors prefers-reduced-motion and has a pause button. Gallery supports arrow controls, keyboard arrows, mouse drag, and native touch scrolling. Skills implement accessible tabs. Contact uses mailto/tel links. All social and project links open in a new tab.

## Organic design update

Curved section transitions, overlapping decorative elements, shorter copy, animated project gallery and a second tool carousel. The playground supports freehand drawing, text, ink colors, brush sizes, erasing, undo, recoverable clearing, and PNG download. Artwork stays in memory for the current visit and is not transmitted. Pointer input supports mouse, pen and touch; text can be added using a keyboard.
