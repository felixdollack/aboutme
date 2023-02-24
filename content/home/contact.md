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
  email: felix.dollack@googelmail.com
  #phone: 888 888 88 88
  address:
    street: Gakkuenmae
    city: Nara
    region: Nara-ken
    postcode: '94305'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '35.658330'
    longitude: '139.741460'
  #directions: ''
  #office_hours:
  #  - ''
  #appointment_url: ''
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Linkedin
      link: 'https://www.linkedin.com/in/felix-dollack'
    - icon: twitter
      icon_pack: fab
      name: Follow me
      link: 'https://twitter.com/febendo'
    - icon: skype
      icon_pack: fab
      name: Skype
      link: 'skype:audiophil89?chat'
    - icon: researchgate
      icon_pack: fab
      name: Researchgate
      link: 'https://www.researchgate.net/profile/Felix_Dollack'

    #{icon = "line", icon_pack = "fab", name = "Line Me", link = "https://line.me/felixdollack"},
    #{icon = "comments", icon_pack = "fas", name = "Discuss on Forum", link = "https://discourse.gohugo.io"},

design:
  columns: '2'
---
