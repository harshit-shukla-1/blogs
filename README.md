# blogs

Personal Jekyll blog, published to GitHub Pages at
https://harshit-shukla-1.github.io/blogs/

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/blogs/ in a browser.

## Adding a post

Add a new file to `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```yaml
---
layout: post
title: "My Post"
date: 2025-01-01 00:00:00 +0530
categories: general
---

Post content goes here.
```

## Deployment

Pushes to `main` trigger `.github/workflows/pages.yml`, which builds the
site with Jekyll and deploys it to GitHub Pages via GitHub Actions.
