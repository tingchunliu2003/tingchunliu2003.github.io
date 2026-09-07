---
layout: single
permalink: /
author_profile: true
classes: wide
---

## About Me <a class="cv-link" href="{{ '/assets/CV_TingChunLiu.pdf' | relative_url }}">[CV]</a>

I'm Ting-Chun Liu, a Master's student in Biomedical Engineering at Johns Hopkins
University. Write a couple of sentences here about your research interests,
background, and what you're currently working on.

## News

<ul>
{% for item in site.data.news %}
  <li><strong>{{ item.date }}</strong> &mdash; {{ item.description }}</li>
{% endfor %}
</ul>
