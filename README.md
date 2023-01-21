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

---------

## Using the theme

The theme is quite easy to use if you're familiar with Jekyll. The following collections are implemented:
1. **Speakers**: Curate a [speaker list like this one](speakers) from a set of markdown files, one per speaker. Crops and displays images if available. Adds a short bio. See files in the `_speakers` directory for examples.
2. **Organizers**: Curate an organizer list from a set of markdown files, one per organizer. See files in the `_organizers` directory for examples.
3. **Schedule**: Curate a [schedule like this](schedule) from a set of markdown files, one per event (talk, panel, break, etc.). See files in the `_schedule` directory for examples. Schedule items are sorted by a `sequence_id` attribute.
4. **Papers**: Curate a [list of papers like this](papers) from a bunch of markdown files, one per paper. See files in the `_papers` directory for examples. Papers are sorted by a `sequence_id` attribute if specifed (else they are listed alphabetically).

> **NOTE:** The best way to use these is to turn feature on or off by editing the `collections` attribute in `_config.yml`.

If you experience issues or have cool features to add, feel free to [fork this template]().


### Adding a speaker

To add a speaker, simply create a copy of `_speakers/janedoe.md`, rename it, and edit the attributes of the speaker. Please read the comments in the markdown file; they describe the function of each attribute.


### Adding an organizer

To add an organizer, simply create a copy of `_organizers/organizerjanedoe.md`, rename it, and edit the attributes of the organizer. Please read the comments in the markdown file; they describe the function of each attribute.


### Adding an event to your schedule

To add an event to the workshop schedule, simply create a copy of `_schedule/talk_00_opening.md`, rename it, and edit the attributes of the event. Please read the comments in the markdown file; they describe the function of each attribute.


### Adding a paper to the workshop's proceedings

To add a paper to the workshop's proceedings, simply create a copy of `_schedule/paper_00.md`, rename it and edit the attributes of the paper. Please read the comments in the markdown file; they describe the function of each attribute.
