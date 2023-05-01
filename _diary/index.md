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
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.name | remove: ".md" }}</a>
    </li>
  {% endfor %}
</ul>
