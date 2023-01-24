---
layout: PageLayout
addTitleSuffix: true
socialImage: /images/Events (1).png
title: Events
sections:
  - type: HeroSection
    colors: colors-e
    elementId: ''
    backgroundSize: full
    title: Events
    titleFr: Eventos
    text: |
      Checkout our upcoming events and our past events!
    textFr: |
      Dê uma olhada em nossos eventos futuros e passados!
    actions: []
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    backgroundImage:
      type: BackgroundImage
      url: /images/Events (1).png
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 20
  - type: FeaturedItemsSection
    colors: colors-d
    elementId: ''
    title: Past Events
    titleFr: Événements passés
    subtitle: Click the button below to view more events.
    items:
      - type: FeaturedItem
        elementId: ''
        title: WIE Fall By-Elections
        titleFr: Elections partielles de l'automne WIE
        subtitle: '11/20/2022, 12:30PM'
        subtitleFr: '20/11/2022, 12:30'
        text: >
          Location:
          [Zoom](https://us06web.zoom.us/j/95068465084?pwd=SjV2aFFoTjF2bHY0UHN6VTEvaWlmUT09)
          or SITE 4026




          If you’re interested in being a part of IEEE WIE uOttawa, join us on
          Sunday, November 20th, 2022 at 12:30 PM in SITE 4026.
        textFr: >
          Lieu:
          [Zoom](https://us06web.zoom.us/j/95068465084?pwd=SjV2aFFoTjF2bHY0UHN6VTEvaWlmUT09)
          & SITE 4026




          Si vous souhaitez faire partie de l'IEEE WIE uOttawa, rejoignez-nous
          le dimanche 20 novembre 2022 à 12h30 au SITE 4026.
        isIcon: false
        featuredImage:
          type: ImageBlock
          url: /images/wie-by-elections.jpeg
          altText: WIE Fall By-Elections Poster
          caption: WIE Fall By-Elections Poster
        featuredIcon: apple
        actions:
          - type: Button
            label: Learn More
            altText: ''
            url: 'https://www.instagram.com/p/CkrZX4JtJXZ/'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        elementId: ''
        title: Microchips & DIps
        titleFr: Microchips & DIps
        subtitleFr: '12/11/2022, 13:00 - 15:00'
        text: >
          Location: STEM 117




          Interested in learning about embedded systems? Sign up for our 3 part
          workshops where we'll be teaching you to how to build and program an
          embedded device from scratch!
        textFr: >
          Lieu: STEM 117




          Vous souhaitez en savoir plus sur les systèmes embarqués ?
          Inscrivez-vous à nos ateliers en 3 parties où nous vous apprendrons à
          construire et programmer un dispositif embarqué à partir de zéro !
        isIcon: false
        featuredImage:
          type: ImageBlock
          url: /images/microchips-and-dips.jpeg
          altText: Microchips & Dips Poster
          caption: Microchips & Dips Poster
        featuredIcon: apple
        actions:
          - type: Button
            label: Learn More
            altText: ''
            url: 'https://www.instagram.com/p/CkjJ5-uuNJw/'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
        styles:
          self:
            textAlign: left
        subtitle: '11/12/2022, 1PM - 3PM'
      - type: FeaturedItem
        elementId: ''
        title: BELE Game Night
        titleFr: Soirée de jeux BELE
        subtitle: '11/10/2022, 5PM - 8PM'
        subtitleFr: '10/11/2022, 17:00- 20:00'
        text: >
          Location: CBY A04




          Join us to get to know your big eng/little engs and some of the women
          on campus who already have your back.
        textFr: >
          Lieu: CBY A04


          Rejoignez-nous pour faire connaissance avec vos big eng/little engs et
          certaines des femmes présentes sur le campus qui vous soutiennent
          déjà.
        isIcon: false
        featuredImage:
          type: ImageBlock
          url: /images/bele-game-night.jpeg
          altText: BELE Game Night Poster
        featuredIcon: apple
        actions:
          - type: Button
            label: Learn More
            altText: ''
            url: 'https://www.instagram.com/p/CkQ3tWeM9YJ/'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
        styles:
          self:
            textAlign: left
    actions:
      - type: Button
        label: More
        altText: ''
        url: 'https://www.facebook.com/ieeeuottawa/events'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    columns: 3
    spacingX: 40
    spacingY: 46
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
    subtitleFr: Cliquez sur le bouton ci-dessous pour voir plus d'événements.
  - type: FeaturedPeopleSection
    colors: colors-e
    elementId: ''
    variant: variant-a
    title: About us
    actions: []
    execs: []
    people:
      - content/data/team/vp-comms.json
      - content/data/team/vice-chair.json
      - content/data/team/chair.json
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
  - type: FeaturedPeopleSection
    colors: colors-e
    elementId: ''
    variant: variant-a
    title: About us
    subtitle: Featured people section example
    actions: []
    execs: []
    people:
      - content/data/team/vp-comms.json
      - content/data/team/vice-chair.json
      - content/data/team/chair.json
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
  - type: FeaturedPeopleSection
    colors: colors-e
    elementId: ''
    variant: variant-a
    title: About us
    subtitle: Featured people section example
    actions: []
    execs: []
    people:
      - content/data/team/vp-comms.json
      - content/data/team/vice-chair.json
      - content/data/team/chair.json
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
metaDescription: Checkout our upcoming events and our past events!
metaTags:
  - type: MetaTag
    property: 'og:type'
    content: website
  - type: MetaTag
    property: 'og:image:alt'
    content: CoFlow Logo
  - type: MetaTag
    property: 'og:url'
    content: 'https://ieeeuottawa.ca/events'
  - type: MetaTag
    property: 'og:site_name'
    content: CoFlow
  - type: MetaTag
    property: 'twitter:site'
    content: '@ieeeuottawa'
metaTitle: Events
---
