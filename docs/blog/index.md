---
layout: default
---
<h1>This is my blog</h1>
<p>This is my blog intro bla bla</p>

{% for post in site.posts %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
</article>
{% endfor %}
