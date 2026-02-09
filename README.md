# Certificate Builder

This repository hosts a single-page certificate builder UI (`index.html`) that is published to GitHub Pages.

## GitHub Pages deployment

The site is deployed via GitHub Actions using `.github/workflows/pages.yml`. To ensure updates appear at
`https://haxoranix.github.io/gpt/`:

1. In the repository **Settings → Pages**, set **Source** to **GitHub Actions**.
2. Push to `main` or `work` (the workflow deploys on both).
3. Wait for the **Deploy GitHub Pages** workflow to finish successfully.

If changes still do not appear after a successful run, force refresh the browser cache.
