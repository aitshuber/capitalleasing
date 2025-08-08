---
layout:
  type: auto

seo:
  title:
    type: text
  description:
    type: textarea
  keywords:
    type: text
  image:
    type: image

trailer_title:
  type: text

trailer_type:
  type: select
  options:
    allow_empty: true
    values:
      - Living Quarters
      - Non-Living Quarters
      - Cargo and Specialty

description:
  type: textarea

featured:
  type: switch
  label: Feature on Home Page

price:
  type: text

specifications:
  year:
    type: text
  make:
    type: text
  model:
    type: text
  vin:
    type: text
  color:
    type: text
  length:
    type: text
  width:
    type: text
  height:
    type: text
  number_of_horses:
    type: text
  load_type:
    type: text

condition:
  type: select
  options:
    allow_empty: true
    values:
      - New
      - Used

hitch_type:
  type: select
  options:
    allow_empty: true
    values:
      - Gooseneck
      - Bumper pull

# Object-based arrays (kept here - images/video were previously fixed)
gallery:
  type: array
  label: Images
  options:
    add_button_label: Add image
    structures:
      - label: Image
        preview:
          text: "{{ image | split: '/' | last }}"
        values:
          image:
            type: image
            label: Image

video:
  type: array
  label: Video
  options:
    add_button_label: Add video
    structures:
      - label: Video
        preview:
          text: "{{ url }}"
          subtext: "{{ thumb | split: '/' | last }}"
        values:
          url:
            type: url
            label: Video URL
          thumb:
            type: image
            label: Thumbnail
---
