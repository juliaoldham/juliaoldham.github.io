---
layout: page
title: "Contact"
permalink: /contact
---

email: (juliaoldham@gmail.com)[mailto:juliaoldham@gmail.com]
phone: 347-263-3179
Find me on Facebook
Find me on Instagram

{% for item in site.data.settings.social %}
    <a href="{{ item.link }}" class="menu-link" target="_blank"><i class="fa fa-{{ item.icon }}" aria-hidden="true"></i></a>
{% endfor %}
