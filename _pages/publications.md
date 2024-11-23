---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Publications
======
1. **Xinmiao Yu**, Xiaocheng Feng, Yun Li, Minghui Liao, Ya-Qi Yu, Xiachong Feng, Weihong Zhong, Rui- han Chen, Mengkang Hu, Jihao Wu, Duyu Tang, Dandan Tu, Bing Qin. Cross-Lingual Text-Rich Visual Comprehension: An Information Theory Perspective. submitted to AAAI 2024
2. Mengkang Hu, Yao Mu, **Xinmiao Yu**, Mingyu Ding, Shiguang Wu, Wenqi Shao, Qiguang Chen, Bin Wang, Yu Qiao, Ping Luo. Tree-Planner: Efficient Close-loop Task Planning with Large Language Models [arxiv][ICLR 2024]
3. **Xinmiao Yu**, Meng Qu, Xiaocheng Feng, Bing Qin. GraphAgent: Exploiting Large Language Models for Interpretable Learning on Text-attributed Graphs. [arxiv](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=yflYWnYAAAAJ&citation_for_view=yflYWnYAAAAJ:9yKSN-GCB0IC)
4. Zhangyin Feng, Yuchen Ren, **Xinmiao Yu**, Xiaocheng Feng, Duyu Tang, Shuming Shi, Bing Qin. Improved Visual Story Generation with Adaptive Context Modeling. ACL 2023
5. Xuehui Yu, Jingchi Jiang, **Xinmiao Yu**, Yi Guan*,Xue Li. Causal Coupled Mechanisms: A Control Method with Cooperation and Competition for Complex System The BIBM 2022

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
