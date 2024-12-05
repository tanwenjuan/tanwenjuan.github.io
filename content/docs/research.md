---
title: "Research"
date: 2024-11-25
type: "research"
lead: "This is my research page"
description: "This article helps you get started with the Mainroad theme, including installation and minimal configuration."
tags:
  - "Installation"
authorbox: false
sidebar: false
pager: false
weight: 2
menu: main
---

## AI for Drug Discovery

{{< project image="/img/AiProtacs.png" title="AiProtacs: a PROTAC-targeted-degradation discriminator augmented with graph contrastive learning" 
authors="<em>Xiang-Zhe Kong, <u>Wen-Juan Tan</u>, Ren-Hong Sun, Li Zhang, Fang-Yuan Ren, Chao-Wei Ren, Xiao-Bao Yang, Wen-Bing Huang*, Yang Liu*</em><br> <em>Submitted to <b>Nature Communications</b></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/AiProtacs.pdf' style='color: #007bff;'>Paper</a>"
description="I developed AiPROTACs, a deep learning model that leverages graph-based neural networks and a hybrid learning framework to predict the degradation efficacy of PROTACs (Proteolysis Targeting Chimeras).The model achieved an accuracy of 85.02% on both the PROTAC-DB2.0 dataset and external datasets.To validate the model's predictive capabilities, I applied it to identify potential androgen receptor-targeting PROTACs, which were synthesized and experimentally tested.Of the 16 synthesized candidates, 75% showed predicted degradation efficacy, with one lead candidate exhibiting promising in vitro degradation activity.The AiPROTACs model significantly streamlined the PROTAC discovery process, improving degradation efficiency and specificity, which in turn accelerates drug development timelines." separator="true" >}}
 &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


---


{{< project image="/img/EPT_drug_screen.png" title="Equivariant Pretrained Transformer: AI Accelerated Drug Screening for COVID-19" authors="<em>Rui Jiao, Xiang-Zhe Kong, Zi-Yang Yu, <u>Wen-Juan Tan</u>, Li Zhang, Fang-Yuan Ren, Wen-Bing Huang*, Yang Liu*</em><br> <em>Submitted to <b>Nature Machine Intelligence</b></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/EPT.pdf' style='color: #007bff;'>Paper</a>"description="I used EPT (Equivariant Pretrained Transformer), which integrates E(3) equivariance into transformers, for AI-driven drug screening in COVID-19 research. By leveraging its enhanced representation, I applied it to small molecule and protein modeling, improving 3D structure accuracy and cross-domain learning.Experimental results showed that EPT outperformed existing methods in ligand binding affinity prediction and delivered strong performance in molecular and protein property tasks.The model showed promising results in anti-COVID drug screening." >}}


---

{{< project image="/img/DHD2iff.png" title="DHD2iff: A Docking-Guided Hierarchical Dual Diffusion Model for Target-aware Drug Design" 
authors="<em><u>Wenjuan Tan</u>, Ximing Wen, Ziyang Yu, Wenbing Huang*, Yang Liu*</em><br> <em>Submitted to <b>ICML 2025</b></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/DHD2iff.pdf' style='color: #007bff;'>Paper</a> &nbsp;<a href='https://github.com/tanwenjuan/DHD2iff' style='color: #28a745;'>Code</a>" description="I contributed to the development of DHD2iff, a dual diffusion model designed for generating small molecules targeting protein pockets. The model builds on diffusion-based approaches and incorporates a hierarchical graph structure and attention mechanism to refine molecular interactions, enhancing both stability and conformational accuracy. Experiments on the CrossDocked2020 dataset demonstrated that DHD2iff outperformed existing models, generating high-affinity and stable molecules." separator="true" >}} 



---
{{< project image="/img/Unilinker.jpg" title="Unilinker: A Unified Model for Linker Design in Targeted Drug Development" authors="Li Zhang, <em><u>Wenjuan Tan</u>, Ziyang Yu, Wenbing Huang*, Yang Liu*</em><br> <em><b>In Process</b></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/Unilinker' style='color: #28a745;'>Code</a>"description="In targeted drug design, the linker plays a pivotal role, often directly influencing the drug's efficacy. Targeted drugs encompass a variety of types, including polymorphs and antibody-drug conjugates, among others. To standardize the design process, we propose the Unilinker model, a unified framework for linker design applicable across different categories of targeted drugs. We have developed a Variational Autoencoder (VAE) model, incorporating diffusion within the latent space, to generate a comprehensive linker design approach. Furthermore, during the design process, we leverage a linker template library to guide the linker generation, with the infusion of template knowledge significantly enhancing the validity of the generated linkers. This is particularly beneficial in the design of complex linkers, ensuring more effective and optimized solutions." separator="true" >}}


_____________________________________________________________________________________________________________

## Large Language Models(LLMs)


{{< project image="/img/GAProtoNet.png" title="GAProtoNet: Enhancing LLM Interpretability with Graph Attention-Based Prototypical Model"authors="<em>Ximing Wen, <u>Wenjuan Tan</u>, Rosina O. Weber*</em><br> <em>Accepted by <b>COLLING 2025</b></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/GAProtoNet.pdf' style='color: #007bff;'>Paper</a> &nbsp;<a href='https://github.com/tanwenjuan/GAProtoNet/tree/main' style='color: #28a745;'>Code</a>" description="I proposed a novel white-box multi-head graph attention prototypical network (GAProtoNet), aimed at improving the interpretability of LLMs. GAProtoNet combines prototypical learning with multi-head graph attention mechanisms to better capture deep features of text data and provide visual explanations for classification decisions. Extensive experiments on multiple public benchmark datasets, using different language models demonstrated GAProtoNet’s superiority in both classification performance and interpretability." separator="true" >}}

