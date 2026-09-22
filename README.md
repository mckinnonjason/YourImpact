# YourImpact

This repository contains the static YourImpact website. GitHub Actions deploys it to GitHub Pages automatically whenever the `main` branch is updated.

The website runs entirely in the browser. Login, donation history, XP, streaks, profile data, and achievements are saved in each visitor's browser using `localStorage`; no Replit service or database is required.

## Deployment

The workflow in `.github/workflows/deploy-pages.yml` publishes the site after every push to `main`. In the repository's GitHub Pages settings, the source must be set to **GitHub Actions**.
