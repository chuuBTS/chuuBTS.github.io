---
title: "Research"
permalink: /projects/
author_profile: true
redirect_from:
  - /publications/
  - /portfolio/
---

My work explores language-driven data analysis, visualization, and practical AI systems.

## Alpha-VIS
{: #alpha-vis}

**Dynamic agent workflows for natural language to visualization**<br>
Core contributor - Started March 2025

Alpha-VIS combines Monte Carlo tree search (MCTS) with Bayesian optimization (BO) to dynamically construct multi-agent visualization workflows.

- Independently designed and implemented eight Agent Space modules, covering query understanding, schema mapping, chart generation, and iterative refinement.
- Developed an MCTS + BO optimization framework that searches for agent workflows, with coarse-to-fine BO for fine-tuning parameters.
- Incorporated OCR coverage into evaluation to improve readability and consistency between charts and underlying data.
- Achieved execution accuracy of **80.11%** for single-table queries and **71.86%** for multi-table queries on VisEval, with an average score of **4.14/5**.

{% include research-figure.html path="/images/research/alpha-vis-framework.png" alt="Alpha-VIS framework showing dynamic multi-agent visualization workflows" caption="Overview of the Alpha-VIS framework." %}

## nvBench 2.0
{: #nvbench}

**Resolving Ambiguity in Text-to-Visualization through Stepwise Reasoning**<br>
Research project - July 2024 - February 2025

Tianqi Luo, **Chuhan Huang**, Leixian Shen, Boyan Li, Shuyu Shen, Wei Zeng, Nan Tang, and Yuyu Luo.<br>
*NeurIPS 2025*

[Paper](https://arxiv.org/abs/2503.12880){: .btn .btn--primary} [Project website](https://nvbench2.github.io/){: .btn}

- Contributed to a benchmark of **7,878 natural language queries** and **24,076 visualization queries**, supporting ambiguous requests and multiple valid outputs.
- Implemented data augmentation and reverse-synthesis pipelines in Python, and evaluated language models including GPT-4o and Qwen2.5-7B.
- Contributed to a stepwise reasoning approach for improving text-to-visualization performance under ambiguity.
- In project experiments, the Step-NL2VIS model reached **80.88% F1@5**, with a reported **21.85% improvement over GPT-4o**.

{% include research-figure.html path="/images/research/nvbench2-framework.png" alt="nvBench 2.0 framework for ambiguous text-to-visualization queries" caption="Overview of the nvBench 2.0 framework." %}
