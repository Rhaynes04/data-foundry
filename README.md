# Data Foundry

Data Foundry is a browser-based, project-driven learning platform for data analytics and data engineering. It combines a shared SQL foundation with separate analytics and engineering tracks, interactive exercises, progress tracking, assessments, and guided project work.

## What is included

- A 90-day data engineering track
- An 83-day data analytics track
- Interactive SQL exercises powered by `sql.js`
- Browser-based progress saving
- Optional Supabase cloud synchronization
- Projects, assessments, examples, hints, and debugging guidance

## Run locally

The application is a static website with no build step.

### Quick option

Open `index.html` in a modern browser.

### Recommended option

Serve the folder locally so browser features behave consistently:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Save the settings.

GitHub will provide the published website URL after deployment finishes.

## Data and privacy

By default, progress is saved in the browser with `localStorage`. Optional cloud synchronization can be configured from inside the application. Do not commit real API keys, passwords, `.env` files, or database credentials to this repository.

The SQL engine and fonts are loaded from third-party CDNs, so an internet connection is required for the full experience.

## Ownership

Copyright (c) 2026 Renthal Haynes. All rights reserved.

See [AUTHORSHIP.md](AUTHORSHIP.md) for additional authorship information. Referenced books, videos, trademarks, and third-party materials remain the property of their respective owners and are not distributed with this project.

