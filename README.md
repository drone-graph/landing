# Drone Graph landing page

Standalone static site for [drone-graph](https://github.com/drone-graph/drone-graph). One `index.html`, one `styles.css`, assets under `images/` (copied from the main repo's `docs/images/`).

To preview: open `index.html` directly in a browser, or `python3 -m http.server` from this directory.

To deploy: drop the four files (`index.html`, `styles.css`, `images/`, `README.md`) into any static host — GitHub Pages, Vercel, Netlify, Cloudflare Pages. No build step.

When the README assets in the main repo are updated, copy them over:

```sh
cp ../drone-graph/docs/images/{mission-control,substrate,hierarchy-vs-swarm}.svg ../drone-graph/docs/images/orchestrator-loop.gif images/
```
