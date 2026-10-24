# nofeed-config

GitHub Pages site for the NoFeed iOS app: `filters.json` (remote filter rules, fetched on launch), support page (`index.html`), `privacy.html`, `terms.html`.

Pages is published from the `gh-pages` branch (enabled automatically when the branch was pushed; the repo API had no token to switch the source). `main` and `gh-pages` carry the same files: push every change to both (`git push origin main && git push origin main:gh-pages`), or switch Settings → Pages → Source to `main` once and drop `gh-pages`.
