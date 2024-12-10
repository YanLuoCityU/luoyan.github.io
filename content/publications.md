---
# To design the details of this section
title: ""
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
      # title: Publications
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
# sections:
#   - block: collection
#     content:
#       username: admin
#       title: Publications by Year
#       filters:
#         folders:
#           - publication
#         featured_only: false
#         tag: ''
#         category: ''
#         publication_type: ''
#         author: ''
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a view for the listings:
#       view: citation
#       columns: '2'

#   # Add year-based grouping
#   - block: collection
#     id: publications-by-year
#     content:
#       title: Publications by Year
#       filters:
#         folders:
#           - publication
#       group_by: 'date' # This assumes your publication dates are set properly
#       group_format: 'YYYY' # Group publications by year
#     design:
#       view: citation
#       columns: 1
---