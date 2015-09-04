---
layout: page
title: Half Mathematics, Half Programming
tagline: 半醒半醉日复日，花开花落年复年
---
{% include JB/setup %}


    
## Posts

My Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

本博客只是一个半成品，借用了[别人的博客](http://ilz.me/)的框架来写点自己的东西，
所以外观上不见得是好看。笔者大部分的时间会花在文章主题上，也许会在闲暇的时候进行美化。


