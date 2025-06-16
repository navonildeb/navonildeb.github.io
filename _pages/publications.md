---
layout: page
title: "Publications"
permalink: /publications/
---

{% assign pubs = site.data.publications | sort: "year" | reverse %}
{% for pub in pubs %}

<div style="margin-bottom: 1.5em; padding-left: 1em; border-left: 3px solid #ccc;">

### {{ pub.title }}

<p><strong>Authors:</strong> {{ pub.authors }}<br>
<strong>Venue:</strong> {{ pub.venue }}</p>

<p>
  {% for link in pub.links %}
  <a href="{{ link.url }}" target="_blank">[{{ link.name }}]</a>
  {% endfor %}
</p>

</div>

{% endfor %}
