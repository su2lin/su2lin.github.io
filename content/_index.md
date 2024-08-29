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
  - block: resume-biography
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
        - text: Read my latest paper
          icon: academicons/arxiv
          url: https://scholar.google.com/citations?hl=en&user=XBwfd50AAAAJ&view_op=list_works&sortby=pubdate
        - text: Visit my group website
          icon: brands/youtube
          url: https://biohybrids.group/
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://linkedin.com/in/su2lin
---
