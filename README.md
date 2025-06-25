# jekyll-walkthrough
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
I'm doing this since **bundler** is already installed and I like step by step:
```
$ gem install jekyll
$ jekyll new my-awesome-site
$ cd my-awesome-site
$ bundle install   → not needed since jekyll already did this
$ jekyll serve
# => Now browse to http://localhost:4000
```
