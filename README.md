# Vortec hydromulching services mockup

Static preview of the hydromulching services page.

**Preview:** https://lilmonstersam.github.io/vortec-hydromulching-services/

The page entry point is `index.html`, and its saved local resources are in `assets/`. Links to articles, case studies and service pages may lead to the live Vortec site. The preview includes a `noindex, nofollow` directive to keep this mockup out of search results.

## Deployment

Pushing to `main` or running the **Deploy mockup to GitHub Pages** workflow manually publishes the site via GitHub Actions. In the repository's **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**.

The workflow copies only `index.html`, `assets/` and `.nojekyll` into its upload directory. No build tools or secrets are required.
