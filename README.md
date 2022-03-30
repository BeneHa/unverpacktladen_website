# Unverpackt store Munich north webpage

The webpage of our unverpackt store. Created in Jekyll based on the [agency theme](https://startbootstrap.com/theme/agency).

Website hosted at [unverpackt-mucnord.de](https://www.unverpackt-mucnord.de).

Basend on the [Jekyll agency theme](https://github.com/raviriley/agency-jekyll-theme).

## Setup with Docker

**Prerequisites**:
To use the setup with Docker, Docker and Docker Compose needs to be installed. For detailed information see [Get Docker](https://docs.docker.com/get-docker/) and [Install Docker Compose](https://docs.docker.com/compose/install/).

To install all dependencies for the Jekyll server run `docker-compose run jekyll bundle install` in root directory. This will create a `vendor/bundle` folder, containing all dependencies.

To run the server, start the container with `docker-compose up`.
