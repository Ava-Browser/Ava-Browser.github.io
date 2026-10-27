# ava-browser.github.io

The single-page site for [Ava](https://github.com/Ava-Browser/ava), a native macOS browser built on the Ladybird engine.

Serve at <https://ava-browser.github.io>. One HTML file, no build step, no dependencies, no cookies, no analytics.

## Editing

`index.html` holds the markup and styles; `ava-lift.svg` is the app icon. The page must never scroll — content is laid out to fit the viewport at every size, so check any copy change at 1440×900 and 390×844 before pushing.

## Deploy

GitHub Pages serves `main` from the repository root. Push to `main` and the site updates.
