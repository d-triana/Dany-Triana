---
# An instance of the Contact widget.
widget: contact

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
  email: dtriana@comunidad.unam.mx
  # phone: 888 888 88 88
  address:
    street: Avenida Circuito Ciudad Universitaria, C.U.
    city: Mexico City
    region: Coyoacan
    postcode: '04510'
    country: Mexico
    country_code: MX
  coordinates:
    latitude: '19.336384061084544'
    longitude: '-99.18865596931076'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 17:00 to 18:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: d_triana
      link: 'https://twitter.com/d_triana'
   # - icon: video
   #   icon_pack: fas
   #   name: Zoom Me
   #   link: 'https://zoom.com'

design:
  columns: '2'
---
