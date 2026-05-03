# BioXArena Project Page

This repository contains a static project page template for a research paper.
It is designed to work directly with GitHub Pages.

## Files

- `index.html`: Page structure and placeholder research content.
- `styles.css`: Responsive visual styling.
- `assets/figure-placeholder.svg`: Placeholder image used by the figure section.

## How to Customize

Replace the placeholder content in `index.html`:

- Paper title in the hero `<h1>`.
- Author names, profile links, and institution superscripts.
- Institution names in the affiliations line.
- `Paper`, `Leaderboard`, `GitHub`, and `Hugging Face` URLs.
- Abstract text.
- Figure image paths and captions.
- BibTeX citation.

To add real figures, put image files in `assets/` and update each `<img src="...">`
path in `index.html`.

## GitHub Pages

In the GitHub repository settings:

1. Go to `Settings` -> `Pages`.
2. Select `Deploy from a branch`.
3. Choose branch `main` and folder `/root`.
4. Save the settings.

After deployment, GitHub Pages will serve `index.html` as the homepage.
