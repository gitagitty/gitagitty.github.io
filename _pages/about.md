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

I am a senior undergraduate student at [School of Mechanical, Electronic and Control Engineering](https://mece.bjtu.edu.cn/), [Beijing Jiaotong University](https://www.bjtu.edu.cn/) (BJTU), expecting to receive my B.Eng. degree in 2027. I will pursue my graduate studies at [Institute of Automation, Chinese Academy of Sciences](https://ia.cas.cn/) (CASIA) as a master's student. My current research centers on multimodal perception and embodied agents; at CASIA I plan to work on vision-language-action (VLA) models and world models. If you are interested in my research, please feel free to contact me at <a href="mailto:23222002@bjtu.edu.cn">23222002@bjtu.edu.cn</a>.



# 🔥 News
- *2026.10*: &nbsp;🔥🔥 We release **[ROMA](https://gewu-lab.github.io/ROMA/)**, an LLM-Based System for Real-World Object-Centric Multi-Sensory Active Perception! One step towards active multi-sensory embodied agents!
- *2026.03*: &nbsp;🎉🎉 **Nonholonomic Narrow Dead-end Escape with Reinforcement Learning** is accepted to CSAI 2026! The [codes](https://github.com/gitagitty/cisDRL-RobotNav) are released!

# 📝 Publications

- **<font size=4>Nonholonomic Narrow Dead-end Escape with Reinforcement Learning</font>**<br>
  Denghan Xiong\*, Yanzhe Zhao\*, **Yutong Chen\***, Zichun Wang\* &nbsp; (\*equal contribution)<br>
  **CSAI 2026**<br>
  [\[Paper\]](https://doi.org/10.1145/3788149.3788204) \| [\[Code\]](https://github.com/gitagitty/cisDRL-RobotNav)

# 📄 Preprints
<div class='paper-box'><div class='paper-box-image'><div><img src='images/ROMA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>ROMA: LLM System for Real-World Object-Centric
Multi-Sensory Active Perception</font>**

Ruoxuan Feng\*, **Yutong Chen\***, Ruihua Song, Huan Yang, Zhongyuan Wang, Guocai Yao, Di Hu &nbsp; (\*equal contribution)

arXiv 2610.06955

[\[Paper\]](https://arxiv.org/abs/2610.06955) \| [\[Code\]](https://github.com/GeWu-Lab/ROMA) \| [\[Project\]](https://gewu-lab.github.io/ROMA/)
</div>
</div>

# 💻 Projects
<!-- TODO: 项目展示，格式示例：
- **[Project Name](https://github.com/gitagitty/xxx)** — One-sentence description. `Python` `PyTorch`
-->
- **[Visually based automatic docking system for two-wheeled robots](https://github.com/gitagitty/yolodc_ws)** — A YOLO-based ROS 2 pipeline that uses an RGB-D camera to detect docking targets and close the loop for autonomous two-wheeled robot docking. `Python` `PyTorch` `ROS2`

# 📖 Educations
- *2027.09 - 2030.06 (expected)*, M.S., [Institute of Automation, Chinese Academy of Sciences](https://ia.cas.cn/) (CASIA).
- *2023.09 - 2027.06 (expected)*, B.Eng., [School of Mechanical, Electronic and Control Engineering](https://mece.bjtu.edu.cn/), [Beijing Jiaotong University](https://www.bjtu.edu.cn/) (BJTU).

# 💼 Internships
- *2025.10 - 2026.10*, Research Assistant, [Gewu Lab](https://gewu-lab.github.io/), Gaoling School of Artificial Intelligence, Renmin University of China, Beijing, China. Advised by [Prof. Di Hu](https://dtaoo.github.io/).<br>
  Co-first author of **[ROMA](https://gewu-lab.github.io/ROMA/)**, an LLM-based system for real-world object-centric multi-sensory active perception. ROMA turns passive sensing into an active **reasoning–interaction–feedback loop**: a multi-sensory LLM (ROMA-7B) decides which evidence is missing and which object, interaction and modality to probe, while a physical interface executes it on a real robot arm and streams back vision, audio, touch and force feedback, reaching **72.9%** success versus **53.0%** for the strongest baseline.<br>
  I was responsible for the following: 1. Grasp pose planning of real-world interaction; 2. Anotation design and data collection


<!-- TODO: 上面第 2、3 句写的是 ROMA 这个项目本身（数据已对照项目主页核实）。
     建议再补一条你【个人具体负责】的部分，越具体越好，例如：
       - 数据采集 pipeline / teleoperation 采集 / 标注协议
       - ROMA-7B 某个模块的实现或训练
       - ROMA Bench 的评测脚本
     导师和审稿人最想看到的是「你做了什么」，而不只是「这个项目是什么」。 -->


# 🎖 Honors and Awards
<!-- TODO: 格式示例：
- *2025.10* National Scholarship, Beijing Jiaotong University.
-->
- *2024.10* Shenzhou Railway Scholarship, Beijing Jiaotong University.