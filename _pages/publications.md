---
permalink: /publications/
title: "Selected Publications"
author_profile: true
---

{% assign pubs = site.publications | sort: 'date' | reverse %}

{% for post in pubs %}
### [{{ post.title }}]({{ post.url | relative_url }})
{{ post.authors }}  
*{{ post.venue }}*, {{ post.year }}{% if post.note %}. {{ post.note }}{% endif %}

{% if post.paperurl %}[PDF / Paper]({{ post.paperurl }}){% endif %}{% if post.codeurl %} · [Code]({{ post.codeurl }}){% endif %}

{% endfor %}
