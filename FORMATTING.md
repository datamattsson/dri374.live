# Legend for Minimal Mistakes content

This is merely the notes of the site author. Disregard.

## Global 

### Global variables 

- https://jekyllrb.com/docs/variables/ 

### Useful things
- https://mmistakes.github.io/minimal-mistakes/docs/helpers/
- https://mmistakes.github.io/minimal-mistakes/docs/utility-classes/
- https://www.markdownguide.org/tools/jekyll/

### Local Variables

YAML Front Matter:

```yaml
foobar: barfoo
```

`{{ page.foobar }}` renders as barfoo.


## Posts

Put new markdown in `YYYY-MM-DD-sensible-name.md` in `_posts`.

YAML Front Matter keys that matter (use as template).

```yaml
---
title: This is your title.
# Mandatory for dri374.live
#tags:
#- pinball
#- shmup
#- arcade
#- league
#- tournaments
#- events
#- opinions
#- news
#header:
#  teaser: /assets/images/teaser-600x400.png
#  og_image: /assets/images/og-1200x630.png
#  image: /assets/images/unsplash-image-1280xN.jpg
#  image_description: "A description of the image"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
# These are header overlay options
#  overlay_image: header image rules
#  overlay_filter: Color/opacity to overlay on top of the header image. Example: 0.5, rgba(255, 0, 0, 0.5) or linear-gradient.
#  show_overlay_excerpt: false # true by default
#  excerpt: Auto-generated page excerpt is added to the overlay text or can be overridden.
#  tagline: Overrides page excerpt. Useful when header text needs to be different from excerpt in archive views.
#  actions: # A button
#  - label: foo
#  - url: https://google.com 
#  overlay_color: "#333" # If you skip the overlay_image.
#  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
#  overlay_filter: rgba(255, 0, 0, 0.5)
#  overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
#  sidebar:
#  - title: "Title"
#    image: http://placehold.it/350x250
#    image_alt: "image"
#    text: "Some text here."
#  - title: "Another Title"
#    text: "More text here."

# These are all true by default _config.yml

#author_profile: false
#read_time: false
#comments: false
#share: false
#related: false

# Reminders
#layout: no <-- No matter how much Google begs, MM does not use layouts for posts

# Advanced forward facing
#permalink: /holyshite/this/needs/its/own/url
#published: false
#date: YYYY-MM-DD HH:MM:SS +/-TTTT (H:M:S TTTT is optional)
#last_modified_at: 2017-10-26T15:12:19-04:00

---

My content, oh my, pinball!
```

## Pages

TBD

## Landings

TBD
