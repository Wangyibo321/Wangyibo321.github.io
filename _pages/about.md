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

I am Yibo Wang, a junior majoring in Computer Science at College of Computer Science, Sichuan University (Chengdu, China). Currently, I am in AI-System Lab, under the supervision of [Prof. Mingjie Tang](http://merlintang.github.io/). 

My research interests lie in the intersection of database management systems (DBMSs) and machine learning (ML), especially using ML/AI techniques to automate database administration/tuning to remove human impediments. 

My aim is to make significant contributions to the field of self-driving DBMS through advanced research and collaborative efforts.

I am a highly self-motivated undergraduate eagerly seeking admission to **a Ph.D. program**.

*Email*: *wangyibo2@stu.scu.edu.cn*



# 🔥 News
- *2024.03*: &nbsp;🎉🎉 [Demo of GPTuner](https://www.youtube.com/watch?v=Hz5Zck-9TlA) is accepted by SIGMOD '24. !
- *2024.03*: &nbsp;🎉🎉 [GPTuner](https://arxiv.org/abs/2311.03157) is accepted by VLDB '24!
- *2024.01*: &nbsp;🎉🎉 A video demonstration of GPTuner is available on [YouTube](https://www.youtube.com/watch?v=Hz5Zck-9TlA)!
- *2023.12*: &nbsp;🎉🎉 [GPTuner](https://arxiv.org/abs/2311.03157) is under revision of Proceedings of Very Large Data Bases Conference (VLDB) !
- *2023.07*: &nbsp;🎉🎉 I become one of AI-System lab at College of Computer Science, Sichuan University!

# 📖 Educations
- *2021.09 - 2025.06*, Bachelor of Computer Science, College of Computer Science, Sichuan University, Chengdu, China

# 📝 Publications


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">VLDB 2024</div>
      <img src='images/gptuner.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian](https://arxiv.org/abs/2311.03157)

Jiale Lao, **Yibo Wang**, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Chen, Wanghu Chen, Mingjie Tang, Jianguo Wang

Proceedings of Very Large Data Bases Conference (VLDB), 2024.

  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">SIGMOD 2024</div> 
      <img src='images/demo.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[A Demonstration of GPTuner: A GPT-Based Manual-Reading Database Tuning System](https://www.youtube.com/watch?v=Hz5Zck-9TlA)

Jiale Lao, **Yibo Wang**, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Chen, Wanghu Chen, Yuanchun Zhou, Mingjie Tang, Jianguo Wang

Proceedings of ACM Conference on Management of Data (SIGMOD), 2024.
  </div>
</div>


# 📝 Research

<div style="overflow: hidden;">
    <div style="float: left;font-size: 18px"><strong>LLM-Powered Interactive Tool to Explore and Exploit Domain Insights </strong> </div>
    <div style="float: right;font-size: 18px"><i><strong>Research Assistant</strong></i></div>
</div>
<div style="overflow: hidden;">
    <div style="float: left;font-size: 15px">
      <i>Advisors: Prof. Jianguo Wang (Purdue); Prof. Mingjie Tang (SCU)</i>
    </div>
      <div style="float: right;font-size: 16px"><i>Jan. 2024 – Jan. 2024</i></div>
</div>

- Engaged users to probe into the ingenious LLM-powered pipeline which refines and unifies heterogeneous knowledge to guide system optimization.
- Unleashed the potential of everyday users, enabling them to delve into the nuances of knob features and maximize the efficiency of their tailored DBMS seamlessly.
- Empowered DBAs to supercharge GPTuner with their priceless tuning expertise expressed in natural language and witness how it can be customized to the Coarse-to-Fine Optimization Framework.
- Outcomes: a demo paper accepted by **SIGMOD** 2024, and an open-source project with more than **3000 views, 200 clones and 50 stars** on GitHub.


<div style="overflow: hidden;">
    <div style="float: left;font-size: 18px"><strong>Automated Optimization of Database with Large Language Model</strong> </div>
    <div style="float: right;font-size: 18px"><i><strong>Research Assistant</strong></i></div>
</div>
<div style="overflow: hidden;">
    <div style="float: left;font-size: 15px">
      <i>Advisors: Prof. Jianguo Wang (Purdue); Prof. Mingjie Tang (SCU) </i>
    </div>
    <div style="float: right;font-size: 16px"><i>Sept. 2023 – Feb. 2024</i></div>
</div>

- Designed and implemented **GPTuner**, a novel manual-reading database tuning system that automatically exploits domain knowledge to enhance the knob tuning process.
- Developed a LLM-based data pipeline, a prompt ensemble algorithm, a workload-aware and training-free knob selection strategy, and a Coarse-to-Fine Bayesian Optimization Framework. 
- Evaluated **GPTuner** under different benchmarks, metrics and DBMS. It identifies better configurations **16x** faster and achieves **30%** performance improvement over the **best-performing** alternative.


<div style="overflow: hidden;">
    <div style="float: left;font-size: 18px"><strong>Automated Optimization for Stream Processing Systems</strong> </div>
    <div style="float: right;font-size: 18px"><i><strong>Research Assistant</strong></i></div>
</div>
<div style="overflow: hidden;">
    <div style="float: left;font-size: 15px">
      <i>Advisors: Prof. Mingjie Tang (SCU); Dr. Xiaojun Zhan (AntGroup)</i>
    </div>
    <div style="float: right;font-size: 16px"><i>Aug. 2023 – Sept. 2023</i></div>
</div>

- Collaborated with AntGroup to develop an automated optimization system for Flink, reducing resource consumption to cope with tight budget while maintaining SLA adherence.
- Proposed a rule-based method to get pod features based on the degree of parallelism of vertexes.
- Implemented an ML-based evaluator to estimate resource utilization of a pod given its features.
