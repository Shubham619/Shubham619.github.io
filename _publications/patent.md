---
title: "Optimizing Transformer Based Inference Efficiency Using CMM-D"
date: 2024-12-05
venue: 'IIT Kharagpur, India'
---


_**Abstract**_ -- Recent advancements in large language models like GPT have significantly impacted AI, expanding model sizes to hundreds of billions of parameters. Meanwhile, GPU memory has increased only 5x, from 16GB to 80GB, leading to the GPU memory wall, where memory limitations severely hinder performance. System architecture improvements have allowed for larger models by integrating GPU memory across multiple units. However, training a trillion-parameter model would require 80 NVIDIA V100 GPUs, making it prohibitively expensive and resource-intensive. This paper demonstrates that integrating DDR with CMM-D mitigates issues of memory capacity and bandwidth saturation, improving IPM (Inference per minute) by up to 3x compared to using DDR alone. To fully address these limitations, adopting CXL (Compute Express Link) becomes crucial, as it decouples memory expansion from physical constraints, allowing for scalable and efficient memory growth across multiple devices, thereby optimizing overall system performance and cost-effectiveness for AI workloads.

[Check the link]([https://patentcenter.uspto.gov/applications/18218893/](https://ieeexplore.ieee.org/abstract/document/10958315))




