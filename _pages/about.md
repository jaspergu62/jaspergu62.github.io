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

Jiazhen Gu is a postdoctoral researcher in the [Automated Reliable Intelligent Software Engineering (ARISE) Lab](http://ariselab.cse.cuhk.edu.hk/) at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/), mentored by Prof. [Michael R. Lyu](https://www.cse.cuhk.edu.hk/lyu/). Jiazhen Gu received both Ph.D. and B.S. degrees from [Fudan University](https://www.fudan.edu.cn/), supervised by Prof. [Xin Wang](https://faculty.fudan.edu.cn/wangxin/zh_CN/) and Prof. [Yangfan Zhou](https://appsrv.cse.cuhk.edu.hk/~yfzhou/).

His research focuses on software reliability engineering for cloud & AI systems, including:

- AIOps for cloud systems
  - Adopts data-driven methods to automate operations tasks (*e.g.,* anomaly detection, root cause analysis) based on heterogeneous data (*e.g.,* metrics, logs, alerts, and traces)
- Reliability of AI systems
  - Robustness/Fairness of AI models
  - Reliability of AI infrastructure (*e.g.,* TensorFlow and TVM)


# 🔥 News
- [2024.04] Our paper "Combating Missed Recalls in E-commerce Search: a CoT-prompting Testing Approach" was accpeted by [the industry track of FSE 2024 (The ACM International Conference on the Foundations of Software Engineering)](https://2024.esec-fse.org/track/fse-2024-industry). Congurations to Shengnan!
- [2024.04] Our paper "Less Cybersickness, Please: Demystifying and Detecting Stereoscopic Visual Inconsistencies in Virtual Reality Apps" was accpeted by [FSE 2024 (The ACM International Conference on the Foundations of Software Engineering)](https://conf.researchr.org/home/fse-2024) after major revision. Congurations to [Shuqing](https://shuqing-li.github.io/)!
- [2024.03] Our paper "A Large-Scale Evaluation for Log Parsing Techniques: How Far Are We?" was accepted by [ISSTA 2024 (The ACM SIGSOFT International Symposium on Software Testing and Analysis)](https://conf.researchr.org/home/issta-2024).
- [2024.01] 2 papers were accpeted by [FSE 2024 (The ACM International Conference on the Foundations of Software Engineering)](https://conf.researchr.org/home/fse-2024).
- [2023.12] 3 papers were accpeted by [ICSE-SEIP 2024 (The 46th IEEE/ACM International Conference on Software Engineering, The Software Engineering in Practice track)](https://conf.researchr.org/track/icse-2024/icse-2024-software-engineering-in-practice).
- [2023.08] Our paper "Appaction: Automatic GUI Interaction for Mobile Apps via Holistic Widget Perception" was accepted by [the industry track of FSE 2023 (The ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering)](https://conf.researchr.org/home/fse-2023/).
- [2023.08] 3 papers were accepted by [The 38th IEEE/ACM International Conference on Automated Software Engineering (ASE), 2023](https://conf.researchr.org/home/ase-2023). 
- [2023.07] Our paper "Ditto: An Elastic and Adaptive Memory-Disaggregated Caching
  System" was accepted by [The 29th ACM Symposium on Operating Systems Principles (SOSP), 2023](https://sosp2023.mpi-sws.org/).

# 📝 Publications 
## Selected Papers ([all](./full_pub.html))
1. SMART: A High-Performance Adaptive Radix Tree for Disaggregated Memory.\
   Xuchuan Luo, Pengfei Zuo, Jiacheng Shen, **<u>Jiazhen Gu</u>**, Xin Wang, Michael R. Lyu, and Yangfan Zhou.\
   In Proc. of [OSDI 2023](https://www.usenix.org/conference/osdi23).
2. Ditto: An Elastic and Adaptive Memory-Disaggregated Caching System.\
   Jiacheng Shen, Pengfei Zuo, Xuchuan Luo, Yuxin Su, **<u>Jiazhen Gu</u>**, Hao Feng, Yangfan Zhou, and Michael R. Lyu.\
   In Proc. of [SOSP 2023](https://sosp2023.mpi-sws.org/).
3. Appaction: Automatic GUI Interaction for Mobile Apps via Holistic Widget Perception.\
   Yongxiang Hu, **<u>Jiazhen Gu</u>**, Shuqing Hu, Yu Zhang, Wenjie Tian, Shiyu Guo, Chaoyi Chen, and Yangfan Zhou.\
   In Proc. of [ESEC/FSE 2023](https://conf.researchr.org/home/fse-2023), Industry Track.
4. An Image is Worth a Thousand Toxic Words: A Metamorphic Testing Framework for Content Moderation Software.\
   Wenxuan Wang, Jingyuan Huang, Jen-tse Huang, Chang Chen, **<u>Jiazhen Gu</u>**, Pinjia He, and Michael R. Lyu.\
   In Proc. of [ASE 2023](https://conf.researchr.org/home/ase-2023).
5. Revealing Performance Issues in Server-side WebAssembly Runtimes via Differential Testing.\
   Shuyao Jiang, Ruiying Zeng, Zihao Rao, **<u>Jiazhen Gu</u>**, Yangfan Zhou, and Michael R. Lyu.\
   In Proc. of [ASE 2023](https://conf.researchr.org/home/ase-2023).
6. Prism: Revealing Hidden Functional Clusters of Massive Instances in Cloud Systems.\
   Jinyang Liu, Zhihan Jiang, **<u>Jiazhen Gu</u>**, Junjie Huang, Zhuangbin Chen, Cong Feng, Zengyin Yang, Yongqiang Yang, and Michael R. Lyu.\
   In Proc. of [ASE 2023](https://conf.researchr.org/home/ase-2023).
7. Validating Multimedia Content Moderation Software via Semantic Fusion.\
   Wenxuan Wang, Jingyuan Huang, Chang Chen, **<u>Jiazhen Gu</u>**, Jianping Zhang, Weibin Wu, Pinjia He, and Michael R. Lyu.\
   In Proc. of [ISSTA 2023](https://conf.researchr.org/home/issta-2023).
8. BiasAsker: Measuring the Bias in Conversational AI System.\
   Yuxuan Wan, Wenxuan Wang, Pinjia He, **<u>Jiazhen Gu</u>**, Haonan Bai, and Michael R. Lyu.\
   In Proc. of [ESEC/FSE 2023](https://conf.researchr.org/home/fse-2023).
9. Muffin: Testing Deep Learning Libraries via Neural Architecture Fuzzing.\
    **<u>Jiazhen Gu</u>**, Xuchuan Luo, Yangfan Zhou, and Xin Wang.\
    In Proc. of [ICSE 2022](https://conf.researchr.org/home/icse-2022).
10. Efficient Incident Identification from Multi-dimensional Issue Reports via Meta-heuristic Search.\
    **<u>Jiazhen Gu</u>**, Chuan Luo, Si Qin, Bo Qiao, Qingwei Lin, Hongyu Zhang, Ze Li, Yingnong Dang, Shaowei Cai, Wei Wu, Yangfan Zhou, Murali Chintalapati, and Dongmei Zhang.\
    In Proc. of [ESEC/FSE 2020](https://2020.esec-fse.org/).
11. Efficient Customer Issue Triage via Linking with System Incidents.\
    **<u>Jiazhen Gu</u>**, Jiaqi Wen, Zijian Wang, Pu Zhao, Chuan Luo, Yu Kang, Yangfan Zhou, Li Yang, Jeffrey Sun, Zhangwei Xu, Bo Qiao, Liqun Li, Qingwei Lin, and Dongmei Zhang.\
    In Proc. of [ESEC/FSE 2020](https://2020.esec-fse.org/), Industry Track.



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 💬 Invited Talks
- [2023.06] "Towards Intelligent Operations for Reliable Cloud Systems: Current Landscape, Opportunities, and Challenges".