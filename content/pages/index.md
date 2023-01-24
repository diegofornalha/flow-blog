---
title: Home
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: full
        padding:
          - pt-0
          - pb-0
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-b
    elementId: ''
    title: Meet our Blog
    titleFr: Conheça nosso Blog
    subtitle: All about Flow Blockchain
    subtitleFr: Tudo sobre Flow Blockchain
    items: []
    actions:
      - type: Button
        label: Most Recent Posts
        altText: Postagens Mais Recentes
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    columns: 3
    spacingX: 32
    spacingY: 32
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: BreadcrumbsSection
    colors: colors-d
    elementId: ''
    title: About Navigation Links
    navLinks: []
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
  - type: FeaturedItemsSection
    colors: colors-d
    elementId: ''
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Faster
        actions: []
        styles:
          self:
            textAlign: left
        featuredImage:
          type: ImageBlock
          url: /images/browser.svg
          altText: discord
          caption: discord
          width: 400
          height: 400
          elementId: ''
      - type: FeaturedItem
        actions: []
        styles:
          self:
            textAlign: left
        featuredImage:
          type: ImageBlock
          url: /images/certificate-medal.svg
          altText: Cursos
          caption: Cursos
          width: 600
          height: 600
          elementId: ''
      - type: FeaturedItem
        actions: []
        styles:
          self:
            textAlign: left
        featuredImage:
          type: ImageBlock
          url: /images/groups.svg
          altText: altText of the image
          caption: Caption of the image
          width: 500
          height: 500
          elementId: ''
    actions: []
    columns: 3
    spacingX: 16
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeatureHighlightSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Check out our gallery
    titleFr: Visite nossa galeria de fotos
    subtitle: ''
    text: |
      Visit our gallery to see photos of events we have hosted in the past.
    textFr: |
      Visite nossa galeria para ver fotos de eventos que já realizamos.
    actions:
      - type: Button
        label: Gallery
        showIcon: true
        icon: arrowRight
        style: primary
        url: 'https://flow.coflow.com.br'
    backgroundImage:
      type: ImageBlock
      url: /images/gridgallery.png
      backgroundSize: cover
      backgroundPosition: center
      opacity: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-72
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: center
  - type: CtaSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Get in touch
    titleFr: Contactez-nous
    text: >
      Got a question? Event suggestions? Feedback? We want to hear it! Send us a
      message and we will get back to you as soon as we can.
    textFr: >
      Vous avez une question ? Des suggestions d'événements ? Des commentaires ?
      Nous voulons les entendre ! Envoyez-nous un message et nous vous
      répondrons dès que possible.
    actions:
      - type: Button
        label: Contact
        showIcon: true
        icon: arrowRight
        url: 'mailto:communications@ieeeuottawa.ca'
        style: primary
    backgroundImage: null
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
addTitleSuffix: true
metaTags:
  - type: MetaTag
    property: 'og:type'
    content: website
  - type: MetaTag
    property: 'og:image:alt'
    content: CoFlow Logo
  - type: MetaTag
    property: 'og:url'
    content: 'https://ieeeuottawa.ca/'
  - type: MetaTag
    property: 'og:site_name'
    content: CoFlow
  - type: MetaTag
    property: 'twitter:site'
    content: '@ieeeuottawa'
metaTitle: Powering Your Student Experience
metaDescription: >-
  The CoFlow is the official student branch for the University of Ottawa and the
  official Sub-Association for ELG/CEG/SEG under the Engineering Students
  Society (ESS).
socialImage: /images/LOGO_HALLOWEEN.svg
---
