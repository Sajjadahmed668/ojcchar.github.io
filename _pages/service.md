---
layout: archive
title: "Service"
permalink: /service/
author_profile: true
---

{% include base_path %}

I have served the Software Engineering academic community as a co-organizer, student volunteer, and co-reviewer.

{% for post in site.service%}
  {% include teaching-single.html %}
{% endfor %}
