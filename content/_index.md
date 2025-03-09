---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Duke Cosmology Group
      image:
        filename: dukecosmo1.png
      text: |
        <br>

        The **Duke Cosmology Group** has been a center of excellence for cosmology research, teaching, and practice since its founding in 2018.

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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: dukecosmo2.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title: Joining the group
      subtitle:
      text: |
        We are always looking for talented students and postdocs to join our group.
        If you are interested in joining as a student, please apply to the [Duke Physics graduate program](https://physics.duke.edu/graduate/prospective-students/admissions).
        If you are interested in joining as a postdoctoral researcher, keep an eye out on the [AAS jobs website](https://aas.org/jobregister?q=Duke).

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
