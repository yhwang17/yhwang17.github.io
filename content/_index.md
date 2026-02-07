---
# Leave the homepage title empty to use the site title
title:
date: 2025-09-21
type: landing

sections:
  - block: hero
    content:
      title: |
        Wang
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wang Research Group** bridges the worlds of AI and the natural sciences. We build and apply computational tools to uncover the laws of biomolecules.
  
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
      title: Latest Preprints
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
      subtitle: ''
      text: |
        <div class="row align-items-center">
          <div class="col-md-8">
            <img src="/images/group-photo.png" alt="Wang Research Group" style="width: 100%; border-radius: 8px;" />
          </div>
          <div class="col-md-4 d-flex justify-content-center justify-content-md-end">
            <ul class="cta-group">
              <li><a href="./people/" class="btn btn-primary px-3 py-3">Meet the team →</a></li>
            </ul>
          </div>
        </div>
    design:
      columns: '1'
---
