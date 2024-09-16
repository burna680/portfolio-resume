---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: brain.png
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  # - block: collection
  #   id: projects
  #   content:
  #     title: Projects
  #     subtitle: A subtitle
  #     text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  #     # Display content from the `content/post/` folder
  #     filters:
  #       folders:
  #         - project
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     # Choose your content listing view - here we use the `showcase` view
  #     view: card
  #     # For the Showcase view, do you want to flip alternate rows?
  #     flip_alt_rows: true
  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - project
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: showcase
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
