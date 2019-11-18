---
layout: page
title: About
description: 打码改变世界
keywords: zt, zhangtuo, zhangtuodd
comments: true
menu: 关于
permalink: /about/
---

我是ZT，Don't think too much,just do it.

立志，努力，怀疑，坚持。

坚信熟能生巧，努力改变人生。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
