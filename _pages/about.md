---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## Official Bio

I am a PhD student at **MBZUAI** working at the intersection of machine learning, chemistry, and catalysis. My research focuses on developing reliable and data-efficient ML methods for scientific discovery, including Neural ODEs for reaction kinetics, graph neural networks (GNNs) for catalyst design, and ML-based prediction of partial density of states (pDOS). By combining chemical domain knowledge with modern ML, I aim to accelerate catalyst discovery, improve reaction efficiency, and support scalable solutions for clean energy and low-emission industrial processes.

## Research Interests

- Neural ODEs for reaction kinetics
- Graph neural networks (GNNs) for catalyst design
- ML-based prediction of partial density of states (pDOS)
- Data-driven methods for sustainable chemistry and catalysis

## Selected Publications

{% assign selected_pubs = site.publications | sort: 'date' | reverse %}
{% for post in selected_pubs limit:4 %}
- *{{ post.title }}* ({{ post.venue }}, {{ post.date | date: "%Y" }})
{% endfor %}

See full list on [Research](/research/) or [Google Scholar](https://scholar.google.com/citations?user=JLqxspUAAAAJ).

## Talks

I regularly give talks on machine learning for chemistry and catalysis.  
My talks and publications are listed on the [Research](/research/) page.

## Links

- Google Scholar: [JLqxspUAAAAJ](https://scholar.google.com/citations?user=JLqxspUAAAAJ)
- GitHub: [klea-ziu](https://github.com/klea-ziu)
- LinkedIn: [klea-ziu](https://www.linkedin.com/in/klea-ziu)
