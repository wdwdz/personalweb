---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about


- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Google via Signature
      company_logo: org-gc
      company_url: ""
      date_end: "2022-12-26"
      date_start: "2022-05-26"
      description: |2-
          Responsibilities include:

          * Designed and led 7 lab and field studies on key features of wearable and hearable devices (e.g. algorithm, wearing comfort) to help stakeholders determine the product direction.
          * Planned the roadmap with a series of studies on watch form design guidelines to inform next generation product engineering and design.
      title: UX Researcher
    - company: Alibaba
      company_logo: org-x
      company_url: ""
      date_end: "2021-09-30"
      date_start: "2021-07-30"
      description: |2-
          Responsibilities include:

          * Created & analyzed a competitive comparison experiment (n = 4k+) on price to help leaders determine the price strategy.•Created & analyzed a competitive comparison experiment (n = 4k+) on price to help leaders determine the price strategy.
          * Created & analyzed a NPS survey (n = 3k+) to inform product and business teams.
      title: UX Researcher Intern
    title: Experience

  design:
    columns: "2"
# 
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Academic UXR
      tag: Academic UXR
    - name: Industrial UXR 
      tag: Industrial UXR
    - name: Design
      tag: Design
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
# - block: collection
#   content:
#     filters:
#       exclude_featured: true
#       folders:
#       - publication
    # text: |-
    #   {{% callout note %}}
    #   Quickly discover relevant content by [filtering publications](./publication/).
    #   {{% /callout %}}
  #   title: Recent Publications
  # design:
  #   columns: "2"
  #   view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: Ithaca
      country: United States
      country_code: US
      postcode: "14850"
      region: NY
    #   street: 450 Serra Mall
    # appointment_url: https://calendly.com
    autolink: true
    contact_links:
    # - icon: twitter
    #   icon_pack: fab
    #   link: https://twitter.com/Twitter
    #   name: DM Me
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: wz334@cornell.edu
    # form:
    #   formspree:
    #     id: null
    #   netlify:
    #     captcha: false
    #   provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    phone: 201 360 1957
    subtitle: null
    # text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    #   ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
