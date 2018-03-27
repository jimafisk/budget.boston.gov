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
  - fields:
      - label: Grid Title
        name: grid_title
        widget: string
      - fields:
          - label: Title
            name: title
            widget: string
          - label: Body
            name: body
            widget: string
          - label: Image
            name: image
            widget: image
        label: Card
        name: card
        widget: list
      - label: Body
        name: body
        widget: markdown
      - label: Right Image
        name: right_image
        widget: image
    grid:
      card:
        - title: First Card Title
          body: Card body description text
          image: /_source/fy19_recommended/img/card.jpg
        - title: 2nd Card Title
          body: Card body.... test test
          image: /_source/fy19_recommended/img/fa-charter-school-tuition.jpg
        - title: Third and final card in grid
          body: this is the description text for the 3rd card
          image: /_source/fy19_recommended/img/fa-city-services.jpg
      grid_title: Grid Title
    label: Grid
    name: grid
    widget: object
  - fields:
      - label: Title
        name: title
        widget: string
      - fields:
          - label: Name
            name: name
            widget: string
          - label: Link
            name: link
            widget: string
        label: Right Text
        name: right_text
        widget: object
      - fields:
          - fields:
              - label: Column Name
                name: column
                widget: string
              - label: Value
                name: value
                widget: string
            label: Columns
            label_singular: Column
            name: columns
            widget: list
        label: Rows
        label_singular: Row
        name: rows
        widget: list
    label: Table
    name: table
    table:
      right_text:
        link: /right-text-link
        name: Right Text Name
      rows:
        - columns:
            - column: Category
              value: Total revenues
            - column: FY15 Actual
              value: '2,780.42'
            - column: FY16 Actual
              value: '2,883.01'
            - column: FY17 Budget
              value: '2,996.09'
            - column: FY18 Budget
              value: '3,139.79'
        - columns:
            - column: Category
              value: Total expenditures
            - column: FY15 Actual
              value: '2,773.06'
            - column: FY16 Actual
              value: '2,881.09'
            - column: FY17 Budget
              value: '2,996.09'
            - column: FY18 Budget
              value: '3,139.79'
        - columns:
            - column: Category
              value: Test Link
            - column: FY15 Actual
              value: '2773'
            - column: FY16 Actual
              value: '288109'
            - column: FY17 Budget
              value: '90'
            - column: FY18 Budget
              value: '3,139.79'
      title: Table Title
    widget: object
  - fields:
      - label: Column 1
        name: col1
        widget: markdown
      - label: Column 2
        name: col2
        widget: markdown
    label: 2 Column Text
    name: text_col_2
    text_col_2:
      col1: |-
        Text in 2 col

        ![alt text for embedded img](/_source/fy19_recommended/img/test.png)

        Text below the embedded image
      col2: >-
        Unordered list:


        * Donec sodales massa vel leo porttito

        * ondimentum. Ut condimentum commodo quam.

        * Phasellus sed metus eu velit pellentesque


        Ordered list:


        1. Paragraph Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        Aliquam non turpis nibh.

        2. Sed eleifend orci pretium magna tempus vehicula.

        3. Paragraph Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        Aliquam non turpis nibh.

        4. Sed eleifend orci pretium magna tempus vehicula.
    widget: object
  - fields:
      - label: Column 1
        name: col1
        widget: markdown
      - label: Column 2
        name: col2
        widget: markdown
      - label: Column 3
        name: col3
        widget: markdown
    label: 3 Column Text
    name: text_col_3
    text_col_3:
      col1: >-
        Fisrt Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
        non turpis nibh. Sed eleifend orci Ut condimentum commodo quam.
        Phasellus sed metus eu velit pellentesque porta.
      col2: >-
        Second Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
        non turpis nibh. Sed eleifend orci pretium magna tempus vehicula.
        <blockquote>Donec sodales massa vel leo porttitor</blockquote>
        condimentum. Ut condimentum commodo quam. Phasellus sed metus eu velit
        pellentesque porta.
      col3: >-
        Third Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
        non turpis nibh. Sed eleifend orci pretium magna tempus vehicula. Donec
        sodales massa vel leo condimentum. Ut condimentum commodo quam.
        Phasellus sed metus eu velit pellentesque porta.
    widget: object
---
This is the body field (to be removed)
