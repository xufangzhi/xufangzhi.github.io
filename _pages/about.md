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

I am Fangzhi Xu (徐方植), a first-year PhD student in Xi'an Jiaotong University, major in Computer Science, advised by [Prof. Jun Liu](https://gr.xjtu.edu.cn/en/web/liukeen/4). I am currently a research intern at Shanghai AI LAB, supervised by [Dr. Zhiyong Wu](https://lividwo.github.io/zywu.github.io/). Also, I will start my visiting to Univeristy of Waterloo this Fall, advised by [Prof. Wenhu Chen](https://wenhuchen.github.io/).

I have published researches in some top-tier conferences and journals, such as ACL, SIGIR, IEEE TKDE, and IEEE TNNLS. Also, I serve as a PC member (or reviewer) for IJCAI, SIGIR and IEEE TNNLS.

My research interests include (but not limited to) natural language processing, large language models and neuro-symbolic reasoning. 




# 🔥 News
- *2024.05.20*: &nbsp; Our paper ENVISIONS is submitted to NIPS 2024 🚀🚀!
- *2024.05.16*: &nbsp; Three papers are accepted by ACL 2024 (main conference) 🎉🎉!
- *2024.03.24*: &nbsp; Our recent survey on neural code intelligence is made public 🎉🎉!
- *2024.02.20*: &nbsp; One paper is accepted by COLING 2024 🎉🎉!
- *2024.02.10*: &nbsp; One paper is accepted by ICDE 2024 (TKDE Poster Track) 🎉🎉!
- *2023.11.15*: &nbsp; We make the recent work Symbol-LLM public 🚀!
  

# 📖 Educations
- *2023.09 - 2026.06 (expected)*, PhD student in Computer Science, Xi'an Jiaotong University.
- *2021.09 - 2023.06*, M.S. in Computer Science, Xi'an Jiaotong University. &emsp; GPA:**91.77**/100, Rankings:**1**/173
- *2017.09 - 2021.06*, B.S. in Electrical Engineering, Xi'an Jiaotong University. &emsp; GPA:**97.62**/100, Rankings:**1**/365


# 💻 Internships
- *2023.07 - Present*, Research Intern @ Shanghai AI LAB. Focus on Large Language Models and Neuro-Symbolic.

# 📝 Selected Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/ENVISIONS.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Interative Evolution: A Neural-symbolic Self-Training Framework for Large Language Models 🔥🔥](http://arxiv.org/abs/2406.11736) <span style="color:red">[Preprint]</span> \\
**Fangzhi Xu**, Qiushi Sun, Kanzhi Cheng, Jun Liu, Yu Qiao, Zhiyong Wu.

[**Code**](https://github.com/xufangzhi/ENVISIONS) &nbsp;
[**Project Page**](https://github.com/xufangzhi/ENVISIONS) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E30-brightgreen.svg)](https://github.com/xufangzhi/ENVISIONS) &nbsp;
[![](https://img.shields.io/github/stars/xufangzhi/ENVISIONS?style=social&label=Code+Stars)](https://github.com/xufangzhi/ENVISIONS)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/symbol-llm.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Symbol-LLM: Towards Foundational Symbol-centric Interface
For Large Language Models 🔥🔥](https://arxiv.org/pdf/2311.09278) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Zhiyong Wu, Qiushi Sun, Siyu Ren, Fei Yuan, Shuai Yuan, Qika Lin, Qiao Yu and Jun Liu.

[**Code**](https://github.com/xufangzhi/Symbol-LLM) &nbsp;
[**Project Page**](https://xufangzhi.github.io/symbol-llm-page/) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E170-brightgreen.svg)](https://github.com/xufangzhi/Symbol-LLM)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/Model.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PathReasoner: Modeling Reasoning Path with Equivalent Extension for Logical Question Answering 🔥🔥](https://xufangzhi.github.io/) <span style="color:red">[CCF-A]</span> \\
**Fangzhi Xu**, Qika Lin, Tianzhe Zhao, Jiawei Han, Jun Liu 

[**Code**](https://github.com/xufangzhi/)

- We are the first to rethink the logical reasoning task by unifying the inputs into atoms and reasoning paths.

- We propose an atom extension strategy with equivalent logical formulas to generate diverse new samples. Also, we introduce a stack of transformer-style blocks. Specifically, a path-attention module with high-order relation modeling is proposed to joint update information within and across atoms.
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/codesurvey.png' alt="sym" width="99%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey of Neural Code Intelligence: Paradigms, Advances and Beyond 🔥🔥](https://arxiv.org/abs/2403.14734) <span style="color:red">[Preprint]</span> \\
Qiushi Sun, Zhirui Chen, **Fangzhi Xu**, Chang Ma, Kanzhi Cheng, Zhangyue Yin, Jianing Wang, Chengcheng Han, Renyu Zhu, Shuai Yuan, Pengcheng Yin, Qipeng Guo, Xipeng Qiu, Xiaoli Li, Fei Yuan, Lingpeng Kong, Xiang Li, Zhiyong Wu

[**Code**](https://github.com/QiushiSun/NCISurvey) &nbsp;
[![](https://img.shields.io/github/stars/QiushiSun/NCISurvey?style=social&label=Code+Stars)](https://github.com/QiushiSun/NCISurvey)

- We make a thorough conclusion of the paradigm shifts on neural code intelligence and provide extensive insights on advances and future directions. Check it out!
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/radar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Are Large Language Models Really Good Logical Reasoners? A Comprehensive Evaluation and Beyond 🔥🔥](https://arxiv.org/abs/2306.09841) <span style="color:red">Under Review at IEEE TKDE [CCF-A]</span> \\
**Fangzhi Xu**\*, Qika Lin\*, Jiawei Han, Tianzhe Zhao, Jun Liu and Erik Cambria

(\* means equal contributions)

[**Code**](https://github.com/xufangzhi/)

- This paper provides a systematic, comprehensive and fine-level evaluation of logical reasoning capability from deductive, inductive and abductive
views.

- We propose a new dataset named NeuLR. It contains 3K samples with neutral content, covering deductive, inductive and abductive reasoning manners.
  
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS</div><img src='images/TaCo.jpg' alt="sym" width="100%"></div></div>
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
- ``ACL 2024`` [SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/pdf/2401.10935.pdf) <span style="color:red">[CCF-A]</span>[![](https://img.shields.io/github/stars/njucckevin/SeeClick?style=social&label=Code+Stars)](https://github.com/njucckevin/SeeClick)<br>
  Kanzhi Cheng, Qiushi Sun, Yougang Chu, **Fangzhi Xu**, Yantao Li, Jianbing Zhang, Zhiyong Wu
- ``COLING 2024`` [A Semantic Mention Graph Augmented Model for Document-Level Event Argument Extraction](https://dl.acm.org/doi/abs/10.1145/3477495.3531996) <span style="color:red">[CCF-B]</span><br>
  Jian Zhang, Changlin Yang, Haiping Zhu, Qika Lin, **Fangzhi Xu** and Jun Liu
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
- Program Committee Member: IJCAI 2024, SIGIR 2024, AACL 2023, SIGIR 2023, SIGIR-AP 2023
- Reviewer: IEEE TNNLS
