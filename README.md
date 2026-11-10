# Gared Graphics - WordPress Documentation

The client guide for the Gared Graphics WordPress site: how to edit pages and their sections, portfolio projects, blog posts, forms, images and site settings.

Published with GitHub Pages: https://coalitiontech.github.io/gared-graphics-doc/

## Working on it

- Install MkDocs: `pip install mkdocs`
- Preview with live reload: `mkdocs serve --livereload`, then open http://127.0.0.1:8000/
- Pages are in `docs/` (Markdown), screenshots in `docs/img/`, the menu in `mkdocs.yml`, colours in `docs/style.css`.
- Check before publishing: `mkdocs build --strict` (fails on broken links or missing images).
- Publish: `mkdocs gh-deploy` (builds the site and pushes it to the `gh-pages` branch). The `site/` folder is a local build and isn't committed.
