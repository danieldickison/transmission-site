---
toc:
  - url: about.html
    title: About
  - url: gallery.html
    title: Gallery
  - url: "#news-anchor"
    title: News
---

{::options parse_block_html="true" /}

<section>
<a id="about-anchor"></a>

Quilts have been given as gifts to mark life transition across time
and cultures. They help us see ourselves on longer time scales,
which is something that many trans people can’t access easily.
Transmissions is a project that makes quilts with and for trans
people.

This project explores the act of gift giving. It commissions trans
artists to make art that ends up in a quilt for their friend, the quilt
recipient. They end up with a quilt that reminds them of the love
and care that hold them.

The process can be conducted with teens or adults. We plan to
make 16 quilts over the next 18 months.
</section>

<section>
<a id="news-anchor"></a>

## News and Updates

<ul class="posts">
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.date | date_to_string }} – {{ post.title }}</a></li>
{% endfor %}
</ul>
</section>
