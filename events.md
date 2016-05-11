---
layout: page
title: eventos
permalink: /events/
---

<p>Aqui tem uma lista dos nossos próximos eventos. :-)</p>

{% if site.events %}
<ul>
{% for event in site.events reversed %}
    <li>
        <p><a href="{{ event.url }}">{{ event.title }}</a></p>
    </li>
{% endfor %}
</ul>
{% endif %}