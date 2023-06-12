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

Hello, I am Yidong Wang \[i:doʊn wɑ:n\] (王一栋). My research interests lie in semi-supervised learning, transfer learning, and imbalanced learning. I have published more than 5 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=YomxTXQAAAAJ&hl=en'>google scholar citations almost <strong><span id='total_cit'>400</span></strong></a>.


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
- PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization. [\[paper\]](https://arxiv.org/abs/2306.05087).
  
  **Yidong Wang**, Zhuohao Yu, Zhengran Zeng, Linyi Yang, Cunxiang Wang, Hao Chen, Chaoya Jiang, Rui Xie, Jindong Wang, Xing Xie, Wei Ye, Shikun Zhang, Yue Zhang.

- Evaluating open question answering evaluation. [\[paper\]](https://arxiv.org/abs/2305.12421). 
  
  Cunxiang Wang, Sirui Cheng, Zhikun Xu, Bowen Ding, **Yidong Wang**, Yue Zhang.
  
- Imprecise Label Learning: A Unified Framework for Learning with Various Imprecise Label Configurations. [\[paper\]](https://arxiv.org/abs/2305.12715).
  
  Hao Chen, Ankit Shah, Jindong Wang, Ran Tao, **Yidong Wang**, Xing Xie, Masashi Sugiyama, Rita Singh, Bhiksha Raj.
  
- Out-of-Distribution Generalization in Text Classification: Past, Present, and Future. [\[paper\]](https://arxiv.org/abs/2305.14104).
  
  Linyi Yang, Yaoxiao Song, Xuan Ren, Chenyang Lyu, **Yidong Wang**, Lingqiao Liu, Jindong Wang, Jennifer Foster, Yue Zhang.
  
- PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts. [\[paper\]](https://arxiv.org/abs/2306.04528).
  
  Kaijie Zhu, Jindong Wang, Jiaheng Zhou, Zichen Wang, Hao Chen, **Yidong Wang**, Linyi Yang, Wei Ye, Neil Zhenqiang Gong, Yue Zhang, Xing Xie.

- Conv-Adapter: Exploring Parameter Efficient Transfer Learning for ConvNets. [\[paper\]](https://arxiv.org/abs/2208.07463). 
  
  Hao Chen, Ran Tao, Han Zhang, **Yidong Wang**, Wei Ye, Jindong Wang, Guosheng Hu, Marios Savvides.

- Towards Optimization and Model Selection for Domain Generalization: A Mixup-guided Solution. [\[paper\]](https://arxiv.org/abs/2209.00652). 

  Wang Lu, Jindong Wang, **Yidong Wang**, Kan Ren, Yiqiang Chen, Xing Xie. 

- An Embarrassingly Simple Baseline for Imbalanced Semi-Supervised Learning. [\[paper\]](https://arxiv.org/abs/2211.11086). 
  
  Hao Chen, Yue Fan, **Yidong Wang**, Jindong Wang, Bernt Schiele, Xing Xie, Marios Savvides, Bhiksha Raj. 

# 📝 Publications
- Exploring Vision-Language Models for Imbalanced Learning. [\[paper\]](https://arxiv.org/abs/2304.01457); [![](https://img.shields.io/github/stars/Imbalance-VLM/Imbalance-VLM?style=social&label=Code+Stars)](https://github.com/Imbalance-VLM/Imbalance-VLM)

  **Yidong Wang**, Zhuohao Yu, Jindong Wang, Qiang Heng, Hao Chen, Wei Ye, Rui Xie, Xing Xie, Shikun Zhang.
  
   International Journal of Computer Vision 2023 (**IJCV 2023**).
  
- GLUE-X: Evaluating Natural Language Understanding Models from an Out-of-distribution Generalization Perspective. [\[paper\]](https://arxiv.org/abs/2211.08073); [![](https://img.shields.io/github/stars/YangLinyi/GLUE-X?style=social&label=Code+Stars)](https://github.com/YangLinyi/GLUE-X)

  Linyi Yang, Shuibai Zhang, Libo Qin, Yafu Li, **Yidong Wang**, Hanmeng Liu, Jindong Wang, Xing Xie, Yue Zhang. 
  
  Findings of Annual Meeting of the Association for Computational Linguistics 2023 (**ACL 2023 Findings**)

- On the Robustness of ChatGPT: An Adversarial and Out-of-distribution Perspective. [\[paper\]](https://arxiv.org/abs/2302.12095); [![](https://img.shields.io/github/stars/microsoft/robustlearn?style=social&label=Code+Stars)](https://github.com/microsoft/robustlearn/tree/main/chatgpt-robust)
  
  Jindong Wang, Xixu Hu, Wenxin Hou, Hao Chen, Runkai Zheng, **Yidong Wang**, Linyi Yang, Haojun Huang, Wei Ye, Xiubo Geng, Binxin Jiao, Yue Zhang, Xing Xie.
  
  Workshop on Trustworthy and Reliable Large-Scale Machine Learning Models at ICLR 2023 (**RTML Workshop 2023**).
  
- FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning. [\[paper\]](https://arxiv.org/abs/2205.07246);  [![](https://img.shields.io/github/stars/microsoft/Semi-supervised-learning?style=social&label=Code+Stars)](https://github.com/microsoft/Semi-supervised-learning)
  
  **Yidong Wang**, Hao Chen, Qiang Heng, Wenxin Hou, Yue Fan, Zhen Wu, Jindong Wang, Marios Savvides, Takahiro Shinozaki, Bhiksha Raj, Bernt Schiele, Xing Xie.
  
  International Conference on Learning Representations 2023 (**ICLR 2023**).

- SoftMatch: Addressing the Quantity-Quality Tradeoff in Semi-supervised Learning. [\[paper\]](https://arxiv.org/abs/2301.10921); [![](https://img.shields.io/github/stars/microsoft/Semi-supervised-learning?style=social&label=Code+Stars)](https://github.com/microsoft/Semi-supervised-learning) 
  
  Hao Chen, Ran Tao, Yue Fan, **Yidong Wang**, Marios Savvides, Jindong Wang, Bhiksha Raj, Xing Xie, Bernt Schiele. 
  
  International Conference on Learning Representations 2023 (**ICLR 2023**).

- USB: A Unified Semi-supervised Learning Benchmark for Classification. [\[paper\]](https://arxiv.org/abs/2208.07204); [![](https://img.shields.io/github/stars/microsoft/Semi-supervised-learning?style=social&label=Code+Stars)](https://github.com/microsoft/Semi-supervised-learning) 
  
  **Yidong Wang**, Hao Chen, Yue Fan, Wang Sun, Ran Tao, Wenxin Hou, Renjie Wang, Linyi Yang, Zhi Zhou, Lan-Zhe Guo, Heli Qi, Zhen Wu, Yu-Feng Li, Satoshi Nakamura, Wei Ye, Marios Savvides, Bhiksha Raj, Takahiro Shinozaki, Bernt Schiele, Jindong Wang, Xing Xie, Yue Zhang. 
  
  Advances in Neural Information Processing Systems 2022 (**NeurIPS 2022**).

- Margin Calibration for Long-Tailed Visual Recognition. [\[paper\]](https://arxiv.org/abs/2112.07225); [![](https://img.shields.io/github/stars/microsoft/robustlearn?style=social&label=Code+Stars)](https://github.com/microsoft/robustlearn/tree/main/marc)
  
  **Yidong Wang**, Bowen Zhang, Wenxin Hou, Zhen Wu, Jindong Wang, Takahiro Shinozaki. 
  
  Asian Conference on Machine Learning 2022 (**ACML 2022**).

- Exploiting Unlabeled Data for Target-Oriented Opinion Words Extraction. [\[paper\]](https://arxiv.org/abs/2208.08280); [![](https://img.shields.io/github/stars/TOWESSL/TOWESSL?style=social&label=Code+Stars)](https://github.com/TOWESSL/TOWESSL) 
  
  **Yidong Wang**, Hao Wu, Ao Liu, Wenxin Hou, Zhen Wu, Jindong Wang, Takahiro Shinozaki, Manabu Okumura, Yue Zhang. 
  
  International Conference on Computational Linguistics 2022 (**COLING 2022**).

- Exploiting Adapters for Cross-lingual Low-resource Speech Recognition. [\[paper\]](https://arxiv.org/abs/2105.11905); [![](https://img.shields.io/github/stars/jindongwang/transferlearning?style=social&label=Code+Stars)](https://github.com/jindongwang/transferlearning/tree/master/code/ASR/Adapter) 
  
  Wenxin Hou, Han Zhu, **Yidong Wang**, Jindong Wang, Tao Qin, Renjun Xu, Takahiro Shinozaki. 
  
  IEEE/ACM Transactions on Audio, Speech and Language Processing 2022 (**TASLP 2022**).

- Flexmatch: Boosting Semi-supervised Learning with Curriculum Pseudo Labeling. [\[paper\]](https://arxiv.org/abs/2110.08263); [![](https://img.shields.io/github/stars/TorchSSL/TorchSSL?style=social&label=Code+Stars)](https://github.com/TorchSSL/TorchSSL) 
  
  Bowen Zhang, **Yidong Wang (co-first author)**, Wenxin Hou, Hao Wu, Jindong Wang, Manabu Okumura, Takahiro Shinozaki. 
  
  Advances in Neural Information Processing Systems 2021 (**NeurIPS 2021**).

- Meta-Adapter: Efficient Cross-Lingual Adaptation With Meta-Learning. [\[paper\]](https://ieeexplore.ieee.org/document/9414959); [![](https://img.shields.io/github/stars/jindongwang/transferlearning?style=social&label=Code+Stars)](https://github.com/jindongwang/transferlearning/tree/master/code/ASR/Adapter) 
  
  Wenxin Hou, **Yidong Wang**, Shengzhou Gao, Takahiro Shinozaki. 
  
  IEEE International Conference on Acoustics, Speech, and Signal Processing 2021 (**ICASSP 2021**).

# 💻 Selected Projects
- PandaLM [![](https://img.shields.io/github/stars/WeOpenML/PandaLM?style=social&label=Code+Stars)](https://github.com/WeOpenML/PandaLM) refers to ReProducible and Automated Language Model Assessment. PandaLM aims to provide reproducible and automated comparisons between different large language models (LLMs). By giving PandaLM the same context, it can compare the responses of different LLMs and provide a reason for the decision, along with a reference answer. I am the main contributor to this repo and now leading the PandaLM team.
- USB [![](https://img.shields.io/github/stars/microsoft/Semi-supervised-learning?style=social&label=Code+Stars)](https://github.com/microsoft/Semi-supervised-learning) is a Pytorch-based Python package for Semi-Supervised Learning (SSL). It is easy-to-use/extend, affordable, and comprehensive for developing and evaluating SSL algorithms. USB provides the implementation of 14 SSL algorithms based on Consistency Regularization, and 15 tasks for evaluation from CV, NLP, and Audio domain. I am the main contributor to this repo and now leading the USB team.
- TorchSSL [![](https://img.shields.io/github/stars/TorchSSL/TorchSSL?style=social&label=Code+Stars)](https://github.com/TorchSSL/TorchSSL) is an all-in-one toolkit based on PyTorch for semi-supervised learning (SSL). Currently, we implemented 9 popular SSL algorithms to enable fair comparison and boost the development of SSL algorithms. I am the main contributor to this repo and now leading the TorchSSL team.
- Microsoft NeuralSpeech [![](https://img.shields.io/github/stars/microsoft/NeuralSpeech?style=social&label=Code+Stars)](https://github.com/microsoft/NeuralSpeech) is a research project in Microsoft Research Asia focusing on neural network based speech processing, including automatic speech recognition (ASR), text to speech (TTS), etc. The code of Exploiting Adapters for Cross-lingual Low-resource Speech Recognition (TASLP 2022) has been moved to this repo.

# 🎖 Honors and Awards
- Outstanding Student Award, Tokyo Institue of Technology, 2022.
- Stars of Tomorrow, Microsoft Research Asia, 2021&2022.
- Jasso Scholarship, Tokyo Institue of Technology, 2020.
- Excellence in Nanjing University Training Program of Innovation for Undergraduates, 2019.
- Honorable Mention of Interdisciplinary Contest in Modeling, 2018.
- Renmin Scholarship, Nanjing University, 2017&2018.

# 📄 Academic Services
- Reviewer for Conferences: NeurIPS 2022, CVPR 2023, ICML 2023, ICCV 2023, NeurIPS 2023.
- Reviewer for Journals: ACM TIST, JCST.
