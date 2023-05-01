---
layout: post
title: Diary
---
<ol style="list-style:none;">
    <li>
        <h1><b> 文章列表</b> </h1>
    </li>
</ol>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.url | replace : "/","-" | remove_first: "-" }}</a>
    </li>
  {% endfor %}
</ul>
