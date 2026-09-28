# Grace Creative Portfolio

A bold, editorial-style personal portfolio for Grace McGlashan &mdash; a second,
more visual take on her [primary portfolio site](https://github.com/gracemcglashan/Grace-PersonalPortfolio).

Built with plain HTML, CSS, and JavaScript (no build step required). Features:

- A full-bleed hero with a large portrait, hand-drawn SVG blobs, and a
  scrolling marquee of skills
- A polaroid-style About section
- A dark, timeline-style Experience section
- An icon-driven Skills section
- Projects & Community cards with generated gradient/SVG cover art
- A bold Contact section with a downloadable resume

## Running locally
Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying
Static site &mdash; deploy for free with GitHub Pages:

1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Under "Build and deployment", set the source to the `main` branch (root).
4. Site publishes at `https://<username>.github.io/<repo-name>/`.
