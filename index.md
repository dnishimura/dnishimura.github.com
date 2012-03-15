---
layout: page
title: Polygot Techie
tagline: Supporting tagline
full_posts: 5
---
{% include JB/setup %}

### I can do

`C++` `Ruby` `C#` `Python` `DevOps` 

### I am learning

`Go` `C++11` `MachineLearning` `Security` 

### I hope to one day do

`KernalHacking` `GameDev` `Haskell` `R` `OpenGL`  

#### Recent Blog Posts

<ul class="posts">
  {% for post in site.posts limit:5 %}
    <li class="bloglist"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
    <li class="bloglist"><a href="{{ BASE_PATH }}/blog">more blogs...</a></li>
</ul>



