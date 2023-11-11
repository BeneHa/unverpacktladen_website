# Rieselbar (Unverpackt store Munich north) webpage

The webpage of our unverpackt store. Created in Jekyll based on the [agency theme](https://startbootstrap.com/theme/agency).

Website hosted at [unverpackt-mucnord.de](https://www.unverpackt-mucnord.de).

Basend on the [Jekyll agency theme](https://github.com/raviriley/agency-jekyll-theme).

## Setup with Docker

docker build . -t jekyll

docker run -p 4000:4000 -v $(pwd):/site jekyll
