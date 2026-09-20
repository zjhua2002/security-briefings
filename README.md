# Security Briefings

This repository is a simple GitHub Pages site for publishing security-related articles across product security, industry developments, and engineering lessons learned.

Published site: <https://zjhua2002.github.io/security-briefings/>

## Repository Layout

```text
.
|-- _config.yml
|-- _layouts/
|-- _posts/
|-- index.md
`-- README.md
```

## How To Publish

1. Push changes to `main`.
2. In GitHub repository settings, open `Pages`.
3. Set the source to deploy from the `main` branch and the repository root.

GitHub Pages will build the Jekyll site automatically. No GitHub Actions workflow is required.


## Writing Articles

Add articles to `_posts/` using this filename format:

```text
YYYY-MM-DD-title.md
```

Use basic front matter like this:

```yaml
---
title: My Article Title
date: 2026-09-10
---
```
