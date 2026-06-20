---
title: Explore
nav: false
---
  order: 1
  tooltip: art and hobbies
# {% include icon.html icon="fa-solid fa-feather-pointed" %}Explore

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html component="card" data="posts" filter="group == 'explore'" %}
