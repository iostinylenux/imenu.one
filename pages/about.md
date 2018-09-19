---
layout: page
title: About
description: iostinylenux's enumivo project
keywords: iostinylenux, imenu
comments: true
menu: About
permalink: /about/
---

This is enumivo project BP Wiki Page

BP Name:iostinylenux


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
