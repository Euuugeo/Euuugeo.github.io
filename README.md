# Richard Chen's Academic Portfolio

A personal academic website built with [Academic Pages](https://github.com/academicpages/academicpages.github.io) and published at:

<https://Euuugeo.github.io>

## Content

- Biography and research interests
- Education
- Research and engineering projects
- Honors and competitions
- Web-based curriculum vitae

## Local Preview

Install Ruby, Bundler, and the project dependencies, then run:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Open <http://localhost:4000>.

Alternatively, use Docker:

```bash
docker compose up
```

## Editing

- Site metadata: `_config.yml`
- Navigation: `_data/navigation.yml`
- Homepage: `_pages/about.md`
- CV: `_pages/cv.md`
- Honors: `_pages/awards.md`
- Projects: `_portfolio/`

## Privacy

The public website intentionally excludes private details from the original resume, including phone number, birthday, political affiliation, and home address.
