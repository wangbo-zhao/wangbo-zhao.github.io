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


I am currently a fourth(final)-year Ph.D. Student in the School of Computing, National University of Singapore, advised by Prof. <a href='https://www.comp.nus.edu.sg/~youy/'>Yang You</a>. Before that, I obtained my master's and bachelor's degrees from Northwestern Polytechnical University, China, in 2019 and 2022, respectively. During my master's study, I was fortunatedly to collaborate with Dr. <a href='https://sites.google.com/site/liunian228/'> Nian Liu</a>, under the supervision from Prof. <a href='https://scholar.google.com.hk/citations?user=xrqsoesAAAAJ&hl=zh-CN&oi=ao'> Junwei Han</a>. 



My research interest includes **Efficient AI, Dynamic Models and Model-system Co-design**. I have published more than 20 papers at the top international AI conferences and journals with <a href='https://scholar.google.com.hk/citations?user=aocj89kAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

All talents are welcome to send an email (wangbo.zhao96@gmail.com) to me if you are interested in collaborating on projects related to efficient deep learning or other promising research directions.

Beyond research, I am an amateur athlete specializing in the 400 meters (personal best: 53.40) and 400-meter hurdles (personal best: 1:01.78). I was honored to represent NUS in national-level competitions in Singapore and NWPU in provincial-level competitions in Shanxi, China.


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper accepted to TPAMI 2026. Congratulations to all the authors!
- *2025.11*: &nbsp;🎉🎉 I was invited to give a talk at the the Eastern Institute of Technology and HKUST(GZ).
- *2025.10*: &nbsp;🎉🎉 I was invited to give a talk at the Global College of Shanghai Jiao Tong University.
- *2025.10*: &nbsp;🎉🎉 Recipient of the Google PhD Fellowship 2025 in Machine Learning and ML Foundations.
- *2025.09*: &nbsp;🎉🎉 I was invited to give a talk at ShanghaiTech University.
- *2025.07*: &nbsp;🎉🎉 One paper accepted to ICCV 2025. 
- *2025.06*: &nbsp;🎉🎉 I begin my Internship at Meta in Zurich. 
- *2025.05*: &nbsp;🎉🎉 One paper accepted to ICML 2025. 
- *2025.02*: &nbsp;🎉🎉 One paper accepted to CVPR 2025. 
- *2025.01*: &nbsp;🎉🎉 One paper accepted to ICLR 2025. 
- *2024.09*: &nbsp;🎉🎉 One paper accepted to NeurIPS 2024. 
- *2024.07*: &nbsp;🎉🎉 One paper accepted to ECCV 2024. 

# 📝 Selected Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2026</div><img src='images/dydit++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DyDiT++: Dynamic Diffusion Transformers for Efficient Visual Generation](https://arxiv.org/abs/2504.06803)

