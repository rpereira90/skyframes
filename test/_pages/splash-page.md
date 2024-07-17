---
title: "Roberto's Aerial Photography"
layout: splash
date: 2023-07-17
header:
  overlay_color: "#005f73"
  overlay_filter: "0.7"
  overlay_image: /assets/images/drone-view-landscape.jpg
  actions:
    - label: "View Portfolio"
      url: "/portfolio/"
    - label: "Contact Me"
      url: "/contact/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Professional drone photography showcasing breathtaking landscapes, stunning real estate, dynamic automotive scenes, and luxurious hotels."
intro:
  - excerpt: 'Explore the world from above with high-quality drone visuals, perfect for advertising, documentation, and personal projects.'
feature_row:
  - image_path: assets/images/landscape-drone.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Landscape aerial view"
    title: "Landscape Photography"
    excerpt: "Explore breathtaking natural scenes from a unique aerial perspective."
    url: "/gallery-landscape/"
    btn_label: "View Gallery"
    btn_class: "btn--primary"
  - image_path: /assets/images/real-estate-drone.jpg
    alt: "Real estate aerial view"
    title: "Real Estate Photography"
    excerpt: "Enhance real estate listings with detailed aerial imagery."
    url: "/gallery-real-estate/"
    btn_label: "View Gallery"
    btn_class: "btn--primary"
  - image_path: /assets/images/automotive-drone.jpg
    title: "Automotive Photography"
    excerpt: "Capture dynamic images of automobiles in stunning locations."
    url: "/gallery-automotive/"
    btn_label: "View Gallery"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/luxury-hotel-drone.jpg
    alt: "Luxury hotel aerial view"
    title: "Luxury Hotel Promotions"
    excerpt: 'Showcase the elegance and amenities of luxury hotels with aerial photography.'
    url: "/gallery-luxury-hotels/"
    btn_label: "View Gallery"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}