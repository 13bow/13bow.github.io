---
layout: splash
title: "溫暖製造室"
excerpt: "把心意，慢慢縫進生活裡"


header:
  overlay_color: "#94ddfc"
  overlay_filter: "0.35"
  overlay_image: /assets/images/lo.jpg
  actions:
    - label: "POST"
      url: /posts/
    - label: "品牌故事"
      url: /about/

intro:
  - excerpt: "一針一線 縫進日常 製造每一份溫暖"

# 第一排（3個卡片）
feature_row:
  - image_path: /assets/images/feature-1.jpg
    alt: "feature 1"
    title: "Blog"
    excerpt: "Read my latest posts."
    url: /posts/
    btn_label: "Read"
    btn_class: "btn--primary"

  - image_path: /assets/images/feature-2.jpg
    alt: "feature 2"
    title: "Resources"
    excerpt: "Useful materials and guides."
    url: /resources/
    btn_label: "Explore"
    btn_class: "btn--primary"

  - image_path: /assets/images/feature-3.jpg
    alt: "feature 3"
    title: "Projects"
    excerpt: "Things I'm working on."
    url: /projects/
    btn_label: "View"
    btn_class: "btn--primary"

# 第二排（2個卡片）
feature_row2:
  - image_path: /assets/images/feature-4.jpg
    alt: "feature 4"
    title: "Guides"
    excerpt: "Step-by-step tutorials."
    url: /guides/
    btn_label: "Open"
    btn_class: "btn--primary"

  - image_path: /assets/images/feature-5.jpg
    alt: "feature 5"
    title: "Downloads"
    excerpt: "Files and documents."
    url: /downloads/
    btn_label: "Download"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}