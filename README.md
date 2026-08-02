# 2026 U.S. Gravel Bike Race Calendar Planner

This is a self-contained static HTML site for browsing and planning 2026 U.S. gravel bike races.

## What's included

- `index.html` — the full calendar/planner web page
- `.nojekyll` — tells GitHub Pages not to process the site with Jekyll
- `DEPLOY_TO_GITHUB.md` — step-by-step upload and publishing instructions
- `PACKAGE_MANIFEST.txt` — quick inventory of the package

## Features

- Calendar, List, Map, and Favorites views
- Sticky filters and visible results summary
- Filters by month, state, event type, favorites, and distance/proximity
- Favorite stars saved in your browser
- Notes for favorited events saved in your browser
- Per-event `.ics` export from Favorites view, including your notes
- Trip-planning buttons for map route, hotels, and campgrounds

## Important notes

Favorites and notes are stored in your browser's local storage. That means:

- Favorites/notes saved while opening the file locally may not carry over after you publish to GitHub Pages.
- Favorites/notes are specific to each browser and device.
- Clearing browser data may remove saved favorites/notes.

## Quick publishing path

1. Upload `index.html` and `.nojekyll` to the root of your GitHub repository.
2. Go to your repo's **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Choose your branch, usually `main`, and folder `/(root)`.
5. Save and wait for GitHub Pages to publish.

See `DEPLOY_TO_GITHUB.md` for full instructions.
