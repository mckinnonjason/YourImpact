# YourImpact

This repository contains the static YourImpact website. GitHub Pages publishes the files from the root of the `main` branch automatically whenever the branch is updated.

User accounts are managed by Supabase Auth. Profiles, donation history, XP, levels, and streaks are stored in Supabase PostgreSQL with Row Level Security so signed-in users can access only their own records. No Replit service or database is required.

## Deployment

The repository's GitHub Pages source is configured as **Deploy from a branch**, using `main` and the repository root (`/`).
