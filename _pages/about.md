---
permalink: /
title: ""
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

# 🐯 About Me

I am Fangzhi Xu (徐方植), a second-year PhD student in Xi'an Jiaotong University, major in Computer Science, advised by [Prof. Jun Liu](https://gr.xjtu.edu.cn/en/web/liukeen/4). I was previously a research intern at Shanghai AI LAB, supervised by [Dr. Zhiyong Wu](https://lividwo.github.io/zywu.github.io/). I am starting the one-year visiting to Nanyang Technological University (NTU, Singapore 🇸🇬), advised by [Prof. Luu Anh Tuan](https://tuanluu.github.io/).

I have published researches in some top-tier conferences and journals, such as ACL, ICLR, SIGIR, and IEEE TKDE. Also, I serve as a PC member (or reviewer) for ACL, NAACL, IJCAI, SIGIR.

I will be on the job market **this autumn (Fall 2025)**, please feel free to reach out !


## Research Interests
In general, my research interests lie in large language models, self-training and neuro-symbolic.

Previously, I mainly work on the topic of logical reasoning:
- Logical Reasoning: [PathReasoner](https://arxiv.org/abs/2405.19109)(ACL'24), [Evaluation](https://arxiv.org/abs/2306.09841)(IEEE TKDE), [Logiformer](https://arxiv.org/abs/2205.00731)(SIGIR'22), [TaCo](https://arxiv.org/abs/2301.02983)(IEEE TNNLS)

Currently, my researches focus on *how to advance LLM self-evolution (through interaction with the environment)*. This encompasses a variety of topics, including self-training, reasoning, autonomous (GUI) agents, and more:
- LLM Self-Training: [Genius](https://arxiv.org/abs/2504.08672)(ACL'25), [ENVISIONS](https://arxiv.org/abs/2406.11736)(ACL'25), 
- Foundation Model: [Symbol-LLM](https://arxiv.org/abs/2311.09278)(ACL'24)
- LLM Reasoning Algorithm: [$\phi$-Decoding](https://arxiv.org/abs/2503.13288)(ACL'25), [MUR](https://arxiv.org/abs/2507.14958)(Preprint)
- (Multimodal) Autonomous Agents: [OS-Atlas](https://arxiv.org/pdf/2410.23218)(ICLR'25 *Spotlight*), [SeeClick](https://arxiv.org/abs/2401.10935)(ACL'24)

# 🔥 News
- *2025.07.22*: &nbsp; Our Training-free work [MUR] on LLM Reasoning is released 🎉🎉!
- *2025.06.09*: &nbsp; Our paper [ScienceBoard] is accepted by WCUA@ICML 2025 as oral paper 🎉🎉!
- *2025.05.15*: &nbsp; Seven papers are accepeted by ACL 2025 🎉🎉!
- *2025.01.26*: &nbsp; Our paper is accepeted by IEEE TKDE 🎉🎉!
- *2025.01.23*: &nbsp; Our paper [OS-Atlas] is accepeted by ICLR 2025 (Spotlight) and [R3-V] is accepted by NAACL 2025 🎉🎉!
- *2024.12.30*: &nbsp; Our paper [OS-Genesis] is recently released 🚀🚀!
  

# 📖 Educations
- *2021.09 - 2026.06 (expected)*, M.S. + Ph.D Student, Computer Science, Xi'an Jiaotong University. &emsp;
- *2017.09 - 2021.06*, B.S. in Electrical Engineering, Xi'an Jiaotong University. &emsp; GPA:**97.62**/100, Rankings:**1**/365


# 💻 Internships
- *2025.03 - Now*, Visiting Ph.D Student @ NTU 🇸🇬. Focus on LLM Reasoning and Neuro-Symbolic.
- *2023.07 - 2025.02*, Research Intern @ Shanghai AI LAB 🇨🇳. Focus on LLM, AI Agents and Neuro-Symbolic.

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/mur.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[MUR: Momentum Uncertainty guided Reasoning for Large Language Models 🔥🔥](https://arxiv.org/abs/2507.14958) \\
Hang Yan\*, **Fangzhi Xu**\*, Rongman Xu, Yifei Li, Jian Zhang, Haoran Luo, Xiaobao Wu, Luu Anh Tuan, Haiteng Zhao, Qika Lin, Jun Liu

(\* means equal contributions)

[**Code**](https://github.com/yayayacc/MUR) &nbsp;
[![](https://img.shields.io/github/stars/yayayacc/MUR?style=social&label=Code+Stars)](https://github.com/yayayacc/MUR)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Main)</div><img src='images/genius_model.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Genius: A Generalizable and Purely Unsupervised Self-Training Framework For Advanced Reasoning 🔥🔥](https://arxiv.org/abs/2504.08672)<span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Hang Yan, Chang Ma, Haiteng Zhao, Qiushi Sun, Kanzhi Cheng, Junxian He, Jun Liu, Zhiyong Wu

[**Code**](https://github.com/xufangzhi/Genius) &nbsp;
[![](https://img.shields.io/github/stars/xufangzhi/Genius?style=social&label=Code+Stars)](https://github.com/xufangzhi/Genius)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Main)</div><img src='images/phi_model.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[ϕ-Decoding: Adaptive Foresight Sampling for Balanced Inference-Time Exploration and Exploitation 🔥🔥](https://arxiv.org/abs/2503.13288)<span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**\*, Hang Yan\*, Chang Ma, Haiteng Zhao, Jun Liu, Qika Lin, Zhiyong Wu

(\* means equal contributions)

[**Code**](https://github.com/xufangzhi/phi-Decoding) &nbsp;
[**PyPi-Package**](https://github.com/xufangzhi/phi-Decoding) &nbsp;
[![](https://img.shields.io/github/stars/xufangzhi/phi-Decoding?style=social&label=Code+Stars)](https://github.com/xufangzhi/phi-Decoding)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 (Spotlight)</div><img src='images/Intro.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[OS-ATLAS: A Foundation Action Model for Generalist GUI Agents](https://arxiv.org/abs/2410.23218) \\
Zhiyong Wu\*, Zhenyu Wu\*, **Fangzhi Xu**\*, Yian Wang\*, Qiushi Sun, Chengyou Jia, Kanzhi Cheng, Zichen Ding, Liheng Chen, Paul Pu Liang, Yu Qiao

(\* means equal contributions)

[**Code**](https://github.com/OS-Copilot/OS-Atlas) &nbsp;
[**Project Page**](https://osatlas.github.io) &nbsp;
[**Demo**](https://huggingface.co/spaces/maxiw/OS-ATLAS) &nbsp;
[![](https://img.shields.io/github/stars/OS-Copilot/OS-Atlas?style=social&label=Code+Stars)](https://github.com/OS-Copilot/OS-Atlas)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Main)</div><img src='images/ENVISIONS.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Interative Evolution: A Neural-symbolic Self-Training Framework for Large Language Models](http://arxiv.org/abs/2406.11736) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Qiushi Sun, Kanzhi Cheng, Jun Liu, Yu Qiao, Zhiyong Wu.

[**Code**](https://github.com/xufangzhi/ENVISIONS) &nbsp;
[**Project Page**](https://github.com/xufangzhi/ENVISIONS) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E400-steelblue.svg)](https://github.com/xufangzhi/ENVISIONS) &nbsp;
[![](https://img.shields.io/github/stars/xufangzhi/ENVISIONS?style=social&label=Code+Stars)](https://github.com/xufangzhi/ENVISIONS)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 (Main)</div><img src='images/symbol-llm.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Symbol-LLM: Towards Foundational Symbol-centric Interface
For Large Language Models](https://arxiv.org/pdf/2311.09278) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Zhiyong Wu, Qiushi Sun, Siyu Ren, Fei Yuan, Shuai Yuan, Qika Lin, Qiao Yu and Jun Liu.

[**Code**](https://github.com/xufangzhi/Symbol-LLM) &nbsp;
[**Project Page**](https://xufangzhi.github.io/symbol-llm-page/) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E500-steelblue.svg)](https://github.com/xufangzhi/Symbol-LLM) &nbsp;
[![](https://img.shields.io/github/stars/xufangzhi/Symbol-LLM?style=social&label=Code+Stars)](https://github.com/xufangzhi/Symbol-LLM)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 (Main)</div><img src='images/Model.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PathReasoner: Modeling Reasoning Path with Equivalent Extension for Logical Question Answering](https://xufangzhi.github.io/) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Qika Lin, Tianzhe Zhao, Jiawei Han, Jun Liu 

[**Code**](https://github.com/xufangzhi/)
  
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TKDE</div><img src='images/radar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Are Large Language Models Really Good Logical Reasoners? A Comprehensive Evaluation and Beyond](https://arxiv.org/abs/2306.09841) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**\*, Qika Lin\*, Jiawei Han, Tianzhe Zhao, Jun Liu and Erik Cambria

(\* means equal contributions)

[**Code**](https://github.com/DeepReasoning/NeuLR)
[![](https://img.shields.io/github/stars/DeepReasoning/NeuLR?style=social&label=Code+Stars)](https://github.com/DeepReasoning/NeuLR)
  
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2022</div><img src='images/ModelStructure.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Logiformer: A Two-Branch Graph Transformer Network for Interpretable Logical Reasoning](https://arxiv.org/abs/2205.00731) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Jun Liu, Qika Lin, Yudai Pan and Lingling Zhang

[**Code**](https://github.com/xufangzhi/Logiformer/) &nbsp;
[![](https://img.shields.io/github/stars/xufangzhi/Logiformer?style=social&label=Code+Stars)](https://github.com/xufangzhi/Logiformer)

</div>
</div>


#### 🧑‍ Other Paper
- ``WCUA@ICML 2025``[ScienceBoard: Evaluating Multimodal Autonomous Agents in Realistic Scientific Workflows](https://arxiv.org/abs/2505.19897) [![](https://img.shields.io/github/stars/OS-Copilot/ScienceBoard?style=social&label=Code+Stars)](https://github.com/OS-Copilot/ScienceBoard) <br>
Qiushi Sun, Zhoumianze Liu, Chang Ma, Zichen Ding, **Fangzhi Xu**, Zhangyue Yin, Haiteng Zhao, Zhenyu Wu, Kanzhi Cheng, Zhaoyang Liu, Jianing Wang, Qintong Li, Xiangru Tang, Tianbao Xie, Xiachong Feng, Xiang Li, Ben Kao, Wenhai Wang, Biqing Qi, Lingpeng Kong, Zhiyong Wu
- ``Preprint``[BioMaze: Benchmarking and Enhancing Large Language Models for Biological Pathway Reasoning](https://arxiv.org/pdf/2502.16660) <br> 
Haiteng Zhao, Chang Ma, **Fangzhi Xu**, Lingpeng Kong, Zhi-Hong Deng
- ``ACL 2025 Findings``[CapArena: Benchmarking and Analyzing Detailed Image Captioning in the LLM Era](https://arxiv.org/abs/2503.12329) [![](https://img.shields.io/github/stars/njucckevin/CapArena?style=social&label=Code+Stars)](https://github.com/njucckevin/CapArena) <br> 
Kanzhi Cheng, Wenpo Song, Jiaxin Fan, Zheng Ma, Qiushi Sun, **Fangzhi Xu**, Chenyang Yan, Nuo Chen, Jianbing Zhang, Jiajun Chen
- ``ACL 2025`` [OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis](https://arxiv.org/pdf/2412.19723) [![](https://img.shields.io/github/stars/OS-Copilot/OS-Genesis?style=social&label=Code+Stars)](https://github.com/OS-Copilot/OS-Genesis) <br> 
Qiushi Sun, Kanzhi Cheng, Zichen Ding, Chuanyang Jin, Yian Wang, **Fangzhi Xu**, Zhenyu Wu, Chengyou Jia, Liheng Chen, Zhoumianze Liu, Ben Kao, Guohao Li, Junxian He, Yu Qiao, Zhiyong Wu
- ``ACL 2025`` [Self-supervised Quantized Representation for Seamlessly Integrating Knowledge Graphs with Large Language Models](https://arxiv.org/abs/2501.18119)<br> 
Qika Lin, Tianzhe Zhao, Kai He, Zhen Peng, **Fangzhi Xu**, Ling Huang, Jingying Ma, Mengling Feng
- ``ACL 2025 Findings`` [AgentStore: Scalable Integration of Heterogeneous Agents As Specialized Generalist Computer Assistant](https://arxiv.org/abs/2410.18603) [![](https://img.shields.io/github/stars/chengyou-jia/AgentStore?style=social&label=Code+Stars)](https://github.com/chengyou-jia/AgentStore)<br>
Chengyou Jia, Minnan Luo, Zhuohang Dang, Qiushi Sun, **Fangzhi Xu**, Junlin Hu, Tianbao Xie, Zhiyong Wu
- ``NAACL 2025 (Oral)`` [Vision-Language Models Can Self-Improve Reasoning via Reflection](https://arxiv.org/pdf/2411.00855) <span style="color:red">[CCF-B]</span> [![](https://img.shields.io/github/stars/njucckevin/MM-Self-Improve?style=social&label=Code+Stars)](https://github.com/njucckevin/MM-Self-Improve) <br>
Kanzhi Cheng, Yantao Li, **Fangzhi Xu**, Jianbing Zhang, Hao Zhou, Yang Liu
- ``Preprint`` [A Survey of Neural Code Intelligence: Paradigms, Advances and Beyond](https://arxiv.org/abs/2403.14734) [![](https://img.shields.io/github/stars/QiushiSun/NCISurvey?style=social&label=Code+Stars)](https://github.com/QiushiSun/NCISurvey) <br>
Qiushi Sun, Zhirui Chen, **Fangzhi Xu**, Chang Ma, Kanzhi Cheng, Zhangyue Yin, Jianing Wang, Chengcheng Han, Renyu Zhu, Shuai Yuan, Pengcheng Yin, Qipeng Guo, Xipeng Qiu, Xiaoli Li, Fei Yuan, Lingpeng Kong, Xiang Li, Zhiyong Wu
- ``ACL 2024`` [SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/pdf/2401.10935.pdf) <span style="color:red">[CCF-A]</span>[![](https://img.shields.io/github/stars/njucckevin/SeeClick?style=social&label=Code+Stars)](https://github.com/njucckevin/SeeClick)<br>
  Kanzhi Cheng, Qiushi Sun, Yougang Chu, **Fangzhi Xu**, Yantao Li, Jianbing Zhang, Zhiyong Wu
- ``COLING 2024`` [A Semantic Mention Graph Augmented Model for Document-Level Event Argument Extraction](https://dl.acm.org/doi/abs/10.1145/3477495.3531996) <span style="color:red">[CCF-B]</span><br>
  Jian Zhang, Changlin Yang, Haiping Zhu, Qika Lin, **Fangzhi Xu** and Jun Liu
- ``ACL 2023`` [TECHS: Temporal Logical Graph Networks for Explainable Extrapolation Reasoning](https://dl.acm.org/doi/abs/10.1145/3477495.3531996) <span style="color:red">[CCF-A]</span><br>
  Qika Lin, Jun Liu, Rui Mao, **Fangzhi Xu** and Erik Cambria
- ``Information Fusion`` [Fusing Topology Contexts and Logical Rules in Language Models for Knowledge Graph Completion](https://www.sciencedirect.com/science/article/pii/S1566253522001592) <span style="color:red">[SCI-Q1]</span> <br>
  Qika Lin, Rui Mao, Jun Liu, **Fangzhi Xu**, Erik Cambria
- ``IEEE TNNLS`` [Mind Reasoning Manners: Enhancing Type Perception for Generalized Zero-shot Logical Reasoning over Text](https://arxiv.org/abs/2301.02983) <span style="color:red">[CCF-B]</span><br>
  **Fangzhi Xu**, Jun Liu, Qika Lin, Tianzhe Zhao, Jian Zhang, Lingling Zhang
- ``APWEB-WAIM 2022`` [Incorporating Prior Type Information for Few-shot Knowledge Graph Completion](https://link.springer.com/chapter/10.1007/978-3-031-25198-6_21) <span style="color:red">[CCF-C] (Excellent Student Paper)</span> <br>
  Siyu Yao, Tianzhe Zhao, **Fangzhi Xu**, Jun Liu
- ``SIGIR 2022`` [Incorporating Context Graph with Logical Reasoning for Inductive Relation Prediction](https://dl.acm.org/doi/abs/10.1145/3477495.3531996) <span style="color:red">[CCF-A]</span><br>
  Qika Lin, Jun Liu, **Fangzhi Xu**, Yudai Pan, Yifan Zhu, Lingling Zhang and Tianzhe Zhao
- ``Pattern Recognition`` [MoCA: Incorporating Domain Pretraining and Cross Attention for Textbook Question Answering](https://arxiv.org/abs/2112.02839) <span style="color:red">[CCF-B]</span><br>
  **Fangzhi Xu**, Qika Lin, Jun Liu, Lingling Zhang, Tianzhe Zhao, Qi Chai, Yudai Pan
- ``IEEE TKDE`` [Contrastive Graph Representations for Logical Formulas Embedding](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9667296) <span style="color:red">[CCF-A]</span> <br>
  Qika Lin, Jun Liu, Lingling Zhang, Yudai Pan, Xin Hu, **Fangzhi Xu**, Hongwei Zeng



# 🎖 Honors and Awards
**Honors**
- *Oct.2022* &emsp; Outstanding Student in Xi’an Jiaotong University
- *Jun.2021* &emsp; Outstanding Undergraduate Graduates in Shaanxi Province
- *Sep.2020* &emsp; **Top-10** Students of the Year (**Top Personal Award** in Xi’an Jiaotong University)
- *Sep.2019* &emsp; Outstanding Student in Xi’an Jiaotong University
- *Sep.2018* &emsp; Outstanding Student in Xi’an Jiaotong University

**Competition Awards**
- *Dec.2022* &emsp; ”Huawei Cup” Mathematical Contest in Modeling, **Second Prize**
- *Mar.2022* &emsp; Asia and Pacific Mathematical Contest in Modeling (APMCM), **First Prize + Innovation Award (Top-2)**
- *Dec.2021* &emsp; ”Huawei Cup” Mathematical Contest in Modeling, **Second Prize**
- *Sep.2020* &emsp; IKCEST International Big Data Competition, **Excellence Award**
- *Apr.2020*  &emsp; Mathematical Contest in Modeling (COMAP), **Finalist**
- *Dec.2019* &emsp; China Mathematical Contest in Modeling (CUMCM), **Second Prize**
- *May.2018* &emsp; National English Competition for College Students (NECCS), **Second Prize**


# 🎖 Scholarships
- *2023.09* &emsp; Freshman First Prize Scholarship (PhD)
- *2022.09* &emsp; National Scholarship
- *2022.09* &emsp; Huawei Scholarship
- *2022.04* &emsp; ACM SIGIR Student Travel Grant
- *2021.09* &emsp; Freshman First Prize Scholarship (Master)
- *2020.09* &emsp; Chinese Modern Scientists Scholarship (Only for Top-10 Student)
- *2019.09* &emsp; National Scholarship
- *2018.09* &emsp; National Scholarship

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💬 Academic Services
- Program Committee Member: ACL ARR 2024, IJCAI 2024, SIGIR 2024, AACL 2023, SIGIR 2023, SIGIR-AP 2023
- Reviewer: IEEE TNNLS
