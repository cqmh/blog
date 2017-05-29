---
layout: page
title: Wiki
description: 多看点多学点总是好的
keywords: 维基, Wiki
comments: false
menu: 维基
permalink: /wiki/
---

{% if site.github.public_repositories != null %}
{% assign sorted_repos = (site.github.public_repositories | sort: 'stargazers_count') | reverse %}

> 多看点多学点总是好的......

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
