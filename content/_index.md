---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV (PDF)
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research Overview'
      subtitle: ''
      text: |-
        I am an Assistant Professor in the Department of Mathematics at National Institute of Technology Rourkela.

        My research focuses on randomized neural networks (RVFL, SCN), extreme learning machines (ELM), and efficient numerical optimization for machine learning.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publication
          - publications
        exclude_featured: false
    design:
      view: citation
---
