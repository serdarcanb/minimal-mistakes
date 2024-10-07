---
layout: home
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/main-image.png
  overlay_filter: .8
---

## Latest Posts

{% assign posts = site.posts | limit:3 %}

{% for post in posts %}
{% capture post_image %}
  {% if post.image %}
    {{ post.image }}
  {% else %}
    /assets/images/default-image.jpg
  {% endif %}
{% endcapture %}

{% assign feature_row_item = {
  image_path: post_image,
  alt: post.title,
  title: post.title,
  excerpt: post.excerpt,
  url: post.url,
  btn_label: "Read More",
  btn_class: "btn--primary"
} %}

{% include feature_row id="post-feature-row" type="left" %}
{% endfor %}