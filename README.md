# push-docker-to-digitalocean-with-gh-action
This repository contains sample Docker image and GitHub Actions workflow for pushing an image to DigitalOcean container registry.


## Building
Run `docker build -t sample/my-page .`.

## Running
Run `docker run -it --rm -p 9999:80 --name my-website sample/my-page` and open http://localhost:9999/hello.html
