---
title: "Publications & Research"
permalink: /projects/
author_profile: true
redirect_from:
  - /publications/
  - /portfolio/
---

My work explores language-driven data analysis, visualization, and practical AI systems.

<section class="research-project" markdown="1">

## Agentic-VIS: Search-Guided Natural Language to Visualization with Readability-Aware Optimization
{: #alpha-vis}

Core contributor &middot; Started March 2025
{: .research-meta}

{% include research-figure.html path="/images/research/alpha-vis-framework.png" alt="Agentic-VIS framework showing dynamic multi-agent visualization workflows" caption="Overview of the Agentic-VIS framework." %}

### Method and contributions

- **Workflow design.** Agentic-VIS combines Monte Carlo tree search (MCTS) with Bayesian optimization (BO) to dynamically construct multi-agent visualization workflows.
- **Agent architecture.** Independently designed and implemented eight Agent Space modules, covering query understanding, schema mapping, chart generation, and iterative refinement.
- **Search and optimization.** Developed an MCTS + BO optimization framework that searches for agent workflows, with coarse-to-fine BO for fine-tuning parameters.
- **Chart quality.** Incorporated OCR coverage into evaluation to improve readability and consistency between charts and underlying data.
- **Evaluation.** Achieved execution accuracy of **80.11%** for single-table queries and **71.86%** for multi-table queries on VisEval, with an average score of **4.14/5**.

</section>

<section class="research-project" markdown="1">

## nvBench 2.0
{: #nvbench}

**Resolving Ambiguity in Text-to-Visualization through Stepwise Reasoning**<br>
Research project &middot; July 2024 - February 2025
{: .research-meta}

Tianqi Luo, **Chuhan Huang**, Leixian Shen, Boyan Li, Shuyu Shen, Wei Zeng, Nan Tang, and Yuyu Luo.<br>
<span class="publication-badge">NeurIPS 2025</span>

[Paper](https://arxiv.org/abs/2503.12880){: .btn .btn--primary} [Project website](https://nvbench2.github.io/){: .btn}

{% include research-figure.html path="/images/research/nvbench2-framework.png" alt="nvBench 2.0 framework for ambiguous text-to-visualization queries" caption="Overview of the nvBench 2.0 framework." %}

### Benchmark and contributions

- **Benchmark.** Contributed to a benchmark of **7,878 natural language queries** and **24,076 visualization queries**, supporting ambiguous requests and multiple valid outputs.
- **Data and evaluation.** Implemented data augmentation and reverse-synthesis pipelines in Python, and evaluated language models including GPT-4o and Qwen2.5-7B.
- **Reasoning.** Contributed to a stepwise reasoning approach for improving text-to-visualization performance under ambiguity.
- **Results.** In project experiments, the Step-NL2VIS model reached **80.88% F1@5**, with a reported **21.85% improvement over GPT-4o**.

</section>
