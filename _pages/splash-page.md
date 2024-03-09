---
title: "Under construction"
layout: splash
permalink: /photography/
date: 2024-03-08
header:
  overlay_color: "#000"
  # overlay_color: "#ca423b"
  overlay_filter: "0.5"
  overlay_image: /assets/images/thumbnail/teaser.png
  # overlay_image: /assets/splash/red.jpg

  actions:
    - label: "More here!"
      url: "https://www.instagram.com/laviediu/"
    #- label: "Read blog"
excerpt: Hi! Enjoy!
intro: 
  - excerpt: '*The journey of a thousand miles begins with one step*, quoting Lao Tzu, my journey began when I discovered my love for `photography` in junior high school.'
feature_row:
  - image_path: /assets/images/photography/feat1-1.png
    title: "Spring"
    excerpt: "Sample text 1 with **markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/photography/feat1-2.png
    title: "Winter"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondary"
  - image_path: /assets/images/photography/feat1-3.png
    title: "Autumn"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--success"
#feature_row_left:
#  - image_path: /assets/images/photography/feat1-1.jpg
#    title: "Left aligned placeholder 1"
#    excerpt: "Left-aligned image centered with"
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
#feature_row_right:
#  - image_path: /assets/images/photography/feat1-2.jpg
#    title: "Placeholder 1"
#    excerpt: "Right-aligned image with ``"
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
feature_row_center:
  - image_path: /assets/images/photography/feat1-1.png
    title: "Spring"
    excerpt: "Center aligned image"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

#{% include feature_row id="feature_row_left" type="left" %}

#{% include feature_row id="feature_row_center" type="right" %}

{% include feature_row id="feature_row_center" type="center" %}
