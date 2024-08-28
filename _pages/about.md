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
I'm a **Ph.D student in School of Biomedical Engineering, University of Science and Technology of China**, advised by Prof. [Xin Gao](http://sibet.cas.cn/sourcedb/zw/yjdw/yjy/201306/t20130621_3879548.html). I'm also pursuing my doctoral studies at the Shanghai Innovation Institute through a joint program. Prior to this, I obtained my bachelor's degree in biomedical engineering from Northeastern University in 2022. My research interests lie in **medical image analysis** and **AI in medicine**. My goal is to address medical challenges through computational methods and contribute to improving the quality of healthcare. 

In addition to my academic pursuits, I have a keen interest in sports and game data analysis. I maintain [PAGE](https://ieeexplore.ieee.org/abstract/document/10123061), a large-scale annotated database of professional Go games. I am also the developor of DeepKylin, an AI agent for Gomoku. It won the [National Computer Game Tournament](http://computergames.caai.cn/) in both 2020 and 2021.

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 Two papers are accepted at **MICCAI 2024**! 
- *2023.12*: &nbsp;🎉🎉 [Our work](https://github.com/yifangao112/PAGE) is accepted at **IEEE Transactions on Games** (IF=2.3).
- *2023.05*: &nbsp;🎉🎉 [Our work](https://www.sciencedirect.com/science/article/abs/pii/S0010482523004651) is accepted at **Computers in Biology and Medicine** (IF=7.7).
- *2022.06*: &nbsp;🎉🎉 Awarded by **Excellence Scholarship**, Northeastern University, 2022.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/desam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeSAM: Decoupled Segment Anything Model for Generalizable Medical Image Segmentation](https://arxiv.org/pdf/2306.00499)

**Yifan Gao**, Wei Xia, Dingdu Hu, Wenkui Wang, Xin Gao

**MICCAI 2024**

[**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=lzAiM94AAAAJ&citation_for_view=lzAiM94AAAAJ:7PzlFSSx8tAC) <strong><span class='show_paper_citations' data='lzAiM94AAAAJ:7PzlFSSx8tAC'></span></strong>
- DeSAM addresses the performance degradation of SAM in automatic segmentation scenarios. By decoupling the mask generation process from prompts and introducing prompt-relevant IoU and prompt-decoupled mask modules, DeSAM achieves state-of-the-art performance in two public datasets. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/mbanet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MBA-Net: SAM-driven Bidirectional Aggregation Network for Ovarian Tumor Segmentation](https://arxiv.org/pdf/2306.00499)

**Yifan Gao**, Wei Xia, Wenkui Wang, Xin Gao

**MICCAI 2024**

[**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=lzAiM94AAAAJ&citation_for_view=lzAiM94AAAAJ:-f6ydRqryjwC) <strong><span class='show_paper_citations' data='lzAiM94AAAAJ:f6ydRqryjwC'></span></strong>
- We developed MBA-Net, a novel architecture for ovarian tumor segmentation that integrates the Segment Anything Model (SAM) with domain-specific knowledge through bidirectional feature aggregation. MBA-Net demonstrates superior segmentation accuracy, robustness to tumor heterogeneity, and strong generalization capability across different imaging modalities and clinical sites. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIBM 2023</div><img src='images/parotid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Anatomy-aware Framework for Automatic Segmentation of Parotid Tumor from Multimodal MRI](https://www.sciencedirect.com/science/article/abs/pii/S0010482523004651)

**Yifan Gao**, Yin Dai, Fayu Liu, Weibing Chen, Lifu Shi

**Computers in Biology and Medicine**

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ToG 2023</div><img src='images/page.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Professional Go Annotation Dataset](https://github.com/yifangao112/PAGE)

**Yifan Gao**, Danni Zhang, Haoyue Li

**IEEE Transactions on Games**

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronics 2021</div><img src='images/nogo.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Efficiently Mastering the Game of NoGo with Deep Reinforcement Learning Supported by Domain Knowledge](https://www.mdpi.com/2079-9292/10/13/1533)

**Yifan Gao**, Lezhou Wu

**Electronics**

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [PGD: A Large-scale Professional Go Dataset for Data-driven Analytics](https://ieeexplore.ieee.org/abstract/document/9893704), **Yifan Gao**, **IEEE Conference on Games**, 2022
- [GomokuNet: A Novel UNet-style Network for Gomoku Zero Learning via Exploiting Positional Information and Multiscale Features](https://ieeexplore.ieee.org/abstract/document/9619111), **Yifan Gao**, Lezhou Wu, Haoyue Li, **IEEE Conference on Games**, 2021
- [TransMed: Transformers Advance Multi-modal Medical Image Classification](https://www.mdpi.com/2075-4418/11/8/1384), Yin Dai, **Yifan Gao**, Fayu Liu, **Diagnostics**, 2021


# 🏆 Honors and Awards
- Academic Excellence Scholarship, University of Science and Technology of China, 2023
- Excellence Scholarship, Northeastern University, 2022
- National Computer Game Tournament Champion, 2020-2021
- Academic Excellence Scholarship, Northeastern University, 2019-2022

# 💻 Services
- Reviewer of IEEE Journal of Biomedical and Health Informatics (JBHI), Medical Image Computing and Computer Assisted Intervention (MICCAI), International Journal of Imaging Systems and Technology (IMA), PeerJ Computer Science,  IEEE Access

# 📖 Educations
- 2024 - present, Ph.D. in Biomedical Engineering, University of Science and Technology of China, Hefei, China 
- 2022 - 2024, M.Sc. in Biomedical Engineering, University of Science and Technology of China, Hefei, China 
- 2018 - 2022, B.E. in Biomedical Engineering, Northeastern University, Shenyang, China. 

# 🏸 Hobbies
- Go (Weiqi): Certificated as amateur 5 dan by Chinese Weiqi Association.
- On my spare time, I like playing badminton, tennis, and video games!
