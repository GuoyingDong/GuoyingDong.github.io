# IDM Lab website

Personal and lab website for Dr. Guoying Dong, built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Updating content

Most updates are edits to the YAML files in `_data/`. You don't need to touch any HTML for these:

| What | File |
| --- | --- |
| Publications | `_data/publications.yml` |
| Lab members | `_data/people.yml` (photos in `assets/img/people/`) |
| News | `_data/news.yml` (images in `assets/img/news/`) |
| Research areas | `_data/research.yml` (images in `assets/img/research/`) |
| Contact info, profile links, menu | `_config.yml` |

Keep images small: about 1400px wide for photos and 500px square for headshots. Save them as `.webp` or `.jpg`.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
