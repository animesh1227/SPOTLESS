# SPOTLess.web — GitHub Pages Launcher

This repository can be published with GitHub Pages.

The included `index.html` redirects visitors to the live Spotless application:

https://spotless.floot.app

## Why this setup?

The full Spotless application uses Floot-hosted backend/database features.
GitHub Pages only hosts static files, so it cannot run the complete backend.

This launcher lets your GitHub Pages URL open the real, working Spotless website.

## GitHub Pages setup

1. Upload these files to the root of the `SPOTLess.web` repository.
2. Open repository **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Branch: `main`
6. Folder: `/ (root)`
7. Click **Save**.
8. Wait 1–5 minutes.

Your GitHub Pages address should be:

https://animesh1227.github.io/SPOTLess.web/

Opening it will forward to:

https://spotless.floot.app/

## Security

Do not upload `.env` files, database URLs, JWT secrets, API keys, payment keys,
private certificates, or any other credentials to GitHub.
