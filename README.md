# Paw Clock Public Pages

Standalone GitHub Pages site for Paw Clock's public review links.

Intended repository:

- `springdatauk/paw-clock-pages`

Expected GitHub Pages URLs after publishing:

- `https://springdatauk.github.io/paw-clock-pages/`
- `https://springdatauk.github.io/paw-clock-pages/privacy.html`
- `https://springdatauk.github.io/paw-clock-pages/support.html`

## Publish

1. Create a new public repository named `paw-clock-pages` under the `springdatauk` GitHub account.
2. Push this folder as the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Save and wait for the first deployment to complete.

## Files

- `index.html`: landing page with support, privacy, and EULA links
- `privacy.html`: Paw Clock privacy policy
- `support.html`: Paw Clock support page for App Review and customers
- `styles.css`: shared styles
- `sitemap.xml`: sitemap for the public pages
- `robots.txt`: crawler hints
- `.nojekyll`: disables Jekyll processing on GitHub Pages
