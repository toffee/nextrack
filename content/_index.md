---
title: Welcome to Hinode!
description: A clean documentation and blog theme for your Hugo site based on Bootstrap 5.
content_blocks:
  - _bookshop_name: hero
    heading:
      title: Welcome to Hinode!
      content: |-
        A clean documentation and blog theme for your Hugo site based on Bootstrap 5.
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/sunrise.jpg
      ratio: 16x9
    width: 8
    links:
      - title: Getting started
        url: https://gethinode.com/docs
        icon: fas chevron-right
    orientation: horizontal
    justify: center
  - _bookshop_name: articles
    heading:
      title: Latest Updates       # Replaces root-level 'title'
    input:
      section: posts              # Replaces root-level 'section'
      max: 3                    # Replaces 'count' (Hinode uses max)
    more:
      title: View all posts       # Replaces root-level 'button'
      url: /posts/
---
