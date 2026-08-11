---
title: Explore
nav:
  order: 1
  tooltip: art and hobbies
---
  
  
# {% include icon.html icon="fa-solid fa-feather-pointed" %}Explore

Sharing processes and passion

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html component="post-excerpt" data="posts" filter="group == 'explore'" %}
