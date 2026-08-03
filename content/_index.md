---
title: ''
summary: ''
date: 2026-08-03
type: landing

sections:
  # Compact introduction and biography
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/Maria_Jose_Gomez_CV.pdf
      headings:
        about: About me
        education: Education
        interests: Interests
    design:
      background:
        image:
          filename: background.png
          filters:
            brightness: 0.85
            opacity: 0.25
            blur: 3px
      name:
        size: lg
      avatar:
        size: medium
        shape: circle
      spacing:
        padding: [48px, 0, 32px, 0]

  # Research overview
  - block: markdown
    id: research
    content:
      title: Research
      subtitle: Evolutionary biology across genomic, ecological, and historical scales
      text: |-
        I investigate how evolutionary forces interact with ecological processes to shape the trajectories of natural plant populations. My research combines population genomics, quantitative genetics, field experiments, and historical collections to study local adaptation, demographic history, mating systems, and biological invasions.

        My current research uses temporal population genomics and herbarium collections to reconstruct the introduction, spread, and adaptation of capeweed (*Arctotheca calendula*) across Australia.
    design:
      columns: '1'
      spacing:
        padding: [48px, 0, 48px, 0]

  # Featured publications
  - block: collection
    id: featured-publications
    content:
      title: Featured Publications
      text: Selected research contributions
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
      spacing:
        padding: [48px, 0, 32px, 0]

  # Recent publications
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      archive:
        enable: true
        text: View all publications
        link: /publications/
    design:
      view: citation
      spacing:
        padding: [32px, 0, 48px, 0]
---
