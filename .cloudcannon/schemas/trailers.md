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

additional_specs:
  type: array
  label: Additional Specifications
  options:
    add_button_label: Add specification
    structures:
      - label: Specification
        values:
          spec_title:
            type: text
            label: Specification Title
          spec:
            type: text
            label: Specification

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

highlighted_features:
  type: array
  label: Highlighted Features
  options:
    type: text
    add_button_label: Add feature

trailer:
  type: array
  label: Trailer Features
  options:
    type: text
    add_button_label: Add feature

living_quarters:
  type: array
  label: Living Quarter Features
  options:
    type: text
    add_button_label: Add feature

gallery:
  type: array
  label: Images
  options:
    add_button_label: Add image
    structures:
      - label: Image
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
        values:
          url:
            type: url
            label: Video URL
          thumb:
            type: image
            label: Thumbnail
---
