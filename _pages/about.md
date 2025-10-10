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
Dongping Liao (廖东平) is now a postdoc researcher at University of Macau. In 2024, he received his Ph.D. degree in computer science from the Faculty of Science and Technology, University of Macau, Taipa, China. Before that, he received B.S. (2016) and M.S. (2019) degrees in the School of Astronautics from Beihang University, during which he dedicated on cooperative perception and planing of Unmanned Aerial Vehicles (UAVs) and Robots (Multi-agent System). 
His current research interests include distributed optimization, class imbalance learning and multi-modal models.


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Two papers (one first author) are accepted by NeurIPS 2025. 
- *2025.08*: &nbsp;🎉🎉 One co-authored paper is accepted by EMNLP 2025 (main conference). 
- *2025.04*: &nbsp;🎉🎉 One co-authored paper is accepted by CVPR 2025. 
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by AAAI 2025. 
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by AAAI 2024. 
- *2023.02*: &nbsp;🎉🎉 One paper is accepted by CVPR 2023. 

# 📝 Publications 

**2025**


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/paper-flip-overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLiP: Towards Comprehensive and Reliable Evaluation of Federated Prompt Learning](https://arxiv.org/abs/2503.22263)

**Dongping Liao**, Xitong Gao, Chengzhong Xu

- To date, the reliable evaluation of federated prompt learning (FPL) algorithms for vision tasks remains an understudied area in current research. In this work, we introduce a comprehensive benchmark, named FLiP, to evaluate FPL algorithms. FLiP assesses the performance of 13 state-of-the-art centralized and FPL methods across 3 FL protocols and 12 open datasets, considering 6 distinct evaluation scenarios. Our findings demonstrate that PL maintains strong generalization performance in both in-distribution and out-of-distribution settings with minimal resource consumption. This work highlights the suitable application scenarios of each FPL algorithm in various environments characterized by data scarcity, unseen classes, and cross-domain distributional shifts.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/paper-mixsga-overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mixture of Weight-shared Heterogeneous Group Attention Experts for Dynamic Token-wise KV Optimization](https://arxiv.org/pdf/2506.13541)

Guanghui Song, **Dongping Liao**, Yiren Zhao, Kejiang Ye, Cheng-zhong Xu, Xitong Gao

- Transformer models face scalability challenges in causal language modeling (CLM) due to inefficient memory allocation for growing keyvalue (KV) caches, which strains compute and storage resources. Existing methods like Grouped Query Attention (GQA) and tokenlevel KV optimization improve efficiency but rely on rigid resource allocation, often discarding “low-priority” tokens or statically grouping them, failing to address the dynamic spectrum of token importance. We propose mixSGA, a novel mixture-of-expert (MoE) approach that dynamically optimizes token-wise computation and memory allocation. Unlike prior approaches, mixSGA retains all tokens while adaptively routing them to specialized experts with varying KV group sizes, balancing granularity and efficiency.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/paper-fedpdm-overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Progressive Distribution Matching for Federated Semi-supervised Learning](https://ojs.aaai.org/index.php/AAAI/article/view/32551)

**Dongping Liao**, Xitong Gao, Yabo Xu, Chengzhong Xu

- We observe the distribution mismatch phenomenon of federated semi-supervised learning and propose to leverage Optimal Transport to align the distribution of unlabeled data.
</div>
</div>

**2024**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/paper-ipad-overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Impartial Adversarial Distillation: Addressing Biased Data-free Knowledge Distillation via Adaptive Constrained Optimization](https://ojs.aaai.org/index.php/AAAI/article/view/28120)

**Dongping Liao**, Xitong Gao, Chengzhong Xu

- We observe an interesting phenomenon when exploring the *biased adversarial data-free knowledge distillation* problem, which has a diverse impact on different groups of synthetic data. We put forward an adaptive constrained optimization framework to balance the KL divergence of the majority and minority classes.
</div>
</div>

**2023**


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/paper-flado-overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive Channel Sparsity for Federated Learning under System Heterogeneity](https://openaccess.thecvf.com/content/CVPR2023/papers/Liao_Adaptive_Channel_Sparsity_for_Federated_Learning_Under_System_Heterogeneity_CVPR_2023_paper.pdf)

**Dongping Liao**, Xitong Gao, Yiren Zhao, Chengzhong Xu

- We figure out the coupling effect of data and system heterogeneity under federated training, namely, the gradient deviation among client models. We propose Flado, which is equipped with adaptive channel sparsity layers to address the conflicting gradient problem while achieving computational efficiency. 
</div>
</div>

# 🎖 Honors and Awards
- *2018.06* The second place for Gomoku AI Competition, DeepGlint
- *2019.03* Outstanding academic publication award for master student, Beihang University. 
- *2019.06* Macau Ph.D. scholarship (1,000,000 MOP), University of Macau. 

<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=WYPUyek2JoLfJkFYzz0xq0foo5Zcx8BuXFP0ODkcy1w&cl=ffffff&w=a"></script> -->

---

<div align="center">
    <a href="https://clustrmaps.com/site/1c6jc"  title="ClustrMaps">
        <img src="//www.clustrmaps.com/map_v2.png?d=WYPUyek2JoLfJkFYzz0xq0foo5Zcx8BuXFP0ODkcy1w&cl=ffffff&w=300" width="300" />
    </a>
</div>

---

<p style="color:#787878;margin-top:0;text-align:center">© Copyright 2025 Dongping Liao</p>
<p style="color:#787878;margin-top:0;text-align:center">Last Updated: June 10th, 2025</p>