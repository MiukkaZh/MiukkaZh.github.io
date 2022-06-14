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

章瀚逸的主要研究方向为复杂场景下的声纹识别、元学习与模式识别, 作为主要参与者参加了国家自然科学基金面上项目、新大陆横向项目等科研与合作项目, 并在**ICASSP**、**Interspeech**等信号处理的国际顶尖会议上发表3篇一作论文。

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 研究方向
- **语音信息处理**: 复杂场景下的声纹识别
- **模式识别与机器学习**: 元学习, 对抗攻击

# 📖 Educations
- *2020.09 - 至今*, 硕士学位, 天津大学, 智能与计算学部, 软件工程专业, 导师: 王龙标、党建武, 外导: Kong Aik Lee (Senior Scientist)
- *2016.09 - 2020.07*, 学士学位, 云南大学, 国家示范性软件学院, 信息安全专业, 导师: 谢诚副教授

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2022</div><img src='images/icassp2022.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Domain-Invariant Transformation for Speaker Verification (CCF B)](https://ieeexplore.ieee.org/abstract/document/9747514)

**Hanyi Zhang**, Longbiao Wang, Kong Aik Lee, Meng Liu, Jianwu Dang, Hui Chen

- 针对声纹识别系统在实际应用中所面临的由于采录方式和说话风格等内在和外在因素不匹配而导致的域漂移问题, 提出了元泛化转换以自适应地将提取的特征映射到域不变的嵌入空间中, 并实现了支持高阶梯度的通用架构。该方法适用于不同的主干网络, 在未见领域上取得了 16% 的相对性能提升。[[Code]](https://github.com/MiukkaZh/MGT)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2021</div><img src='images/icassp2021.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta-Learning for Cross-Channel Speaker Verification (CCF B)](https://ieeexplore.ieee.org/abstract/document/9413978)

**Hanyi Zhang**, Longbiao Wang, Kong Aik Lee, Meng Liu, Jianwu Dang, Hui Chen

- 为降低信道不匹配对声纹识别系统造成的不利影响, 提出了元说话人嵌入网络来优化语音嵌入在子空间中的局部与全局分布。在不增加额外参数的前提下, 取得了 10% 的相对性能提升。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interspeech 2020</div><img src='images/interspeech2020.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adversarial Separation Network for Speaker Recognition (CCF C)](https://www.isca-speech.org/archive_v0/Interspeech_2020/pdfs/1966.pdf)

**Hanyi Zhang**, Longbiao Wang, Yunchun Zhang, Meng Liu, Kong Aik Lee, Jianguo Wei

- 为防止声纹识别系统被不易察觉的对抗攻击所干扰, 提出了对抗分离网络以从对抗样本中抽离对抗扰动, 并恢复自然样本。面对不同强度、不同类型的对抗攻击, 该方法均显著提高了声纹识别系统抵御对抗攻击的能力。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TASLP</div><img src='images/new.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Meta-Generalization for Domain-Invariant Speaker Verification (IEEE TASLP; SCI Q1; Under review)**

**Hanyi Zhang**, ...

- 针对部署在实际应用中的声纹识别系统所面临的未见域和多变量挑战, 采用基于度量和高阶梯度的优化策略, 结合创新性的元任务采样方案, 降低了泛化网络训练的难度, 大幅提升了声纹识别系统在处理未见域的语音时的性能。
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASRU 2021</div><img src='images/ASRU.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeepLip: A Benchmark for Deep Learning-Based Audio-Visual Lip Biometrics](https://ieeexplore.ieee.org/abstract/document/9688240)

Meng Liu, Longbiao Wang, Kong Aik Lee, **Hanyi Zhang**, Chang Zeng, Jianwu Dang

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronics 2020</div><img src='images/electronics.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generative Adversarial Network-Based Neural Audio Caption Model for Oral Evaluation (SCI)](https://www.mdpi.com/2079-9292/9/3/424)

Liu Zhang, Chao Shu, Jin Guo, **Hanyi Zhang**, Cheng Xie, Qing Liu

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICEBE 2019</div><img src='images/icebe.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Speech Evaluation Based on Deep Learning Audio Caption](https://link.springer.com/chapter/10.1007/978-3-030-34986-8_4)

Liu Zhang, **Hanyi Zhang**, Jin Guo, Detao Ji, Qing Liu, Cheng Xie

</div>
</div>

# 💬 Invited Talks
### 主要参与者
- *2021.05 - 至今*, 国家自然科学基金面上项目, 面向复杂环境的声纹识别与声纹反欺诈研究, NO: 62176182
- *2021.08 - 至今*, 新大陆横向项目
- *2019.02 - 2020.05*, “基于深度学习的语音评价”校企合作项目
### 参与者
- *2020.08 - 至今*, 科技部国家重点研发计划“智能机器人”专项课题, 基于语言认知机理的类脑自然语言识别与交互
- *2020.08 - 2021.12*, 国家自然科学基金面上项目, 面向混响环境的多口音语音识别研究, No. 61771333


# 专利与证书
- 中国发明专利, 融合深度语言生成模型的语言表达能力评价方法和系统, CN111341346A
- 软件著作权, 基于灰度图的恶意文件分类软件, 2017SR601808
- 信息安全工程师 (软考证书)
- 英语六级
- 国家信息安全水平认证 (NISP) 一级


# 🎖 Honors and Awards
- *2019.10* 本科生国家奖学金, 中华人民共和国教育部
- *2019.05* 第五届 “互联网+” 创新创业大赛省赛银奖
- *2019.04* 第十届 “蓝桥杯” 大赛云南赛区二等奖
- *2019.04* “未来杯”高校 AI 挑战赛西南赛区第二名
- *2021.11* 三好学生, 天津大学
- *2021.09, 2020.09* 一等奖学金, 天津大学
- *2020.06* 云南大学优秀本科学生毕业论文; 云南大学优秀毕业生
- *2017.10, 2018.10* 学业奖学金, 云南大学


# 科研服务
- *2022.03 - 2022.05*, 天津大学硕士生课程《智能网联汽车技术》助教
- *2021.08 - 2022.01*, 天津大学本科生课程《语音信息处理》助教
- 参与编撰《语音信息处理理论与实践》教材