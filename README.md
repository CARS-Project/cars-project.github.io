# CARS Project website

This repo contains the [website for the CARS Project](https://cars-project.github.io/).

## Editing the website

The pages of the website are written in Markdown in the [`docs`](docs/) directory and built using [MkDocs](https://www.mkdocs.org/).

Preview the website locally by [installing MkDocs](hthttps://www.mkdocs.org/user-guide/installation/) and running `mkdocs serve`.

To update the live site, push your changes up to this GitHub repo, and the build will run automatically [using a GitHub action](.github/workflows/deploy.yml).
You **do not** need to use deploy command provided by MkDocs.
