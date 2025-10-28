# Portfolio Website

A clean, minimal portfolio website built with Jekyll and hosted on GitHub Pages.

## Quick Start

1. Edit `_config.yml` to update your name and bio
2. Add portfolio items to `_portfolio/` folder
3. Add images to `assets/images/`
4. Push to GitHub

## Adding Projects

Create a new `.md` file in `_portfolio/`:

```markdown
---
title: Project Name
description: Short description
image: /assets/images/your-image.jpg
order: 1
---
```

## Local Development

```bash
bundle exec jekyll serve
```

Visit http://localhost:4000
