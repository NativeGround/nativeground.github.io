---
layout: single
author_profile: true
title: 'LIVE'
excerpt: " Topology is Destiny "
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  overlay_filter: rgba(252, 234, 13, 0.5)
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "More Info"
  cta_url: "https://unsplash.com"
  image_description: "This image"
feature_row:
  - image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Sustainable Spaces"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "Traditional Superfoods"
    title: "Traditional Superfoods"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Intelligent Wearables"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
search: true
---
<h1>Native Ground</h1>
<ul>
  {% for page in site.live %}
    <li>
      <a href="{{ page.url | prepend: site.baseurl }}">{{page.title}}</a>
    </li>
  {% endfor %}
</ul>   

{% include feature_row %}