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


<span class="anchor" id="about-me"></span>

Hello! 👋 I am **Shuai Wang**, a Ph.D. student at the University of Electronic Science and Technology of China (UESTC).

My research interests broadly include **Brain-inspired Computing**, **Spiking Neural Networks**, **Efficient Vision and Multimodal Models**, **Event-based Tracking**, and **Model Compression**. My goal is to develop accurate, efficient, and hardware-friendly neural networks for real-world intelligent systems.

I have published research papers at major artificial intelligence and computer vision conferences, including **ICLR**, **NeurIPS**, and **CVPR**. My Google Scholar citation record is available here:

[![Google Scholar](https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations)](https://scholar.google.com/citations?user=89j9Uu4AAAAJ)

Please feel free to contact me via [Email](mailto:wangshuai718@std.uestc.edu.cn) for research discussions and collaborations.


<span class="anchor" id="education"></span>

# 📖 Education

- *[TODO: 开始年份] - Present*, Ph.D. Student, **University of Electronic Science and Technology of China (UESTC)**.
- *[TODO: 开始年份] - [TODO: 毕业年份]*, [B.Eng./M.Eng.] in **[专业名称]**, **[学校名称]**.


<span class="anchor" id="honors-and-awards"></span>

# 🎖 Honors and Awards

- *2025*, **Spotlight Paper**, NeurIPS 2025, for “Bipolar Self-attention for Spiking Transformers.”
- *[TODO: 日期]*, **[奖项名称]**, [颁发单位或比赛名称].
- *[TODO: 日期]*, **[奖项名称]**, [颁发单位或比赛名称].


<span class="anchor" id="internships"></span>

# 💻 Internships

- *[TODO: 开始时间] - [TODO: 结束时间]*, **[公司或研究机构]**, [部门或课题组名称].  
  Research topic: [研究内容，例如 multimodal learning、SNN、tracking].


<span class="anchor" id="academic-services"></span>

# 💬 Academic Services

- **Conference Reviewer:** [TODO: NeurIPS / ICLR / ICML / AAAI 等，请只填写实际审稿经历].
- **Journal Reviewer:** [TODO: 期刊名称].
- **Other Services:** [TODO: 学术组织、会议志愿者、开源社区等].


<span class="anchor" id="publications"></span>

# 📝 Selected Publications

## First Author


<div class="paper-box">
<div class="paper-box-image">
<div>
<div class="badge">NeurIPS 2025 Spotlight</div>
<img src="/images/bsa.png" alt="Bipolar Self-attention" width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[Bipolar Self-attention for Spiking Transformers](https://papers.nips.cc/paper_files/paper/2025/hash/9316cfcb0a81e53a1f35b4353f115571-Abstract-Conference.html)

**Shuai Wang**, Malu Zhang, Jingya Wang, Dehao Zhang, Yimeng Shan, Jieyuan Zhang, Yichen Xiao, Honglin Cao, Haonan Zhang, Zeyu Ma, Yang Yang, Haizhou Li

**NeurIPS 2025, Spotlight**

- Introduces Bipolar Self-attention to model multi-polar membrane-potential interactions in spiking Transformers.
- Proposes Shiftmax for efficient and accurate spike-driven attention allocation.

[Paper](https://papers.nips.cc/paper_files/paper/2025/hash/9316cfcb0a81e53a1f35b4353f115571-Abstract-Conference.html) |
[OpenReview](https://openreview.net/forum?id=nG45z7lJ7D)

</div>
</div>


<div class="paper-box">
<div class="paper-box-image">
<div>
<div class="badge">ICLR 2025</div>
<img src="/images/saccadic_attention.png" alt="Saccadic Attention" width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[Spiking Vision Transformer with Saccadic Attention](https://openreview.net/forum?id=qzZsz6MuEq)

**Shuai Wang**, Malu Zhang, Dehao Zhang, Ammar Belatreche, Yichen Xiao, Yu Liang, Yimeng Shan, Qian Sun, Enqi Zhang, Yang Yang

**ICLR 2025**

- Introduces Saccadic Spike Self-Attention for improving spatial relevance and temporal interaction in spiking Vision Transformers.
- Achieves efficient visual modeling with linear computational complexity.

[Paper](https://openreview.net/forum?id=qzZsz6MuEq) |
[arXiv](https://arxiv.org/abs/2502.12677)

</div>
</div>


<div class="paper-box">
<div class="paper-box-image">
<div>
<div class="badge">ICLR 2026</div>
<img src="/images/robust_snn.png" alt="Robust Spiking Neural Networks" width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[Robust Spiking Neural Networks Against Adversarial Attacks](https://openreview.net/forum?id=qTqAL2t8Aa)

**Shuai Wang**, Malu Zhang, Yulin Jiang, Dehao Zhang, Ammar Belatreche, Yu Liang, Yimeng Shan, Zijian Zhou, Yang Yang, Haizhou Li

**ICLR 2026**

- Studies why threshold-neighboring spiking neurons limit adversarial robustness.
- Introduces Threshold Guarding Optimization to improve the robustness of directly trained SNNs.

[Paper](https://openreview.net/forum?id=qTqAL2t8Aa) |
[arXiv](https://arxiv.org/abs/2602.20548)

</div>
</div>


## Co-author


<div class="paper-box">
<div class="paper-box-image">
<div>
<div class="badge">CVPR 2026 Oral</div>
<img src="/images/sdtrack.png" alt="SDTrack" width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[SDTrack: A Baseline for Event-based Tracking via Spiking Neural Networks](https://openaccess.thecvf.com/content/CVPR2026/html/Shan_SDTrack_A_Baseline_for_Event-based_Tracking_via_Spiking_Neural_Networks_CVPR_2026_paper.html)

Yimeng Shan, Zhenbang Ren, Haodi Wu, Wenjie Wei, Rui-Jie Zhu, **Shuai Wang**, et al.

**CVPR 2026, Oral**

- Develops a Transformer-based, fully spike-driven pipeline for event-based object tracking.
- Achieves competitive tracking performance with low parameter count and energy consumption.

[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Shan_SDTrack_A_Baseline_for_Event-based_Tracking_via_Spiking_Neural_Networks_CVPR_2026_paper.html) |
[Code](https://github.com/YmShan/SDTrack)

</div>
</div>
