---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
A collection of selected publications.
{% if site.author.googlescholar %}
  <div class="wordwrap">You can find a more on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
