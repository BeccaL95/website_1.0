---
title: 
date: 2024-05-22
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your profile text from `authors/admin/_index.md`?
      text: |
        Hey, there! I'm **Rebecca**, a PhD student in Clinical Neuroscience at the University of Duisburg-Essen. My interests include how pain impacts affective and cognitive processes, as well as behavior. In my research I want to utilize neuroimaging and behavioral experiments to explore these topics. Committed to the principles of open scholarship, I ensure my findings are accessible and reproducible. 
        
        Learn more about [me](/about/) or get insights into my [life in academia](/academic-adventures/).
  - block: contact
    id: contact
    content:
      title: Contact
      email: rebecca.lutz@uk-essen.de
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
