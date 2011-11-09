---
layout: default
title: News
---

{% for post in site.posts limit:10 %}

<div class="post">
    <div class="date">{{ post.date | date: "%A, %d %b %Y" }}</div>
    <div class="topic"><a href="{{ post.url }}">{{ post.title }}</a></div>
    <p>{{ post.content | strip_html | truncatewords: 50 | textize}}</p>
    <div class="author">{{ post.author }}</div>
    <br/><br/>        
</div>

{% endfor %}