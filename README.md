# AlamiaSoft Engineering Portfolio

A dependency-free static portfolio published with GitHub Pages via GitHub Actions.

## Contents
- `index.html` — portfolio page and curated project descriptions
- `assets/styles.css` — responsive visual system and project diagrams
- `.github/workflows/pages.yml` — static-site validation and Pages deployment

## Publish
The workflow runs on pushes to `main` and can be triggered manually. In GitHub, open **Settings → Pages** and ensure the build/deployment source is set to **GitHub Actions**. The workflow requires the Pages and id-token permissions declared in its YAML.

The site contains a deliberate public allowlist. Do not sync the private engineering audit, repository inventory, credentials, internal notes, or private project links into this repository.

## Update project selection
Edit the cards in `index.html`. Before publishing a project, verify its repository is public and that its description, project name, screenshots, and claims are approved for public disclosure.
