---
layout: default
---

<h1>Tüm Makaleler</h1>
{% for post in site.posts %}

* {{ post.date | date: "%Y-%m-%d" }} [{{ post.title }}]({{ post.url }}) 

{% endfor %}