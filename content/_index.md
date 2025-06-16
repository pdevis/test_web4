---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
  - block: cta-image-paragraph
    id: examples
    content:
      items:
        - title: Exploring the possibilities!
          text: CoMet can be used to
          feature_icon: bolt
          features:
            - "Propagate uncertainties"
            - "Handle error-correlation/error-covariance matrices"
            - "Create digital effects tables"
            - "Validate measurements"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
          button:
            text: More applications
            url: user-guide/examples/
            icon: rocket-launch
---
