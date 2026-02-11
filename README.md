# Hosting test - GitHub Pages with official Docker image

![Build and deploy](https://github.com/jmooring/hosting-github-pages-official-docker-image/actions/workflows/hugo.yaml/badge.svg)

This is a test of hosting a Hugo site on GitHub Pages using the official Docker image to ensure a fast and reproducible build environment.

Unlike standard workflows that install binaries at runtime, this repository uses the official Docker image ghcr.io/gohugoio/hugo. The workflow:

- Includes Git, Go, Dart Sass, and Node.js pre-installed in the image
- Uses a persistent cache for downloaded modules and processed images

Available tags are listed on the official Hugo [container registry][].

[container registry]: https://github.com/gohugoio/hugo/pkgs/container/hugo
