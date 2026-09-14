# Christian González — Portfolio

Professional portfolio built with [Hugo](https://gohugo.io/) and the [Spectra](https://github.com/JoeYang1412/hugo-theme-spectra) theme.

## Local development

Requirements:

- Hugo Extended 0.157.0 or newer
- Go 1.25 or newer

```bash
git clone https://github.com/christianglezper/portfolio.git
cd portfolio
hugo server
```

Hugo will resolve the Spectra theme through Hugo Modules.

## Content structure

- `content/about.md` — professional profile
- `content/contact.md` — contact page
- `content/posts/selected-work/` — flagship case studies
- `content/posts/writing-media/` — editorial and media projects
- `static/css/portfolio.css` — portfolio-specific refinements
- `i18n/es.toml` — Spanish interface copy

## Deployment

Pushes to `main` trigger the GitHub Actions workflow in `.github/workflows/hugo.yaml` and deploy the generated site to GitHub Pages.

## Next improvements

The first version intentionally prioritizes structure and credible case-study copy. Next passes should add project imagery, measurable outcomes where documentation exists, LinkedIn/contact links, and an English-language version if needed.
