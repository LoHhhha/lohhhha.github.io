---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Hang Long (龙航), a M.S. student at the [School of Computer Science and Technology, Huazhong University of Science and Technology](http://www.cs.hust.edu.cn/), in the [HUST Media Lab](http://media.hust.edu.cn), advised by Prof. [Wei Yang](https://weiyang-hust.github.io/).

<span class='anchor' id='-internships'></span>

# Internships
- *2026.05 - Present*, Research Scientist Intern, Meshy AI.
- *2024.07 - 2024.11*, AI Engineer Intern, Huawei Technologies Co., Ltd.
- *2024.01 - 2024.02*, AI Engineer Intern, China Southern Power Grid Company Limited.

<span class='anchor' id='-publications'></span>

# Publications 

**Equal contribution**$^\star$

**Corresponding author**$^\dagger$

<!-- LATO.2 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/LATO.2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LATO.2: Factorized 3D Mesh Generation with Vertex and Topology Flow](https://github.com/LoHhhha/LATO.2)

**Hang Long\***, Tianhao Zhao\*, Junkai Lin, Youjia Zhang, Huipeng Guo, Rendong Liang, Jiale Xu, Jozef Hladký, Matthias Nießner, Wei Yang †

[**Paper**](https://arxiv.org/pdf/2607.10623) | [**Code**](https://github.com/LoHhhha/LATO.2)
- We introduce LATO.2, a factorized flow matching framework that decomposes mesh generation into a vertex flow followed by a connectivity flow conditioned on the realized vertices, both anchored to a shared coarse voxel scaffold. LATO.2 employs dedicated VAEs to recover vertices at sub‑voxel precision and embed discrete connectivity into a continuous latent space, disentangling continuous geometry from discrete topology. This factorization enables part‑wise generation with full latent capacity per part and topology‑adaptive editing without re‑optimization, achieving superior geometric fidelity and connectivity quality over state‑of‑the‑art methods.
</div>
</div>
<!-- LATO.2 -->

<!-- LATO -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/LATO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LATO: 3D Mesh Flow Matching with Structured TOpology Preserving LAtents](https://tianhaozhao668.github.io/LATO)

Tianhao Zhao\*, Youjia Zhang\*, **Hang Long**, Jinshen Zhang, Wenbing Li, Yang Yang, Gongbo Zhang, Jozef Hladký, Matthias Nießner, Wei Yang †

<span style="color:blue"><em>International Conference on Machine Learning (ICML), 2026</em></span>

[**Project**](https://tianhaozhao668.github.io/LATO/) | [**Paper**](https://arxiv.org/pdf/2603.06357) | [**Code**](https://github.com/TianhaoZhao668/LATO)
- We introduce LATO, a topology-preserving latent representation for scalable flow-matching-based generation of explicit 3D meshes. LATO encodes a mesh as a surface-anchored Vertex Displacement Field and reconstructs vertices through progressive voxel subdivision and pruning. For generation, LATO uses a two-stage flow matching process that first synthesizes structural voxels and then refines voxel-wise topology features.
</div>
</div>
<!-- LATO -->

<!-- MeshRipple -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Highlight</div><img src='images/MeshRipple.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MeshRipple: Structured Autoregressive Generation of Artist-Meshes](https://maymhappy.github.io/MeshRipple)

Junkai Lin\*, **Hang Long\***, Huipeng Guo, Jielei Zhang, JiaYi Yang, Tianle Guo, Yang Yang, Jianwen Li, Wenxiao Zhang, Matthias Nießner, Wei Yang †

<span style="color:red"><b>Highlight</b> </span><span style="color:blue"><em>Computer Vision and Pattern Recognition (CVPR), 2026</em></span>

[**Project**](https://maymhappy.github.io/MeshRipple) | [**Paper**](https://arxiv.org/pdf/2512.07514) | [**Code**](https://github.com/MayMhappy/MeshRipple)
- We introduce MeshRipple, a mesh generation framework that expands a surface outward from an active generation frontier, akin to a ripple, to overcome the long-range dependency bottlenecks of autoregressive serialization. MeshRipple rests on three key innovations: a frontier‑aware BFS tokenization that aligns generation order with surface topology; an expansive prediction strategy that sustains coherent, connected growth; and a sparse‑attention global memory that offers an effectively unbounded receptive field for resolving long‑range topological dependencies. This integrated design enables MeshRipple to generate meshes with high surface fidelity and topological completeness, surpassing strong recent baselines.
</div>
</div>
<!-- MeshRipple -->

<!-- # 🎖 Honors and Awards -->

<span class='anchor' id='-educations'></span>

# Educations
- *2025.09 - Present*, Master, Huazhong University of Science and Technology.
- *2021.09 - 2025.06*, Undergraduate, Jinan University.
