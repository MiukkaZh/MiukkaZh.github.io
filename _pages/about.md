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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2022</div><img src='images/icassp2022.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Domain-Invariant Transformation for Speaker Verification (CCF B)](https://ieeexplore.ieee.org/abstract/document/9747514)

**Hanyi Zhang**, Longbiao Wang, Kong Aik Lee, Meng Liu, Jianwu Dang, Hui Chen

- 针对声纹识别系统在实际应用中所面临的由于采录方式和说话风格等内在和外在因素不匹配而导致的域漂移问题, 提出了元泛化转换以自适应地将提取的特征映射到域不变的嵌入空间中, 并实现了支持高阶梯度的通用架构。该方法适用于不同的主干网络, 在未见领域上取得了 16% 的相对性能提升。

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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interspeech 2020</div><img src='images/new.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Meta-Generalization for Domain-Invariant Speaker Verification (IEEE TASLP; SCI Q1; Under review)**

**Hanyi Zhang**, ...

- 针对部署在实际应用中的声纹识别系统所面临的未见域和多变量挑战, 采用基于度量和高阶梯度的优化策略, 结合创新性的元任务采样方案, 降低了泛化网络训练的难度, 大幅提升了声纹识别系统在处理未见域的语音时的性能。
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.