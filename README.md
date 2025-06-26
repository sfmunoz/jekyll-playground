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

## Install

Quick-start directly from [Jekyll](https://jekyllrb.com/):
```
$ gem install bundler jekyll
$ jekyll new my-awesome-site
$ cd my-awesome-site
$ bundle exec jekyll serve
# => Now browse to http://localhost:4000
```
**Note**: `bundle exec jekyll serve` is used instead of just `jekyll serve` to make sure the **Gemfile.lock → jekyll** version is used.

## Themes

> https://rubygems.org/ → search 'jekyll-theme'
