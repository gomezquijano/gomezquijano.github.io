---
title: ''
summary: ''
date: 2026-08-03
type: landing

sections:
  # Compact introduction and biography
  - block: markdown
    id: hero
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="mjg-hero-content">

    <p class="mjg-hero-kicker">
            Evolutionary Biologist · Molecular Ecologist · Science Educator
          </p>

     <h1>Dr. María José Gómez Quijano</h1>

    <p class="mjg-hero-summary">
            I study how evolutionary and ecological processes shape adaptation,
            demographic history, and biological invasions in natural plant populations.
          </p>

     <div class="mjg-hero-buttons">
            <a href="#about" class="mjg-button mjg-button-primary">
              About me
            </a>

    <a href="/uploads/Maria_Jose_Gomez_CV.pdf"
               class="mjg-button mjg-button-secondary">
              Download CV
            </a>
          </div>

    </div>

    design:
      columns: '1'
      background:
        image:
          filename: purple-loosestrife-hero.jpg
          filters:
            brightness: 0.55
      spacing:
        padding: [110px, 24px, 110px, 24px]

  # Research overview
  - block: markdown
    id: research
    content:
      title: Research Projects
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
