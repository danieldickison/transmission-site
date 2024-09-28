---
---

![Line drawing of a person draped in a quilt]({{ "assets/images/illustration-landing.png" | relative_url }})

Transmissions is a project that makes quilts for trans people.

Quilts have been given as gifts to mark life transition across time and cultures. They help us see ourselves on longer time scales, which is something that many trans people can’t access easily.

May these quilts keep us living.

## News and Updates

<ul class="posts">
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.date | date_to_string }} – {{ post.title }}</a></li>
{% endfor %}
</ul>
