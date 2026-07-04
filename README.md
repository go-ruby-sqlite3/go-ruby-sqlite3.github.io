<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-sqlite3/brand/main/social/go-ruby-sqlite3.png" alt="go-ruby-sqlite3/go-ruby-sqlite3.github.io" width="720"></p>

# go-ruby-sqlite3.github.io

The organization's institutional landing page, served at
<https://go-ruby-sqlite3.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-sqlite3/docs](https://github.com/go-ruby-sqlite3/docs), served at
<https://go-ruby-sqlite3.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
