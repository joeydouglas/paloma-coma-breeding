# paloma-coma-breeding

Markdown **data repo** for the Paloma Coma (Cherry Paloma x Nana Glue) breeding project.

## Layout

- `project.md` — project-level frontmatter and notes (cross name, seed source, status).
- `plants/<ID>.md` — one markdown file per plant (`PC01`, `PC04`, …), the record of truth
  an observation mutates.

These files are read by the breeding data API, which serves the current frontend.
Observations are committed here automatically by the Discord ingestion monitor.

## Legacy dashboard

The old static GitHub Pages dashboard (`index.html`, `style.css`, `plants/*.html`, and its
deploy workflow) previously lived in this repo alongside the data files. It has moved to
[joeydouglas/paloma-coma-dashboard-legacy](https://github.com/joeydouglas/paloma-coma-dashboard-legacy).
