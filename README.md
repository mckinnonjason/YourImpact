# YourImpact

## Live Website

[Visit YourImpact](https://mckinnonjason.github.io/YourImpact/)

This repository contains the static YourImpact website. GitHub Pages publishes the files from the root of the `main` branch automatically whenever the branch is updated.

User accounts are managed by Supabase Auth. Profiles, donation history, XP, levels, and streaks are stored in Supabase PostgreSQL with Row Level Security so signed-in users can access only their own records. No Replit service or database is required.

Donation amounts and organization checks are documented in [CATALOG_REVIEW.md](CATALOG_REVIEW.md). The catalog was last reviewed in September 2026 against each nonprofit's own published gift pages and Charity Navigator profiles where available.

## Deployment

The repository's GitHub Pages source is configured as **Deploy from a branch**, using `main` and the repository root (`/`).
