# Project 99 — JEE Main Study Dashboard

Aesthetic, responsive personal study tracker built as a static web app (HTML/CSS/JS). No build tools or API keys required.

## Run locally
Open `index.html` in a modern browser, or use VS Code Live Server.

## Publish with GitHub Pages
1. Create a new GitHub repository named `project-99`.
2. Upload `index.html` and this README to the repository root.
3. In GitHub: **Settings → Pages**.
4. Under Build and deployment choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Your site URL will be shown on that page.

## Data and privacy
- Tasks, chapter progress, mock scores and mistake notes are stored in this browser's localStorage.
- Uploaded question photos are stored locally in IndexedDB in this browser.
- Data does not automatically sync between devices or browsers.
- Use **Progress → Export backup JSON** regularly. The JSON export currently excludes uploaded image blobs; keep original photos backed up separately.
- Do not upload private question images or personal data into the public GitHub repository.

## Features
- Dashboard and completion indicators
- Calendar with editable tasks and seeded BHU weekly class timetable
- 75 chapter records, filters, progress, notes, formula fields
- Per-chapter image bank for difficult/incorrect questions
- Automatic spaced revision tasks at +1, +3, +7 and +14 days when a linked study task is checked off
- Chapter, part, cumulative and full mock result logging
- Mistake notebook and progress analytics
- JSON export/import for text data

## Important
The BHU calendar entries are based on the timetable and tentative exam dates shared in the chat. Confirm dates and applicable papers against your current official BHU notices. The site is a tracker, not a guarantee of any JEE percentile.
