# Mortgage Marketplace Hub

Internal Mortgage Marketplace workspace for resources, calculators, projects, checklists, and AI assistant links.

## Files

- `index.html` - Main hub page
- `mortgage-marketplace-background.jpg` - Background image used by the hub

Keep both files in the same folder so the background image loads correctly.

## GitHub Pages

To publish this hub:

1. Upload `index.html` and `mortgage-marketplace-background.jpg` to the repository.
2. Go to **Settings > Pages** in GitHub.
3. Set the source to the `main` branch.
4. Save and wait for GitHub Pages to deploy.

If uploaded to the root of the repo, the hub will load at:

`https://jeromemmplace.github.io/mortgagemarketplace/`

If uploaded inside a `hub` folder, the hub will load at:

`https://jeromemmplace.github.io/mortgagemarketplace/hub/`

## Current Features

- Dashboard with quick access cards
- Mortgage calculator
- Resource library
- Projects workspace with editable placeholders
- File/link upload prototype using browser storage
- Comments and review status controls
- Transaction checklists
- AI Assistant page with custom GPT link

## Notes

The Projects workspace currently saves data locally in the browser using `localStorage`. For real team login, shared projects, and cloud file uploads, connect Firebase Authentication, Firestore, and Firebase Storage.
