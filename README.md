# Portfolio Deployment

This `portfolio` folder is ready to deploy directly to GitHub Pages.

## Main Site File

GitHub Pages should use:

- `index.html`

That file redirects to:

- `portfolio.html`

## Folder Contents

Keep these together:

- `index.html`
- `portfolio.html`
- `image.png`
- `graphicdesign/`

## How To Deploy On GitHub

1. Create a new GitHub repository.
2. Upload the contents of this `portfolio` folder to the repository root.
3. In GitHub, open `Settings`.
4. Open `Pages`.
5. Under `Build and deployment`, choose `Deploy from a branch`.
6. Select `main` and `/ (root)`.
7. Save and wait for the site to publish.

Your GitHub Pages link will look like:

- `https://your-username.github.io/your-repository-name/`

## Notes

- If you rename files in `graphicdesign/`, update the paths in `portfolio.html`.
- The portfolio is static, so no build step is needed.
