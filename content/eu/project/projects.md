---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 1

title: ''
subtitle: ''


content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how much pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  # Filter on criteria
  filters:
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filters:
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
  
  filter_default: 

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Ecology
    tag: Eko
  - name: Fisio
    tag: Fisio
  - name: Other
    tag: Other

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: 2

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 1

  # For Showcase view, flip alternate rows?
  flip_alt_rows: true
---
