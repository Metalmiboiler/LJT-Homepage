---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<div class="publications">
  <ul>
    {% for post in site.publications reversed %}
      {% include archive-single.html %}
    {% endfor %}
  </ul>
</div>