[**Code**](https://github.com/alibaba-damo-academy/DyDiT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

**Wangbo Zhao\***, Yizeng Han\*, Jiasheng Tang, Kai Wang, Hao Luo, Yibing Song, Gao Huang, Fan Wang, Yang You

- DyDiT++ enhances DyDiT with integration with flow matching for broader applications, improved adaptability to complex tasks, and timestep-based dynamic LoRA for efficient training。
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/EA-ViT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EA-ViT: Efficient Adaptation for Elastic Vision Transformer](https://arxiv.org/pdf/2507.19360)

[**Code**](https://github.com/zcxcf/EA-ViT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

Chen Zhu, **Wangbo Zhao†**, Huiwen Zhang, Samir Khaki, Yuhao Zhou, Weidong Tang, Shuo Wang, Zhihang Yuan, Yuzhang Shang, Xiaojiang Peng, Kai Wang, Dawei Yang†

- EA-ViT is an efficient adaptation framework for Vision Transformers, enabling a single process to generate flexible models of varying sizes for diverse resource constraints, using a nested elastic architecture and a lightweight router optimized with Pareto-optimal configurations.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/screenshot-20250915-135005.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unsupervised Learning for Class Distribution Mismatch](https://arxiv.org/pdf/2505.06948)


Pan Du, **Wangbo Zhao†**, Xinai Lu, Nian Liu, Zhikai Li, Chaoyu Gong, Suyun Zhao†, Hong Chen, Cuiping Li, Kai Wang, Yang You

- UCDM addresses Class Distribution Mismatch (CDM) by leveraging unlabeled data to train classifiers through positive-negative pairs, synthesized using a diffusion model, and a confidence-based pseudo-labeling mechanism, achieving superior performance over semi-supervised methods without relying on labeled data.
</div>
</div>












<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/1740983914229.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Stitch in Time Saves Nine: Small VLM is a Precise Guidance for Accelerating Large VLMs](https://arxiv.org/pdf/2412.03324)

[**Code**](https://github.com/NUS-HPC-AI-Lab/SGL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

**Wangbo Zhao**, Yizeng Han, Jiasheng Tang, Zhikai Li, Yibing Song, Kai Wang, Zhangyang Wang, Yang You

- We employ the attention map aggregated from a small VLM to guide visual token pruning in a large VLM. And an early exiting mechanism is developed to fully use the small VLM's predictions, dynamically invoking the larger VLM only when necessary, yielding a superior trade-off between accuracy and computation.
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/1729770756002.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic diffusion transformer](https://arxiv.org/pdf/2410.03456)

[**Code**](https://github.com/NUS-HPC-AI-Lab/Dynamic-Diffusion-Transformer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

**Wangbo Zhao**, Yizeng Han, Jiasheng Tang, Kai Wang, Yibing Song, Gao Huang, Fan Wang, Yang You

- We propose to dynamically adjust the computation of DiT in different timesteps and spatial locations of images. The computation of DiT-XL could be saved by 50% without sacrificing generation quality. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/1729771121493.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Tuning Towards Parameter and Inference Efficiency for ViT Adaptation](https://arxiv.org/pdf/2403.11808)

[**Code**](https://github.com/NUS-HPC-AI-Lab/Dynamic-Tuning) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


**Wangbo Zhao**, Jiasheng Tang, Yizeng Han, Yibing Song, Kai Wang, Gao Huang, Fan Wang, Yang You

- We propose to adapt static ViT to dynamic ViT via parameter-efficient fine-tuning without full-parameter tuning. 
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024 (Oral)</div><img src='images/1729771541362.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mmbench: Is your multi-modal model an all-around player?](https://arxiv.org/pdf/2307.06281)

Yuan Liu, Haodong Duan, Yuanhan Zhang, Bo Li, Songyang Zhang, **Wangbo Zhao**, Yike Yuan, Jiaqi Wang, Conghui He, Ziwei Liu, Kai Chen, Dahua Lin

- We propose MMBench, a bilingual benchmark for assessing the multi-modal capabilities of VLMs.
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/1729772837643.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning](https://openaccess.thecvf.com/content/CVPR2024/papers/Luo_VSCode_General_Visual_Salient_and_Camouflaged_Object_Detection_with_2D_CVPR_2024_paper.pdf)

Ziyang Luo, Nian Liu, **Wangbo Zhao**, Xuguang Yang, Dingwen Zhang, Deng-Ping Fan, Fahad Khan, Junwei Han

- We introduce VSCode a generalist model with novel 2D prompt learning to jointly address four SOD tasks and three COD tasks
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/1729772895998.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-grained temporal prototype learning for few-shot video object segmentation](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_Multi-grained_Temporal_Prototype_Learning_for_Few-shot_Video_Object_Segmentation_ICCV_2023_paper.pdf)

Nian Liu, Kepan Nan, **Wangbo Zhao**, Yuanwei Liu, Xiwen Yao, Salman Khan, Hisham Cholakkal, Rao Muhammad Anwer, Junwei Han, Fahad Shahbaz Khan

- We propose to leverage multi-grained temporal guidance information for handling the temporal correlation nature of video data for few-shot video object segmentation
</div>
</div>










<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/1729772971568.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Modeling motion with multi-modal features for text-based video segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_Modeling_Motion_With_Multi-Modal_Features_for_Text-Based_Video_Segmentation_CVPR_2022_paper.pdf)

**Wangbo Zhao**, Kai Wang, Xiangxiang Chu, Fuzhao Xue, Xinchao Wang, Yang You

- We design a method to fuse and align appearance, motion, and linguistic features to achieve accurate text-based video segmentation.
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/screenshot-20241024-203556.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Light field saliency detection with dual local graph learning and reciprocative guidance](https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Light_Field_Saliency_Detection_With_Dual_Local_Graph_Learning_and_ICCV_2021_paper.pdf)

Nian Liu\*, **Wangbo Zhao\***, Dingwen Zhang, Junwei Han, Ling Shao

- We introduce a reciprocative guidance scheme for light field saliency detection.
</div>
</div>






<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/screenshot-20241024-203022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Weakly supervised video salient object detection](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhao_Weakly_Supervised_Video_Salient_Object_Detection_CVPR_2021_paper.pdf)

**Wangbo Zhao**, Jing Zhang, Long Li, Nick Barnes, Nian Liu, Junwei Han

- We present the first weakly supervised video salient object detection model based on relabeled fixation guided scribble annotations. 
</div>
</div>


<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->









<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2022.08 - 2026.06*, Ph.D., School of Computing, National University of Singapore, Singapore. 
- *2019.09 - 2022.04*, Master, School of Automation, Northwestern Polytechnical University, China
- *2017.07 - 2019.01*, Undergraduate, Université de technologie de Troyes, France
- *2015.09 - 2019.06*, Undergraduate, Honors College, Northwestern Polytechnical University, China

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
