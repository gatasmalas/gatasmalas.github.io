---
layout: default
---

{% if post.content contains '<!--more-->' %}
    {{ post.content | split:'<!--more-->' | first }}
{% else %}
    <!-- Case for when no excerpt is defined -->
{% endif %}
    
