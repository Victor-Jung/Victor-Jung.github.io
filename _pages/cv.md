---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **ETH Zürich**, Zürich, Switzerland (2022 - present)
  * Ph.D. Candidate in Information Technology & Electrical Engineering
  * Advisor: Prof. Dr. Luca Benini
  * Second Advisor: Dr. Francesco Conti
  * Thesis Title (work in progress): *Efficient Foundation Model Deployment on Heterogeneous RISC-V-based SoCs with Software-Managed Caches*
* **Institut Supérieur de l'Electronique et du Numérique of Lille (ISEN Lille)**, Lille, France, (2017 - 2022)
  * M.S. in Computer Science
  * Major: Artificial Intelligence
  * Advisor: Dr. Antoine Frappé
* **Juniata College**, PA, USA (2021)
  * B.S. in Computer Science and Engineering Physics

Research Experience
======
**Integrated Systems Laboratory (IIS)**, ETH Zürich, Switzerland, (July 2022 - Present)
* **Optimization of Tiny Transformers Deployment on MCUs with Software-Managed Caches:**
  * Developed, quantized, and benchmarked tiny transformer networks for EEG seizure detection via surface EEG and ECG-based arrhythmia classification (IEEE TBioCAS).
  * Developed a new kernel library targeting transformers at the edge and a fusion tiling scheme to reduce the memory peak caused by the Self-Attention mechanism (**IEEE Transactions on Computers, First Author**).
* **Quantization and Deployment of Llama-based Tiny Language Model on Heterogeneous SoC:**
  * Developed [Deeploy](https://github.com/pulp-platform/Deeploy), an open-source DNN compiler for heterogeneous RISC-V SoCs with Software-Managed Caches. 
  * Quantized and benchmarked the execution of a tiny Llama model on [Siracusa](https://pulp-platform.org/siracusa/), a heterogeneous RISC-V SoC, using our open-source tools [Deeploy](https://github.com/pulp-platform/Deeploy) and [QuantLib](https://github.com/pulp-platform/quantlib) (IEEE CASES, IEEE TCAD).
  * Built and evaluated Transformers on an MCU-class architectural template to efficiently integrate specialized hardware accelerators with multi-core clusters (IEEE D&T). 

**ESAT-MICAS**, KU Leuven, Belgium, (May 2021 - Aug 2022)
* **Design Space Exploration of the Temporal Mapping on DNN Accelerators with the ZigZag Framework:**
  * Developed, integrated, and benchmarked SALSA, a new temporal mapping optimizer based on Simulated Annealing in the [ZigZag](https://github.com/KULeuven-MICAS/zigzag) framework (**IEEE AICAS 2023, First Author**)

Publications
======
  For an up-to-date list of my publications, please check my [Google Scholar profile](https://scholar.google.com/citations?user=TiaXdIkAAAAJ&hl=en)
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  * **Machine Learning on Microcontrollers** - Teaching Assistant
    * Developed exercises and supervised laboratory session and final projects
  
Service
======
**Reviewer**
  * International Symposium on Computer Architecture (ISCA)
  * IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)
  * ACM Transactions on Embedded Computing Systems (TECS)
  * IEEE International Conference on Artificial Intelligence Circuits and Systems (AICAS)

IEEE Graduate Student Member
