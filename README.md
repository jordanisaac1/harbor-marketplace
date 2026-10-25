# Harbor marketplace

The signed app catalog for [Harbor](https://jordanisaac1.github.io/harbor-marketplace/),
served by GitHub Pages. Everything here is written by `harbor publish`; don't edit it by hand.

- `index.json` + `index.json.sig` — the catalog, signed with the publisher key.
- `apps/<id>/<version>.harbor` — signed app bundles, plus each app's icon and README.
- `harbor/latest.json` — Harbor's own update manifest. The app downloads live in this repo's Releases.
- `index.html` — the landing page.
