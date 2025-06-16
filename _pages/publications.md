---
layout: page
title: "Publications"
permalink: /publications/
---

{% for pub in site.data.publications %}
### {{ pub.title }}

**Authors:** {{ pub.authors }}  
**Venue:** {{ pub.venue }}

{% for link in pub.links %}
[{{ link.name }}]({{ link.url }})  
{% endfor %}

<br>
{% endfor %}
