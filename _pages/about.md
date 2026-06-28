---

permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:

* /about/
* /about.html

---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 About Me

I am **Dan Shi**, a Ph.D. Candidate in the School of Computer Science and Technology at **Tianjin University**, advised by **Prof. Deyi Xiong**.

My research focuses on **Large Language Models (LLMs)**, with particular interests in **LLM post-training**, **safety alignment**, **mechanistic interpretability**, and **reinforcement learning for LLMs**. My recent work aims to understand *why reinforcement learning generalizes better than supervised fine-tuning*, develop efficient safety alignment methods against jailbreak attacks, improve multilingual safety alignment, and interpret internal representations of large language models.

I am currently a **Research Intern** at the **ERNIE Foundation Model Team, Baidu**, and previously worked as a **Visiting Researcher** at the **German Research Center for Artificial Intelligence (DFKI)**.

I have published first-author papers at **ICML, ACL, ACL Findings, NeurIPS, AAAI, and DASFAA**.

📧 **Email:** [shidan@tju.edu.cn](mailto:shidan@tju.edu.cn)

📄 **Google Scholar:** <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID">Google Scholar <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=Citations"></a>



# 📌 Open Positions

I am actively seeking full-time LLM Algorithm Engineer positions, with research and engineering interests in LLM post-training, reinforcement learning for LLMs, and coding agents. Feel free to contact me if you think my background matches your team.



## 🔍 Research Interests

* Large Language Models
* LLM Post-training
* Reinforcement Learning for LLMs
* Safety Alignment
* Mechanistic Interpretability
* Multilingual LLMs
* Hallucination Mitigation
* LLM Agents



# 🔥 News

* **May. 2026** Joined the **ERNIE Foundation Model Team, Baidu** as a Research Intern.
* **Jun. 2026** 🎉 One paper accepted to **ICML 2026**.
* **Feb. 2026** 🎉 One paper accepted to **ACL 2026**.
* **Jan. 2026** 🎉 One paper accepted to **ACL Findings 2026**.
* **May. 2025** Started visiting the **German Research Center for Artificial Intelligence (DFKI)**.
* **Sep. 2024** 🎉 One paper accepted to **NeurIPS 2024**.
* **Dec. 2023** 🎉 One paper accepted to **AAAI 2024**.
* **Apr. 2022** 🎉 One paper accepted to **AAAI 2024**.



# 📝 Selected Publications

### ICML 2026

**Multilingual Safety Alignment via Representation-Space Separability**

**Dan Shi**, *et al.*

* Proposes a representation-space optimization framework for multilingual safety alignment by transferring safety capability from high-resource languages to low-resource languages.



### ACL 2026

**Why Does Reinforcement Learning Generalize? A Feature-Level Mechanistic Study of Post-Training in Large Language Models**

**Dan Shi**, *et al.*

* Reveals why reinforcement learning achieves stronger generalization than supervised fine-tuning through sparse feature analysis and causal intervention.



### ACL Findings 2026

**Neuronal Insights into LLM Attacks: Targeted Neuron Tuning for Precise and Efficient Vulnerability Patching**

**Dan Shi**, *et al.*

* Introduces Targeted Neuron Tuning (TNT), an efficient neuron-level safety alignment method against jailbreak attacks.


### NeurIPS 2024

**IRCAN: Mitigating Knowledge Conflicts in LLM Generation via Identifying and Reweighting Context-Aware Neurons**

**Dan Shi**, *et al.*

* Identifies context-aware neurons to mitigate hallucinations caused by conflicts between contextual and parametric knowledge.



### AAAI 2024

**CORECODE: A Common Sense Annotated Dialogue Dataset with Benchmark Tasks for Chinese Large Language Models**

**Dan Shi**, *et al.*

* Constructs a large-scale benchmark for evaluating commonsense reasoning in Chinese LLMs.



### DASFAA 2022

**Counterfactual-guided and Curiosity-driven Multi-Hop Reasoning over Knowledge Graph**

**Dan Shi**, *et al.*

* Proposes a reinforcement learning framework for knowledge graph reasoning with counterfactual guidance and intrinsic curiosity.



# 💼 Experience

**Research Intern**
**ERNIE Foundation Model Team, Baidu**
*May 2026 – Present*

Research on LLM post-training, reinforcement learning, safety alignment, and multilingual alignment.

**Visiting Researcher**
**German Research Center for Artificial Intelligence (DFKI)**
*May 2025 – May 2026*

Research on LLM post-training, safety alignment, and mechanistic interpretability.



# 🎓 Education

**Tianjin University**
Ph.D. in Computer Science and Technology
*Sep. 2022 – Present*

Advisor: Prof. Deyi Xiong



**Jilin University**

M.S. in Computer Software and Theory

*Sep. 2019 – Jun. 2022*

Advisor: Prof. Bo Yang



**Nanchang University**

B.Eng. in Computer Science and Technology

*Sep. 2015 – Jun. 2019*



# 🏆 Honors and Awards

* Honda Kenshi Frontier Language Science Scholarship (Top 1%)
* National Second Prize, China Collegiate Computing Contest
* Outstanding Master's Thesis, Jilin University
* Outstanding Undergraduate Graduate, Nanchang University
* National Encouragement Scholarship (Three Times)
