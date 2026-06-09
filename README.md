# joseramasa.github.io

Personal website of Jose Ramon Martinez Saavedra — VP of Innovation and Lead Scientist at [Quside Technologies](https://quside.com).

**Live:** [joseramasa.github.io](https://joseramasa.github.io)

## Stack

- [Jekyll](https://jekyllrb.com/) with the [al-folio](https://github.com/alshedivat/al-folio) theme
- Hosted on [GitHub Pages](https://pages.github.com/)
- CI: html-proofer (internal links, HTML) + Lighthouse CI (performance, accessibility, SEO)
- Publications via [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar) from BibTeX

## Structure

| Section | Path | Source |
|---------|------|--------|
| About / Home | `/` | `_pages/about.md` |
| Publications | `/publications/` | `_bibliography/papers.bib` |
| Patents | `/patents/` | `_pages/patents.md` |
| Research | `/research/` | `_pages/research.md` |
| Teaching | `/teaching/` | `_pages/teaching.md` |
| CV | `/cv/` | `_data/cv.yml` |
| Projects | `/projects/` | `_projects/*.md` |
| Notes | `/blog/` | `_posts/*.md` |

## Machine-readable endpoints

- `/llms.txt` — compact identity summary for LLMs
- `/llms-full.txt` — full profile with publications, patents, projects
- `/profile.json` — structured identity data

## Local development

```bash
bundle install
bundle exec jekyll serve
```

## License

Content (text, images, CV data) is copyright Jose Ramon Martinez Saavedra. Theme code follows [al-folio's MIT license](https://github.com/alshedivat/al-folio/blob/master/LICENSE).
