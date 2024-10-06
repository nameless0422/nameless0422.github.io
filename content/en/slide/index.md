---
title: My page
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: 👋 Hello!
          content: 
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: coders.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: I prefer to talk about development. ☕️
          content:
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: contact.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: For work-related contacts, 
          content: please refer to the following
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: welcome.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: phone
            icon_pack: fas
            text: Contact
            url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---
