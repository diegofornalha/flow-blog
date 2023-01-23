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
    items:
      - type: FeaturedItem
        title: Use our lab equipment
        titleFr: Use nossos equipamentos de laboratório
        text: >
          Need to use a breadboard, wire strippers or CD-Rs? Need to use an
          Altera DE2 Board or an oscilloscope for a project? We got your back.
        actions: []
        styles:
          self:
            textAlign: left
        featuredIcon: circuit
        isIcon: true
        featuredImage:
          type: ImageBlock
          url: /images/profile.svg
          altText: coflow-perfil
          caption: coflow-perfil
          width: 300
          height: 300
          elementId: ''
      - type: FeaturedItem
        title: Get homework help
        titleFr: Obtenha ajuda com sua lição de casa
        text: >
          Need to study with your friends in a quiet environment to prepare for
          your midterm? Our office is the perfect place for that.
        actions: []
        styles:
          self:
            textAlign: left
        isIcon: true
        featuredImage:
          type: ImageBlock
          url: /images/video-play.svg
          altText: coflow-video
          caption: coflow-video
          width: 300
          height: 300
          elementId: ''
        featuredIcon: youtube
      - type: FeaturedItem
        title: Borrow textbooks
        titleFr: Livros didáticos emprestados
        text: >
          Need to borrow a textbook for one of your courses? Take advantage of
          our carefully curated selection of EECS textbooks at no cost.
        actions: []
        styles:
          self:
            textAlign: left
        featuredImage:
          type: ImageBlock
          url: /images/books.svg
          altText: Textbooks illustration
          caption: Caption of the image
          elementId: ''
        featuredIcon: books
        isIcon: true
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
  - type: FeaturedItemsSection
    colors: colors-b
    elementId: ''
    title: Grants
    titleFr: Concessões
    subtitle: ''
    subtitleFr: ''
    items:
      - type: FeaturedItem
        elementId: ''
        title: BootCamp
        titleFr: BootCamp
        subtitleFr: '23/11/2022, 18:00 - 20:00'
        isIcon: false
        featuredImage:
          type: ImageBlock
          url: /images/ceg-hangout.jpeg
          altText: Spectroscopy Seminar Poster
        featuredIcon:
          label: Apple
          value: apple
        actions:
          - type: Button
            label: Learn More
            altText: Learn More
            url: 'https://www.instagram.com/p/Ck6xk_Ou7m6/'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
      - type: FeaturedItem
        elementId: ''
        title: Conteúdo
        titleFr: Conteúdo
        subtitle: ''
        subtitleFr: ''
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        textFr: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        isIcon: false
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
        featuredIcon: apple
        actions: []
        styles:
          self:
            textAlign: left
    actions: []
    columns: 2
    spacingX: 40
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        margin:
          - mb-0
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
