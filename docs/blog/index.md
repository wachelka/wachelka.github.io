---
layout: default
---

# This is my blog

This is my blog intro bla bla

{% for post in site.posts %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
</article>
{% endfor %}
