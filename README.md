# Soccer Cup — GitHub Pages edition

This folder is a complete browser-only website. It has no server, database, package manager, or build step.

## Publish it with GitHub Pages

1. Create a new GitHub repository, such as `soccer-cup`.
2. Upload the **contents** of this folder — `index.html`, `styles.css`, `app.js`, `.nojekyll`, and this README — to the root of that repository.
3. In the repository, open **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. After GitHub finishes publishing, use the URL shown on that same Pages screen.

For a repository named `soccer-cup`, the address is normally:

`https://YOUR-GITHUB-USERNAME.github.io/soccer-cup/`

## What each file does

- `index.html` — the page GitHub Pages opens.
- `styles.css` — all visual styling, including the field and soccer ball.
- `app.js` — the complete game and team-draft logic.
- `.nojekyll` — tells GitHub Pages to serve these files exactly as supplied.

All team imports, exports, and downloaded JSON files happen locally in the visitor's browser.
