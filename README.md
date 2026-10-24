# NRG Website

This repository contains a static, mobile-friendly National Register Guard website designed for GitHub Pages.

## What is included

- Home page with mission, tagline, and agency overview
- Divisions and staff overview for RRT, MD, IID, RD, and VAU
- Recruitment and application information section
- Announcements section
- Discord community section with link placeholder
- Command dashboard with a Discord-style embed creator and live preview
- Dark red and black tactical design
- Android-friendly editing instructions

## Files

- `index.html` – main page content
- `styles.css` – tactical visual design and responsive layout
- `script.js` – embed dashboard behavior
- `.github/workflows/pages.yml` – GitHub Pages deployment workflow
- `.nojekyll` – prevents Jekyll processing issues

## GitHub Pages publishing

1. Push this repository to GitHub.
2. Open the repository in GitHub.
3. Go to Settings → Pages.
4. Under Source, choose:
   - Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
5. Save.
6. Wait a few minutes, then open the Pages URL shown in GitHub.

You can also use the included workflow file, which publishes the site automatically for the repo.

## Android editing instructions

### Option 1: Edit using the GitHub mobile app

1. Install the GitHub app on Android.
2. Open the repo and tap the file you want to edit.
3. Tap the pencil icon to edit text.
4. Save the file with a commit.
5. GitHub Pages will rebuild after the update.

### Option 2: Edit using an Android code editor

1. Install a file editor such as Termux, QuickEdit, or a Git client.
2. Clone the repo from GitHub.
3. Edit `index.html`, `styles.css`, and `script.js` directly.
4. Commit changes with Git.
5. Push the repo to GitHub.
6. GitHub Pages updates automatically.

### Common edits to make later

- Replace placeholder team names and leadership text
- Update the Discord invite URL
- Add new announcements in the announcements section
- Add application links or real contact details
- Adjust colors, text, and layout in `styles.css`

## Important notes

- No Discord tokens, bot secrets, or live API keys are included.
- Leadership details remain placeholders by design.
- The Discord server is a static placeholder link and should be replaced with a real invite when available.
- This website is static, lightweight, and suitable for free GitHub Pages hosting.
