---
# Leave the homepage title empty to use the site title
title: Yerro Research Group
subtitle: Virginia Tech – Civil and Environmental Engineering
date: 2026-01-19
type: landing

sections:
  - block: hero
    content:
      title: |
        Yerro
        Research Group
      #image:
        #filename: welcome.jpg  # Replace with a lab photo or VT image if you want
      text: |
        <br>
       Welcome to the **Yerro Research Group**, led by **Alba Yerro**, Associate Professor at Virginia Tech. We study geotechnical hazards, landslides, tailings dam safety, internal erosion, and soil–water–structure interactions.

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
