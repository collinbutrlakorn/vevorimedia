# Vevori Media

Landing page for Vevori Media (vevorimedia.com). One static page, no build step.

Personal and creative work lives on a separate site, collinmotion.com.

## Files

- `index.html` — the whole site (HTML, CSS, and a little JavaScript in one file)
- `assets/` — `hero.jpg`, `about.jpg`, `og.jpg` (social share image)
- `logos/` — full lockup (`vevori-logo*.png`), framed mark (`vevori-mark*.png`), `favicon.png`

## Editing

Search `index.html` for these markers:

| Marker | Meaning |
|---|---|
| `PLACEHOLDER` | Text or value that still needs real content |
| `[[COPY]]` | Wording to rewrite in your own voice |
| `[[LINK]]` | URL to fill in (email, form endpoint, video embeds) |
| `[[MEDIA]]` | Image or video to swap |
| `[[CLIENT]]` | Portfolio entry |

Brand colors (sampled from the logo) are CSS variables at the top of the stylesheet.

## Before launch checklist

1. The Work section is a "samples on request" panel for now. When you have real client work, swap it for the tile grid kept in a comment right below it in `index.html`.
2. Create a free form endpoint at formspree.io or web3forms.com and paste it into the form's `action`.
3. Replace the testimonial, prices, and turnaround placeholders, or delete those blocks.
4. Swap `about.jpg` for a photo of you.
5. Delete the `noindex` meta tag in `<head>` so search engines can find the site.
6. Turn on GitHub Pages (Settings, Pages, deploy from `main`, root folder).
7. Add a file named `CNAME` containing `vevorimedia.com`, point DNS at GitHub Pages, then enable "Enforce HTTPS".
