# data-science-intro

This repository is a Quarto website for the ICT/LIS 661 data science introduction course.

Preview the site locally with:

```bash
quarto preview
```

Build the static site with:

```bash
quarto render
```

The rendered website is written to the `_site` folder, as configured in `_quarto.yml`.

## Updating the Course Site

When updating course content, edit the `.qmd` files, preview the site locally, render the site, then commit both the source changes and the updated `_site` output:

```bash
quarto preview
quarto render
git status
git add -A
git commit -m "Update course site"
git push
```

GitHub Actions publishes the existing `_site` folder to GitHub Pages after each push to `main`.

## Acknowledgment

This repository is based on teaching materials originally developed by Dr. Spencer Greenhalgh, released under the Unlicense.
