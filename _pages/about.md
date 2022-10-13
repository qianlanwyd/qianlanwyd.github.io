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

My research interests lie in semi-supervised learning, transfer learning, and imbalanced learning.

My research interest includes neural machine translation and computer vision. I have published more than 5 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=YomxTXQAAAAJ&hl=en'>google scholar citations <strong><span id='total_cit'>100+</span></strong></a>.


# 🔥 News
- *2022.10*: &nbsp;🎉🎉 I finished my internship at MSRA. 
- *2022.09*: &nbsp;🎉🎉 Our paper USB: A Unified Semi-supervised Learning Benchmark for Classification has been accepted by NeurIPS 2022 Datasets and Benchmarks Track. 

# 📖 Educations
- *2023.09 - 2027.06*, doctoral student in the National Engineering Research Center for Software Engineering of Peking University, advised by Prof. Wei Ye and Prof. Shikun Zhang.
- *2020.09 - 2022.10*, master student in the Department of Information and Communications Engineering of Tokyo Institute of Technology, advised by Prof. Takahiro Shinozaki.
- *2015.09 - 2019.06*, undergraduate student in the Department of Computer Science and Technology of Nanjing University, advised by Prof. Xinyu Dai.

# 💼 Internships
- *2022.05 - 2022.10*, Microsoft Research Asia, advised by Dr. Jindong Wang.
- *2022.02 - 2022.05*, Westlake University, advised by Prof. Yue Zhang.
- *2021.11 - 2022.02*, Microsoft Research Asia, advised by Dr. Jindong Wang.

# 📝 Preprints
- FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning. [\[paper\]](https://arxiv.org/abs/2205.07246). **Yidong Wang**, Hao Chen, Qiang Heng, Wenxin Hou, Yue Fan, Zhen Wu, Jindong Wang, Marios Savvides, Takahiro Shinozaki, Bhiksha Raj, Bernt Schiele, Xing Xie.
- Conv-Adapter: Exploring Parameter Efficient Transfer Learning for ConvNets. [\[paper\]](https://arxiv.org/abs/2208.07463). Hao Chen, Ran Tao, Han Zhang, **Yidong Wang**, Wei Ye, Jindong Wang, Guosheng Hu, Marios Savvides.

# 📝 Publications 
- USB: A Unified Semi-supervised Learning Benchmark for Classification. [\[paper\]](https://arxiv.org/abs/2208.07204); [\[code\]](https://github.com/microsoft/Semi-supervised-learning). **Yidong Wang**, Hao Chen, Yue Fan, Wang Sun, Ran Tao, Wenxin Hou, Renjie Wang, Linyi Yang, Zhi Zhou, Lan-Zhe Guo, Heli Qi, Zhen Wu, Yu-Feng Li, Satoshi Nakamura, Wei Ye, Marios Savvides, Bhiksha Raj, Takahiro Shinozaki, Bernt Schiele, Jindong Wang, Xing Xie, Yue Zhang. Advances in Neural Information Processing Systems 2022 (**NeurIPS 2022**).
- Margin Calibration for Long-Tailed Visual Recognition. [\[paper\]](https://arxiv.org/abs/2112.07225). **Yidong Wang**, Bowen Zhang, Wenxin Hou, Zhen Wu, Jindong Wang, Takahiro Shinozaki. Asian Conference on Machine Learning 2022 (**ACML 2022**).
- Exploiting Unlabeled Data for Target-Oriented Opinion Words Extraction. [\[paper\]](https://arxiv.org/abs/2208.08280); [\[code\]](https://github.com/TOWESSL/TOWESSL). **Yidong Wang**, Hao Wu, Ao Liu, Wenxin Hou, Zhen Wu, Jindong Wang, Takahiro Shinozaki, Manabu Okumura, Yue Zhang. International Conference on Computational Linguistics 2022 (**COLING 2022**).
- Exploiting Adapters for Cross-lingual Low-resource Speech Recognition. [\[paper\]](https://arxiv.org/abs/2105.11905); [\[code\]](https://github.com/jindongwang/transferlearning/tree/master/code/ASR/Adapter). Wenxin Hou, Han Zhu, **Yidong Wang**, Jindong Wang, Tao Qin, Renjun Xu, Takahiro Shinozaki. IEEE/ACM Transactions on Audio, Speech and Language Processing 2022 (**TASLP 2022**).
- Flexmatch: Boosting Semi-supervised Learning with Curriculum Pseudo Labeling. [\[paper\]](https://arxiv.org/abs/2110.08263); [\[code\]](https://github.com/TorchSSL/TorchSSL). Bowen Zhang, **Yidong Wang (co-first author)**, Wenxin Hou, Hao Wu, Jindong Wang, Manabu Okumura, Takahiro Shinozaki. Advances in Neural Information Processing Systems 2021 (**NeurIPS 2021**).
- Meta-Adapter: Efficient Cross-Lingual Adaptation With Meta-Learning. [\[paper\]](https://ieeexplore.ieee.org/document/9414959); [\[code\]](https://github.com/jindongwang/transferlearning/tree/master/code/ASR/Adapter). Wenxin Hou, **Yidong Wang**, Shengzhou Gao, Takahiro Shinozaki. IEEE International Conference on Acoustics, Speech, and Signal Processing 2021 (**ICASSP 2021**).

# 💻 Projects
- [USB](https://github.com/microsoft/Semi-supervised-learning) (300+ stars and 20+ forks!) is a Pytorch-based Python package for Semi-Supervised Learning (SSL). It is easy-to-use/extend, affordable, and comprehensive for developing and evaluating SSL algorithms. USB provides the implementation of 14 SSL algorithms based on Consistency Regularization, and 15 tasks for evaluation from CV, NLP, and Audio domain. I am the main contributor to this repo and now leading the USB team.
- [TorchSSL](https://github.com/TorchSSL/TorchSSL) (950+ stars and 150+ forks!) is an all-in-one toolkit based on PyTorch for semi-supervised learning (SSL). Currently, we implemented 9 popular SSL algorithms to enable fair comparison and boost the development of SSL algorithms. I am the main contributor to this repo and now leading the TorchSSL team.
- [Microsoft NeuralSpeech](https://github.com/microsoft/NeuralSpeech) (600+ stars and 75+ forks!) is a research project in Microsoft Research Asia focusing on neural network based speech processing, including automatic speech recognition (ASR), text to speech (TTS), etc. The code of Exploiting Adapters for Cross-lingual Low-resource Speech Recognition (TASLP 2022) has been moved to this repo.

# 🎖 Honors and Awards
- Outstanding Student Award, Tokyo Institue of Technology, 2022.
- Stars of Tomorrow, Microsoft Research Asia, 2021&2022.
- Jasso Scholarship, Tokyo Institue of Technology, 2020.
- Excellence in Nanjing University Training Program of Innovation for Undergraduates, 2019.
- Honorable Mention of Interdisciplinary Contest in Modeling, 2018.
- People's Scholarship, Nanjing University, 2017&2018.

# 📄 Academic Services
- Reviewer for Conferences: CVPR 2022, ICML 2022, NeurIPS 2022.
