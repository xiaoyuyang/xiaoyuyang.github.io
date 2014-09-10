---
layout: page
title: Hello World!
---
{% include JB/setup %}


## 写作的初衷 
2002年一次因为一本“修电脑”的书而初次接触网络安全，从那之后接触过各种安全技术（除了网络安全外还有很多奇葩技术）,所以写在这里供有兴趣的人感受安全的神奇

在和安全结缘之后，为了学习各种知识或是技能，走了很多弯路，也总结了一些经验，所以找个地方写下来，分享给大家

同时，过去学习的经验让我明白与人交流的重要性，所以也在这个地方把自己的想法写下来，供大家讨论
    
## 博文

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

