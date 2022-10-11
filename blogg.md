---
layout: default
title: Tíst
---



### Allt um vefhönnun sem þú villt vita en hefur ekki þorað að spyrja um

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url | prepend: site.baseurl }})  
  
    {{ post.excerpt }}
{% endfor %}
