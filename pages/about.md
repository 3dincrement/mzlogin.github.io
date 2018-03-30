---
layout: page
title: About
description: 团队介绍
keywords: 3D Increment Introduction
comments: true
menu: 关于
permalink: /about/
---

我们的团队由山东大学[吕琳副教授][1]带领，是一支致力于提供3D打印设计与制造解决方案的创新创业团队。依托于山东大学3D打印与增材制造资源，我们的团队面向客户需求提供包括3D打印设计与制造的一体化解决方案。近两年，我们的团队已经申请3D打印与增材制造领域专利多项，已投顶级会议或期刊论文若干篇。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

<<<<<<< HEAD
## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}

=======
>>>>>>> be1d1216e62774cf6f5f39be69438690c4c3e0dd
[1]: http://www.cs.sdu.edu.cn/zh/~llu
