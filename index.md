---
layout: default
title: "Home"
---

[About me and links](/about/)

# Recent posts

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>
