---
title: Get in Touch
hide_title: false
sections:
  - section_id: links
    col_number: two
    is_numbered: false
    grid_items:
      - title: Contact me
        image_alt: lorem-ipsum
        actions:
          - url: 'mailto:rlrh1996@gmail.com'
            style: link
            icon: dribbble
            new_window: true
            no_follow: false
            type: action
            label: Email rlrh1996@gmail.com
          - label: Telegram @raynerl
            url: 'https://t.me/raynerl'
            style: link
            icon: dribbble
            new_window: true
            no_follow: false
            type: action
        type: grid_item
      - title: Add me
        image_alt: lorem-ipsum
        actions:
          - label: LinkedIn
            url: 'https://www.linkedin.com/in/raynerlimrh/'
            style: icon
            icon: linkedin
            new_window: true
            no_follow: false
            type: action
          - label: GitHub
            url: 'https://github.com/rlrh'
            style: icon
            icon: github
            new_window: true
            no_follow: false
            type: action
        type: grid_item
    type: section_grid
  - section_id: contact-form
    type: section_form
    content: >
      Hi there! Thank you so much for getting in touch. Please fill the contact
      form below or send me an email at <rlrh1996@gmail.com>.
    form_id: contactForm
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
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
