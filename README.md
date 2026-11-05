# Mercy Gathoni Kihuna's Website

This site uses the [AcademicPages](https://github.com/academicpages/academicpages.github.io) Jekyll template, based on the Minimal Mistakes theme, and is deployed to GitHub Pages with GitHub Actions. See [LICENSE](./LICENSE) for the template's license.

## Content

- Edit the homepage in `_pages/about.md`.
- Edit the CV in `_pages/cv.html`.
- Add publications to `_publications/`, talks to `_talks/`, and blog posts to `_posts/`.
- Change the navigation in `_data/navigation.yml` and site details in `_config.yml`.

The Publications, Talks, and Blog Posts pages show a placeholder until content is added.

## Local preview

Install Ruby, Bundler, and Node.js, then run:

```sh
bundle install
npm install
npm run build:js
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser. GitHub Pages must be configured to deploy from **GitHub Actions**.