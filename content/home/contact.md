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
  email: caozhong@tsinghua.edu.cn
  address:
    street: Tsinghua University
    city: Beijing
    region: CA
    postcode: '94305'
    country: China
    country_code: US
  directions: Lee Shaukee Building A639

design:
  columns: '2'
---
