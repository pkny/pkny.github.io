---
layout: page
title:
header: Pages
group: navigation
---

---

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>

{% for post in site.posts limit:1  %}
{% if forloop.last %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endif %}
{% endfor %}
