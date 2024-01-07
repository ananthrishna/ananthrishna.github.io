---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Quantum Network Nonlocality with X States
======
A manuscript based on the work done is being prepared, for updates, please check here.


Comment: >
  {% if author.googlescholar %}
    You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
  {% endif %}

  {% include base_path %}

  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
