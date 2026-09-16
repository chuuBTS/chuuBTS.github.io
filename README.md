# Chuhan Huang - Personal Website

An English academic and professional website built with Jekyll and Academic Pages.

## Content

- `_pages/about.md`: biography, education, and selected research
- `_pages/projects.md`: research and engineering projects
- `_pages/experience.md`: internship and technical skills
- `_pages/cv.md`: printable English CV and awards
- `_data/navigation.yml`: main navigation
- `_config.yml`: identity, contact details, and publication settings
- `_sass/_personal.scss`: layout refinements and print styles

The confirmed portrait is `images/profile.jpg`. Public contact information includes email, GitHub, and city (Guangzhou, China).

## Local development

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. For a production check:

```sh
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
```

The GitHub Actions build runs on pushes and pull requests and uploads a `website-preview` artifact. It validates the site; GitHub Pages publication still follows the repository's Pages settings.

## Content notes for the owner

The English content was transcribed from the supplied Chinese resume. The owner confirmed the name Chuhan Huang and final-year master's student status in September 2026, with graduation expected on October 15, 2026. The navigation balances academic and professional experience. The company name is transliterated as Zhuoyue Licheng Education Technology; replace it if an official English name is available. Degree types and certificate names have not been expanded beyond the supplied information.

The nvBench paper title and author order follow https://arxiv.org/abs/2503.12880. As requested by the owner, the website lists the public author order without an authorship-rank claim. NeurIPS 2025 and the project experiment metrics come from the resume. Step-NL2VIS is the model name used in the resume; the current paper calls its model Step-Text2Vis.

Unused template pages, sample publications, talks, posts, and sample downloads are excluded from the generated site in `_config.yml`. They remain in the repository for reference. Old `/year-archive/`, `/publications/`, `/portfolio/`, `/cv-json/`, and `/awards/` URLs redirect to the relevant personal pages.

## Credits

Built on [Academic Pages](https://github.com/academicpages/academicpages.github.io), based on Minimal Mistakes. Original licensing and theme credits are retained.
