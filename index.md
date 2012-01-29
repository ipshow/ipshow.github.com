---
layout: page
title: 欢迎来到我的Blog!
---
{% include JB/setup %}



<img class='inset left' title='Steven Lee' src='images/avatar.jpg'>
I’m Justend, a 30-something Chinese, academic, husband, programmer, father, snowboarder, and web-nerd—amongst other things. You can find out more about me by poking around the links above and below.

<br />
## 文章列表：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 书籍推荐

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


