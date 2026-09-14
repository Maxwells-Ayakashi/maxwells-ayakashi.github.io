---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my full CV as a [PDF](/files/cv.pdf).

Education
======
* **M.Phil. in Artificial Intelligence**, The Hong Kong University of Science and Technology (Guangzhou), 2025.08 – 2027.06 (expected). Advisor: Prof. Xiaowen Chu.
* **B.Eng. in Electronic Information Science and Technology**, Hefei University of Technology, 2019.09 – 2023.06. Major ranking: 1/147.

Research & Industry Experience
======
* **Research Intern, Baidu ERNIE (Foundation Model Pre-training)**, 2026.04 – present
  * Designed and implemented a trajectory-construction module for code-agent training data, converting GitHub pull-request diffs, commit histories, CI results and review signals into multi-turn conversations in the OpenAI tool-use format (290k+ GitHub repositories, 300B+ tokens for model mid-training).
  * Built an end-to-end pipeline for constructing executable software-engineering environments, mining candidate commits, reconstructing runnable Docker environments and automatically running fail-to-pass tests (222 repositories, 4,000+ verifiable coding tasks for SFT trajectory generation and RL rollouts).
  * Adapted SWE-style code-repair environments for unit-test generation and built a code-data flywheel; GRPO fine-tuning of Qwen3.5-9B improved SWT-Bench Verified from 42.3% to 56.4% and SWE-Bench Verified from 50.2% to 54.0%.
* **Multimodal GUI Agent for Visual Grounding and Reasoning**, 2026.01 – 2026.03
  * Built an end-to-end data cleaning and augmentation pipeline (OmniParser V2 for IoU alignment; Gemini-generated multi-view instructions), reducing the error rate of the original training data from 23.3% to below 8%.
  * Introduced a zoom-in tool at inference time and applied SFT + GRPO with LoRA to Qwen2.5-VL-7B, reaching a 79.1% success rate on MMBench-GUI L2 (a 51% relative improvement over the base model).
* **Code-R1: Reinforcement-Learning Code Agent**, 2025.12 – 2026.02
  * Applied GRPO with LoRA to fine-tune Qwen2.5-7B-Instruct on LeetCode-2k, improving test-set Pass@1 from 15% to 49%; with a Firejail Python sandbox and terminal tool use, Pass@1 reached 72%.
* **Evaluation Pitfalls in Text-to-Image Diffusion Guidance**, 2024.11 – 2025.03
  * Revealed and quantified a major evaluation pitfall in text-to-image diffusion models: increasing the guidance scale can substantially improve mainstream human-preference metrics without improving actual quality. The first-author paper was accepted to **ICLR 2026 (CCF-A)**.
* **Brain Activity Visual Reconstruction (BrainRAM)**, 2023.10 – 2024.04
  * Reconstructed visual stimuli from fMRI signals with text-to-image diffusion models; retrieval-augmented generation (RAG) improved reconstruction performance by 9%. Accepted to **ACM Multimedia 2024 (CCF-A)** as an **Oral** presentation (top 3.97%).

Publications
======
* **Dian Xie**, Xiaowen Chu. Guidance Games the Judge: Spoof-Invariance Debiasing for Shortcut-Resistant Text-to-Image Reward Models. *(Submitted to AAAI 2027)*
* **Dian Xie**, Shitong Shao, Lichen Bai, Zikai Zhou, Bojun Cheng, Shuo Yang, Jun Wu, Zeke Xie. Guidance Matters: Rethinking the Evaluation Pitfall for Text-to-Image Generation. **ICLR 2026**.
* Shitong Shao, Zikai Zhou, **Dian Xie**, Yuetong Fang, Tian Ye, Lichen Bai, Bo Han, Zeke Xie. Improved and Accelerated Text-to-Image Generation with Collect, Reflect, and Refine. **IEEE T-PAMI**.
* **Dian Xie**, Peiang Zhao, Jiarui Zhang, Kangqi Wei, Xiaobao Ni, Jiong Xia. BrainRAM: Cross-Modality Retrieval-Augmented Image Reconstruction from Human Brain Activity. **ACM Multimedia 2024 (Oral)**.
* **Dian Xie**, Huajun Xing, Liangyu Chen, Shijie Hao. A Lightness-aware Loss for Low-light Image Enhancement. **Pattern Recognition Letters**.

Awards
======
* HKUST(GZ) Red Bird Scholarship — 2025
* National Scholarship (three times) — 2019 – 2022
* Outstanding Graduate of Anhui Province — 2023
* Second Prize, National College Students Smart Car Competition — 2022

Skills
======
* **Programming:** Python, C++, Java, Matlab
* **Machine Learning:** PyTorch, GRPO, SFT, LoRA, Reinforcement Learning
* **Tools:** Docker, Git, LaTeX
