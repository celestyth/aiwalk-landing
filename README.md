# aiwalk-landing

Static landing page for [aiwalk](https://github.com/celestyth/aiwalk),
deployed via GitHub Pages.

Split out from the main (private) repo so Pages can run on GitHub's
free plan — Pages on a private repository requires a paid plan; this
repo is public and needs no plan upgrade. See aiwalk's
`docs/internal/01_architecture.md` and
`docs/internal/06_operations_runbook.md` for the full deployment
picture.

## Setup

One-time manual step: repo Settings → Pages → Source →
"GitHub Actions". After that, `.github/workflows/deploy-pages.yml`
publishes `index.html` automatically on every push to `main`.
