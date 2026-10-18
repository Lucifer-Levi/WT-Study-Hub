# WT Study Hub — 25CS201 Web Technology

A responsive multi-page study website based on the uploaded `25CS201 Web Tech notes.pdf`.

## Files
- `index.html` — dashboard and learning-unit overview
- `html5.html` — Learning Unit I: Constructing Web Pages with HTML5
- `core-css.html` — Learning Unit II: Applying Core CSS Styling
- `advanced-css.html` — Learning Unit III: Organizing Layouts with Advanced CSS
- `javascript.html` — Learning Unit IV: JavaScript Libraries / client-side interaction topics
- `dynamic.html` — Learning Unit V: Assembling Dynamic Frontend Applications
- `styles.css` — shared responsive styling and dark theme
- `app.js` — topic content, navigation UI, quiz, flashcards, search and local progress

## Run it
1. Download and extract the ZIP.
2. Open `index.html` in a browser. No build tools or server are required for the study pages.
3. To publish it on GitHub Pages, upload all HTML files, `styles.css`, `app.js` and this README to the repository root. In GitHub, open **Settings → Pages**, select deployment from the `main` branch and `/ (root)`, and save. Open the generated Pages URL (not the README URL).

## Interactive features
- Separate pages for all five learning units
- Search topics within a unit
- Expand/collapse examples, reveal quick-check answers
- Unit quizzes with score feedback
- Flashcards
- Mark topics complete and track progress
- Light/dark theme toggle
- Responsive layout and keyboard focus states

## Content scope
The PDF provides a complete unit/topic outline and detailed notes for several advanced CSS and DOM sections, but some topics are listed mainly as headings. The website keeps the syllabus structure and uses concise foundational explanations and practice examples for topics whose detailed notes are not present in the extracted source. Examples are for learning and may need adaptation for a real production app. Progress and quiz scores are stored in browser `localStorage` on the current device/browser.
