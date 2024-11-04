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

I am Yibo Wang, a senior student majoring in Computer Science at College of Computer Science, Sichuan University (Chengdu, China). Currently, I am fortunate to be advised by Professor [Prof. Mingjie Tang](http://merlintang.github.io/) and Professor [Jianguo Wang](https://www.cs.purdue.edu/homes/csjgwang/) from [Purdue University](https://www.purdue.edu/), focusing on utilizing ML/AI techniques to optimize database performance.

I am a highly self-motivated undergraduate eagerly looking for **PhD opportunities (Fall 2025) in the US**.

*Email*: *wangyb0520[at]gmail[dot]com*



# 🔥 News
- *2024.08*: &nbsp;🎉🎉 I presented [GPTuner](https://vldb.org/pvldb/vol17/p1939-tang.pdf) at [VLDB 2024](https://vldb.org/2024/) !
- *2024.03*: &nbsp;🎉🎉 [Demo of GPTuner](https://dl.acm.org/doi/10.1145/3626246.3654739) is accepted by SIGMOD, 2024 !
- *2024.03*: &nbsp;🎉🎉 [GPTuner](https://vldb.org/pvldb/vol17/p1939-tang.pdf) is accepted by VLDB, 2024 !
- *2024.01*: &nbsp;🎉🎉 A video demonstration of GPTuner is available on [YouTube](https://www.youtube.com/watch?v=Hz5Zck-9TlA)!
- *2023.07*: &nbsp;🎉🎉 I become one of [IDs lab](https://ids-lab-asia.github.io/) at College of Computer Science, Sichuan University!

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

[GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian](https://vldb.org/pvldb/vol17/p1939-tang.pdf)

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

[A Demonstration of GPTuner: A GPT-Based Manual-Reading Database Tuning System](https://dl.acm.org/doi/10.1145/3626246.3654739)

Jiale Lao, **Yibo Wang**, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Chen, Wanghu Chen, Yuanchun Zhou, Mingjie Tang, Jianguo Wang

Proceedings of ACM Conference on Management of Data (SIGMOD), 2024.
  </div>
</div>


# 📝 Research

<div style="overflow: hidden;">
    <div style="float: left;font-size: 18px"><strong>Runtime-Efficient Adaptive Knob Tuning System</strong> </div>
    <div style="float: right;font-size: 18px"><i><strong>Project Leader</strong></i></div>
</div>
<div style="overflow: hidden;">
    <div style="float: left;font-size: 15px">
      <i>Advisors: Prof. Jianguo Wang (Purdue); Prof. Mingjie Tang (SCU)</i>
    </div>
    <div style="float: right;font-size: 16px"><i>Mar. 2024 – Present</i></div>
</div>

- Developed **WAter**, an adaptive knob tuning framework that uses runtime-profile to significantly reduce benchmark evaluation costs by only selecting SQL subsets to evaluate at different time slices.
- Proposed a novel greedy algorithm to optimize a runtime-statistics-based representativity metric, continually refining the subset as the optimization proceeds.
- Developed a new history reuse mechanism to achieve efficient subset tuning, mitigating the overheads of switching between tuning different subsets.
- Proposed a hybrid scoring method to prune, score and rank configurations, evaluating only the most promising configurations to achieve minimum overheads.
- Evaluated **WAter** under four OLAP workloads, it identifies better configurations with up to **73.5%** less tuning time, achieving up to **16.2%** better performance than the **best-performing** alternative.
- Outcomes: a research paper submitted to **SIGMOD** 2025, and an upcoming project to be open-sourced.


<div style="overflow: hidden;">
    <div style="float: left;font-size: 18px"><strong>LLM-Powered Interactive Tool to Explore and Exploit Domain Insights </strong> </div>
    <div style="float: right;font-size: 18px"><i><strong>Research Assistant</strong></i></div>
</div>
<div style="overflow: hidden;">
    <div style="float: left;font-size: 15px">
      <i>Advisors: Prof. Jianguo Wang (Purdue); Prof. Mingjie Tang (SCU)</i>
    </div>
      <div style="float: right;font-size: 16px"><i>Jan. 2024 – Feb. 2024</i></div>
</div>

- Engaged users to probe into the ingenious LLM-powered pipeline which refines and unifies heterogeneous knowledge to guide system optimization.
- Unleashed the potential of everyday users, enabling them to delve into the nuances of knob features and maximize the efficiency of their tailored DBMS seamlessly.
- Empowered DBAs to supercharge GPTuner with their priceless tuning expertise expressed in natural language and witness how it can be customized to the Coarse-to-Fine Optimization Framework.
- Outcomes: a demo paper accepted by **SIGMOD** 2024, and an open-source project with **70 stars** on GitHub.


<div style="overflow: hidden;">
    <div style="float: left;font-size: 18px"><strong>Automated Optimization of Database with Large Language Model</strong> </div>
    <div style="float: right;font-size: 18px"><i><strong>Research Assistant</strong></i></div>
</div>
<div style="overflow: hidden;">
    <div style="float: left;font-size: 15px">
      <i>Advisors: Prof. Jianguo Wang (Purdue); Prof. Mingjie Tang (SCU) </i>
    </div>
    <div style="float: right;font-size: 16px"><i>Sept. 2023 – Present</i></div>
</div>

- Designed and implemented **GPTuner**, a novel manual-reading database tuning system that automatically exploits domain knowledge to enhance the knob tuning process.
- Developed a LLM-based data pipeline, a prompt ensemble algorithm, a workload-aware and training-free knob selection strategy, and a Coarse-to-Fine Bayesian Optimization Framework. 
- Evaluated **GPTuner** under different benchmarks, metrics and DBMS. It identifies better configurations **16x** faster and achieves **30%** performance improvement over the **best-performing** alternative.
- Outcomes: a research paper accepted by **VLDB** 2024.

