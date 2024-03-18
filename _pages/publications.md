---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Only the first/co-first author publications are shown, and other articles can be found on my <a href="{{site.author.googlescholar}}">Google Scholar</a> profile.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
