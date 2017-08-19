---
layout: default
tags: [ghim]
categories: [orther,items,news]
---
<p>reversed</p>
{% for post in site.posts reversed limit:5 %}
    {{post.date}}-{{post.title}}
{% endfor %}
<p>no reversed</p>
{% for post in site.posts limit:5 %}
    {{post.date}}-{{post.title}}
{% endfor %}