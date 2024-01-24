---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hi!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          company: Institute for Research in Fundamental Sciences (IPM), School of Cognitive Science
          company_url: 'https://scs.ipm.ac.ir/learningmemlb.jsp'
          company_logo: ipm_logo
          location: Iran
          date_start: '2018-07-01'
          date_end: ''
          description: ''
        - title: Graduate Student Researcher
          company: Centre For Convergent Technologies Research, University of Tehran
          company_url: 'https://utnbic.ir/en'
          company_logo: nbic-logo
          location: Iran
          date_start: '2020-12-01'
          date_end: '2023-04-01'
          description: ''
        - title: Co-Founder and Technical Lead
          company: Cardano Trader
          company_url: 'https://utnbic.ir/en'
          company_logo: cardano-logo
          location: Iran
          date_start: '2019-06-01'
          date_end: '2021-11-01'
          description: ''
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: conference
    content:
      title: Conference Highlights
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: card
      flip_alt_rows: false
---
