---
title: KM-GBF Model Review
layout: splash
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/images/landscape.png
excerpt: "Convening a network of modellers and scenario developers to tackle the couple biodiversity and climate crises"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/landscape.png
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/explore_database.png
    alt: "Image of database desciptive statistics"
 #   title: "Explore the database"
 #   excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/database_explorer/"
    btn_label: "Explore the database"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/landscape.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}

{$ include feature_row type="left %}

{% include feature_row id="feature_row2" type = "right" %}

{% include feature_row id="feature_row3" type = "left" %}