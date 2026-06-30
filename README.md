# soerenhenning.github.io

Personal academic portfolio website built with [Hugo](https://gohugo.io) and the custom `academic-portfolio` theme. Deployed to GitHub Pages at <https://soerenhenning.github.io>.

## Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)

## Local development

```bash
hugo server
```

Open <http://localhost:1313> in your browser. The server hot-reloads on file changes.

## Content

All content is driven by YAML files in [data/](data/):

| File | Section |
|---|---|
| `publications.yaml` | Publications |
| `projects.yaml` | Projects |
| `talks.yaml` | Talks |
| `theses.yaml` | Supervised theses |
| `service.yaml` | Academic service |
| `cv.yaml` | CV entries |

General settings (name, bio, social links, navigation) live in [config.toml](config.toml).

## Build & deploy

```bash
hugo
```

Output is written to `public/`. GitHub Pages deploys automatically on push to `main`.
