+++
title = "blog --init"
description = "How this blog is created, built, and deployed."
date = 2022-05-27

[taxonomies]
categories=["personal"]
tags=["meta"]
+++

# 0th Post

I am a blog to track personal learning and future projects. The site uses [Zola](https://www.getzola.org/) as a static site generator (SSG) with the [zerm](https://github.com/ejmg/zerm) theme made by [ejmg](https://github.com/ejmg). It uses [Zola Deploy Action](https://github.com/shalzz/zola-deploy-action) to automatically build and deploy the site on GitHub Pages. At some point in the future, I'll look at creating a Nix flake environment as demonstrated by [Luke Bentley-Fox](https://lukebentleyfox.net/posts/building-this-blog/), and change the build and deploy steps to use [install-nix-action](https://github.com/cachix/install-nix-action) and [actions-gh-pages](https://github.com/peaceiris/actions-gh-pages) as demonstrated in [jordanisaacs workflow](https://github.com/jordanisaacs/jdisaacs.com/blob/main/.github/workflows/deploy.yml).
