# jayceeshi.github.io

A cleaned-up Jekyll academic homepage styled to resemble the structure of Tianpei Yang's site, while removing the Talks and CV pages.

## Included

- Top navigation: Home / Publications / Teaching
- Sidebar author profile
- Home page migrated from the current site
- Publication pages generated from the current publication list
- Placeholder avatar at `assets/images/avatar-placeholder.svg`

## What you should replace

1. `assets/images/avatar-placeholder.svg` with your real portrait, then update `author.avatar` in `_config.yml` if needed.
2. `author.googlescholar` in `_config.yml` with your real Google Scholar link.
3. `repository` in `_config.yml` if your repo name changes.
4. The placeholder text on `_pages/teaching.md`.

## Deploy on GitHub Pages

For a user site named `jayceeshi.github.io`:

1. Push this repo to the `main` branch of `jayceeshi/jayceeshi.github.io`.
2. In GitHub, go to **Settings → Pages**.
3. Set the source to **Deploy from a branch** and choose `main` / `/ (root)`.
4. Wait for Pages to build.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```
