---
_schema: default
title: About
description: Learn about Prism Studio — a creative digital agency that designs and builds extraordinary web experiences.
pageSections:
  - _component: page-sections/heroes/hero-split
    eyebrow: About Prism Studio
    heading: We believe in the power of design to transform brands
    subtext: >-
      Prism Studio was founded on a simple belief: great digital experiences
      come from the intersection of bold creativity and disciplined craft.


      We are a small, focused team of designers, developers, and strategists
      who care deeply about the web. Every project we take on gets our full
      attention — no assembly lines, no junior handoffs.
    imageSource: /src/assets/images/component-docs/sunset.jpg
    imageAlt: Prism Studio at work
    imageAspectRatio: portrait
    buttonSections: []
    reverse: true
    colorScheme: inherit
    backgroundColor: base
    paddingVertical: 4xl
  - _component: page-sections/features/feature-grid
    eyebrow: Our Values
    heading: The principles that guide everything we build
    subtext: These are not just words on a wall — they shape every decision we make.
    gap: xl
    minItemWidth: 280
    maxItemWidth: 360
    features:
      - title: Craft over shortcuts
        description: >-
          We write clean code, design with intention, and refuse to ship anything
          we would not proudly put our name on.
        iconName: cube
        iconColor: purple
      - title: Performance is non-negotiable
        description: >-
          Every millisecond matters. We build static-first, optimize aggressively,
          and measure everything.
        iconName: bolt
        iconColor: cyan
      - title: Clarity in everything
        description: >-
          From our communication to our code, we believe simplicity is the
          ultimate sophistication.
        iconName: eye
        iconColor: blue
      - title: Partnership, not service
        description: >-
          We do not just take orders. We collaborate deeply to understand your
          goals and push the work further than you imagined.
        iconName: users
        iconColor: green
    colorScheme: inherit
    backgroundColor: surface
    align: center
  - _component: page-sections/info-blocks/faq-section
    heading: Frequently asked questions
    headingLevel: h2
    headingSize: lg
    singleOpen: true
    openFirst: false
    items:
      - title: What kind of projects do you take on?
        contentSections:
          - _component: building-blocks/core-elements/text
            text: >-
              We specialize in brand-new websites, complete redesigns, and
              performance overhauls. We work best with teams who value quality
              and want a true creative partner.
      - title: What technologies do you use?
        contentSections:
          - _component: building-blocks/core-elements/text
            text: >-
              We build primarily with Astro, modern CSS, and vanilla JavaScript.
              For content management, we integrate with CloudCannon for the best
              visual editing experience available.
      - title: How long does a typical project take?
        contentSections:
          - _component: building-blocks/core-elements/text
            text: >-
              Most projects span 6-12 weeks from kickoff to launch, depending on
              scope. We move fast without cutting corners.
      - title: Do you work with startups or enterprises?
        contentSections:
          - _component: building-blocks/core-elements/text
            text: >-
              Both! We have worked with early-stage startups launching their
              first product, and established companies reimagining their digital
              presence. What matters most is shared ambition.
    maxContentWidth: xl
    paddingHorizontal: xl
    paddingVertical: 4xl
    colorScheme: inherit
    backgroundColor: none
  - _component: page-sections/people/team-grid
    heading: The team behind the prism
    headingLevel: h2
    headingSize: lg
    gap: xl
    members:
      - name: Alex Morgan
        title: Creative Director
        image: /src/assets/images/component-docs/profile1.jpg
      - name: Jordan Lee
        title: Lead Engineer
        image: /src/assets/images/component-docs/profile2.jpg
      - name: Sam Rivera
        title: Design Lead
        image: /src/assets/images/component-docs/profile3.jpg
      - name: Casey Wu
        title: Strategy Director
        image: /src/assets/images/component-docs/profile4.jpg
    colorScheme: inherit
    backgroundColor: surface
  - _component: page-sections/ctas/cta-center
    heading: Let us build something remarkable together
    subtext: >-
      Whether you have a clear vision or just a spark of an idea, we would love to
      hear from you. Every great project starts with a conversation.
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Start a Conversation
        hideText: false
        link: /
        iconName: ''
        iconPosition: before
        variant: primary
        size: md
    colorScheme: dark
    backgroundColor: surface
    rounded: false
---
