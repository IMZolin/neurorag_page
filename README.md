# NeuroRAG project page

Standalone static page for the NeuroRAG paper.

## Run locally

From this directory, run `python3 -m http.server 8000` and open <http://localhost:8000>.

## Deploy with GitHub Pages

The `pages.yml` GitHub Actions workflow publishes this project site on pushes to `main` and when run manually. The repository is <https://github.com/IMZolin/neurorag_page>, and GitHub Pages serves it at <https://imzolin.github.io/neurorag_page/>.

For the first deployment, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. After that, pushes to `main` publish the site automatically.
