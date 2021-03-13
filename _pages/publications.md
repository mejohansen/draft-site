---
layout: page
title: "Publications"
permalink: /research2/
redirect_from: 
  - /publications/
  - /publications/index.html
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
* {{ post.title }} in {{ post.venue}} ({{ post.date }})

    {{ post.excerpt }}

    
{% endfor %}
