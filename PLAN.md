# Portfolio site plan

## Goal
Build a fast, responsive, text-first personal portfolio for Ray Lu, published as the GitHub user site `summer-momoko.github.io`.

## Pages and content
- **Home:** Name, concise introduction, and links to About, Work Experience, and Contact.
- **About:** Clearly labeled placeholder for a professional summary Ray has not supplied.
- **Work Experience:** Supplied roles, dates, locations, descriptions, and education, without adding achievements, employers, metrics, or projects.
- **Contact:** Link to the supplied LinkedIn profile; no public email address or mailto link.
- Shared navigation and footer across pages.

## Design
- Simple, single-column layout inspired by the text-first feel of patrickcollison.com: generous white space, clear scanning hierarchy, and minimal visual clutter.
- Light theme with a clean modern sans-serif body font and slightly heavier, understated headings.
- Responsive, accessible semantic HTML with readable contrast and no decorative animation.

## Technical approach
- Static Jekyll site with Markdown pages and YAML front matter, reusable layouts/includes, and plain HTML/CSS with minimal JavaScript.
- Website files live directly at the project root for GitHub Pages deployment from `main` and `/` (root).
- `_config.yml` uses an empty `baseurl`; internal links and assets use Jekyll URL filters.
- Include SEO metadata, sitemap, favicon, and a README covering edits, local preview, and Lighthouse checks.
- No backend, database, form service, blog, CMS, framework, package manifest, or third-party trackers.

## Assumptions and pending details
- The About copy remains a visible placeholder until Ray supplies text.
- Contact uses only the supplied LinkedIn URL.
- No portfolio projects or additional biography were provided, so none will be invented.
- GitHub Pages can publish the site from `Summer-Momoko/summer-momoko.github.io`, branch `main`, folder `/` (root); no repository changes or publishing action are being made here.
