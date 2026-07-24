# Floyd's Finishing Touch — Business Website

A one-page marketing website for **Floyd's Finishing Touch LLC**, a
veteran-owned handyman and home-repair business serving Valparaiso,
Niceville, Fort Walton Beach, Destin, and the surrounding Florida
panhandle (Okaloosa & Walton County).

The site introduces the business, lists the services offered, and shows
real before/after photos from completed jobs so potential customers can
see the quality of the work firsthand.

## Features

- Single-page layout covering services, service area, and contact info
- Before/after photo gallery from real completed jobs
- Mobile-friendly, fast-loading, no external JS frameworks
- SEO basics: descriptive meta tags, Open Graph/Twitter cards, and
  `LocalBusiness` structured data (JSON-LD) for local search
- `robots.txt` and `sitemap.xml` for search engine crawling
- Security headers configured for Netlify hosting (`netlify.toml`)

## Tech Stack

- Plain HTML, CSS, and JavaScript — no frameworks, no build tools, no
  dependencies
- Static site, deployable anywhere

## Running / Previewing Locally

No build step is required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder with any static file server, e.g.:

  ```bash
  npx serve .
  ```

## Deployment

The site is a plain static site and can be hosted on any static host.

- **Netlify**: `netlify.toml` is already configured with HTTPS redirects
  and security headers (HSTS, CSP, X-Frame-Options, etc.) — just point
  Netlify at this repo and deploy.
- **GitHub Pages**: also works out of the box — enable Pages on this
  repo and serve from the root of the default branch.

The production domain is `floydsfinishingtouch.org`, referenced in
`robots.txt`, `sitemap.xml`, and the page's canonical/Open Graph tags.

## License

MIT — see [LICENSE](LICENSE).
