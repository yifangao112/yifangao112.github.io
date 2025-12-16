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

# 🧑‍🎓 About me
I'm a Ph.D student at School of Biomedical Engineering, University of Science and Technology of China. I'm also pursuing my doctoral studies at the Shanghai Innovation Institute (上海创智学院) through a joint program, advised by Prof. [Xiaosong Wang](https://scholar.google.com/citations?user=c66GnOEAAAAJ&hl=en) and Prof. [Xin Gao](http://sibet.cas.cn/sourcedb/zw/yjdw/yjy/201306/t20130621_3879548.html). Prior to this, I obtained my bachelor's degree in biomedical engineering from Northeastern University in 2022. My research interests include medical image analysis and AI in medicine, with a particular focus on developing **Foundation models** and **AI agents** for healthcare applications. My goal is to address medical challenges through computational methods and contribute to improving the quality of healthcare. 

In addition to my academic pursuits, I have a keen interest in sports and game data analysis. I maintain [PAGE](https://ieeexplore.ieee.org/abstract/document/10123061), a large-scale annotated database of professional Go games. I am also the developer of DeepKylin, an AlphaZero-like AI agent for Gomoku. It won the [National Computer Game Tournament](http://computergames.caai.cn/) in both 2020 and 2021.

# 🔥 News
- *2025.12*: &nbsp;🎉🎉 Our work is accepted at **Medical Image Analysis** (IF=11.8).
- *2025.07*: &nbsp;🎉🎉 Two papers are accepted at **Engineering Applications of Artificial Intelligence** (IF=8.0).
- *2025.06*: &nbsp;🎉🎉 Three papers are accepted at **MICCAI 2025**.
- *2025.01*: &nbsp;🎉🎉 Our work is accepted at **International Journal of Surgery** (IF=12.5).
- *2024.11*: &nbsp;🎉🎉 Received the **Shenyang Natural Science Academic Achievement** (First Prize, First Student Contributor), 2024.
- *2024.06*: &nbsp;🎉🎉 Two papers are accepted at **MICCAI 2024**! 
- *2023.12*: &nbsp;🎉🎉 Our work is accepted at **IEEE Transactions on Games** (IF=2.3).
- *2023.05*: &nbsp;🎉🎉 Our work is accepted at **Computers in Biology and Medicine** (IF=7.7).
- *2022.06*: &nbsp;🎉🎉 Received the **Excellence Scholarship**, Northeastern University, 2022.

# 📖 Education
- 2024 - present, Ph.D. in Artificial Intelligence, Shanghai Innovation Institute, Shanghai, China 
- 2024 - present, Ph.D. in Biomedical Engineering, University of Science and Technology of China, Hefei, China 
- 2022 - 2024, M.Sc. in Biomedical Engineering, University of Science and Technology of China, Hefei, China 
- 2018 - 2022, B.E. in Biomedical Engineering, Northeastern University, Shenyang, China. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MedIA 2025</div><img src='images/cianet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CIA-Net: Cross-modality Interaction and Aggregation Network for Ovarian Tumor Segmentation from Multi-modal MRI](https://www.sciencedirect.com/science/article/abs/pii/S1361841525004530)

**Yifan Gao**, Yong’ai Li, Xin Gao

**MICCAI 2025**

[**Project**](https://www.sciencedirect.com/science/article/abs/pii/S1361841525004530)
- This paper proposes CIA-Net, a novel hybrid architecture for ovarian tumor segmentation that treats T2-weighted MRI as the primary modality while selectively integrating complementary features from minor modalities to reduce noise and redundancy. Validated on a large multi-center dataset and public benchmarks, the method achieves state-of-the-art performance by effectively handling the heterogeneous and complex nature of ovarian tumors.</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025</div><img src='images/safeclick.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SafeClick: Error-Tolerant Interactive Segmentation of Any Medical Volumes via Hierarchical Expert Consensus](https://link.springer.com/chapter/10.1007/978-3-032-04965-0_46)

**Yifan Gao#**, Jiaxi Sheng#, Wenbin Wu, Haoyue Li, Yaoxian Dong, Chaoyang Ge, Feng Yuan, Xin Gao

**MICCAI 2025**

[**Project**](https://github.com/yifangao112/SafeClick)
- SafeClick is an error-tolerant interactive segmentation approach that uses hierarchical expert consensus to handle imperfect user prompts. As a plug-and-play module compatible with foundation models like SAM 2, it significantly improves segmentation accuracy and robustness across 15 public datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025</div><img src='images/caaseg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Composite Alignment-Aware Framework for Myocardial Lesion Segmentation in Multi-sequence CMR Images](https://link.springer.com/chapter/10.1007/978-3-032-04927-8_1)

**Yifan Gao**, Shaohao Rui, Haoyang Su, Jinyi Xiang, Lianming Wu, Xiaosong Wang

**MICCAI 2025**

[**Project**](https://github.com/yifangao112/CAA-Seg)
- CAA-Seg addresses spatial misalignment and intensity variations in multi-sequence CMR images through selective slice alignment and hierarchical feature alignment. It achieves superior performance in myocardial lesion segmentation, particularly for myocardial infarction, on a large-scale dataset.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI 2025</div><img src='images/prnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prior-driven refinement network for small organ-at-risk segmentation in head and neck cancer](https://www.sciencedirect.com/science/article/abs/pii/S0952197625016070)

Taibao Wang#, **Yifan Gao#**, Bingyu Liang, Qin Wang

**Engineering Applications of Artificial Intelligence**

[**Project**](https://www.sciencedirect.com/science/article/abs/pii/S0952197625016070)
- PRNet is a prior-driven refinement network that leverages foundation models and domain-specific knowledge for small organ-at-risk segmentation. It incorporates a prior encoder and mask refinement transformer to improve accuracy, demonstrating superior performance on multiple public datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/dinounet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dino U-Net: Exploiting High-Fidelity Dense Features from Foundation Models for Medical Image Segmentation](https://arxiv.org/abs/2508.20909)

**Yifan Gao**, Haoyue Li, Feng Yuan, Xiaosong Wang, Xin Gao

**arXiv 2025**

[**Project**](https://github.com/yifangao112/DinoUNet)
- Dino U-Net exploits high-fidelity dense features from the DINOv3 foundation model for medical image segmentation. It features a fidelity-aware projection module to preserve feature quality, achieving state-of-the-art performance and scalability across diverse medical imaging datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJS 2024</div><img src='images/larynxllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multimodal Large Language Models Address Clinical Queries in Laryngeal Cancer Surgery: A Comparative Evaluation of Image Interpretation Across Different Models](https://pubmed.ncbi.nlm.nih.gov/39869389/)

Bingyu Liang#, **Yifan Gao#**, Taibao Wang, Lei Zhang, Qin Wang

**International Journal of Surgery**

[**Project**](https://pubmed.ncbi.nlm.nih.gov/39869389/)
- Six multimodal large language models (MLLMs) were evaluated across 6 image types, 169 images, and 1084 open-ended clinical questions in laryngeal cancer surgery. Advanced MLLMs demonstrate high accuracy (up to 79.43%) in interpreting diverse image modalities, with commercial models outperforming open-source alternatives. MLLMs show potential to enhance clinical decision-making across the surgical timeline of laryngeal cancer, from preoperative planning to post-operative care.
 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/desam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeSAM: Decoupled Segment Anything Model for Generalizable Medical Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_48)

**Yifan Gao**, Wei Xia, Dingdu Hu, Wenkui Wang, Xin Gao

**MICCAI 2024**

[**Project**](https://github.com/yifangao112/DeSAM)
- DeSAM addresses the performance degradation of SAM in automatic segmentation scenarios. By decoupling the mask generation process from prompts and introducing prompt-relevant IoU and prompt-decoupled mask modules, DeSAM achieves state-of-the-art performance in two public datasets. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/mbanet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MBA-Net: SAM-driven Bidirectional Aggregation Network for Ovarian Tumor Segmentation](https://link.springer.com/chapter/10.1007/978-3-031-72120-5_41)

**Yifan Gao**, Wei Xia, Wenkui Wang, Xin Gao

**MICCAI 2024**

[**Project**](https://link.springer.com/chapter/10.1007/978-3-031-72120-5_41)
- We developed MBA-Net, a novel architecture for ovarian tumor segmentation that integrates the Segment Anything Model (SAM) with domain-specific knowledge through bidirectional feature aggregation. MBA-Net demonstrates superior segmentation accuracy, robustness to tumor heterogeneity, and strong generalization capability across different imaging modalities and clinical sites. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIBM 2023</div><img src='images/parotid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Anatomy-aware Framework for Automatic Segmentation of Parotid Tumor from Multimodal MRI](https://www.sciencedirect.com/science/article/abs/pii/S0010482523004651)

**Yifan Gao#**, Yin Dai#, Fayu Liu, Weibing Chen, Lifu Shi

**Computers in Biology and Medicine**

[**Project**](https://github.com/yifangao112/PTNet)
- We propose PT-Net, a Transformer-based multimodal fusion network that effectively integrates information from three MRI modalities. By incorporating a novel anatomy-aware loss function, PT-Net significantly improves segmentation accuracy by distinguishing parotid tumors from similar surrounding anatomical structures, outperforming existing state-of-the-art methods. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ToG 2023</div><img src='images/page.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Professional Go Annotation Dataset](https://ieeexplore.ieee.org/document/10123061)

**Yifan Gao**, Danni Zhang, Haoyue Li

**IEEE Transactions on Games**

[**Project**](https://github.com/yifangao112/PAGE) 
- We present PAGE, the first large-scale dataset of professional Go games with extensive annotations. Spanning over 70 years, it contains 98,525 games played by 2,007 professional players. The dataset includes comprehensive game-level metadata and detailed in-game statistics generated by the KataGo engine, enabling advanced research in game analysis and AI. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronics 2021</div><img src='images/nogo.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Efficiently Mastering the Game of NoGo with Deep Reinforcement Learning Supported by Domain Knowledge](https://www.mdpi.com/2079-9292/10/13/1533)

**Yifan Gao#**, Lezhou Wu#

**Electronics**

[**Project**](https://www.mdpi.com/2079-9292/10/13/1533)
- We propose NoGoZero+, an enhanced AlphaZero-based agent for the game of NoGo. By introducing innovative training strategies, it achieves a 6x speedup in training and defeats the original AlphaZero agent with significantly less data (20k vs 120k games). The program was the runner-up in the 2020 China Computer Game Championship. 
</div>
</div>

- [An unsupervised anatomy-aware dual-constraint cascade network for lung computed tomography deformable image registration](https://www.sciencedirect.com/science/article/pii/S0952197625015507), Wenbin Wu, **Yifan Gao**, Xin Jin, Rui Zhang, Yuemei Pan, Xin Gao, **Engineering Applications of Artificial Intelligence**, 2025

- [EG-Net: An Edge-Guided Network for Rigid Registration of Laparoscopic Low-Overlap Point Clouds](https://ieeexplore.ieee.org/abstract/document/9619111), Wenbin Wu, **Yifan Gao**, Yixiu Wang, Jiayi Zhang, Yiming Zhao, Xin Gao, **MICCAI 2025**, 2025

- [PGD: A Large-scale Professional Go Dataset for Data-driven Analytics](https://ieeexplore.ieee.org/abstract/document/9893704), **Yifan Gao**, **IEEE Conference on Games**, 2022

- [GomokuNet: A Novel UNet-style Network for Gomoku Zero Learning via Exploiting Positional Information and Multiscale Features](https://ieeexplore.ieee.org/abstract/document/9619111), **Yifan Gao**, Lezhou Wu, Haoyue Li, **IEEE Conference on Games**, 2021

- [TransMed: Transformers Advance Multi-modal Medical Image Classification](https://www.mdpi.com/2075-4418/11/8/1384), Yin Dai, **Yifan Gao**, Fayu Liu, **Diagnostics**, 2021 (This paper was the most cited article among 3,223 papers published in this journal in 2021, according to Web of Science)

# 🏆 Honors and Awards
- Shenyang Natural Science Academic Achievement Award (First Prize, First Student Contributor), 2024
- Academic Scholarship, University of Science and Technology of China, 2022-2024
- Excellence Scholarship, Northeastern University, 2022
- National Computer Game Tournament Champion, 2020-2021
- Academic Scholarship, Northeastern University, 2018-2021

# 💻 Services
Reviewer of:
- IEEE Transactions on Medical Imaging (TMI)
- International Journal of Surgery
- IEEE Journal of Biomedical and Health Informatics (JBHI)
- Medical Image Computing and Computer Assisted Intervention (MICCAI)
- International Journal of Imaging Systems and Technology (IMA)
- PeerJ Computer Science
- IEEE Access
- Applied Sciences
- IEEE Transactions on Radiation and Plasma Medical Sciences
- Advanced Engineering Informatics
- Frontiers in Medicine
- Cell Reports Medicine

# 🏸 Hobbies
- Go (Weiqi): Certified as amateur 5 dan by Chinese Weiqi Association.
- In my spare time, I like playing badminton, tennis, and video games!
