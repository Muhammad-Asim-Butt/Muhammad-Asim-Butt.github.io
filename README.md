# Muhammad-Asim-Butt.github.io

Personal portfolio/resume site built with [Quarto](https://quarto.org).

## Local development

```
quarto preview
```

Renders and serves the site locally with live reload.

## Structure

- `index.qmd` — About / home page
- `resume.qmd` — Resume / CV
- `projects.qmd` — Projects listing (entries live under `projects/`)
- `contact.qmd` — Contact info
- `_quarto.yml` — site configuration (navbar, theme)

## Deployment

Pushing to `main` triggers `.github/workflows/publish.yml`, which renders the
site with Quarto and publishes it to the `gh-pages` branch. In the repo's
**Settings → Pages**, set the source to the `gh-pages` branch (created
automatically after the first successful workflow run).
