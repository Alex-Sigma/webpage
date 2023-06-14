---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Kontakt
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
  email: astakhova.anna1210@gmail.com
  phone: +49 172 2790468
  address:
    street: Reuterweg 51
    city: Frankfurt am Main
    region: Hessen
    postcode: '60323'
    country: Deutschland
    country_code: DE
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: 2 Etage
  office_hours:
    - 'Montag   10:00 bis 13:00'
    - 'Mittwoch 10:00 bis 13:00'
    - 'Freitag  10:00 bis 13:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom
    #   link: 'https://zoom.com'

design:
  columns: '2'
---
