---
layout: home
classes:
  - landing
  - dark-theme
author_profile: true
header:
  overlay_image: /assets/images/header.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_url: "about-me"
  cta_label: "Read More"
  overlay_color: "#000"
  overlay_filter: "0.5"
intro: "21, Computer Science student at University of Birmingham. Aspiring Developer, formerly UBCU Prayer Secretary (2016-17)"
feature_row:
  - image_path: /assets/images/profile.jpg
    alt: "Profile Image"
    title: "About Me"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row2:
  - image_path: /assets/images/astonwebb.jpg
    alt: "University of Birmingham"
    title: "University of Birmingham"
    excerpt: 'I am a final-year MSci student in the School of Computer Science.'
    url: "cs.bham.ac.uk"
    btn_label: "Read More"
    btn_class: "btn--inverse"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}
