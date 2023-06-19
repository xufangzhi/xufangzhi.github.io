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

I am Fangzhi Xu (徐方植), a second-year master student in Xi'an Jiaotong University, major in Computer Science, advised by [Prof. Jun Liu](https://gr.xjtu.edu.cn/en/web/liukeen/4). In 2021, I received the B.S. degree in Electrical Engineering from Xi’an Jiaotong University.

My research interests include (but not limited to) natural language processing, question answering and logical reasoning.

I have published researches in some top-tier conferences and journals, such as SIGIR, IEEE TKDE and Pattern Recognition. Also, I was awarded National Scholarship (3 times) and won a lot of international competition prizes. Also, I serve as a PC member (or reviewer) for SIGIR 2023 and IEEE TNNLS.

I am actively looking for Research Intern opportunities currently! Please feel free to contact me.


# 🔥 News
- *2023.05.02*: &nbsp;🎉🎉 One paper is accepted by ACL 2023 !
- *2023.04.25*: &nbsp;🎉🎉 I am invited as a PC member at SIGIR-AP 2023 !
- *2023.04.01*: &nbsp;🎉🎉 One paper is accepted to Pattern Recognition !
- *2023.01.16*: &nbsp;🎉🎉 Two papers are submitted to ACL 2023 !
- *2023.11.21*: &nbsp;🎉🎉 Our paper is awarded Excellent Student Paper Award in APWeb-WAIM 2022 ! !
- *2022.11.05*: &nbsp;🎉🎉 One paper is submitted to IEEE TNNLS !
- *2022.10.24*: &nbsp;🎉🎉 I am awarded National Scholarship for the THIRD times !
- *2022.10.10*: &nbsp;🎉🎉 I am awarded Huawei Scholarship !
- *2022.10.10*: &nbsp;🎉🎉 One paper is accepted by Information Fusion !
- *2022.07.13*: &nbsp;🎉🎉 I make an oral presentation in SIGIR conference !
- *2022.06.07*: &nbsp;🎉🎉 One paper is accepted by APWeb 2022 !
- *2022.05.10*: &nbsp;🎉🎉 I am invited as a reviewer for TNNLS !

# 📖 Educations
- *2021.09 - 2023.06 (expected)*, M.S. in Computer Science, Xi'an Jiaotong University. &emsp; GPA:**91.77**/100, Rankings:**1**/173
- *2017.09 - 2021.06*, B.S. in Electrical Engineering, Xi'an Jiaotong University. &emsp; GPA:**97.62**/100, Rankings:**1**/365


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/radar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Are Large Language Models Really Good Logical Reasoners? A Comprehensive Evaluation From Deductive, Inductive and Abductive Views](https://arxiv.org/abs/2306.09841) <span style="color:red">[Arxiv]</span> \\
**Fangzhi Xu**\*, Qika Lin\*, Jiawei Han, Tianzhe Zhao, Jun Liu and Erik Cambria

[**Code**](https://github.com/xufangzhi/)

- To explore real logical reasoning capability of LLMs, this paper provides a systematic, comprehensive and fine-level evaluation from deductive, inductive and abductive
views. The in-depth evaluation and analysis fill the blanks and are expected to provoke new thoughts of LLMs.

- To provide fair evaluations with neutral content and decouple logical reasoning from text understanding, this paper proposes a new dataset named NeuLR. It contains 3K content-neutral samples and covers deductive, inductive and abductive reasoning manners.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2022</div><img src='images/ModelStructure.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Logiformer: A Two-Branch Graph Transformer Network for Interpretable Logical Reasoning](https://arxiv.org/abs/2205.00731) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Jun Liu, Qika Lin, Yudai Pan and Lingling Zhang

[**Code**](https://github.com/xufangzhi/Logiformer/)
  
- Logiformer is a two-branch network for the logical reasoning task in the field of multiple-choice machine reading comprehension.
- Up to publication, it is the state-of-the-art (SOTA) model compared with all the RoBERTa-Large based single model methods. Also, it ranks on the 9th place in the leaderboard compared with other larger models.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS (Under Review)</div><img src='images/TaCo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mind Reasoning Manners: Enhancing Type Perception for Generalized Zero-shot Logical Reasoning over Text](https://arxiv.org/abs/2301.02983) <span style="color:red">[CCF-B]</span> \\
**Fangzhi Xu**, Jun Liu, Qika Lin, Tianzhe Zhao, Jian Zhang, Lingling Zhang

[**Code**](https://github.com/xufangzhi/TaCo/)
  
- We propose the first benchmark for generalized zero-shot logical reasoning, named ZsLR
- A strong baseline TaCo is proposed, which is based on contrastive learning.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition</div><img src='images/MoCA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MoCA: Incorporating Domain Pretraining and Cross Attention for Textbook Question Answering](https://arxiv.org/abs/2112.02839) <span style="color:red">[CCF-B]</span> \\
**Fangzhi Xu**, Qika Lin, Jun Liu, Lingling Zhang, Tianzhe Zhao, Qi Chai, Yudai Pan

[**Code**](https://github.com/xufangzhi/MoCA/)

- MoCA focuses on the task of Textbook Question Answering, which is a multimodal task with abundant diagrams and large context.
- It conducts multi-stage pretraining on the text part and introduces dense layers of cross-guided multimodel attention for the diagram part. 
  
</div>
</div>

#### 🧑‍ Other Paper
- ``ACL 2023`` [TECHS: Temporal Logical Graph Networks for Explainable Extrapolation Reasoning](https://dl.acm.org/doi/abs/10.1145/3477495.3531996) <span style="color:red">[CCF-A]</span><br>
  Qika Lin, Jun Liu, Rui Mao, **Fangzhi Xu** and Erik Cambria
- ``Information Fusion`` [Fusing Topology Contexts and Logical Rules in Language Models for Knowledge Graph Completion](https://www.sciencedirect.com/science/article/pii/S1566253522001592) <span style="color:red">[SCI-Q1]</span> <br>
  Qika Lin, Rui Mao, Jun Liu, **Fangzhi Xu**, Erik Cambria
- ``APWEB-WAIM 2022`` [Incorporating Prior Type Information for Few-shot Knowledge Graph Completion](https://link.springer.com/chapter/10.1007/978-3-031-25198-6_21) <span style="color:red">[CCF-C] (Excellent Student Paper)</span> <br>
  Siyu Yao, Tianzhe Zhao, **Fangzhi Xu**, Jun Liu
- ``SIGIR 2022`` [Incorporating Context Graph with Logical Reasoning for Inductive Relation Prediction](https://dl.acm.org/doi/abs/10.1145/3477495.3531996) <span style="color:red">[CCF-A]</span><br>
  Qika Lin, Jun Liu, **Fangzhi Xu**, Yudai Pan, Yifan Zhu, Lingling Zhang and Tianzhe Zhao
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
- *2022.09* &emsp; National Scholarship
- *2022.09* &emsp; Huawei Scholarship
- *2022.04* &emsp; ACM SIGIR Student Travel Grant
- *2021.09* &emsp; Freshman First Prize Scholarship
- *2020.09* &emsp; Chinese Modern Scientists Scholarship (Only for Top-10 Student)
- *2019.09* &emsp; National Scholarship
- *2018.09* &emsp; National Scholarship

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💬 Academic Services
- Program Committee Member: SIGIR 2023, SIGIR-AP 2023
- Reviewer: IEEE TNNLS

# 💻 Internships
- *2023.05 - 2023.10*, Still Searching!
