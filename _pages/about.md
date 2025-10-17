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

Jiazhen Gu is currently a principal engineer at Huawei Hong Kong Research Center. He was a postdoctoral researcher in the [Automated Reliable Intelligent Software Engineering (ARISE) Lab](http://ariselab.cse.cuhk.edu.hk/) at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/), mentored by Prof. [Michael R. Lyu](https://www.cse.cuhk.edu.hk/lyu/). Jiazhen Gu received both Ph.D. and B.S. degrees from [Fudan University](https://www.fudan.edu.cn/), supervised by Prof. [Xin Wang](https://faculty.fudan.edu.cn/wangxin/zh_CN/) and Prof. [Yangfan Zhou](https://appsrv.cse.cuhk.edu.hk/~yfzhou/).

His research focuses on software reliability engineering for cloud & AI systems, including:

- AIOps for cloud systems
  - Adopts data-driven methods to automate operations tasks (*e.g.,* anomaly detection, root cause analysis) based on heterogeneous data (*e.g.,* metrics, logs, alerts, and traces)
- Reliability of AI systems
  - Robustness/Fairness of AI models
  - Reliability of AI infrastructure (*e.g.,* TensorFlow and TVM)


# 🔥 News
- [2025.10] Our paer "PreServe: Intelligent Management for LMaaS Systems via Hierarchical Prediction" was accepted by [ICSE 2026 (the 47th IEEE/ACM International Conference on Software Engineering)](https://conf.researchr.org/home/icse-2026). Congurations to Zhihan!
- [2024.10] Our paper "ADAMAS: Adaptive Domain-Aware Performance Anomaly Detection in Cloud Service Systems" was accepted by [ICSE 2025 (the 47th IEEE/ACM International Conference on Software Engineering)](https://conf.researchr.org/home/icse-2025). Congurations to Wenwei!
- [2024.08] Our paper "Contextualized Data-Wrangling Code Generation in Computational Notebooks" was accepted by [ASE 2024 (The 39th IEEE/ACM International Conference on Automated Software Engineering)](https://conf.researchr.org/home/ase-2024). Congurations to Junjie!
- [2024.06] "KPIRoot: Efficient Monitoring Metric-based Root Cause Localization in Large-scale Cloud Systems" and "Demystifying and Extracting Fault-indicating Information from Logs for Failure Diagnosis" were accepted by [ISSRE 2024 (The 35th IEEE International Symposium on Software Reliability Engineering)](https://issre.github.io/2024/index.html).
- [2024.04] Our paper "Combating Missed Recalls in E-commerce Search: a CoT-prompting Testing Approach" was accpeted by [the industry track of FSE 2024 (The ACM International Conference on the Foundations of Software Engineering)](https://2024.esec-fse.org/track/fse-2024-industry). Congurations to Shengnan!
- [2024.04] Our paper "Less Cybersickness, Please: Demystifying and Detecting Stereoscopic Visual Inconsistencies in Virtual Reality Apps" was accpeted by [FSE 2024 (The ACM International Conference on the Foundations of Software Engineering)](https://conf.researchr.org/home/fse-2024) after major revision. Congurations to [Shuqing](https://shuqing-li.github.io/)!
- [2024.03] Our paper "A Large-Scale Evaluation for Log Parsing Techniques: How Far Are We?" was accepted by [ISSTA 2024 (The ACM SIGSOFT International Symposium on Software Testing and Analysis)](https://conf.researchr.org/home/issta-2024).
- [2024.01] 2 papers were accpeted by [FSE 2024 (The ACM International Conference on the Foundations of Software Engineering)](https://conf.researchr.org/home/fse-2024).

# 📝 Publications
## Selected Papers ([all](./full_pub.html))
* Corresponding author marked with * *
1. PreServe: Intelligent Management for LMaaS Systems via Hierarchical Prediction. \
   Zhihan Jiang, Yujie Huang, Guangba Yu, Junjie Huang, **<u>Jiazhen Gu*</u>**, and Michael R. Lyu.
2. SMART: A High-Performance Adaptive Radix Tree for Disaggregated Memory.\
   Xuchuan Luo, Pengfei Zuo, Jiacheng Shen, **<u>Jiazhen Gu</u>**, Xin Wang, Michael R. Lyu, and Yangfan Zhou.\
   In Proc. of [OSDI 2023](https://www.usenix.org/conference/osdi23).
3. Ditto: An Elastic and Adaptive Memory-Disaggregated Caching System.\
   Jiacheng Shen, Pengfei Zuo, Xuchuan Luo, Yuxin Su, **<u>Jiazhen Gu</u>**, Hao Feng, Yangfan Zhou, and Michael R. Lyu.\
   In Proc. of [SOSP 2023](https://sosp2023.mpi-sws.org/).
4. Appaction: Automatic GUI Interaction for Mobile Apps via Holistic Widget Perception.\
   Yongxiang Hu, **<u>Jiazhen Gu</u>**, Shuqing Hu, Yu Zhang, Wenjie Tian, Shiyu Guo, Chaoyi Chen, and Yangfan Zhou.\
   In Proc. of [ESEC/FSE 2023](https://conf.researchr.org/home/fse-2023), Industry Track.
5. An Image is Worth a Thousand Toxic Words: A Metamorphic Testing Framework for Content Moderation Software.\
   Wenxuan Wang, Jingyuan Huang, Jen-tse Huang, Chang Chen, **<u>Jiazhen Gu</u>**, Pinjia He, and Michael R. Lyu.\
   In Proc. of [ASE 2023](https://conf.researchr.org/home/ase-2023).
6. Revealing Performance Issues in Server-side WebAssembly Runtimes via Differential Testing.\
   Shuyao Jiang, Ruiying Zeng, Zihao Rao, **<u>Jiazhen Gu</u>**, Yangfan Zhou, and Michael R. Lyu.\
   In Proc. of [ASE 2023](https://conf.researchr.org/home/ase-2023).
7. Prism: Revealing Hidden Functional Clusters of Massive Instances in Cloud Systems.\
   Jinyang Liu, Zhihan Jiang, **<u>Jiazhen Gu</u>**, Junjie Huang, Zhuangbin Chen, Cong Feng, Zengyin Yang, Yongqiang Yang, and Michael R. Lyu.\
   In Proc. of [ASE 2023](https://conf.researchr.org/home/ase-2023).
8. Validating Multimedia Content Moderation Software via Semantic Fusion.\
   Wenxuan Wang, Jingyuan Huang, Chang Chen, **<u>Jiazhen Gu</u>**, Jianping Zhang, Weibin Wu, Pinjia He, and Michael R. Lyu.\
   In Proc. of [ISSTA 2023](https://conf.researchr.org/home/issta-2023).
9.  BiasAsker: Measuring the Bias in Conversational AI System.\
   Yuxuan Wan, Wenxuan Wang, Pinjia He, **<u>Jiazhen Gu</u>**, Haonan Bai, and Michael R. Lyu.\
   In Proc. of [ESEC/FSE 2023](https://conf.researchr.org/home/fse-2023).
10. Muffin: Testing Deep Learning Libraries via Neural Architecture Fuzzing.\
    **<u>Jiazhen Gu</u>**, Xuchuan Luo, Yangfan Zhou, and Xin Wang.\
    In Proc. of [ICSE 2022](https://conf.researchr.org/home/icse-2022).
11. Efficient Incident Identification from Multi-dimensional Issue Reports via Meta-heuristic Search.\
    **<u>Jiazhen Gu</u>**, Chuan Luo, Si Qin, Bo Qiao, Qingwei Lin, Hongyu Zhang, Ze Li, Yingnong Dang, Shaowei Cai, Wei Wu, Yangfan Zhou, Murali Chintalapati, and Dongmei Zhang.\
    In Proc. of [ESEC/FSE 2020](https://2020.esec-fse.org/).
12. Efficient Customer Issue Triage via Linking with System Incidents.\
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