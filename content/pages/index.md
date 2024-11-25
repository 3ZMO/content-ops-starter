---
title: Home
slug: /
sections:
  - type: FeaturedItemsSection
    title:
      text: '3ZMO Holdings, LLC'
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 'Useful, Productive, and Fun Applications'
    items:
      - type: FeaturedItem
        title: Ai
        subtitle: Integration
        text: >
          Leveraging the power of Ai to create powerful and enhanced
          experiences.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Micro SaaS
        subtitle: Portfolio
        text: >
          Building useful tools and services for unique and specific populations
          of users.
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Domain
        subtitle: Properties
        text: >
          Managing a large portfolio of high value domains in a variety of
          industries.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      text: Imagine Apps that are more personal
      color: text-dark
      type: TitleBlock
    subtitle: ...your friend
    text: >
      When Apps become your personal friend and partner, helping you succeed in
      life and in business.
    actions: []
    media:
      url: /images/heropic2DropShadow.png
      altText: Unblock your imagination
      elementId: ''
      type: ImageBlock
    badge:
      label: '[Rapid Evolution]'
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - subtitle: This Could Be Your Domain
    images:
      - url: /images/Drinks.Cool.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/TeenVote.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/grabcool.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/InstaVote.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/million.cool.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/EverVegan.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/ClickBit.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-neutral-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: false
    showAuthor: false
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
    showExcerpt: false
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Make the Box
      color: text-dark
      type: TitleBlock
    subtitle: Sometimes...
    text: >
      ...instead of working inside or outside of the box, you have to flatten
      the box and remake it yourself.
    actions:
      - label: Make a Box
        url: /makebox
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/Cubes1b.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: '[Innovation]'
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Reach Out
      color: text-dark
      type: TitleBlock
    subtitle: We would love to hear from you
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-neutral-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
