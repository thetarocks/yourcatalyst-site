# Your Catalyst — research portfolio

Static Home, Projects and About pages for [yourcatalyst.in](https://yourcatalyst.in/).

Built with HTML, CSS, JavaScript ES modules and SVG. Served by GitHub Pages; no WordPress runtime, application server, cookies or build dependencies. Three live previews run locally in the browser.

## Run locally

```sh
python3 -m http.server 8767
```

Open http://localhost:8767/. The [finance notebook](https://lab.yourcatalyst.in/experiments/) and JoSAA sandbox remain on the lab subdomain.


![Research portfolio](docs/portfolio-desktop.jpg)

## What to inspect

Project cards show a result, data limits, grounding checks and a direct code link. The three featured cards include collapsible architecture and edge-case explanations. The allocation card documents a real assignment-state regression and a source-linked local runtime benchmark; the governance card links archived proposal metadata and the DAO-only SSRN paper. The About page explains the motivation through parallels with politics.

## Source and evidence

Editable portfolio source, Python audits, numerical kernels and CI live in [catalyst-lab](https://github.com/thetarocks/catalyst-lab). This repository publishes its `site/` directory. Update that source first, regenerate with `python scripts/build_portfolio.py`, then copy the static contents here. PDF generation instructions are in the main README.

Results are bounded model examples. Evidence JSON, data limitations, technical notes and the DAO SSRN link are included on the project cards. A passing test suite does not imply complete coverage or a new mathematical proof.

MIT license; see LICENSE.
