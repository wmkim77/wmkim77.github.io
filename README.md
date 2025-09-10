# Jekyll + GitHub Actions Starter

This repository is a minimal setup to build and deploy a Jekyll site to **GitHub Pages** using **GitHub Actions**.
You do **not** need Ruby on your Mac; the build happens in GitHub's runner.

## How to use
1. Create a GitHub repo named `USERNAME.github.io` (public recommended).
2. Copy these files into that repo (or clone this and push to your repo).
3. Push to the `main` branch. The workflow in `.github/workflows/pages.yml` will build & deploy.
4. In the repo: Settings → Pages → the URL will appear after first deploy.

Edit `_config.yml`, `index.md`, `about.md`, and add posts in `_posts/` to customize.
