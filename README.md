# Vevori Media

Landing page for Vevori Media (vevorimedia.com). One static page, no build step.

## Files

- `index.html` — the whole site (HTML, CSS, and a little JavaScript in one file)
- `CNAME` — tells GitHub Pages which custom domain to serve
- `assets/og.jpg` — social share image
- `logos/` — full lockup (`vevori-logo*.png`), framed mark (`vevori-mark*.png`), `favicon.png`

## Editing

Search `index.html` for these markers:

| Marker | Meaning |
|---|---|
| `PLACEHOLDER` | Value that still needs filling in (none right now) |
| `[[COPY]]` | Wording you may want to rewrite |
| `[[LINK]]` | URL to fill in (email, form endpoint) |
| `[[MEDIA]]` | Image or video to swap |
| `[[CLIENT]]` | Portfolio entry |

Brand colors (sampled from the logo) are CSS variables at the top of the stylesheet. Copy is written in company voice ("we") so it holds up as the team grows.

## Before launch checklist

1. Contact form: submissions go through Formspree (form id in the form's `action`) and are emailed to the address set in the Formspree dashboard. Change the destination there, then send a test inquiry.
2. Swap the contact email for collin@vevorimedia.com (or a shared address like hello@) once forwarding works. It appears in the contact section and the search-engine metadata.
3. When there is real client work, replace the Work panel with the tile grid kept in a comment under it. Add a testimonial the same way (template is commented in the About section).
4. Delete the `noindex` meta tag in `<head>` so search engines can find the site.
5. GitHub Pages: Settings, Pages, deploy from `main`, root folder, custom domain `vevorimedia.com`, then enable "Enforce HTTPS" once it's available.