---
{{< project image="/img/RLHF.png" title="Prototype-Enhanced Reinforcement Learning for LLM Fine-Tuning with Sparse Human Feedback" authors="<em>Ximing Wen, <u>Wenjuan Tan</u>, Rosina O. Weber*</em><br> <em><b>In Process </b></em>" description="The answers generated by LLMs are sometimes useful, but at other times they are not. To train a better model that provides useful answers to users, fine-tuning based on user feedback is necessary. However, due to the limited amount of labeled data, fine-tuning LLMs using Reinforcement Learning from Human Feedback (RLHF) sometimes fails to achieve effective results. We propose a prototype reward model that leverages the prototype's suitability for few-shot learning, and constructs a reward model based on human feedback. The reward score generated from the output is then used to train the reinforcement learning model." separator="true" >}}


---

## AI + Healthcare


{{< project image="/img/TIS.png" title="Diaphragm motion and shape as a function of the scoliotic spinal curve in thoracic insufficiency syndrome (TIS)"authors="<em><u>Wenjuan Tan</u>, Jayaram K Udupa*, Yubing Tong, Caiyun Wu, Mahdie Hosseini, Mostafa Al-Noury, Shiva Shaghaghi, Joseph M McDonough, Samantha Gogel, David M Biko, Oscar H Mayer, Jason B Anari, Drew A Torigian, Patrick J Cahill</em><br> <em>Published in <b>SPIE. Medical Imaging 2024: Clinical and Biomedical Imaging</b></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/SPIE.pdf' style='color: #007bff;'>Paper</a>" description="I worked on a project focused on analyzing thoracic movement and respiratory patterns in patients with Thoracic Insufficiency Syndrome (TIS) using dynamic MRI sequences. I applied optical flow techniques to estimate feature point motion, extracting key information about thoracic movement, including dynamic trajectory and speed during different respiratory phases. Additionally, I segmented the diaphragm and other respiratory muscles to analyze their movement, speed, and shape trajectories, creating 3D rendered animations to visualize their motion throughout the breathing process. Through statistical analysis, I identified unique respiratory characteristics among different TIS patient types, which contributed valuable insights for clinical diagnosis and treatment." separator="true" >}}

---

## Robotics


{{< project image="/img/multi-robotics.png" title="Decentralized Formation Control for Multi-Robot Systems in Dynamic Environments" authors="<em><u>Wenjuan Tan (Group Leader)</u>, Zeyang Li, Zikang Shi, Ruibin Liang</em><br> <em>Course Project: <b>ME452 Multi-robot system and control </b>&nbsp;&nbsp;&nbsp; Rating:A+</em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/Multi-robotics.pdf' style='color: #007bff;'>Paper</a> &nbsp;<a href='https://github.com/tanwenjuan/multirobots' style='color: #28a745;'>Code</a> &nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/Multi-robotics.mp4' style='color: #dc3545;'>Video</a>" description="I developed a distributed control system for mobile robot formation in multi-robot collaborative environments. The project addressed key challenges such as obstacle avoidance, dynamic formation selection, and formation tracking. I proposed a decentralized obstacle avoidance strategy that allowed robots to autonomously adjust their formation based on local information. Additionally, I introduced a dynamic formation selection algorithm to estimate global errors from local ones, enabling robots to reconfigure formations during obstacle avoidance while maintaining coordination. I also designed a consensus-based distributed control law to ensure stable tracking of time-varying formations. Through simulations and real-world experiments, we validated the algorithms’ robustness, scalability, and adaptability in dynamic environments. This work demonstrated the potential of decentralized control to enhance the performance and flexibility of mobile robot systems in complex real-world scenarios." separator="true" >}}


---



{{< project_v video="/img/self_driving.mp4" title="Multi-Agent Trajectory Planning and Decision Algorithms for Intelligent Connected Vehicles in Smart Cities" authors="<em><u>Wenjuan Tan (Bachelor's Thesis)</u></em> &nbsp;&nbsp;&nbsp;<a href='https://github.com/tanwenjuan/website_materials/blob/main/self_driving.mp4' style='color: #dc3545;'>Video</a>" description="I developed a distributed control system for mobile robot formation in multi-robot collaborative environments. The project addressed key challenges such as obstacle avoidance, dynamic formation selection, and formation tracking. I proposed a decentralized obstacle avoidance strategy that allowed robots to autonomously adjust their formation based on local information. Additionally, I introduced a dynamic formation selection algorithm to estimate global errors from local ones, enabling robots to reconfigure formations during obstacle avoidance while maintaining coordination. I also designed a consensus-based distributed control law to ensure stable tracking of time-varying formations. Through simulations and real-world experiments, we validated the algorithms’ robustness, scalability, and adaptability in dynamic environments. This work demonstrated the potential of decentralized control to enhance the performance and flexibility of mobile robot systems in complex real-world scenarios." separator="true" >}}


---

<!--more-->