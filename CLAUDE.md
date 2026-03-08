# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a Jekyll-based GitHub Pages personal blog for Eric Sal, deployed at https://esalavat.github.io/devolver. There is no local build toolchain checked in — the site is built and deployed automatically by GitHub Pages on every push to `main`.

## Site Structure

- `_config.yml` — Jekyll configuration (theme: minima, site title, author, URL)
- `index.md` — Homepage (displays the title image)
- `_posts/` — Blog posts; filenames must follow the format `YYYY-MM-DD-title.md`
- `assets/images/` — Static image assets referenced in posts and pages

## Writing Blog Posts

Create a new file in `_posts/` with the naming convention `YYYY-MM-DD-slug.md` and include front matter:

```markdown
---
title: "Post Title"
date: YYYY-MM-DD
---

Post content here.
```

## Local Preview (optional)

If Jekyll is installed locally:

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.
