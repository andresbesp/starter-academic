---

widget: portfolio
headless: true  # This file represents a page section.

weight: 50

# ... Put Your Section Options Here (title etc.) ...
title: En medios
subtitle: ''

content:
  
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
      - project
    # Uncomment below to only show content with specific tags:
#    tags:
#      - Machine Learning
    # Uncomment below to exclude content with specific tags:
#    exclude_tags:
#      - preface    
    # Uncomment below to show specific Hugo Page kinds
    kinds:
      - page
#      - section
  # Choose how many pages you would like to display (0 = all pages)
  count: 2
  # Choose how many pages you would like to offset by
  # Useful if you wish to show the first item in the Featured widget
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: true
  
  

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:


  # Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  # Choose a listing view
  view: 2
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
