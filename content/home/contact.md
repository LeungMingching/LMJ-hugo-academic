---
# An instance of the Contact widget.
widget: contact

# Activate this widget? true/false
active: false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: liangmingjing@gacrnd.com
  phone: +86 158 1244 9572
  address:
    street: 668 Jinshan Road East, Panyu District
    city: Guangzhou
    region: Guangdong
    postcode: '511434'
    country: China
    country_code: CN
  coordinates:
    latitude: '23.040150185941574'
    longitude: '113.49835123762357'
  directions: Enter Building 1 and go to Xlab on Floor 9
  office_hours:
    - 'Weekday 9:30 to 17:30'
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
  #   - icon: video
  #     icon_pack: fas
  #     name: Zoom Me
  #     link: 'https://zoom.com'

design:
  columns: '2'
---
