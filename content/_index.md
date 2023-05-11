---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD
          company: University of Bristol
          company_url: ''
          company_logo: org-UoB
          location: U.K.
          date_start: '2018-10-01'
          date_end: '2022-12-23'
          description: |2-
              Responsibilities include:
              * Behaviour
              * Analysing
              * Modelling
             
        - title: Msc
          company: Antwerp University 
          company_url: ''
          company_logo: org-UA
          location: Belgium
          date_start: '2015-09-23'
          date_end: '2017-07-01'
          description: Correlating calcium dynamics with network activity in an in vitro model of a cortical microcircuitry.
    design:
      columns: '2'

---
