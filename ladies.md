---
layout: page
title: ladies
permalink: /ladies/
---

{% for lady in site.ladies %}

{% if lady.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ lady.redirect }}" target="_blank">
        {% if lady.img %}
        <img class="thumbnail resize-img" src="{{ lady.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}
        <span>
            <h1>{{ lady.title }}</h1>
            <br/>
            <p>{{ lady.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}
<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ lady.url }}">
        {% if lady.img %}
        <img class="thumbnail resize-img" src="{{ lady.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}
        <span>
            <h1>{{ lady.title }}</h1>
            <br/>
            <p>{{ lady.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
