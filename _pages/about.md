---
layout: about
title: About
permalink: /
author_profile: true

sidebar:
  - title: "Affiliation"
    image: /assets/images/photos/head.jpg
    image_alt: "Junteng Liu"
    text: >-
      First-year PhD Candidate<br/>
      HKUST NLP Group<br/>
      Hong Kong University of Science and Technology
---

I am a first-year PhD candidate at the [HKUST NLP Group](https://hkust-nlp.github.io/), supervised by [Professor Junxian He](https://jxhe.github.io/). I graduated from Shanghai Jiao Tong University (SJTU) in June 2024, where I was also advised by Professor Junxian He during my undergraduate studies.

My research focuses on **natural language processing** and **machine learning**. I am particularly interested in:
- **LLM Reasoning and Reinforcement Learning**
- **Hallucination in Vision-Language Models (VLMs)**
- **LLM Truthfulness and Interpretability**

## Selected Publications

{% if site.publications %}
{% assign sorted_publications = site.publications | sort: 'year' | reverse %}
{% for pub in sorted_publications %}
<div class="publication-item" style="margin-bottom: 1.5rem;">
  <h4 style="margin-bottom: 0.25rem;">{{ pub.title }}</h4>
  <p style="margin: 0; color: #666;">{{ pub.authors | markdownify }}</p>
  <p style="margin: 0;">
    {% if pub.venue %}<em>{{ pub.venue }}</em>{% endif %}{% if pub.year %}, {{ pub.year }}{% endif %}
    {% if pub.link %} | <a href="{{ pub.link.url }}" target="_blank">{{ pub.link.text }}</a>{% endif %}
    {% if pub.code %} | <a href="{{ pub.code.url }}" target="_blank">{{ pub.code.text }}</a>{% endif %}
  </p>
</div>
{% endfor %}
{% endif %}

<p>For the full list of publications, see the <a href="{{ '/publications/' | relative_url }}">Publications</a> page.</p>

## Education

- **Ph.D. in Computer Science** (2024 – Present)  
  Hong Kong University of Science and Technology

- **B.Eng.** (2020 – 2024)  
  Shanghai Jiao Tong University

## Research Experience

- **Research Intern** (February 2025 – Present)  
  MINIMAX

- **Research Intern** (June 2024 – September 2024)  
  Tencent WXG  
  Advisor: Zifei Shan

- **Research Intern** (June 2023 – December 2023)  
  Shanghai AI Lab  
  Advisor: Prof. Yu Cheng

## Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Skills

- **Programming Languages:** Python, C++, JavaScript
- **Machine Learning Frameworks:** PyTorch, Hugging Face Transformers
- **Tools & Platforms:** Git, Docker, Linux, Slurm
- **Areas:** Large Language Models, Vision-Language Models, Reinforcement Learning, Reasoning

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://x.com/junteng88716710)
