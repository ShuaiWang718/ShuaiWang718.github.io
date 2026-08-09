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

Hello! 👋 I am **Shuai Wang (王帅)**, a Ph.D. candidate in the School of Computer Science and Engineering at the **University of Electronic Science and Technology of China (UESTC)**. I am pursuing a combined M.S.–Ph.D. program and expect to graduate in June 2027. From September 2026, I will join the **Language Model and Human–Computer Interaction Center at Shenzhen Loop Area Institute** as an Academic Elite joint-training researcher.

My research focuses on **brain-inspired computing**, **spiking neural networks**, **efficient multimodal models**, **event-based object tracking**, and **model compression**. I am particularly interested in developing accurate, energy-efficient, and hardware-friendly spiking models for visual, auditory, and multimodal intelligence on resource-constrained edge platforms.

I have published more than 20 papers in CCF-A conferences and top-tier journals, including eight first-author papers and two corresponding-author papers. Representative works have appeared at **NeurIPS, ICLR, ICML, CVPR, AAAI, IEEE TNNLS**, and **Neural Networks**.

[Email](mailto:wangshuai718@std.uestc.edu.cn) ·
[Google Scholar](https://scholar.google.com/citations?user=89j9Uu4AAAAJ) ·
[GitHub](https://github.com/Hachi-Zhang) ·
[Citation Record](https://scholar.google.com/citations?user=89j9Uu4AAAAJ)
<a href="https://scholar.google.com/citations?user=89j9Uu4AAAAJ"><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations"></a>


<span class="anchor" id="education"></span>

# 📖 Education and Experience

- *2021.09 – 2027.06 (Expected)*, Ph.D. Candidate, School of Computer Science and Engineering, **University of Electronic Science and Technology of China (UESTC)**, Chengdu, China.
- *2026.09 – 2027.06 (Expected)*, Academic Elite Joint-Training Researcher, Language Model and Human–Computer Interaction Center, **Shenzhen Loop Area Institute**, Shenzhen, China.
- *2016.09 – 2020.06*, B.Eng., School of Computer Science and Technology, **Xidian University**, Xi'an, China.


<span class="anchor" id="research-interests"></span>

# 🔬 Research Interests

- Brain-inspired computing and spiking neural networks
- Spiking Transformers and efficient sequence modeling
- Multimodal brain-inspired models for edge intelligence
- Event-based vision and object tracking
- Quantization, pruning, distillation, and hardware-efficient deployment


<span class="anchor" id="honors-and-awards"></span>

# 🎖 Honors and Awards

- *2026.06*, **First Prize Award**, ACM Multimedia 2026 AdoDAS Emotion Analysis Challenge (CCF-A).
- *2025.08*, **Best Dataset & Benchmark Award**, IJCAI 2025 Spike-CV Challenge (CCF-A).
- *2025.10*, **National Scholarship for Ph.D. Students（博士国家奖学金）**, Ministry of Education of China.
- *2026.03*, **Academic Rising Star（学术精英）**, University of Electronic Science and Technology of China.
- *2025*, **Spotlight Paper (Top 3%)**, NeurIPS 2025, for *Bipolar Self-attention for Spiking Transformers*.
- *2025*, **Oral Paper （Top 0.96%）**, CVPR 2025, for *Rethinking Spiking Self-Attention Mechanism: Implementing α-XNOR Similarity Calculation in Spiking Transformers*.


<span class="anchor" id="academic-services"></span>

# 💬 Academic Services

- **Conference Reviewer:** NeurIPS, ICML, ICLR, CVPR, ICCV, ECCV, AAAI, and ACM Multimedia.
- **Journal Reviewer:** IEEE Transactions on Neural Networks and Learning Systems, IEEE Transactions on Emerging Topics in Computational Intelligence, IEEE Transactions on Cognitive and Developmental Systems, Neural Networks, and Neurocomputing.


<span class="anchor" id="research-projects"></span>
<span class="anchor" id="internships"></span>

# 🧪 Research Projects

- *2026.01 – 2028.12*, **Multi-Brain-Region Collaborative Brain-Inspired Modeling with Spiking Neural Networks**, General Program of the National Natural Science Foundation of China. *Key Researcher.*  
  Responsible for biologically inspired visual-pathway modeling and the development of a saccadic Spiking Transformer for active spatiotemporal perception.

- *2024.03 – 2024.12*, **Spiking Neural Networks for Remote-Sensing Object Detection**, Aerospace Innovation Institute. *Student Lead.*  
  Developed an adaptive-bit-width spiking detector and achieved less than a 2% performance degradation under 2-bit model compression. Also led project documentation and the final technical defense.

- *2022.01 – 2024.12*, **Multimodal Brain-Inspired Models Based on Deep Spiking Neural Networks**, Young Scientists Fund of the National Natural Science Foundation of China. *Key Researcher.*  
  Worked on keyword spotting, sound-source localization, EEG classification, and adversarial robustness using spiking neural networks.


<span class="anchor" id="publications"></span>

# 📝 Selected Publications

<sup>†</sup> Equal contribution. <sup>*</sup> Corresponding author. My name is shown in **bold**.


## Representative Papers

<!-- Replace images/500x300.png with images/bsa.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">NeurIPS 2025 Spotlight</div><img src="images/nips2025.png" alt="Bipolar Self-attention for Spiking Transformers" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Bipolar Self-attention for Spiking Transformers](https://papers.nips.cc/paper_files/paper/2025/hash/9316cfcb0a81e53a1f35b4353f115571-Abstract-Conference.html)

**Shuai Wang**, Malu Zhang, Jingya Wang, Dehao Zhang, Yimeng Shan, Jieyuan Zhang, Yichen Xiao, Honglin Cao, Haonan Zhang, Zeyu Ma, Yang Yang, Haizhou Li

**NeurIPS 2025, Spotlight (Top 3%)**

<div class="pub-tags">
  <span class="pub-tag pub-tag--ccfa">CCF-A</span>
  <span class="pub-tag pub-tag--spotlight">Spotlight</span>
</div>

- Introduces bipolar self-attention to model multi-polar membrane-potential interactions in Spiking Transformers.
- Develops Shiftmax for efficient low-entropy attention allocation while preserving spike-driven computation.

[[Paper]](https://papers.nips.cc/paper_files/paper/2025/hash/9316cfcb0a81e53a1f35b4353f115571-Abstract-Conference.html)
[[OpenReview]](https://openreview.net/forum?id=nG45z7lJ7D)

</div></div>


<!-- Replace images/500x300.png with images/saccadic_attention.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICLR 2025</div><img src="images/iclr2025.png" alt="Spiking Vision Transformer with Saccadic Attention" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Spiking Vision Transformer with Saccadic Attention](https://openreview.net/forum?id=qzZsz6MuEq)

**Shuai Wang**, Malu Zhang, Dehao Zhang, Ammar Belatreche, Yichen Xiao, Yu Liang, Yimeng Shan, Qian Sun, Enqi Zhang, Yang Yang

**ICLR 2025**

- Introduces Saccadic Spike Self-Attention to improve spatial relevance and temporal interactions in Spiking Vision Transformers.
- Achieves strong performance across visual tasks with linear computational complexity.

[[Paper]](https://openreview.net/forum?id=qzZsz6MuEq)
[[arXiv]](https://arxiv.org/abs/2502.12677)

</div></div>


<!-- Replace images/500x300.png with images/robust_snn.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICLR 2026</div><img src="images/iclr2026.png" alt="Robust Spiking Neural Networks Against Adversarial Attacks" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Robust Spiking Neural Networks Against Adversarial Attacks](https://openreview.net/forum?id=qTqAL2t8Aa)

**Shuai Wang**, Malu Zhang, Yulin Jiang, Dehao Zhang, Ammar Belatreche, Yu Liang, Yimeng Shan, Zijian Zhou, Yang Yang, Haizhou Li

**ICLR 2026**

- Identifies threshold-neighboring neurons as a key factor limiting adversarial robustness in directly trained SNNs.
- Proposes Threshold Guarding Optimization to reduce state flipping under small perturbations.

[[Paper]](https://openreview.net/forum?id=qTqAL2t8Aa)
[[arXiv]](https://arxiv.org/abs/2602.20548)

</div></div>


<!-- Replace images/500x300.png with images/snn_ft.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">IEEE TNNLS</div><img src="images/tnnls2025.png" alt="SNN-FT" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[SNN-FT: Temporal-Coded Spiking Neural Networks for Fourier Transform](https://doi.org/10.1109/TNNLS.2025.3622893)

**Shuai Wang**, Haorui Zheng, Yukun Chen, Ammar Belatreche, Guoqing Wang, Yeying Jin, Jibin Wu, Malu Zhang, Yang Yang, Haizhou Li

**IEEE Transactions on Neural Networks and Learning Systems, 2026**

- Develops a temporal-coded spiking implementation of the Fourier transform.
- Provides an efficient neuromorphic signal-processing primitive with reduced latency and energy consumption.

[[Paper]](https://doi.org/10.1109/TNNLS.2025.3622893)

</div></div>


<!-- Replace images/500x300.png with images/xnor_attention.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2025 Oral</div><img src="images/cvpr2025.png" alt="Alpha-XNOR Spiking Self-Attention" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Rethinking Spiking Self-Attention Mechanism: Implementing α-XNOR Similarity Calculation in Spiking Transformers](https://openaccess.thecvf.com/content/CVPR2025/html/Xiao_Rethinking_Spiking_Self-Attention_Mechanism_Implementing_a-XNOR_Similarity_Calculation_in_Spiking_CVPR_2025_paper.html)

Yichen Xiao<sup>†</sup>, **Shuai Wang**<sup>†</sup>, Dehao Zhang, Wenjie Wei, Yimeng Shan, Xiaoli Liu, Yulin Jiang, Malu Zhang

**CVPR 2025, Oral**

- Rethinks binary similarity estimation in Spiking Transformers through an α-XNOR attention mechanism.
- **Equal contribution.**

[[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Xiao_Rethinking_Spiking_Self-Attention_Mechanism_Implementing_a-XNOR_Similarity_Calculation_in_Spiking_CVPR_2025_paper.html)

</div></div>


<!-- Replace images/500x300.png with images/ternary_system.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Neural Networks 2025</div><img src="images/nn2025.png" alt="Ternary Spike-Based Neuromorphic Signal Processing System" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Ternary Spike-Based Neuromorphic Signal Processing System](https://doi.org/10.1016/j.neunet.2025.107333)

**Shuai Wang**, Dehao Zhang, Ammar Belatreche, Yichen Xiao, Hongyu Qing, Wenjie Wei, Malu Zhang, Yang Yang

**Neural Networks, 187:107333, 2025**

- Develops threshold-adaptive encoding and a quantized ternary SNN for efficient signal processing.
- Supports speech and EEG recognition with substantially reduced memory and energy consumption.

[[Paper]](https://doi.org/10.1016/j.neunet.2025.107333)
[[arXiv]](https://arxiv.org/abs/2407.05310)

</div></div>


<!-- Replace images/500x300.png with images/sound_localization.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">NeurIPS 2024</div><img src="images/nips2024.png" alt="Spike-Based Neuromorphic Model for Sound Source Localization" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Spike-Based Neuromorphic Model for Sound Source Localization](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ce953d71deeb33d9ffa2c879b518d273-Abstract-Conference.html)

Dehao Zhang<sup>†</sup>, **Shuai Wang**<sup>†</sup>, Ammar Belatreche, Wenjie Wei, Yichen Xiao, Haorui Zheng, Zijian Zhou, Malu Zhang, Yang Yang

**NeurIPS 2024** · **Equal contribution**

- Integrates phase-locking auditory encoding with spike-based neural computation for sound-source localization.
- Uses Resonate-and-Fire neurons to capture biologically meaningful spectral and temporal cues.

[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ce953d71deeb33d9ffa2c879b518d273-Abstract-Conference.html)
[[OpenReview]](https://openreview.net/forum?id=CyCDqnrymT)

</div></div>


<!-- Replace images/500x300.png with images/keyword_spotting.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">INTERSPEECH 2024</div><img src="images/interspeech2024.png" alt="Global-Local Convolution for Keyword Spotting" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Global-Local Convolution with Spiking Neural Networks for Energy-Efficient Keyword Spotting](https://www.isca-archive.org/interspeech_2024/wang24p_interspeech.html)

**Shuai Wang**, Dehao Zhang, Kexin Shi, Yuchen Wang, Wenjie Wei, Jibin Wu, Malu Zhang

**INTERSPEECH 2024**, pp. 4523–4527

- Introduces Global-Local Spiking Convolution for sparse and energy-efficient speech feature extraction.
- Combines it with a Bottleneck-PLIF module to achieve competitive accuracy with a compact model.

[[Paper]](https://www.isca-archive.org/interspeech_2024/wang24p_interspeech.html)
[[PDF]](https://www.isca-archive.org/interspeech_2024/wang24p_interspeech.pdf)

</div></div>


<!-- Replace images/500x300.png with images/activation_aware_conversion.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">AAAI 2026</div><img src="images/aaai2026.png" alt="Activation-Aware ANN-to-SNN Conversion" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Towards Training-Free and Accurate ANN-to-SNN Conversion via Activation-Aware Redistribution](https://ojs.aaai.org/index.php/AAAI/article/view/37148)

Honglin Cao, **Shuai Wang**<sup>*</sup>, Zijian Zhou, Ammar Belatreche, Wenjie Wei, Yu Liang, Yang Yang, Rui Xi, Malu Zhang, Haizhou Li

**AAAI 2026** · **Corresponding author**

- Introduces activation-aware redistribution to reduce the mismatch between ANN activations and SNN firing rates.
- Enables accurate, low-latency ANN-to-SNN conversion without retraining.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/37148)
[[PDF]](https://ojs.aaai.org/index.php/AAAI/article/view/37148/41110)

</div></div>


<!-- Replace images/500x300.png with images/spikinglm.png after uploading the paper thumbnail. -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICML 2026</div><img src="images/icml2026.png" alt="SpikingLM" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[SpikingLM: Towards Fully Spiking Language Model](https://openreview.net/forum?id=RirE9gm77w)

Yu Liang, Zijian Zhou, Wenjie Wei, **Shuai Wang**<sup>*</sup>, Honglin Cao, Ammar Belatreche, Yu Yang, Malu Zhang, Yang Yang, Haizhou Li

**ICML 2026** · **Corresponding author**

- Develops a fully spiking architecture for efficient language modeling.
- Replaces major dense ANN operations with spike-driven computation while retaining competitive language-modeling capability.

[[Paper]](https://openreview.net/forum?id=RirE9gm77w)

</div></div>


## Additional Selected Papers

1. Malu Zhang, **Shuai Wang**, Jibin Wu, Wenjie Wei, Dehao Zhang, Zijian Zhou, Siying Wang, Fan Zhang, Yang Yang. Toward Energy-Efficient Spike-Based Deep Reinforcement Learning with Temporal Coding. **IEEE Computational Intelligence Magazine**, 20(2):45–57, 2025.

2. Dehao Zhang, Malu Zhang, **Shuai Wang**, Jingya Wang, Wenjie Wei, Zeyu Ma, Guoqing Wang, Yang Yang, Haizhou Li. [Dendritic Resonate-and-Fire Neuron for Effective and Efficient Long Sequence Modeling](https://papers.nips.cc/paper_files/paper/2025/hash/9a6ca401f890aeb2c272d2bb26196d3f-Abstract-Conference.html). **NeurIPS 2025**.

3. Jieyuan Zhang, Xiaolong Zhou, **Shuai Wang**, Wenjie Wei, Hanwen Liu, Qian Sun, Malu Zhang, Yang Yang, Haizhou Li. Unveiling the Spatial-Temporal Effective Receptive Fields of Spiking Neural Networks. **NeurIPS 2025**.

4. Wenjie Wei, Malu Zhang, Jieyuan Zhang, Ammar Belatreche, **Shuai Wang**, Yimeng Shan, Hanwen Liu, Honglin Cao, Guoqing Wang, Yang Yang, et al. [S²NN: Sub-Bit Spiking Neural Networks](https://arxiv.org/abs/2509.24266). **NeurIPS 2025**.

5. Dehao Zhang, **Shuai Wang**, Yichen Xiao, Wenjie Wei, Yimeng Shan, Malu Zhang, Yang Yang. [Memory-Free and Parallel Computation for Quantized Spiking Neural Networks](https://arxiv.org/abs/2503.00040). **ICASSP 2025**.

6. Yu Liang, Yu Yang, Wenjie Wei, Ammar Belatreche, **Shuai Wang**, Malu Zhang, Yang Yang. [BSO: Binary Spiking Online Optimization Algorithm](https://proceedings.mlr.press/v267/liang25r.html). **ICML 2025**.

7. Yu Liang, Wenjie Wei, Ammar Belatreche, **Shuai Wang**, Malu Zhang, Yang Yang. Towards Accurate Binary Spiking Neural Networks: Learning with Adaptive Gradient Modulation Mechanism. **AAAI 2025, Oral**.

8. Kexin Shi, Hanwen Liu, Zeyang Song, Yang Liu, Jieyuan Zhang, **Shuai Wang**, Jibin Wu, Malu Zhang, Yang Yang. [Temporal Interaction in Spiking Transformers with Multi-Delay Mixer](https://openaccess.thecvf.com/content/CVPR2026/html/Shi_Temporal_Interaction_in_Spiking_Transformers_with_Multi-Delay_Mixer_CVPR_2026_paper.html). **CVPR 2026**.

9. Jingya Wang, Xin Deng, Wenjie Wei, Dehao Zhang, **Shuai Wang**, Qian Sun, Jieyuan Zhang, Hanwen Liu, Ning Xie, Malu Zhang. [Training-Free ANN-to-SNN Conversion for High-Performance Spiking Transformers](https://ojs.aaai.org/index.php/AAAI/article/view/37195). **AAAI 2026**.


## Preprints and Manuscripts

1. **Shuai Wang**, Malu Zhang, Dehao Zhang, Yimeng Shan, Jieyuan Zhang, Siqi Cai, Jibin Wu, Yang Yang, Huajin Tang, Haizhou Li. Towards High-Performance and Energy-Efficient Spiking Transformers with Bipolar Self-Attention. *Manuscript under review.*

2. **Shuai Wang**, Jieyuan Zhang, Yang Yang, Huajin Tang, Haizhou Li. Algorithm–Hardware Co-Design of Binary Spiking Transformers for Edge Intelligence. *Manuscript under review.*
