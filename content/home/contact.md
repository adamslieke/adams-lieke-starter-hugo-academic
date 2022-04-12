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
      captcha: true

  # Contact details (edit or remove options as required)
  email: adamslieke@gmail.com
  phone: +31618561316
  address:
    street: achter st. pieter 11G
    city: Utrecht
    postcode: '3512HP'
    country: Nederland
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: contact me
      link: 'https://www.linkedin.com/in/lieke-adams-378a40184/'

design:
  columns: '2'
---
