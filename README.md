# Awesome DNN Watermarking [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This Github repo collects helpful resources we found pertaining to the research topic **DNN Watermarking**. 

We will take efforts to continuously update this repo on a *weekly* basis.

## Table of Contents
- [Survey](#survey)
- [Toolbox](#toolbox)
- [Dissertation and Thesis](#dissertation-and-thesis)
- [Supervised Learning (Image classification)](#Supervised-Learning-Image-classification))
- [Diffusion Model](#Diffusion-Model)
- [Generative Adversarial Network](#Generative-Adversarial-Network)

## Survey
- A survey of deep neural network watermarking techniques [[pdf]](https://arxiv.org/pdf/2103.09274)
  - Li, Yue, Hongxia Wang, and Mauro Barni. *Neurocomputing, Elsevier*, 2021
  
- A Systematic Review on Model Watermarking for Neural Networks [[link]](https://www.frontiersin.org/articles/10.3389/fdata.2021.729663/full)
  - Boenisch, Franziska. *Frontiers in big Data*, 2021
  
- Deep Intellectual Property: A Survey [[pdf]](https://arxiv.org/pdf/2304.14613)
  - Sun, Yuchen, Tianpeng Liu, Panhe Hu, Qing Liao, Shouling Ji, Nenghai Yu, Deke Guo, and Li Liu. *arXiv preprint*, 2023

- I Know What You Trained Last Summer A Survey on Stealing Machine Learning Models and Defences [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3595292)
  - Oliynyk, Daryna, Rudolf Mayer, and Andreas Rauber. *ACM Computing Surveys*, 2023

- Intellectual Property Protection for Deep Learning Models Taxonomy, Methods, Attacks, and Evaluations [[pdf]](https://arxiv.org/pdf/2011.13564)
  - Xue, Mingfu, Yushu Zhang, Jian Wang, and Weiqiang Liu. *IEEE Transactions on Artificial Intelligence*, 2021
  
## Toolbox
- [Watermark-Robustness-Toolbox](https://github.com/dnn-security/Watermark-Robustness-Toolbox)
- [ml-model-watermarking](https://github.com/SAP/ml-model-watermarking)
- [model-watermarking](https://github.com/sbaresearch/model-watermarking)


## Dissertation and Thesis

| Year | Degree  |  University  | Paper    |
|:----:|:------------:| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2022 | Ph.D. | UCSD | [Towards Holistic Secure and Trustworthy Deep Learning](https://escholarship.org/uc/item/87w4t4p2) |
| 2020 | Master | Skolkovo Institute of Science and Technology | [Developing a watermarking method for deep neural networks with no extra training](http://dde.binghamton.edu/kaziakhmedov/pdfs/edgar_master_thesis.pdf) |
  
  
## Supervised Learning (Image classification)
| Year | Venue  | Paper                                                        | Code                                                         |
|:----:|:------------:| ------------------------------------------------------------ |:------------------------------------------------------------:|
| 2024 | S&P | [MEA-Defender: A Robust Watermark against Model Extraction Attack](https://arxiv.org/pdf/2401.15239.pdf) | [:octocat:](https://github.com/lvpeizhuo/MEA-Defender) |
| 2023 | NeurIPS | [Domain Watermark Effective and Harmless Dataset Copyright Protection is Closed at Hand](https://www.researchgate.net/profile/Yiming-Li-36/publication/374440504_Domain_Watermark_Effective_and_Harmless_Dataset_Copyright_Protection_is_Closed_at_Hand/links/651e0a2ed717ef1293cc5df1/Domain-Watermark-Effective-and-Harmless-Dataset-Copyright-Protection-is-Closed-at-Hand.pdf) | [:octocat:](https://github.com/JunfengGo/Domain-Watermark) |
| 2023 | ICML | [Trapdoor Normalization with Irreversible Ownership Verification](https://proceedings.mlr.press/v202/liu23an/liu23an.pdf) |  |
| 2023 | TDSC | [RemovalNet: DNN Fingerprint Removal Attacks](https://arxiv.org/pdf/2308.12319.pdf) | [:octocat:](https://github.com/grasses/RemovalNet) |
| 2022 | ICML | [Certified Neural Network Watermarks with Randomized Smoothing](https://proceedings.mlr.press/v162/bansal22a/bansal22a.pdf) | [:octocat:](https://github.com/arpitbansal297/certified_watermarks) |
| 2022 | CVPR | [Fingerprinting Deep Neural Networks Globally via Universal Adversarial Perturbations](https://openaccess.thecvf.com/content/CVPR2022/papers/Peng_Fingerprinting_Deep_Neural_Networks_Globally_via_Universal_Adversarial_Perturbations_CVPR_2022_paper.pdf) |  |
| 2022 | S&P | [Copy, Right A Testing Framework for Copyright Protection of Deep Learning Models](https://arxiv.org/pdf/2112.05588.pdf) | [:octocat:](https://github.com/Testing4AI/DeepJudge) |
| 2022 | ICLR | [Non-Transferable Learning: A New Approach for Model Ownership Verification and Applicability Authorization](https://arxiv.org/pdf/2106.06916.pdf) | [:octocat:](https://github.com/conditionWang/NTL) |
| 2021 | ACM MM | [DAWN Dynamic Adversarial Watermarking of Neural Networks](https://arxiv.org/pdf/1906.00830) | [:octocat:](https://github.com/ssg-research/dawn-dynamic-adversarial-watermarking-of-neural-networks) |
| 2021 | ICLR | [Deep Neural Network Fingerprinting by Conferrable Adversarial Examples](https://arxiv.org/pdf/1912.00888.pdf) | [:octocat:](https://github.com/ayberkuckun/DNN-Fingerprinting) |
| 2021 | USENIX | [Entangled Watermarks as a Defense against Model Extraction](https://www.usenix.org/system/files/sec21fall-jia.pdf) | [:octocat:](https://github.com/cleverhans-lab/entangled-watermark) |
| 2018 | AsiaCCS | [Protecting Intellectual Property of Deep Neural Networks with Watermarking](https://www.researchgate.net/profile/Zhongshu-Gu/publication/325480419_Protecting_Intellectual_Property_of_Deep_Neural_Networks_with_Watermarking/links/5c1cfcd4a6fdccfc705f2cd4/Protecting-Intellectual-Property-of-Deep-Neural-Networks-with-Watermarking.pdf) | |



## Diffusion Model
| Year | Venue  | Paper                                                        | Code                                                         |
|:----:|:------------:| ------------------------------------------------------------ |:------------------------------------------------------------:|
| 2023 | NeurIPS | [Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust](https://arxiv.org/pdf/2305.20030.pdf) | [:octocat:](https://github.com/YuxinWenRick/tree-ring-watermark) |
| 2023 | arXiv | [A Recipe for Watermarking Diffusion Models](https://arxiv.org/pdf/2303.10137.pdf) | [:octocat:](https://github.com/yunqing-me/WatermarkDM) |
| 2023 | arXiv | [Watermarking Diffusion Model](https://arxiv.org/pdf/2305.12502.pdf) |  |
| 2023 | arXiv | [DiffusionShield: A Watermark for Copyright Protection against Generative Diffusion Models](https://arxiv.org/pdf/2306.04642.pdf) |  |

## Generative Adversarial Network
| Year | Venue  | Paper                                                        | Code                                                         |
|:----:|:------------:| ------------------------------------------------------------ |:------------------------------------------------------------:|
| 2021 | CVPR | [Protecting Intellectual Property of Generative Adversarial Networks from Ambiguity Attacks](https://openaccess.thecvf.com/content/CVPR2021/papers/Ong_Protecting_Intellectual_Property_of_Generative_Adversarial_Networks_From_Ambiguity_Attacks_CVPR_2021_paper.pdf) | [:octocat:](https://github.com/dingsheng-ong/ipr-gan) |
| 2022 | ICLR | [Responsible Disclosure of Generative Models Using Scalable Fingerprinting](https://openreview.net/pdf?id=sOK-zS6WHB) | [:octocat:](https://github.com/ningyu1991/ScalableGANFingerprints) |



  
  
