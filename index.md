---
layout: page
title: Yasuhiro Yoshikawa's Blog
tagline: 個人的なメモを記します
---
{% include JB/setup %}

### 最新の記事
<ul class="posts">
 {% for post in site.posts %}
   <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
 {% endfor %}
</ul>

<!--
## To-Do
This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
-->


