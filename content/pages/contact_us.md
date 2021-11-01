---
title: Contact us
sections:
  - type: HeroSection
    title: Contact us
    text: >-
      Fill out the form below and we will get in touch within 1 business day.
      Various versions have evolved over the years, sometimes by accident,
      sometimes on purpose (injected humour and the like).
    feature:
      type: FormBlock
      action: /.netlify/functions/submission_created
      elementId: contact-form
      submitLabel: Contact
      fields:
        - type: TextFormControl
          label: Name
          placeholder: Your name
          width: 1/2
        - type: TextFormControl
          label: Last name
          placeholder: Your last name
          width: 1/2
        - type: EmailFormControl
          label: Email
          placeholder: Your email
          width: full
        - type: CheckboxFormControl
          label: Sign me up to receive updates
          width: full
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
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-c
    backgroundWidth: full
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
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
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
layout: PageLayout
---
