# jekyll-playground
Reference repository to work and play with [Jekyll](https://jekyllrb.com/)

## References

- [Jekyll](https://jekyllrb.com/)
- [Setting Up Jekyll for GitHub Pages in 60 Seconds](https://youtu.be/oYnBpDuYCgg): I used that for the simple and very basic setup of the repo
  - Files
    - [index.md](index.md)
    - [_config.yml](_config.yml)
    - [_layouts/default.html](_layouts/default.html)
  - Settings → Pages → Build and deployment → Branch=main + root=/
- [Jekyll - Static Site Generator | Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
- Liquid: https://shopify.github.io/liquid/ → https://github.com/Shopify/liquid

## Install

Quick-start directly from [Jekyll](https://jekyllrb.com/):
```
$ gem install bundler jekyll
$ jekyll new my-awesome-site
$ cd my-awesome-site
$ bundle exec jekyll serve --livereload
# => Now browse to http://localhost:4000
```
Details:

- `bundle exec jekyll serve` is used instead of just `jekyll serve` to make sure the **Gemfile.lock → jekyll** version is used.
- `--livereload` is optional: it automatically refreshes the page with each change made to the source files.

## Themes

> https://rubygems.org/ → search 'jekyll-theme'
