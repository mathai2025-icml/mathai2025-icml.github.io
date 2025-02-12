---
layout: page
title: MATH-AI
subtitle: "Pushing the Frontiers of AI for Mathematical Problem Solving, Discovery, and Reasoning"
use-site-title: true
---
<!-- <div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (West Meeting Room 118-120, Vancouver, December 14, 2024, <a href="https://neurips.cc/virtual/2024/workshop/84719" target="_blank">Website</a>)
</div> -->



<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />

# Related MATH-AI Workshops

<div class="container" style="margin-bottom: 10px;"></div>
- 4th MATH-AI Workshop at NeurIPS'24: [The 4th Workshop on Mathematical Reasoning and AI](https://mathai2024.github.io)
- [AI for Math Workshop @ ICML 2024](https://sites.google.com/view/ai4mathworkshopicml2024)
- 3rd MATH-AI Workshop at NeurIPS'23: [The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- 2nd MATH-AI Workshop at NeurIPS'22: [Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- 1st MATH-AI Workshop at ICLR'21: [The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- MATHAI4ED Workshop at NeurIPS'21: [Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)

<div class="container" style="margin-bottom: 10px;"></div>

<!-- # Reviewer Nomination

If you'd like to become a reviewer for the workshop, or recommend someone, [please use this form](https://forms.gle/BssMrXeGgfMfLLFH9). -->

# Overview

Mathematical reasoning is a fundamental aspect of human cognition, studied by philosophers, logicians, and neuroscientists. It is a cyclical process of analyzing complex information, identifying patterns and relationships, drawing logical conclusions from evidence, and refining generalizations through refutations. 

In recent years, large language models (LLMs) have reached a significant inflection point in mathematical reasoning, with models such as o3-mini and DeepSeek-R1. Meanwhile, as mathematical problem solving benchmarks start to saturate, more challenging targets are currently being explored. However, models have made considerable progress on these benchmarks, and there is still a long way to go when it comes to using AI for these expert-level mathematics tasks. At the same time, advancements in LLMs have triggered a paradigm shift in the broader intersection of artificial intelligence and experimental mathematics, giving rise to novel methods for generating conjectures, proving theorems, and fostering new forms of human–machine collaboration in mathematical discovery.

Our proposed workshop focuses on the intersection of deep learning, experimental mathematics, and mathematical reasoning, with a particular emphasis on leveraging the recent progress made with large language models. Our guiding theme is:

*"How can AI be used to expand the boundaries of human discoveries in mathematics?"*

In pursuing this question, we aim to bridge the gap between computer scientists and mathematicians, moving beyond toy-datasets towards exploring genuine applications in research-level mathematics. This year, we have confirmed speakers working in AI, pure mathematics, and a combination of both. Our objective is to foster a lively and constructive dialogue on areas including, but not limited, to the following:

- **AI for mathematical problem solving**: Building off of the success of today's frontier models, how can we leverage LLMs to solve problems at the college level and beyond?
- **AI for mathematical discovery**: How can modern deep learning methods uncover new patterns, confirm or refute conjectures, and enable high-precision computation while remaining interpretable and offering strong generalization? Can AI assist with research-level mathematics?
- **Human-AI collaboration in mathematics**: While machines are great at large-scale pattern recognition, humans are able to think more abstractly and develop intuition. How can humans and machines complement each other productively?
- **Measuring progress in mathematics**: How do we design benchmarks that push the frontier of what LLMs are able to do when it comes to mathematics? What are the milestones in AI for math?




<hr>

# Speakers & Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% if forloop.index<=5 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>5 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
<!-- <a href="speakers">More Info</a> -->
</div>

<hr>

# Organizers
<!-- # Organizers -->

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <!-- <br> 
  <div class="row" style="margin: -30px;"> -->
  <div class="row">
    {% for p in site.data.organizers %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=8%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

<!-- # Program Committee
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr> -->

# Related Venues

<div class="container" style="margin-bottom: 10px;"></div>
- [NeurIPS'23 Workshop on MATH-AI - The 4th Workshop on Mathematical Reasoning and AI](https://mathai2024.github.io/)
- [ICML'24 Workshop on AI4MATH - AI for Math Workshop @ ICML 2024](https://sites.google.com/view/ai4mathworkshopicml2024)
- [NeurIPS'23 Workshop on MATH-AI - The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- [NeurIPS'22 Workshop on MATH-AI - Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- [NeurIPS'21 workshop on MATHAI4ED - Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)
- [ICLR'21 workshop on MATH-AI - The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- [NeurIPS'20 Workshop on KR2ML - Knowledge Representation & Reasoning Meets Machine Learning](https://kr2ml.github.io/2020)
- [NeurIPS'20 workshop on Advances and Opportunities: Machine Learning for Education](https://www.ml4ed.org/)
- [ICML'20 workshop on Bridge  Between Perception and Reasoning: Graph Neural Networks & Beyond](https://logicalreasoninggnn.github.io)

<div class="container" style="margin-bottom: 10px;"></div>

<hr>

Contact: <mathai.icml2025@gmail.com>.
