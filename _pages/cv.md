---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
You can also find my CV here: [Jinghao Zheng's Curriculum Vitae]({{ site.baseurl }}/files/JHZheng_CV.pdf).

# 📖 Education
*2025.08 - now*, École Polytechnique Fédérale de Lausanne (EPFL), Lausanne, Switzerland
  M.S. in Computer Science. 

*2021.09 - 2025.06*, Shanghai Jiao Tong University (SJTU), Shanghai, China              
  B.E. in Automation(Computer Science and Engineering).
* Major GPA:3.82/4.3
* Centesimal grade average:89.23/100
* Core Courses: Calculus ΙΙ (98), Probability and Statistics (99), Linear Algebra (92), Discrete Mathematics (93),
Data Structure (90), Pattern Recognition (96), Principles of Automatic Control (94), Robotics (93)

# 📝 Publication
- [Do We Need All the Synthetic Data? Targeted Image Augmentation via Diffusion Models](https://iclr.cc/virtual/2026/poster/10009127), Dang Nguyen†, Jiping Li†, **Jinghao Zheng†**, and Baharan Mirzasoleiman. **ICLR 2026** (Accepted as a poster)

- [Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://proceedings.neurips.cc/paper_files/paper/2024/file/2e622ac74f66df03b686a12e2e0e4424-Paper-Conference.pdf), Z. Huang, X. Cheng, **J. Zheng**, H. Wang, Z. He, T. Li, and X. Huang. **NeurIPS 2024** (Accepted as a spotlight)

# 🔬 Research Experience
* Feb. 2026 -- Present: Research Assistant
  * **Project**: Prompt-Faithful Video Generation with Dynamic Sink Adjustment
    * Investigated sink-based forcing methods in video generation and found that sink mechanisms used to reduce drift can degrade prompt following for salient foreground objects.
    * Designed and implemented a dynamic sink adjustment method that predicts the spatial locations of key foreground objects from prompts and adapts sink placement through perturbations to the corresponding spatial RoPE vectors.
    * Improved prompt following by better aligning foreground object generation and spatial layout with textual prompts.
  * Advisor: **Alexandre Alahi,** Associate Professor, School of Engineering, EPFL
    
* Nov. 2024 -- June. 2025: Research Assistant
  * **Project**: Efficient Continual Learning for LLMs: A Parameter Sorting Approach to Mitigate Catastrophic Forgetting
    * Proposed a dynamic block-wise parameter sorting method that identifies and protects task-critical parameters during fine-tuning, effectively mitigating catastrophic forgetting in a continual learning setting for LLMs.
    * Dynamically updated a subset of parameters to preserve performance on previous tasks while improving training efficiency compared to existing methods.
  * Advisor: **Xiaolin Huang,** Professor, Vice Dean, Department of Automation, SJTU
    
* **July 2024 -- May 2025**: Research Assistant
  * **Project**: Targeted Synthetic Image Augmentation via Diffusion Models
    * Contributed to building a selective synthetic data augmentation framework based on GLIDE text-to-image model, which identifies "slow-learnable" examples early in training and augments only this targeted subset.
    * Designed a faithful image generation pipeline that initializes the diffusion process from real samples to produce synthetic images that preserve semantic features while diversifying noise patterns.
    * Conducted experiments across multiple architectures (ResNet, ViT, ConvNeXt, Swin) and datasets (CIFAR-10/100, TinyImageNet); augmenting only 30%--40% of training data achieves up to 2.8% accuracy gain, while reducing training overhead by 70% vs. 2× full-dataset diffusion augmentation.
  * **Advisor**: Baharan Mirzasoleiman, Assistant Professor, Computer Science Department, UCLA
 
* **Mar 2024 -- June 2024**: Research Assistant
  * **Project**: Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement
    * Proposed replacing Euclidean distance with KL divergence on the remaining set as a retention constraint, better respecting the geometry of the output probability space and improving retained model performance during unlearning.
    * Conducted experiments and hyperparameter tuning on image classification and generation tasks, with systematic comparison against multiple unlearning baselines.
    * Achieved an average 1.8% disparity reduction on CIFAR-10 random-subset forgetting and an average FID improvement of 80 on ImageNet class-forgetting.
  * **Advisor**: [Xiaolin Huang](http://www.pami.sjtu.edu.cn/xiaolin), Professor & Vice Dean, Department of Automation, SJTU
    
* Feb. 2024 -- June 2024: Sole Researcher
  * **Project**: Polyp Detection and Segmentation Augmented by Diffusion Model
    * Implemented yolov10 and ResUnet++ as baselines to finish object detection and segmentation on medical images.
    * Proposed using Diffusion-based generative models to generate synthetic data for data augmentation, which improved the mAP0.5@0.95 in the object detection by 1% and the IoU in the segmentation by 5%.
  * Advisor: **Manhua Liu,** Professor, Artificial Intelligence Research Institute, SJTU

* Oct. 2023 – Mar. 2024: Group Member
  * **Project**: Design of distributed collaborative positioning system
    * Developed motor control code on the STM32 board to precisely manage the yaw and pitch of the camera platform, ensuring accurate angle adjustments.
    * Contributed to the mechanical design of the camera head and designed circuit boards to interface the STM32 board with multiple cameras.
  * Advisor: **Jianping He,** Associate Professor, Department of Automation, SJTU

* Mar. 2023 – Feb. 2024: Project Leader
  * **Project**: Implementation and comparison of gas tracing algorithms for dual robots in confined space
    * Proposed a bionics-based gas tracing algorithm for dual robots in a confined space and conducted experiments to simulate and validate our algorithm, which improved the success rate by 1.5% and the search efficiency by 9%. 
    * Developed control code for Raspberry Pi to ensure precise movement and implemented ROS2 communication protocols for real-time data exchange between the robots and the main computer.
  * Advisor: **Liufang Wang,** Senior Engineer, Student Innovation Center, SJTU
  
# 🎖 Honors & Awards
* Outstanding Graduate of SJTU, 2025
* 3rd Prize of TI Cup National Undergraduate Electronic Design Contest Shanghai area, 2023
* 3rd Prize of Academic Scholarship of Shanghai Jiao Tong University, 2022 & 2023 & 2024
* 2nd Prize of Chinese Physics Olympiad (Zhejiang Area), 2019

# 🛠️ Skills
* Programming Languages: Python, C/C++, ROS2, Matlab, Markdown, LaTex
* Languages: Chinese (Native), English (Proficient)
* Leadership Experience: Head of Sports Department, School of Electronic Information and Electrical Engineering (SEIEE) Student Union, Shanghai Jiao Tong University
  
