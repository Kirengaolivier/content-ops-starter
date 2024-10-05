---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: A Full-Stack Developer
      color: text-neutral
      type: TitleBlock
    subtitle: ''
    text: >
      I'm **Olivier Kirenga**, A Full-Stack Developer, Website Developer, 
      Mobile Software/Apps Developer & USSD Developer
    actions:
      - label: ABOUT ME
        altText: ''
        url: /
        showIcon: false
        icon: chevronBigRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    media:
      url: /images/1.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
      styles:
        self:
          fontWeight: 700
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
  - type: FeaturedItemsSection
    title:
      text: Who am I ?
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: "I'm Olivier Kirenga, a software developer based in Rwanda and I'm currently a graduate at\_Rwanda Polytechnic / HUYE College. I'm a full stack developer who has every knowledge required to work on both application ends. I have serious passion for UI effects, animations and creating intuitive, dynamic user experiences."
    items:
      - type: FeaturedItem
        title: ''
        subtitle: ''
        image:
          type: ImageBlock
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
    actions:
      - label: Contact Me Now
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    badge:
      label: ABOUT ME
      color: text-neutral
      styles:
        self:
          textAlign: center
          fontWeight: 700
      type: Badge
    elementId: ''
    variant: two-col-grid
    colors: bg-light-fg-dark
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
      text: Full-Stack Developer
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >+
      A Full-Stack Developer, Website Developer,  Mobile Software/Apps Developer
      & USSD Developer

    actions:
      - label: Whatsapp Me Now
        url: >-
          https://wa.me/250788933222?text=Hey,%20Can%20I%20get%20more%20information%20on%20this
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/me.jpg
      altText: me
      type: ImageBlock
    badge:
      label: MAKIng your desires real
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title:
      text: My Recent Work
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: "Here are a few design projects I've worked on recently. Want to see more?\_Email me."
    items:
      - title: Ngurira
        tagline: ''
        subtitle: ''
        text: >
          A project that has the aim of connecting farmers and buyers in order
          to balance prices across the country.
        image:
          url: /images/Ngurira.png
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Abroadcorner Ltd
        tagline: ''
        subtitle: ''
        text: >
          Welcome to ABROADCORNER, your trusted visa consultation agency located
          in Kigali, Rwanda. Since our founding in 2019, we have been dedicated
          to guiding individuals through the complexities of visa applications
          and ensuring a smooth, stress-free process for our clients.
        image:
          url: /images/abroad.png
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Smart Door Connect
        tagline: ''
        subtitle: ''
        text: >
          A smart door solution that allows you to open a door remotely using
          your smart phone.
        image:
          url: /images/door.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - title:
      text: ''
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      You want your project to get into action from ideas to a final product,
      just send me a message and I will be glad to help you cover your dreams.


      Feel free to let me know any of your feelings, ideas or suggestions, I
      will be there to respond as quick as possible.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - type: TextFormControl
          name: address
          label: Address
          hideLabel: true
          placeholder: Your address
          isRequired: true
          width: full
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
          isRequired: true
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
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
isDraft: true
---
