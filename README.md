# Project-001

This repository contains a simple personal website built with Jekyll. The site is located in the `docs/` directory so it can be served with GitHub Pages.

## Local development

If you have Ruby installed, you can preview the site locally:

```bash
bundle install
bundle exec jekyll serve --source docs
```

Then open `http://localhost:4000` in your browser.

## Continuous Deployment

Every push to the `main` branch triggers a GitHub Actions workflow that builds the site from the `docs/` directory and deploys it to GitHub Pages.
