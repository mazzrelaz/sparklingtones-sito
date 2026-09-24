# sparklingtones.com

*[Italiano](README.md) · English*

The landing page of [SparklingTones](https://github.com/mazzrelaz/SparklingTones),
the app to control a Positive Grid Spark 2 from the browser.

**Only the showcase is here. The app lives in the other repo**, and stays published at
`mazzrelaz.github.io/SparklingTones/` — this page just sends you there.

## How it's made

HTML files, nothing else: no build step, no dependencies, no requests to third-party
domains. The two fonts (Inter and Space Grotesk, SIL OFL) and the logo are copied from
the app, so the two look like the same thing.

```
index.html    the whole Italian page, style included
privacy.html  the privacy page
en/           the same two pages in English
CNAME         sparklingtones.com — this is the file that tells GitHub Pages
              which domain to answer for
fonts/        Inter and Space Grotesk
icons/        logo and favicon
media/        the video clips — see media/LEGGIMI.md
.nojekyll     tells Pages to serve the files as they are
```

To see it locally just open `index.html` with a double click. The fonts may not load
from `file://` (the browser blocks them, it isn't a fault of the page): to really see
them you need a server, even the dumbest one.

## Publishing

GitHub Pages, `main` branch, root folder. The domain is set in Settings → Pages and
the DNS of `sparklingtones.com` (register.it) points with four `A` records to GitHub's
IPs, plus a `CNAME` for `www`.

## Licence

MIT, Massimo Togni. No affiliation with Positive Grid Inc.
