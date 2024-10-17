---
title: Home
slug: /
sections:
  - subtitle: ''
    text: |+
      <div style="text-align: center">[CONTACT US](google.com)</div>

    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col-reverse
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
    media:
      type: ImageBlock
      url: /images/tdx-logo-test-white.png
      altText: Image alt text placeholder
      elementId: ''
      styles:
        self:
          borderRadius: medium
          margin:
            - mt-0
            - ml-0
            - mr-0
            - mb-0
          padding:
            - pt-10
            - pl-10
            - pb-10
            - pr-10
          borderWidth: 0
  - type: GenericSection
    title:
      type: TitleBlock
      text: Business Consulting
      color: text-dark
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
