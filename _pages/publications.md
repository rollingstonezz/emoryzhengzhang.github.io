---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=fRdZRHsAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Selected Publications
======
* Zheng Zhang, Allen Zhang, Ruth Nelson, Giorgio Ascoli, Liang Zhao. **Representation Learning of Geometric Trees**, 30th SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2024), Research Track, accepted, 2024.
* Zheng Zhang, Sirui Li, Jingcheng Zhou, Junxiang Wang, Abhinav Angirekula, Allen Zhang, Liang Zhao. **Non-Euclidean Spatial Graph Neural Network**, SIAM Conference on Data Mining (SDM 2024), accepted, 2024.
* Zheng Zhang, and Liang Zhao. **Self-Similar Graph Neural Network for Hierarchical Graph Learning**, SIAM Conference on Data Mining (SDM 2024), accepted, 2024.
* Zheng Zhang, Junxiang Wang and Liang Zhao. **Curriculum Learning for Graph Neural Networks: Which Edges Should We Learn First**, The 37th Conference on Neural Information Processing Systems (NeurIPS 2023), full paper, 2023.
* Zheng Zhang and Liang Zhao. **Unsupervised Deep Subgraph Anomaly Detection**, The IEEE International Conference on Data Mining (ICDM 2022), full paper, [Best Paper Award].