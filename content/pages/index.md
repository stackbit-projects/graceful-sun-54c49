---
sections:
  - type: hero_section
    title: Raw Treats By Mila
    subtitle: Raw vegan desserts and chocolate
    actions:
      - label: Order
        url: /contact
        style: primary
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    image: images/главная.jpg
    content: |
      *   Organic

      *   Gluten free
  - type: grid_section
    title: Vegan desserts and chocolate
    align: center
    grid_items:
      - image: images/торт.jpg
        image_alt: Logo 1
        image_align: center
        title_align: center
        actions:
          - label: Cakes
            style: primary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
            url: '/cakes '
        actions_align: center
        image_position: top
      - title_align: center
        content_align: center
        actions:
          - label: Mini cakes
            url: /mini-cakes
            style: primary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        actions_align: center
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        type: grid_item
        image: images/пирожки.jpg
      - image: images/сырки.jpg
        image_alt: Logo 2
        image_align: center
        actions:
          - label: Glazzed curds
            style: primary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
            url: /glazet-curds
        actions_align: center
        image_position: top
      - image: images/Mousse dsserts.jpg
        image_alt: Logo 6
        image_align: center
        actions:
          - url: '#'
            style: primary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
            label: Mousse desserts
        actions_align: center
      - image: images/Vegan chocolate.jpg
        image_alt: Logo 7
        image_align: center
        actions:
          - url: '#'
            style: link
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
          - url: '#'
            style: primary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
            label: Vegan chocolate
        actions_align: center
      - image_alt: Logo 8
        image_align: center
        actions:
          - url: '#'
            style: link
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
          - url: '#'
            style: link
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        actions_align: center
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    actions: []
  - type: features_section
    title: Vegan dessert and chocolate
    subtitle: What I do
    features:
      - title: 'Без глютена, животных жиров, белого сахара и сои.'
        actions:
          - label: See Writing Samples
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - actions: []
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - actions: []
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Rewies
    subtitle: What My Clients Say
    grid_items:
      - content: >
          I have been particular about my bday cake since i was 4. Now 40 yrs
          later I still have to have it made to my taste, elegant design and
          barely sweet
        image: images/beige-lavender.jpg
        image_position: left
        image_width: twenty-five
      - content: |
          Thank you raw treats by Mila!

          For such a dilightful treat!
        image: images/smiling-comet.jpg
        image_position: left
        image_width: twenty-five
      - content: |
          *They all taste like mousse cheesecake and they are INCREADIBLE!*
        image: images/majestic-lime.jpg
        image_position: left
        image_width: twenty-five
      - content: |
          Thank you so much Mila Georgiev!

          The cake was talk of the party and we totally enjoyed it!
        image: images/parallel-eggplant.jpg
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
title: Mila Georgiev
---
