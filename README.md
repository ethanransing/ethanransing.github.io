# ethanransing.github.io

Personal site — static HTML/CSS, no build step. Hosted on GitHub Pages at
<https://ethanransing.github.io/>.

## Local preview

Open `index.html` directly, or serve the folder:

```
python3 -m http.server
```

## Analytics (GoatCounter)

Privacy-friendly, no cookies. **Currently off** — the code is wired up but inert.

To turn it on:

1. Create a free site at <https://www.goatcounter.com/> and choose a code
   (the `CODE` in `CODE.goatcounter.com`).
2. In `index.html`, find `var GC_CODE = '';` and set it to your code,
   e.g. `var GC_CODE = 'ethanransing';`.
3. Commit and push.

You then get, at `https://YOURCODE.goatcounter.com/`:

- **Pageviews** — timestamp, referrer, country, browser/OS, screen size.
- **Link-click events** — Email / GitHub / LinkedIn, plus each publication's and
  project's Site / Paper / Code / Interview links (labelled with the entry title).
- **Raw per-visit CSV export** from the dashboard.

Tip: tag outreach links like `?ref=jane-google` to attribute visits to a person
(shows under **Campaigns**).

## Adding media

Put files in `images/` with the filename the entry expects (see `index.html`).
To add more photos/videos to an entry, drop extra `<img>`/`<video>` tags inside
its `.carousel-track` — the left/right arrows appear automatically.
