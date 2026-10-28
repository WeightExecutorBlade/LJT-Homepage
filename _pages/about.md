---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am **Junteng Liu**, a first-year PhD candidate in the HKUST NLP Group at the Hong Kong University of Science and Technology (HKUST), supervised by Prof. Junxian He. I received my B.Eng. from Shanghai Jiao Tong University (SJTU) in June 2024, where I was also advised by Prof. Junxian He.

My research focuses on **natural language processing and machine learning**. I am particularly interested in LLM reasoning and reinforcement learning, hallucination in vision-language models, and LLM truthfulness and interpretability.

## Education

- **Ph.D. in Computer Science (2024 – Present)**, Hong Kong University of Science and Technology (HKUST), HKUST NLP Group.
- **B.Eng. (2020 – 2024)**, Shanghai Jiao Tong University (SJTU), graduated in June 2024.

## Research Experience

- **Research Intern, MINIMAX (Feb. 2025 – Present).**
- **Research Intern, Tencent WXG (Jun. 2024 – Sep. 2024).** Advised by Zifei Shan.
- **Research Intern, Shanghai AI Lab (Jun. 2023 – Dec. 2023).** Advised by Prof. Yu Cheng.
- **PhD Researcher, HKUST NLP Group, HKUST (2024 – Present).** Advised by Prof. Junxian He.

## Research Interests

- LLM Reasoning and Reinforcement Learning.
- Hallucination in Vision-Language Models (VLM).
- LLM Truthfulness and Interpretability.

## Publications

{% for pub in site.publications reversed %}
<div class="publication-block" style="margin-bottom: 1.4em;">
  <p style="margin-bottom: 0.2em;"><strong>{{ pub.title }}</strong></p>
  <p style="margin-bottom: 0.2em;">{{ pub.authors }}</p>
  <p style="margin-bottom: 0.2em;"><em>{{ pub.venue }}</em>, {{ pub.date | date: "%Y" }}
  {% if pub.paperurl %} · <a href="{{ pub.paperurl }}">Code</a>{% endif %}
  </p>
</div>
{% endfor %}

## Skills & Research Expertise

- Natural Language Processing (NLP).
- Machine Learning.
- LLM Reasoning and Reinforcement Learning.
- Vision-Language Models (Hallucination).
- LLM Truthfulness and Interpretability.

## Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)
