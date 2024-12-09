---
title: Home
slug: /
sections:
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
      text: احصل عليه الان
      color: text-dark
      type: TitleBlock
    subtitle: اجراءات ميسرة وموافقة فورية
    text: |
      تطبق الشروط والاحكام 
    actions:
      - label: للتواصل
        url: 'https://wa.me/+96565657912'
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
        showIcon: false
      - type: Button
        label: اطلب الآن
        altText: ''
        url: 'https://wa.me/+96565657912'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      url: /images/new.jpg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: يمكنك الآن الطلب عبر
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items: []
    actions:
      - type: Button
        label: اطلب الآن
        url: 'https://wa.me/+96565657912'
        icon: arrowRight
        iconPosition: right
        style: primary
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
