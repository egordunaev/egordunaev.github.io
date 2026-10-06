# egordunaev.github.io

Personal site built with plain [Jekyll](https://jekyllrb.com). GitHub Pages builds and deploys it on every push to `gh-pages`

## Run locally

You need Ruby 3.x and Jekyll (`gem install jekyll`).

```sh
jekyll serve            # http://localhost:4000, rebuilds on save
jekyll serve --future   # also show posts dated in the future
```

The output goes to `_site/`, which is gitignored. Restart the server after editing `_config.yml`.

## Writing a post

Create `_posts/<optional-folder>/YYYY-MM-DD-slug.md`:

```markdown
---
title: my post
---

Markdown here. Raw HTML and <script> tags work too.
```

