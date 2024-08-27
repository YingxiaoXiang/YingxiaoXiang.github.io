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

<span class='anchor' id='About-Me'></span>

Hi! I am Yingxiao Xiang (相迎宵 in Chinese). I am an engineer in the [Institute of Information Engineering, CAS](http://www.iie.ac.cn/). I received the Master degree from Beijing Jiaotong University in 2019, Ph.D. degree of cyber security in Beijing Jiaotong University in 2023. My research interests are in AI security and Network Threat Discovery.

Currently, my research has centered on:

- **AI Security:** backdoor attacks and defenses, adversarial attacks and defenses.

* **Safety Testing**:  testing and evaluation for autonomous driving algorithms, modules, and systems.

* **Data Augmentation**: image or video generation, especially focus on generative data augmentation (GDA) in autonomous driving scenarios.

* **Autonomous Driving Security**: attacks and defenses against the physical world, sensors, algorithms and automonous driving systems.

* **Reinforcement Learning**: safety reinforcement learning (SRL), robustness reinforcement learning and offline reinforcement learning for autonomous driving systems.

📮: I am always looking for related colaboration. If you are interested to chat with me, feel free to drop me an <a href="mailto:xiangyingxiao@iie.ac.cn" target="_blank">email</a>.





{% include_relative includes/News.md %}



{% include_relative includes/Publications.md %}



{% include_relative includes/Honors.md %}



{% include_relative includes/Experience.md %}



{% include_relative includes/Educations.md %}



{% include_relative includes/Projects.md %}
