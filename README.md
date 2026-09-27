# Chetan Kushwaha — Portfolio

A responsive, static portfolio site for GitHub Pages. It uses no build step.

The original version is in the repository root. An alternate version featuring a professionally edited portrait is available in [`with-photo/`](with-photo/).

## Preview locally

Open `index.html` in a browser, or run a simple static server from this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Push this repository to GitHub with the default branch named `main`.
2. In **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**.
3. Push to `main`; the workflow in `.github/workflows/deploy.yml` publishes the site.

The page content is in `index.html`; visual styles are in `styles.css`.
