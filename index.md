---
layout: default
---

## fighting game blog

格闘ゲームGuilty Gear striveを練習している人のサイトです。

メインキャラはジオヴァーナ、他には鰤、カイ、ソルなど。


{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
