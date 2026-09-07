---
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

{% for pub in site.data.publications %}
<div class="list__item">
  <article class="archive__item">
    <h3 class="archive__item-title">{{ pub.title }}</h3>
    <p class="archive__item-excerpt">
      {{ pub.authors }}<br>
      <em>{{ pub.venue }}</em>, {{ pub.year }}
      {% if pub.links %}
        <br>
        {% for link in pub.links %}<a href="{{ link.url }}">{{ link.label }}</a>{% unless forloop.last %} &middot; {% endunless %}{% endfor %}
      {% endif %}
    </p>
  </article>
</div>
{% endfor %}
