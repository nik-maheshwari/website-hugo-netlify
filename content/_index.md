---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-09-03
type: landing

design:
  # Default section spacing
  spacing: "4rem"
  background:
    # Choose a color such as from https://html-color-codes.info
    color: 'white'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download my CV
        url: uploads/resume.pdf
      css_class: system #dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  # - block: resume-experience
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin
  #     text: ""
  #   design:
  #     is_education_first: false
  #     columns: 2 # Or '2' if you want a two-column layout
  #     text_align: center # This might center text within the block
  # - block: collection
  #   id: post
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: testimonial
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

---
