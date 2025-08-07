# Zoran Documentation

This repository contains the official documentation for Zoran IA. The docs are written in Markdown and rendered using MkDocs.

## Structure

- `docs/` – contains the documentation pages (`index.md`, `langage-glottal.md`, `guide-glyphe.md`) which describe the glottal language, available glyphes and usage.
- `mkdocs.yml` – configuration file for MkDocs that defines the navigation and theme.

## Building the documentation locally

To build and serve the documentation locally:

```bash
pip install mkdocs
mkdocs serve
```

This will start a local web server at `http://127.0.0.1:8000` where you can view the documentation.

## Publishing

The documentation is intended to be published via GitHub Pages. After pushing updates to `main`, run:

```bash
mkdocs gh-deploy
```

This command builds the site and pushes the generated static files to the `gh-pages` branch.

## License

This repository is licensed under the MIT License. See the `LICENSE` file for more details.
