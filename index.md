---
layout: default
---

## ギルティ日記

Guilty Gear striveを練習している人のサイトです。

メインキャラはジオヴァーナ、他には鰤、カイ、ソルなど。


{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})
{% endfor %}
