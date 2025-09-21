# Yifei Li · Portfolio

Live site: [https://Finn1226.github.io/](https://Finn1226.github.io/)

Personal portfolio highlighting AI/ML research, full-stack projects, and design work. Built as a lightweight static site suitable for GitHub Pages or any static hosting.

## Features
- Responsive layout with sections for experience, projects, skills, and contact details
- PDF embeds for the VU ISIS and ULS posters
- App Store CTA for ChordFanta alongside brand assets
- Project cards for TunTun Weight Tracking, ACC, and Vandy Ice Hockey initiatives
- Timeline-style experience block sourced from the résumé

## Project Structure
```
Portfolio/
├── images/                 # Posters, logos, headshot, résumé (kept off-site)
├── index.html              # Main site markup
├── styles.css              # Styling for all sections
└── README.md               # This file
```

## Getting Started
1. Clone or download the repository.
2. Open `index.html` in your browser to view the site locally.
3. Edit the copy or assets as needed (e.g., update contact info, add new projects).

For a lightweight local server while iterating:
```bash
python3 -m http.server
```
Then visit `http://localhost:8000/`.

## Publishing
This project is configured for GitHub Pages. Each push to `main` in `Finn1226.github.io` redeploys automatically to the live URL. Custom domains can be added by creating a `CNAME` file at the repo root and pointing DNS to GitHub Pages.

## Updating Content
- Add new assets to `images/`, then reference them from `index.html`.
- Extend the experience or projects by duplicating existing card/timeline markup.
- Keep `.gitignore` entries for `.DS_Store` so macOS metadata is excluded from commits.

## Contact
Questions or collaboration ideas? Reach out via the details on the live site: `yifeili1226@gmail.com` or the linked GitHub/LinkedIn profiles.
