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
        Write 1 to 2 paragraphs here summarizing your lab or research agenda. Focus on the core questions you investigate, your methodological approach, and practical applications of your work.

        Prospective students and collaborators should contact me via email.
    design:
      columns: '1'

  # --- JOURNAL ARTICLES ---
  - block: collection
    id: journals
    content:
      title: Peer-Reviewed Journals
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
    design:
      view: citation

  # --- CONFERENCE PROCEEDINGS ---
  - block: collection
    id: conferences
    content:
      title: Conference Proceedings
      text: ''
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
    design:
      view: citation
---
