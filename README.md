# Hosting test - GitHub Pages with official Docker image

![Build and deploy](https://github.com/jmooring/hosting-github-pages-official-docker-image/actions/workflows/hugo.yaml/badge.svg)

This is a test of hosting a Hugo project on GitHub Pages using the official Docker image to ensure a fast and reproducible build environment.

Unlike standard workflows that install binaries at runtime, this repository uses the official Docker image ghcr.io/gohugoio/hugo. The workflow:

- Includes Git, Go, Dart Sass, and Node.js pre-installed in the image
- Uses a persistent cache for downloaded modules and processed images

Available tags are listed on the official Hugo [container registry][].

All components are imported from the [`jmooring/hugo-module-feature-test`][] module. See its [README][] file for details.

[README]: https://github.com/jmooring/hugo-module-feature-test?tab=readme-ov-file#readme
[`jmooring/hugo-module-feature-test`]: https://github.com/jmooring/hugo-module-feature-test
[container registry]: https://github.com/gohugoio/hugo/pkgs/container/hugo
