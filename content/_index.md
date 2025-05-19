---
description: |
  Welcome to my portfolio gallery.
  I enjoy taking photos of all sorts, but love taking photos of people.
  
  If you like my work, follow me on Instagram!
#lastmod: 2023-07-05
title: Vandan's Portfolio Gallery
resources:
  - src: self-portraits/7-P7106386.jpg
    params:
      cover: true # cover of the home page is used for OpenGraph cards, etc.
menus:
  main:
    name: Home
    weight: -2
# sub-galleries on list pages are sorted by date and weight (descending)
cascade:
  build:
    publishResources: false # do not include full images. Also disable download
  params:
    sort_by: Date
    sort_order: desc
---