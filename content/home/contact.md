---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 75

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
  email: sfs.southeast@gmail.com
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/SE_SFS'
    - icon: instagram
      icon_pack: fab
      name: Instagram
      link: 'https://www.instagram.com/southeastsfs/'

design:
  columns: '2'
---
