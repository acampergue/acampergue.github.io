# AGENTS.md

## Repo Shape
- `README.md` is the canonical CV content and the most important file in the repo. Default to editing it for resume/content updates.
- This is a GitHub Pages/Jekyll repo, not an application repo. The checked-in site config is `_config.yml` (`theme: jekyll-theme-cayman`, `gems: [jekyll-mentions]`).
- There is no `index.*`, `_layouts/`, or `_includes/` in the repo. The only checked-in page content is `README.md`, so content changes should usually happen there.
- No package manager, lockfile, CI workflow, lint/typecheck/test config, or repo scripts are tracked. Do not guess `npm`/`pnpm`/test commands; verification here is manual Markdown/YAML sanity checking.

## Editing Gotchas
- `README.md` intentionally mixes Markdown with raw HTML (`<center>`, `<br/>`) for layout. Preserve that structure unless the task is explicitly to redesign the page.
- The repo also contains theme/rendering assets (`stylesheets/*`, `javascripts/main.js`, `fonts/`, `images/`) used for a separate prettier render path. Unless a task is specifically about that themed output, you can mostly ignore them and work in `README.md`.
- Those local CSS/JS files are not referenced by any checked-in page or layout in this repo, so editing them does not change the checked-in GitHub Pages content by itself.
- `README_backup_trainings.md` is not referenced anywhere in the repo; treat it as backup/print-oriented content, not the homepage source.
- `.gitignore` only ignores `README.pdf`. If you generate a PDF locally, do not expect it to be tracked by default.
