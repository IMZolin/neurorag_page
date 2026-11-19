# NeuroRAG project page

Standalone static page for the NeuroRAG paper.

## Run locally

From this directory, run `python3 -m http.server 8000` and open <http://localhost:8000>.

## Deploy with GitHub Pages

The `pages.yml` GitHub Actions workflow publishes this directory on pushes to `main` and when run manually. The personal Pages repository must match the GitHub account name; for `IMZolin`, that repository is `IMZolin.github.io`, and the site URL is <https://imzolin.github.io>.

For the first deployment, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. After that, pushes to `main` publish the site automatically.
