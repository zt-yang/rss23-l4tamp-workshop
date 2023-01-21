# RSS 2023 Workshop on Learning for Task and Motion Planning

## Installation

Install [Ruby](https://www.ruby-lang.org/en/downloads/), [Bundler](https://bundler.io/), and Jekyll. For ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv)*).

```
## on macOS, somehow I have to use sudo for `gem`
brew install ruby
brew install rbenv ruby-build
sudo gem install bundler jekyll
```

Serve the website

```bash
$ git clone git@github.com:zt-yang/rss23-l4tamp-workshop.git
$ cd rss23-l4tamp-workshop
$ sudo bundle install
$ bundle exec jekyll serve
## if I want instant update while I make changes to md files
$ sudo bundle exec jekyll serve --incremental --trace
```

## Modify the page

For **Overview** and **Call for papers** and other sections, edit `index.md`.

To add a **Speaker**, add a `_speakers/someone.md` page.

There will be *Schedule* and *Papers* pages after the workshop proposal is accepted.

## Deploy the page

The page should update live on https://zt-yang.github.io/rss23-l4tamp-workshop/ whenever you push to main branch.

The GitHub Action is set up following instructions in https://jekyllrb.com/docs/continuous-integration/github-actions/. You don't have to worry about it.
