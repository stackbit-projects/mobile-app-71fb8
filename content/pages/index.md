---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-f
    backgroundWidth: full
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: This Is A Big Hero Headline
    subtitle: This Is Subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: /
        style: secondary
    feature:
      type: ImageBlock
      url: /images/Screen smaller-80dd82ed.png
      altText: Hero section image
    styles:
      self:
        height: screen
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: flex-end
        justifyContent: flex-end
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    backgroundWidth: full
    title: Instantly Boost Your Productivity
    text: >
      ## App Land combines your work and home calendars with all your task
      management tools into one seamless experience controlled by a single app
      that you can use on any device.
    actions: []
    feature:
      type: ImageBlock
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-8
        alignItems: center
        justifyContent: center
        flexDirection: col
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-12
          - mb-4
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-8
      actions:
        justifyContent: flex-start
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
  - elementId: ''
    colors: colors-f
    backgroundWidth: inset
    text: |
      ![](/images/Main%20image-6d88eb54.png)
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-8
          - pb-8
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - elementId: ''
    colors: colors-a
    backgroundWidth: full
    backgroundImage:
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Syncronized Calendar
    subtitle: For true work-life balance
    text: >
      Stop juggling between calendar apps and productivity tools — from now on
      all your appointments and meetings appear in one place.
    actions:
      - type: Button
        label: Learn more
        url: /
        style: secondary
        elementId: hero-main-button
        altText: Learn more
        icon: arrowRight
        showIcon: true
    feature:
      type: ImageBlock
      url: /images/Tiles.svg
      altText: Hero section image
    styles:
      self:
        height: screen
        width: narrow
        margin:
          - mt-12
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-h
    backgroundWidth: inset
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Comprehensive Task List
    subtitle: Always be in control
    text: >
      We all have stuff to do all the time: Work tasks, calls to make, groceries
      to buy and dry cleaning to pick up. Get all your tasks in one place for
      easy management.
    actions:
      - type: Button
        label: Take a look
        url: /
        style: secondary
        elementId: hero-main-button
        altText: Learn more
        showIcon: true
        icon: arrowRight
    feature:
      type: ImageBlock
      url: /images/Frame 3-65db89c1.svg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-24
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: TestimonialsSection
    colors: colors-f
    backgroundWidth: inset
    testimonials:
      - quote: >
          # “Fantastic app for planning your day and future tasks. Works
          perfectly everyday!”
        name: Alyvia Cope
        title: Design at Company
        image:
          type: ImageBlock
          url: /images/person-5.png
          altText: Isabelle Parks
        styles:
          self:
            margin:
              - mt-24
              - mb-0
            flexDirection: row
          quote:
            textAlign: left
          name:
            fontWeight: 700
            fontStyle: normal
            textAlign: left
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
      - quote: |
          # “A very useful project management app. I use it every day.”
        name: Travis Guidelines
        title: Manager at Company
        image:
          url: /images/person-6.png
          altText: Product Marketing Manager
        elementId: ''
        styles:
          self:
            margin:
              - mt-24
              - mb-24
            flexDirection: row-reverse
          quote:
            textAlign: left
          name:
            fontWeight: 700
            fontStyle: normal
            textAlign: left
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-36
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
  - elementId: ''
    variant: variant-c
    colors: colors-a
    backgroundWidth: full
    title: Latest news
    subtitle: Featured blog posts section example
    actions:
      - type: Button
        label: View all
        url: /
        style: secondary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPostsSection
---
