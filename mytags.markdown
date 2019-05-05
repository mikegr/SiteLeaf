---
title: MyTags
date: 2019-05-05 13:41:00 Z
---

<h2>{{ title }}</h2>
{{ body }}
<ul>
{% for tag in taxonomy.tags %}
    <li>
        <a href="{{ tag.url }}">{{ tag.value }}</a>
    </li>
{% endfor %}
</ul>