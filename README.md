# Andrea Nigri – Personal Academic Website

This is the personal academic website of **Andrea Nigri**, Associate Professor in Statistics at the University of Foggia.

Built with [Quarto](https://quarto.org) using the **Minty** Bootswatch theme and populated with content from [andreanigri.wordpress.com](https://andreanigri.wordpress.com).

## Website Structure

- `_quarto.yml`: Quarto website configuration (theme: `minty`, output directory: `docs`).
- `index.qmd`: Homepage featuring profile image, academic affiliation, bio, social links (Google Scholar, X, LinkedIn, GitHub, Email), and favorite quotes.
- `research.qmd`: Research overview, research themes (longevity risk, deep learning mortality models, indirect estimation), international visiting appointments, editorial roles, and selected publications with DOI links.
- `cv.qmd`: Curriculum Vitae with interactive embedded PDF viewer and direct download button for the latest CV.
- `styles.css`: Custom CSS enhancements complementing the Minty theme (cards, badges, blockquotes, PDF viewer).
- `assets/`: Image assets (including optimized high-resolution profile portrait).
- `files/`: Documents and downloadable resources (including `anigri_cv_oct_25.pdf`).
- `docs/`: Pre-rendered site directory ready for GitHub Pages hosting.
- `.github/workflows/publish.yml`: GitHub Actions automated build and deployment workflow.

## Local Development & Preview

To preview the website locally with live reload:

```bash
quarto preview
```

To render the website:

```bash
quarto render
```

## GitHub Pages Deployment

The site is set up to publish via **GitHub Pages**:
- **Option A (Pre-rendered):** In your GitHub repository settings under **Settings > Pages**, choose **Deploy from a branch**, select branch `main` and folder `/docs`.
- **Option B (GitHub Actions):** In **Settings > Pages**, choose **GitHub Actions** (the included `.github/workflows/publish.yml` will handle the build automatically).