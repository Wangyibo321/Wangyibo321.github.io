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

# About Me
<span class='anchor' id='about-me'></span>
I am Yibo Wang, a PhD student in Computer Science at Purdue University advised by Professor [Jianguo Wang](https://www.cs.purdue.edu/homes/csjgwang/). My current research focuses on enhancing the efficiency and usability of vector databases using machine learning techniques. I received my Bachelor's degree from Sichuan University, where I worked with Professor [Mingjie Tang](http://merlintang.github.io/) on applying advanced AI techniques to optimize database performance.



# News
<span class='anchor' id='news'></span>
- *2025.10*: &nbsp;🎉🎉 QUITE is under revision for SIGMOD 2026!
- *2025.08*: &nbsp;🎉🎉 I am thrilled to begin my PhD journey at Purdue University!
- *2024.12*: &nbsp;🎉🎉 GPTuner wins <a href="https://sigmod.org/sigmod-awards/sigmod-research-highlights/" style="color:red; font-weight:700;">SIGMOD Research Highlight Award</a>!
- *2024.08*: &nbsp;🎉🎉 I presented [GPTuner](https://vldb.org/pvldb/vol17/p1939-tang.pdf) at [VLDB 2024](https://vldb.org/2024/) !
- *2024.03*: &nbsp;🎉🎉 [Demo of GPTuner](https://dl.acm.org/doi/10.1145/3626246.3654739) is accepted by SIGMOD, 2024!
- *2024.03*: &nbsp;🎉🎉 [GPTuner](https://vldb.org/pvldb/vol17/p1939-tang.pdf) is accepted by VLDB, 2024!
- *2024.01*: &nbsp;🎉🎉 A video demonstration of GPTuner is available on [YouTube](https://www.youtube.com/watch?v=Hz5Zck-9TlA)!
- *2023.07*: &nbsp;🎉🎉 I joined the [IDs lab](https://ids-lab-asia.github.io/) in College of Computer Science, Sichuan University!

# Educations
<span class='anchor' id='educations'></span>
- *2025.08 - Present*, PhD Student of Computer Science, Purdue University
- *2021.09 - 2025.06*, Bachelor of Computer Science, Sichuan University

# Publications
<span class='anchor' id='publications'></span>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Revision</div>
      <img src='images/quite.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[QUITE: A Query Rewrite System Beyond Rules with LLM Agents](https://arxiv.org/pdf/2506.07675)

Yuyang Song, Hanxu Yan, Jiale Lao, **Yibo Wang**, Yuanchun Zhou, Jianguo Wang, Mingjie Tang

Under revision for Proceedings of ACM Conference on Management of Data (**SIGMOD**), 2026.

<a href="https://arxiv.org/pdf/2506.07675" class="paper-link" title="PDF" target="_blank" rel="noopener">
  <i class="fas fa-file-pdf"></i>
  <span class="paper-link-label">PDF</span>
</a> &nbsp;
<a href="https://anonymous.4open.science/r/QUITE-758D" class="paper-link" title="Project" target="_blank" rel="noopener">
  <i class="fas fa-code"></i>
  <span class="paper-link-label">Code</span>
</a>&nbsp;


  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">In Submission</div> 
      <img src='images/water.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[WAter: A Workload-Adaptive Knob Tuning System](https://wangyibo321.github.io/assets/WAter.pdf)

**Yibo Wang**, Jiale Lao, Chen Zhang, Cehua Yang, Yuanchun Zhou, Jianguo Wang, Mingjie Tang

In Submission to Proceedings of ACM Conference on Management of Data (**SIGMOD**), 2026.

<a href="https://wangyibo321.github.io/assets/WAter.pdf" class="paper-link" title="PDF" target="_blank" rel="noopener">
  <i class="fas fa-file-pdf"></i>
  <span class="paper-link-label">PDF</span>
</a> &nbsp;
<a href="https://anonymous.4open.science/r/WAter-1BDD/" class="paper-link" title="Project" target="_blank" rel="noopener">
  <i class="fas fa-code"></i>
  <span class="paper-link-label">Code</span>
</a>&nbsp;

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">SIGMOD Record 2025</div>
      <img src='images/gptuner.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[GPTuner: An LLM-Based Database Tuning System](https://dl.acm.org/doi/pdf/10.1145/3733620.3733641)

Jiale Lao, **Yibo Wang**, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Chen, Wanghu Chen, Mingjie Tang, Jianguo Wang

**SIGMOD Record**, 2025.

<a href="https://dl.acm.org/doi/pdf/10.1145/3733620.3733641" class="paper-link" title="PDF" target="_blank" rel="noopener">
  <i class="fas fa-file-pdf"></i>
  <span class="paper-link-label">PDF</span>
</a> &nbsp;
<a href="https://github.com/SolidLao/GPTuner" class="paper-link" title="Project" target="_blank" rel="noopener">
  <i class="fas fa-code"></i>
  <span class="paper-link-label">Code</span>
</a>&nbsp;
<a href="https://www.youtube.com/watch?v=Hz5Zck-9TlA" class="paper-link" title="Video" target="_blank" rel="noopener">
  <i class="fab fa-youtube"></i>
  <span class="paper-link-label">Video</span>
</a>&nbsp;
<!-- <a href="https://sigmod.org/sigmod-awards/sigmod-research-highlights/" class="paper-link" title="Video" target="_blank" rel="noopener">
  <i class="fas fa-award" aria-hidden="true"></i>
  <span class="badge-text">Award</span>
</a> -->

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">VLDB 2024</div>
      <img src='images/gptuner.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[GPTuner: A Manual-Reading Database Tuning System via GPT-Guided Bayesian Optimization](https://dl.acm.org/doi/10.14778/3659437.3659449)

Jiale Lao, **Yibo Wang**, Yufei Li, Jianping Wang, Yunjia Zhang, Zhiyuan Chen, Wanghu Chen, Mingjie Tang, Jianguo Wang

Proceedings of Very Large Data Bases Conference (**VLDB**), 2024.

<span style="color:red; font-weight:bold;">Selected as SIGMOD Research Highlight</span>

<a href="https://vldb.org/pvldb/vol17/p1939-tang.pdf" class="paper-link" title="PDF" target="_blank" rel="noopener">
  <i class="fas fa-file-pdf"></i>
  <span class="paper-link-label">PDF</span>
</a> &nbsp;
<a href="https://github.com/SolidLao/GPTuner" class="paper-link" title="Project" target="_blank" rel="noopener">
  <i class="fas fa-code"></i>
  <span class="paper-link-label">Code</span>
</a>&nbsp;
<a href="https://www.youtube.com/watch?v=Hz5Zck-9TlA" class="paper-link" title="Video" target="_blank" rel="noopener">
  <i class="fab fa-youtube"></i>
  <span class="paper-link-label">Video</span>
</a>&nbsp;
<a href="https://sigmodrecord.org/publications/sigmodRecord/2503/pdfs/02_editor_notes.pdf" class="paper-link" title="Video" target="_blank" rel="noopener">
  <i class="fas fa-award" aria-hidden="true"></i>
  <span class="badge-text">Award</span>
</a>

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

Jiale Lao\*, **Yibo Wang\***, Yufei Li\*, Jianping Wang, Yunjia Zhang, Zhiyuan Chen, Wanghu Chen, Yuanchun Zhou, Mingjie Tang, Jianguo Wang

Proceedings of ACM Conference on Management of Data (**SIGMOD**), 2024.

<a href="https://dl.acm.org/doi/10.1145/3626246.3654739" class="paper-link" title="PDF" target="_blank" rel="noopener">
  <i class="fas fa-file-pdf"></i>
  <span class="paper-link-label">PDF</span>
</a> &nbsp;
<a href="https://github.com/SolidLao/GPTuner" class="paper-link" title="Project" target="_blank" rel="noopener">
  <i class="fas fa-code"></i>
  <span class="paper-link-label">Code</span>
</a>&nbsp;
<a href="https://www.youtube.com/watch?v=Hz5Zck-9TlA" class="paper-link" title="Video" target="_blank" rel="noopener">
  <i class="fab fa-youtube"></i>
  <span class="paper-link-label">Video</span>
</a>

  </div>
</div>



<!-- # 📝 Research

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
- Proposed a runtime-statistics-based *representativity* metric to continually refine subset, a history reuse method to achieve efficient subset tuning, and a hybrid scoring mechanism to choose the most promising configurations to evaluate.
- Evaluated **WAter** under four OLAP workloads, it identifies better configurations with up to **73.5%** less tuning time, achieving up to **16.2%** better performance than the **best-performing** alternative.
- Outcomes: a research paper in submission, and an open-source project on GitHub.



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
 -->

# Awards
<span class='anchor' id='awards'></span>

- <a href="https://sigmodrecord.org/publications/sigmodRecord/2503/pdfs/02_editor_notes.pdf" class="paper-link" title="Award" target="_blank" rel="noopener">
  <span class="paper-link-label">SIGMOD Research Highlight Award 2024</span>
</a>

# Services
<span class='anchor' id='services'></span>
- Reviewer \- TKDE [2025]
- Reviewer \- Information Systems [2025]
- External Reviewer \- VLDB [2024][2025]
- External Reviewer \- ICDE [2024]

# Teaching
<span class='anchor' id='teaching'></span>
- Teaching Assistant \- Purdue CS348 Information Systems [Fall 2025]