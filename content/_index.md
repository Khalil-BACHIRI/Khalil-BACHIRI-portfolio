---
# Leave the homepage title empty to use the site title
title: ""
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    id: bio
    content:
      username: khalil-bachiri
      text: ""
      button:
        text: Download CV
        url: files/cv_khalil_bachiri.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
      columns: 1

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 1
      show-date: false


  - block: markdown
    id: vitæ
    content:
      title: Curriculum vitæ
      text: |
        Below is a detailed summary of my professional experience and academic background.
    design:
      view: article-grid
      columns: 1

---
