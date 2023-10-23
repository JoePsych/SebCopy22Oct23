---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: vien_group_pic.jpeg
    - title: facial Neuromuscular Electrical Stimulation!
      content: 'Our lab has been busy developing guidelines for a new technique of facial muscle activation!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: nmes_ex.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
        # to add another slide copy and paste everything from title to media
---
