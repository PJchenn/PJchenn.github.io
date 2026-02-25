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

# 🪐 About me

I am a second-year Ph.D. candidate in the School of Automation at [Southeast University (SEU)](https://www.seu.edu.cn/), under the supervision of [Assoc. Prof. Dan Niu](https://automation.seu.edu.cn/nd/list.htm). Prior to this, I obtained my M.Eng. degree in Electronic Information from [SEU](https://www.seu.edu.cn/) supervised by [Prof. Qi Li](https://automation.seu.edu.cn/lq3/list.htm). Currently, I am a visiting Ph.D. candidate at [Eastern Institute of Technology, Ningbo (EIT)](https://www.eitech.edu.cn/), advised by [Prof. Lei He](http://eda.ee.ucla.edu/people/faculty.html), with additional guidance from [Assoc. Prof. Wei W. Xing](http://wxing.me/).




<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<div style="margin-top: 10px;">
  <a href="your-cv-link.pdf" style="text-decoration: none;">
    <button style="background-color: #333333; color: white; padding: 5px 10px; border: none; border-radius: 4px; cursor: pointer; font-size: 14px;">
      📄 Download CV
    </button>
  </a>
</div>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">

<div style="flex: 1; margin-right: 1px;">
    <h2>🌋 Research Interests</h2>
    <ul>
      <li><strong>Electronic Design Automation (EDA)</strong></li>
      <li><strong>Chiplet Thermal/Multiphysics Simulation</strong></li>
      <li><strong>Model Order Reduction (MOR)</strong></li>
    </ul>
</div>

  <div style="flex: 1; margin-left: 1px;">
    <h2>🏛️ Education</h2>
    <ul>
      <li><strong>Ph.D. Control Science and Engineering</strong><br><em>Southeast University (SEU)</em></li>
      <li><strong>M.Eng. Electronic Information</strong><br><em>Southeast University (SEU)</em></li>
      <li><strong>B.Eng. Automation</strong><br><em>Chongqing University (CQU)</em></li>
    </ul>
  </div>

</div>


<span class='anchor' id='-news'></span>

# 🔥 News
- *2026.02*: &nbsp;🎉 One paper about Chiplet Thermal Simulaition (Reduced Thermal Model) has been accepted to DAC 2026!
- *2025.02*: &nbsp;🎉 One paper about Chiplet Thermal Simulaition (FEM Mesh Optimization) has been accepted to DAC 2025!
- *2024.06*: &nbsp;🎓 Graduated from Southeast University and obtain M.Eng. degree in Electronic Information!
- *2023.11*: &nbsp;🎉 One paper about Model Order Reduction has been accepted to DATE 2024! 

<span class='anchor' id='-publications'></span>

# 🏔️ Publications 

## Conference Paper 👇

- [C3] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">DAC 2026</span> [LegoTherm: Modular and Reusable Thermal Model for Chiplet-based Heterogeneous Integration](https://dac.com/2026/accepted-paper-ids), **<u>Pengju Chen</u>**, Dan Niu, Depeng Xie, Gang Wang, Chen Wu, Wei W. Xing and Lei He. 2025 62nd ACM/IEEE Design Automation Conference (DAC), Long Beach, United States, 2026.

- [C2] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">DAC 2025</span> [NeuralMesh: Neural Network for FEM Mesh Generation in 2.5D/3D Chiplet Thermal Simulation](https://ieeexplore.ieee.org/abstract/document/11132601), **<u>Pengju Chen</u>**, Dan Niu, Dekang Zhang, Wenhao Wang, Depeng Xie, Zhou Jin, Wei W. Xing and Lei He. 2025 62nd ACM/IEEE Design Automation Conference (DAC), San Francisco, United States, 2025.

- [C1] <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">DATE 2024</span> [TSA-TICER: A Two-Stage TICER Acceleration Framework for Model Order Reduction](https://ieeexplore.ieee.org/abstract/document/10546520), **<u>Pengju Chen</u>**, Dan Niu, Zhou Jin, Changyin Sun, Qi Li and Hao Yan. 2024 Design, Automation & Test in Europe Conference (DATE), Valencia, Spain, 2024.

<!-- ## Journal Paper 👇 -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<span class='anchor' id='-honors-and-awards'></span>

# 🏆 Honors and Awards
- *2025.10* **First-class Scholarship** for Ph.D. Students.
- *2024.06* Outstanding Graduate.
- *2024.03* **"83791"** Alumni Scholarship.

<span class='anchor' id='-experiences'></span>

# 📖 Experiences
- *2025.07 - 2026.03(now)*, Visiting Ph.D. Candidate at Eastern Institute of Technology, Ningbo (EIT), advised by [Prof. Lei He](http://eda.ee.ucla.edu/people/faculty.html).
<!-- - *2024.07 - 2025.06*, InterLorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->