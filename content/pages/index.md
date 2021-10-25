---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-e
    backgroundWidth: full
    title: Instantly Boost Your Productivity
    text: >
      App Land combines your work and home calendars with all your task
      management tools into one seamless experience controlled by a single app
      that you can use on any device.
    actions:
      - type: Button
        label: App Store
        url: /
        style: primary
        elementId: hero-main-button
        altText: App Store
      - type: Button
        label: Google Play
        url: /
        style: secondary
        altText: Google Play
    feature:
      type: ImageBlock
      url: /images/appland-home-page.svg
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
          - pt-8
          - pb-8
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
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
    subtitle: Stop switching between calendars and task lists!
  - elementId: ''
    variant: variant-a
    colors: colors-a
    backgroundWidth: full
    title: What's Great About App Land
    subtitle: In a Glance
    actions: []
    posts:
      - content/pages/blog/postlayout-wpzmgdvhw.md
      - content/pages/blog/postlayout-psn8yjf9k.md
      - content/pages/blog/postlayout-x3kgw2akx.md
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
  - elementId: ''
    colors: colors-f
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
        style: primary
        elementId: hero-main-button
        altText: Learn more
    feature:
      type: ImageBlock
      url: /images/feature-1.svg
      altText: Hero section image
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
  - type: TestimonialsSection
    colors: colors-f
    backgroundWidth: full
    testimonials:
      - quote: >
          “Fantastic app for planning your day and future tasks. Works perfectly
          everyday!”
        name: Alyvia Cope
        title: Design at Company
        image:
          type: ImageBlock
          url: /images/person-5.png
          altText: Isabelle Parks
        styles:
          self:
            margin:
              - mt-0
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
          “A very useful project management app. I use it every day.”
        name: Travis Guidelines
        title: Manager at Company
        image:
          url: /images/person-6.png
          altText: Product Marketing Manager
        elementId: ''
        styles:
          self:
            margin:
              - mt-0
              - mb-0
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
  - type: CtaSection
    colors: colors-e
    backgroundWidth: full
    title: Regain Control of your To Dos
    text: >
      Download App Land now and connect with all your calendars, project
      management tools and task lists — it doesn't get easier than this!
    actions:
      - type: Button
        label: App Store
        url: /
        style: primary
        altText: App Store
      - label: Google Play
        altText: Google Play
        url: /
        showIcon: false
        icon: arrowLeft
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    actionsPosition: right
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
        alignItems: flex-end
        justifyContent: flex-start
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    variant: variant-b
    colors: colors-a
    backgroundWidth: full
    title: Productivity blog
    subtitle: What's up
    actions:
      - type: Button
        label: View all
        url: /blog
        style: primary
        altText: View all
    posts:
      - content/pages/blog/post-three.md
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
