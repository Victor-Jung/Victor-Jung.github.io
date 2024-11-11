---
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

Invited Talk: Energy-Efficient Generative AI on Open-Source RISC-V Heterogeneous SoCs
-----
<u>Venue:</u> *TinyML Forum: Beyond LLMs and Chatbots – the Journey to Generative AI at the Edge* <br />
<u>Location:</u> Online <br />
[Recording Link (TBA)](TODO)

<u>Abstract:</u>
Transformer-based Generative AI (GenAI) technologies, such as Large Language Models (LLMs) and Foundation Models (FMs), have been central to the recent revolution in AI technologies. The emergence of GenAI, specifically in the domain of Embodied Foundation Models (EFMs), is an interesting opportunity for the TinyML community, as embodied applications must comply with the strict power and memory constraints set by small, embedded devices.
However, the end-to-end deployment of GenAI models on TinyML platforms like heterogeneous Systems-on-Chip (SoCs) is still an open challenge. 
Heterogeneous SoCs are drastically different from one to another, featuring various memory systems, different Neural Processing Units (NPUs), and cores with distinct instruction set architectures (ISA). 
To maximize the energy efficiency of these platforms, these architectural variations need to be taken into account in the software stack; however, current deployment tools fall short of this goal.
In this talk, we introduce Deeploy, a novel Deep Neural Network (DNN) compiler that generates highly optimized bare metal C code tailored for any deployment platform, including multi-core and NPU-based platforms.
Additionally, Deeploy introduces a novel algorithm for solving the tiling and static memory allocation problems for the complex multi-level memory hierarchies present in heterogeneous SoCs, which is paramount to generating a statically allocated memory management strategy.
We demonstrate the flexibility of our tool by deploying two GenAI models on two open-source RISC-V heterogeneous SoCs featuring different NPUs, memory hierarchies, and ISAs.
