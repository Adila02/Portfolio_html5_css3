# Copilot Instructions

- This repo is a simple static portfolio site built with only `index.html` and `style.css`.
- There is no build tool, package manager, or test suite. The product is served by opening `index.html` in a browser.
- Keep changes within the root files: `index.html`, `style.css`, and assets under `img/`.

## Project structure
- `index.html`: the only page. It already includes `lang="pt-br"`, `meta charset`, `viewport`, and a favicon link.
- `style.css`: the only stylesheet. It defines CSS variables in `:root` and a responsive media query for `min-width:576px`.
- `img/`: contains the favicon and any images used by the portfolio.

## Key patterns
- Use the existing CSS variables defined in `style.css` instead of hard-coding colors.
- Preserve the Portuguese language context in page metadata and content.
- Keep the HTML minimal and semantic: this repo is not using JavaScript or complex frameworks.
- Add new styling rules to `style.css` rather than introducing inline styles in `index.html`.

## Workflow notes
- No build or test commands exist. To validate changes, open `index.html` directly in a browser and refresh after edits.
- If assets are needed, place them under `img/` and reference them with relative paths.

## What not to do
- Do not invent a Node/npm workflow, since there is none in this repository.
- Do not add unrelated configuration files unless explicitly requested.
- Do not assume multi-page navigation or dynamic content; the current repository is a single-page static portfolio.
