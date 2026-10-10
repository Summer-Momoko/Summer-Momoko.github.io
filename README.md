# Ray Lu — personal site

This is a static Jekyll site intended for the GitHub user site `summer-momoko.github.io`. GitHub Pages can build and publish it directly from the `main` branch and the repository root.

## Update the site

- Edit `index.md`, `about.md`, `experience.md`, or `contact.md` to update page content. Keep the YAML front matter at the top of each page.
- The About page currently contains a clearly marked placeholder for a professional summary.
- Edit `_config.yml` to change the site description or navigation.
- Edit `_layouts/default.html` and `_includes/` to adjust the shared page structure.
- Edit `assets/css/site.css` for typography, spacing, colors, and responsive styles.
- The contact page intentionally links to LinkedIn only; no email address is published.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`. Changes to Markdown and CSS are rebuilt while the server is running.

## Run Lighthouse

With the local site running, open it in Chrome, open Developer Tools, select **Lighthouse**, and run an audit for Performance, Accessibility, Best Practices, and SEO. The target is at least 90 in each category.

For a command-line audit, install Lighthouse in your local npm cache (no project `package.json` is needed) and run:

```sh
npx --yes lighthouse http://127.0.0.1:4000/ --only-categories=performance,accessibility,best-practices,seo
```

## Publish with GitHub Pages

Push this site to the `Summer-Momoko/summer-momoko.github.io` repository. In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, then select branch `main` and folder `/(root)`. GitHub Pages will run its Jekyll build automatically; no separate build output or app server is needed.
