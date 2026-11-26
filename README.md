# Yilin Liu · Academic Website

This is a static website for GitHub Pages. The repository root contains the home page, stylesheet, and downloads. It needs no build step.

## Preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a repository named `YOUR-USERNAME.github.io` for an account-level site. You can also use an ordinary repository name for a project site.
2. Commit the contents of this folder to the root of the repository’s `main` branch, including the hidden `.nojekyll` file.
3. In **Settings → Pages**, choose **Deploy from a branch** and select **main → /(root)**. Save the configuration.
4. Open the published link from **Settings → Pages** once GitHub finishes deploying.

[GitHub Pages documentation](https://docs.github.com/en/pages/quickstart)

## Update the site

Edit `index.html` for page content or `styles.css` for layout. Replace `assets/yilin-liu-cv.pdf` and `assets/publications.bib` whenever the public CV or bibliography changes.
