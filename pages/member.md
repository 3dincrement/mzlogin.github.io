---
layout: page
title: Member
description: 团队成员
keywords: 团队成员, Member
comments: false
menu: 成员
permalink: /member/
---

> 记多少命令和快捷键会让脑袋爆炸呢？

<ul class="listing">
{% for member in site.member %}
{% if member.title != "Member Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ member.url }}">{{ member.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
