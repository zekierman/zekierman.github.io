# zekierman.github.io

Personal website of Zeki Erman: about, projects and a blog.

Built with [Jekyll](https://jekyllrb.com/) and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (via `remote_theme`), and published with GitHub Pages.

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Structure

- `index.md` – About (home page)
- `_pages/projects.md` – Projects
- `_pages/blog.md` – Blog index; posts go in `_posts/` as `YYYY-MM-DD-title.md`
- `_data/navigation.yml` – top navigation
- `_config.yml` – site settings, author profile and theme
