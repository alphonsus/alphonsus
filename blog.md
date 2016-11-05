---
layout: default
title: Blog
permalink: /blog
---

<div class="home">
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <!-- <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span> -->

        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        {{ post.excerpt }}

        <a href="{{ post.url }}" class="read-more">Read more...</a>
      </li>
    {% endfor %}
  </ul>

  <!-- <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p> -->

</div>
