# Demo-Sample — Template Website

Live site (after enabling Pages):
https://Krutikaweb.github.io/Demo-Sample/

Quick setup

1. In the repository Settings → Pages:
   - Source: choose branch `main` (the default branch) and folder `/ (root)`.
   - Save and wait a minute or two for the first deployment.

2. (Optional) Use the included GitHub Actions workflow to auto-deploy on push. If you commit the workflow file, every push to `main` will publish the repo root to GitHub Pages.

Notes

- Repository visibility: public — this repository is public, so GitHub Pages will publish the site automatically once Pages is enabled.
- The site root contains `index.html` and a minimal stylesheet at `assets/styles.css`.
- If you want a custom domain, provide the domain name and I will add a `CNAME` file and update the workflow with the domain configuration.

Troubleshooting

- If the site does not appear after enabling Pages, check Settings → Pages for build errors or the deployment log linked there.
- If you prefer to serve from `docs/` instead of root, move the static files into a `docs/` folder and set the Pages source to that folder.

Contact

Open an issue in the repository for changes or feature requests.