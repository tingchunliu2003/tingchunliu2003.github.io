---
layout: single
permalink: /
author_profile: true
classes: wide
---

## About Me <a class="cv-link" href="{{ '/assets/CV_TingChunLiu.pdf' | relative_url }}">[CV]</a>

I'm Ting-Chun Liu, a Master's student in Biomedical Engineering at [Johns Hopkins University](https://www.jhu.edu/).<br>
I earned my bachelors degree at [National Taiwan University](https://www.ntu.edu.tw/english/) majoring Electrical Engineering. My previous research and internship work has primarily focused on machine learning, computer vision, and generative modeling.

Recently, I've been focusing on research in autonomous robotic surgery. Here are a few research questions I'm currently exploring:
1. How can we achieve robust and safe motion planning for surgical robots under visual uncertainty? What is the real-world tradeoff between managing uncertainty through probabilistic modeling and incorporating new imaging modalities?
2. What is the optimal model architecture for generating robot control signals from continuous observations of the surgical scene? This architecture should be able to understand task-specific goals, reason over past history, generate robot-agnostic instructions, and produce robot-specific control signals.
3. What metric can serve as a good "feedback signal" for how well a surgery is performed? This metric should capture lessons learned from real domain experts and could be developed from expert demonstrations and language descriptions.

## News

<ul>
{% for item in site.data.news %}
  <li><strong>{{ item.date }}</strong> &mdash; {{ item.description }}</li>
{% endfor %}
</ul>
