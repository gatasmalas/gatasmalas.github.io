---
layout: default
---
## Welcome to my Github Site
![My Header]( {{ site.url }}/assets/images/header.jpeg)

*  {% for post in site.posts %}
   ( {{ post.title }} )[ {{ post.url }} ]
      {{ post.excerpt }}
  {% endfor %}
