---
title: 'Publications'
date: 2024-08-03
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    content:
      username: admin
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
        tag: ''
        category: ''
        publication_type: ''
        author: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Page order: descending (desc) or ascending (asc) date.
      order: desc 
    design:
      # Choose a view for the listings:
      view: citation
      columns: '2'
  - block: collection
    id: conference
    content:
      title: Conferences
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 2
---