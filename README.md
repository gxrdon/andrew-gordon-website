# Andrew Gordon website

Static portfolio site for Andrew Gordon.

## Local development

Serve the repository root with any static web server, for example:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## GitHub Pages

The workflow in `.github/workflows/deploy-pages.yml` deploys the repository root to GitHub Pages whenever `main` changes.

In the repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions**. After the first successful workflow run, the site will be available at:

`https://gxrdon.github.io/andrew-gordon-website/`