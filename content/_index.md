---
title: 'Home'
date: 2023-10-24
type: landing
keywords: "guocc, Chuchen Guo, Guo Chuchen, 郭楚臣, ASDN, PGD, PointInDI"
sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: working
    content:
      title: Working
      text: |
        I am currently exploring the field of 3D reconstruction and actively experimenting with related approaches.
    design:
      columns: 1
      spacing:
        padding: ['3rem', 0, '3rem', 0]
  - block: collection
    id: preprints
    content:
      title: Preprints
      text: ""
      filters:
        folders:
          - preprint
        exclude_featured: false
    design:
      view: card
      columns: 1
      spacing:
        padding: ['3rem', 0, '1rem', 0]
  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: card
      columns: 1
      spacing:
        padding: ['3rem', 0, '3rem', 0]
---

<div aria-hidden="true" style="position:absolute;left:-9999px;top:auto;width:1px;height:1px;overflow:hidden;">
  guocc Chuchen Guo Guo Chuchen 郭楚臣 ASDN PGD
</div>
