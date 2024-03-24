---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
A collection of selected publication.
{% if site.author.googlescholar %}
  <div class="wordwrap">You can a more complete list on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
