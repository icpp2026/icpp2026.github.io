## Learned User Preferences

- Use `AoE` (not `AOE`) for deadline timezone labels across the site.
- Use conference dates as `September 28 - October 1, 2026` consistently across pages.
- Do not change the "55th" edition wording when editing site copy.
- Keep the sponsors placeholder in `overrides/partials/sponsors.html` visually subtle (low-opacity text and background) until real sponsor logos are added.
- When updating CFP or call pages from attached source documents, copy the content verbatim without paraphrasing.
- Keynote speaker entries: place name, affiliation, and photo on one row; put the abstract on its own line below.

## Learned Workspace Facts

- MkDocs Material site: content under `docs/`, theme overrides under `overrides/`.
- CI deploys on push to the `source` branch via `.github/workflows/publish.yml`; `mkdocs gh-deploy` publishes to the `main` branch (`remote_branch` in `mkdocs.yml`).
- Last-modified dates use the `git-revision-date-localized` plugin; CI checkout must use `fetch-depth: 0` for per-file git history.
- Keynote speakers page: `docs/keynote-speakers.md`.
- Sponsors footer partial: `overrides/partials/sponsors.html`.
- Homepage landing override: `overrides/home_landingpage.html`.
