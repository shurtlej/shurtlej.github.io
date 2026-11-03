# Jakob Shurtleff portfolio

The website is edited directly in `_site/`. Its home page is `_site/index.html`; machine learning pages are in `_site/Machine_Learning/`, and the research page is in `_site/research/`.

Commit and push changes to `_site/` on `main` to publish them to `gh-pages`. The workflow copies the complete contents of `_site/` to that branch without running Quarto. A manual run is also available in GitHub Actions. Files removed from `_site/` will be removed from the published site on the next run.

The `.qmd` files remain as source references. Future edits to them do not update the published HTML automatically.
