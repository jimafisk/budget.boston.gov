---
layout: chapters
title: Test Full Feature Analysis Card
permalink: /test-fa-permalink
card:
  title: Test FA Card Title
  body: Test FA Card Body
  image: /_source/fy19_recommended/img/test.png
  link: /test-fa-card-link
components:
  - breadcrumbs:
      current: Test FA
      links:
        - title: Home
          url: /
        - local: true
          title: Featured Analysis
          url: /featured-analysis
      published: '2018-03-27'
    fields:
      - label: Published
        name: published
        widget: date
      - fields:
          - label: Title
            name: title
            widget: string
          - label: URL
            name: url
            widget: string
          - default: false
            label: Local URL
            name: local
            widget: boolean
        label: Links
        label_singular: link
        name: links
        widget: list
      - label: Current
        name: current
        widget: string
    label: Breadcrumbs
    name: breadcrumbs
    widget: object
  - fields:
      - label: Title
        name: title
        widget: string
      - label: Short Description
        name: short_desc
        widget: string
      - label: Description
        name: description
        widget: markdown
      - default: false
        label: Sidebar Menu
        name: sidebar_menu
        widget: boolean
    intro:
      description: This is the longer description for the intro component
      short_desc: 'This is the intro short description '
      sidebar_menu: true
      title: Intro Title
    label: Intro
    name: intro
    widget: object
  - fields:
      - label: Title
        name: title
        widget: string
      - label: Body
        name: body
        widget: markdown
      - label: Right Image
        name: right_image
        widget: image
    label: Text Block
    name: text_block
    text_block:
      title: Introduction
      body: >-
        At the time Mayor Walsh took office, the City of Boston had successfully
        weathered the storms of previous recessions. However, several major
        revenue sources never fully recovered, cost pressures continued to grow,
        and deferred investments persisted across City government. In its first
        two years, the administration has systematically engaged in independent
        operational reviews and other planning efforts aimed at making
        government more efficient in order to address areas needing renewed
        attention.
      right_image: /_source/fy19_recommended/img/recommended-expenditures.png
    widget: object
  - fields:
      - label: Title
        name: title
        widget: string
      - label: Description
        name: desc
        widget: string
      - fields:
          - label: Text
            name: text
            widget: string
          - label: URL
            name: url
            widget: string
        label: Link
        name: link
        widget: object
      - label: Image Source
        name: src
        widget: image
      - label: Alternative Text
        name: alt
        widget: string
    label: Spanning Image
    name: spanning_image
    spanning_image:
      alt: alt text for spanning image
      desc: Spanning Image Description
      link:
        text: Spanning Image Link
        url: /fake-spanning-image-link
      src: /_source/fy19_recommended/img/students-on-a-computer.jpg
      title: Spanning Image Title
    widget: object
---
This is the body field (to be removed)
