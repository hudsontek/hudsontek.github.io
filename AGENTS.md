# Repository Guidelines

## Project Structure & Module Organization
- Root holds `index.md` (landing content) and `_config.yml` (site metadata, Cayman theme).
- Add posts under `_posts/YYYY-MM-DD-title.md` with front matter; prefer dashed slugs matching titles.
- Place shared assets in `assets/` (e.g., `assets/img/` for images, `assets/css/custom.css` for overrides); keep reusable lists in `_data/*.yml`.

## Build, Test, and Development Commands
- `bundle exec jekyll serve --livereload` — run locally at http://localhost:4000, rebuilds on save.
- `bundle exec jekyll build` — produce the static site into `_site/` for release checks.
- `bundle exec jekyll doctor` — flag common config/content issues before pushing.
Ensure Ruby + Bundler are installed; run `bundle install` once to pull dependencies if Gemfile is added.

## Coding Style & Naming Conventions
- Markdown: clear heading hierarchy, descriptive link text, relative links where possible; keep sections short.
- Front matter keys: `layout`, `title`, `description`, optional `permalink`; avoid unused keys.
- Filenames: `_posts/YYYY-MM-DD-title.md`; use lowercase/kebab-case for assets and data files.
- YAML/JSON: 2-space indentation, no tabs; favor concise descriptions.

## Testing Guidelines
- No automated suite; use `jekyll serve` for iterative checks and `jekyll build` for pre-commit validation.
- Click through navigation, external links, and images; confirm `_site` contains expected pages and assets load.
- When adding embeds or external docs, verify they render in both local and published builds.

## Commit & Pull Request Guidelines
- Commits: imperative, present-tense summaries (e.g., "Add project timeline section"); group related edits.
- PRs: include purpose, notable pages touched, manual checks performed (serve/build/doctor), and screenshots for visual changes.
- Reference related issues or requests; keep diffs minimal and focused on one theme.

## Security & Configuration Tips
- Do not commit secrets, tokens, or personal data; link to external docs instead of embedding sensitive content.
- After changing `_config.yml` (theme, URL, baseurl), rerun `jekyll serve` and `jekyll doctor` to catch broken paths.
