# Hugo Bootstrap v5 Template

This is a simple Hugo [Bootstrap v5](https://getbootstrap.com/) template, inspired by [hugo-bootstrap](https://github.com/AuthorGithub/hugo-bootstrap) and [hugo-bootstrap-5](https://github.com/NotWoods/hugo-bootstrap-5).


[![Netlify Status]()](https://app.netlify.com/sites/davidelanz-hugo-bootstrap-5/deploys)
[![Linting](https://github.com/Davidelanz/hugo-bootstrap-5/actions/workflows/super-linter.yml/badge.svg)](https://github.com/Davidelanz/hugo-bootstrap-5/actions/workflows/super-linter.yml)

This is a template repository for easily set up a Hugo site with Bootstrap 5 support and locally testing it with Docker

## Usage

1. Install [Docker](https://docs.docker.com/get-docker/)
2. Install [Docker Compose](https://docs.docker.com/compose/install/)
3. Clone this repository
   ```sh
   git clone https://github.com/Davidelanz/hugo-bootstrap-5.git
   ```
4. Run dockerized local webserver with
   ```sh
   cd hugo-bootstrap-5
   docker-compose up
   ```
5. Your site is locally deployed at http://localhost:1313.

You can then start developing your Hugo site in the `/site` folder.

## Production Deployment

You can deploy the site contained in this repository via [netlify](https://docs.netlify.com/).
The `netlify.toml` configuration file takes already care of the build settings.