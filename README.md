# avaljotsingh.github.io

Personal academic website of [Avaljot Singh](https://avaljotsingh.github.io), PhD
candidate in Computer Science at the University of Illinois Urbana-Champaign.

Built with [Jekyll](https://jekyllrb.com/) on a fork of the
[al-folio](https://github.com/alshedivat/al-folio) theme.

## Running locally

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Add `--drafts` to preview anything in `_drafts/`.

## Where things live

| What | Where |
|---|---|
| Homepage bio and layout switches | `_pages/about.md` |
| Publications | `_bibliography/papers.bib` (rendered by jekyll-scholar) |
| Venue badge colors | `_data/venues.yml` |
| Coauthor homepage links | `_data/coauthors.yml` |
| Research theme cards | `_data/research_projects.yml` |
| News items | `_news/` (one file per item) |
| Blog posts | `_posts/`, drafts in `_drafts/` |
| Theme colors | `_sass/_variables.scss`, `_sass/_themes.scss` |

## Adding a publication

Add an entry to `_bibliography/papers.bib`. Set `abbr` to a venue key that
exists in `_data/venues.yml` so the colored badge renders. Useful fields:
`arxiv`, `doi`, `html`, `pdf`, `code`, `poster`, `slides`, `note`, and
`selected` (features it on the homepage when selected papers are enabled).

## Adding a news item

Create `_news/YYYY-MM-slug.md` with `inline: true` and a `date`. The homepage
shows the five most recent.

## Deploying

Pushing to `master` triggers `.github/workflows/deploy.yml`, which builds the
site and publishes `_site` to the `gh-pages` branch.

## License

MIT, inherited from al-folio. See `LICENSE`.
