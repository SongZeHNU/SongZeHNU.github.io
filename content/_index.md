---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Watch an introduction to my lab
          icon: brands/youtube
          url: https://hnuvpai.github.io/
        - text: Read my published paper
          icon: brands/google-scholar
          url: https://scholar.google.com/citations?user=uatSii8AAAAJ&hl=zh-CN
        - text: Contact me via Email songz at hnu.edu.cn
          icon: at-symbol
          url: https://support.google.com/mail
---
