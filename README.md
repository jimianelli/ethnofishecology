# Ethnofishecology

This repository contains a Quarto book project on ethnofishecology: an emerging interdisciplinary framing for studying how cultural knowledge, fishing practice, governance, and ecological dynamics interact across fisheries systems.

The manuscript is currently a draft synthesis rather than a finished monograph. The goal of the repository is to keep the argument, citations, and published site aligned in one place instead of maintaining separate source and hand-edited HTML versions.

## Repository layout

- `index.qmd`: preface and framing for the book.
- `concept_note.qmd`: concise statement of the field, problem, and research agenda.
- `chapter*.qmd`: main manuscript chapters.
- `_quarto.yml`: Quarto book configuration.
- `docs/`: canonical rendered output for GitHub Pages.

## Prerequisites

- Quarto CLI installed and available on `PATH`.
- A LaTeX distribution if you want to build the PDF artifact.

## Build and preview

Preview the book locally:

```bash
quarto preview
```

Render the publication artifacts into `docs/`:

```bash
quarto render
```

Quarto also creates a local `_book/` directory during some workflows; that directory is ignored and should not be treated as the publish target.

## Editing guidance

- Edit source in `.qmd` files, not the rendered HTML in `docs/`.
- Keep claims tied to identifiable references.
- Prefer concise prose over outline placeholders.
- Use standard scholarly references or stable institutional sources where appropriate.

## Contributing

1. Create a branch for the change.
2. Edit the relevant `.qmd` source files.
3. Run `quarto render` to refresh `docs/`.
4. Review the rendered pages before opening a pull request.

## Contact

Questions or collaboration inquiries: `jim.ianelli@gmail.com`
