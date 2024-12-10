---
# To design the details of this section
title: News & Events
date: 2024-08-03
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    id: news
    content:
      title: News
      filters:
        folders:
          - news
    design:
      view: article-grid
      # fill_image: false
      columns: 3
  - block: collection
    id: event
    content:
      title: Events
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 2
---
