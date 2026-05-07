# data-science-intro

This repository is a Quarto book for the ICT/LIS 661 data science introduction course.

Build the site with:

```bash
quarto render
```

## Updating the Course Site

When updating course content, edit the `.qmd` files, render the book locally, then commit both the source changes and the updated `_book` output:

```bash
quarto render
git add .
git commit -m "Update course site"
git push
```

GitHub Actions publishes the existing `_book` folder to GitHub Pages after each push to `main`.

## Acknowledgment

This repository is based on teaching materials originally developed by Dr. Spencer Greenhalgh, released under the Unlicense.
