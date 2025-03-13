---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-03-13
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research examines glacier change in High Mountain Asia. I'm specifically interested in using satellite remote sensing datasets to quantify ice velocity variability in the region. My research uses open-source software tools and I have enjoyed learning about and becoming involved in the open-source scientific software community during my graduate work. 
        
        Please feel free to reach out if you have any questions about my work or would like to chat!
    design:
      columns: '1'
  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

 
---
