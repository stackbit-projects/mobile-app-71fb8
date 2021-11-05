---
title: About us
sections:
  - elementId: ''
    colors: colors-a
    backgroundWidth: full
    title: What's our deal you ask?
    testimonials:
      - quote: >
          # We made this really great app, and we can't wait for you to use it
          and tell us what you think
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: col
          quote:
            textAlign: left
          name:
            fontWeight: 400
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
        alignItems: left
        justifyContent: left
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
    type: TestimonialsSection
  - elementId: ''
    colors: colors-f
    backgroundWidth: inset
    text: |
      ![](/images/About%20header.png)
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-0
          - pb-0
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - elementId: ''
    colors: colors-a
    backgroundWidth: inset
    title: About
    text: >
      # We are a team of productivity nuts that love to get stuff done without
      the stress of time management. We work together to optimize workflows,
      understand use cases and set up our app to be the most productive and
      useful tool for us, internally, and for you.


      # Work Life Balance


      # Our goal is for work and life to be controlled in one place, to help you
      maintain a zen state of mind.


      > # "Tasks and deadlines should not control our time. We should control
      what when to pay attention to which task." -- Lorinda Mamo, Designer


      # With App Land, we strive to make it clear and easy to follow a healthy
      routine of work effectiveness, collaboration, and also family time and
      social events.


      # We value your YOU time


      # Our team understands that life is a marathon, and it's super important
      to make sure you take care of YOU and your needs. This is why we try to
      remind our users to take time off, reward themselves after a job well
      done, and put down the phone every once in a while when there's nowhere
      you have to be, or nothing you need to do.
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-12
        alignItems: center
        justifyContent: flex-start
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
    type: TextSection
  - elementId: contact-form
    colors: colors-c
    backgroundWidth: full
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Contact form image
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
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
    action: /.netlify/functions/submission_created
    type: ContactSection
layout: PageLayout
---
