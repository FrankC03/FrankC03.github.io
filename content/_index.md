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
  - block: bio
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: 202411051548231.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: research
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: projects
    content:
      title: Projects
      username: admin
  - block: awrds
    content:
      title: Awards
      username: admin
  - block: sks
    content:
      title: Skills & Hobbies
      username: admin
---
