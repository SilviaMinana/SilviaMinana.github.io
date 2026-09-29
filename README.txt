# BB — Scientist Website

This is a simple GitHub Pages website for a scientist/researcher.

## The easiest way to edit it

You only need to edit `index.html`.

Open it and search for comments containing:

    CHANGE THIS

Those comments mark places where you can replace the sample text with your own information.

### Adding a project

Find:

    <!-- COPY THIS CARD TO ADD MORE PROJECTS -->

Copy one of the project cards above it and paste the copy underneath.

### Adding a publication

Find:

    <!-- COPY THIS BLOCK FOR EACH ADDITIONAL PAPER -->

Copy one publication block and change:
- year
- title
- authors
- journal
- DOI link
- PDF link

### Adding your CV PDF

Put your PDF in the same folder as `index.html`, for example:

    BB-CV.pdf

Then find the "Download CV" button in `index.html` and change its link from `#` to:

    BB-CV.pdf

### Changing social links

At the bottom of `index.html`, replace the `#` values after:
- Google Scholar
- ORCID
- GitHub
- LinkedIn

with your real profile URLs.

## Publishing with GitHub Pages

1. Create a GitHub repository named `YOURUSERNAME.github.io`.
2. Upload `index.html` and `style.css`.
3. Go to Settings → Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select the `main` branch and `/ (root)`.
6. Save.
7. After GitHub finishes deploying, visit `https://YOURUSERNAME.github.io`.

You can edit `index.html` directly on GitHub later. You do not need to install anything.
