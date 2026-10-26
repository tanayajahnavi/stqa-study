# TestWise — STQA Study Hub

A static, GitHub Pages-ready study website for Software Testing and Quality Assurance (24CS563), initially covering **Units 1 and 2 only**.

## Features
- Responsive dashboard and unit/topic navigation
- Detailed topic explanations, examples, comparison tables and diagrams
- Unit 2 control-flow graph SVG example
- Important practice questions with revealable model answers
- Quick revision page and interactive quiz
- Browser-local progress, bookmarks and light/dark mode
- Supplementary CMM page visibly separated from core syllabus

## Run locally
Open `index.html` in a modern browser. No build step or backend is required.

## Publish on GitHub Pages
1. Create a new **public** repository, for example `testwise-stqa`.
2. Upload the contents of this folder to the repository root (the `index.html` file must be at the root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for the deployment to finish, then use the site link shown in Settings → Pages.

GitHub's official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Important source/content note
The official course syllabus is the authority for topic coverage. This starter is a first implementation, not a claim that every page has been independently checked against every paragraph of the textbook. Confirm course-specific formal definitions and criteria against your lecturer's notes, especially the formal data-flow testing criteria. No questions are labelled as verified PYQs because question papers were not supplied.

## Files
- `index.html` — page structure
- `styles.css` — responsive design and themes
- `content.js` — topic notes, practice questions and quiz data
- `app.js` — navigation, rendering, progress and interactivity
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing
