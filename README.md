# Awesome-Dual-System-VLA

To address the challenges in vision-language-action (VLA) models, such as the difficulty of achieving efficient real-time performance, the high cost of pre-training, and the complexity of end-to-end fine-tuning on embodied data due to domain shift and catastrophic forgetting, Dual-System VLA models were introduced. 

The development and architectural details of Dual-System VLA models are discussed in the [paper](https://arxiv.org/abs/2505.03912).

This repository will be continuously updated, and we warmly welcome contributions from the community. If you have papers, projects, or resources that are not yet included, please feel free to submit them via a pull request or open an issue for discussion.


## Current Results

### [CALVIN](https://arxiv.org/abs/2112.03227) ABC→D

| Method    | 1 | 2 | 3 | 4 | 5 | Avg. Len. |
|-----------|:------:|:------:|:------:|:------:|:------:|:-------:|
| _Single-System_ |
| [OpenVLA](https://arxiv.org/abs/2406.09246)   | 91.3 | 77.8 | 62.0 | 52.1 | 43.5 | 3.27  |
| [UniVLA](https://www.arxiv.org/abs/2505.06111)    | 95.5 | 85.8 | 75.4 | 66.9 | 56.5 | 3.80  |
| [Seer](https://arxiv.org/abs/2412.15109)      | 94.4 | 87.2 | 79.9 | 72.2 | 64.3 | 3.98  |
| _Dual-System_ |
| [LCB](https://arxiv.org/abs/2405.04798)           | 73.6 | 50.2 | 28.5 | 16.0 | 9.9  | 1.78   |
| [RationalVLA](https://arxiv.org/abs/2506.10826)           | 74.3 | 58.3 | 42.3 | 30.0 | 20.7  | 2.26   |
| [Robodual](https://arxiv.org/abs/2410.08001)      | 94.4 | 82.7 | 72.1 | 62.4 | 54.4 | 3.66   |
| [OpenHelix](https://arxiv.org/abs/2505.03912)  | 97.1 | 91.4 | 82.8 | 72.6 | 64.1 | **4.08** |
    
### [LIBERO](https://arxiv.org/abs/2306.03310)

| Method         |LIBERO-Spatial | LIBERO-Object | LIBERO-Goal | LIBERO-Long | Avg. |
|----------------|:--------------:|:--------------:|:------------:|:------------:|:----:|
| _Single-System_ |
| [OpenVLA](https://arxiv.org/abs/2406.09246)        |     84.7       |     88.4       |     79.2     |     53.7     | 76.5 |
| [π<sub>0</sub>](https://arxiv.org/abs/2410.24164)             |     96.8       |     98.8       |     95.8     |     85.2     | 94.2 |
| [OpenVLA-OFT](https://arxiv.org/abs/2502.19645)    |     97.6       |     98.4       |     97.9     |     94.5     | 97.1 |
| [GR00T N1](https://arxiv.org/abs/2503.14734)       |     94.4       |     97.6       |     90.6     |     93.9     | 93.9 |
| [UniVLA](https://www.arxiv.org/abs/2505.06111)         |     96.5       |     96.8       |     95.6     |     92.0     | 95.2 |
| [Seer](https://arxiv.org/abs/2412.15109)           |       -        |       -        |      -       |     87.7     |  -   |
| _Dual-System_ |
| [DexVLA](https://arxiv.org/abs/2502.05855)         |     97.2       |     99.1       |     95.6     |      -       |  -   |
| [Hume](https://arxiv.org/abs/2505.21432)           |     98.6       |     99.8       |     99.4     |     98.6     | **98.6** |



## ✅ Dual-System VLA

### Robot Manipulation
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Galaxea Open-World Dataset and G0 Dual-System VLA Model**](https://arxiv.org/abs/2509.00576) | arXiv | 2025-08-30 | ![Star](https://img.shields.io/github/stars/OpenGalaxea/G0?style=social&label=Star) [Github](https://github.com/OpenGalaxea/G0) | |
| [**TriVLA: A Unified Triple-System-Based Unified Vision-Language-Action Model for General Robot Control**](https://arxiv.org/abs/2507.01424) | arXiv | 2025-07-01| [Project](https://zhenyangliu.github.io/TriVLA/) | |
| [**RationalVLA: A Rational Vision-Language-Action Model with Dual System**](https://arxiv.org/abs/2506.10826) | arXiv | 2025-06-12 | [Project](https://irpn-eai.github.io/rational_vla) | |
| [**Fast-in-Slow: A Dual-System Foundation Model Unifying Fast Manipulation within Slow Reasoning**](https://arxiv.org/abs/2506.01953) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/CHEN-H01/Fast-in-Slow?style=social&label=Star) [Github](https://github.com/CHEN-H01/Fast-in-Slow) |  |
| [**Hume: Introducing System-2 Thinking in Visual-Language-Action Model**](https://arxiv.org/abs/2505.21432) | arXiv | 2025-05-27 | ![Star](https://img.shields.io/github/stars/hume-vla/hume?style=social&label=Star) [Github](https://github.com/hume-vla/hume) | |
| [**OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation**](https://arxiv.org/abs/2505.03912) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/OpenHelix) |  |
| [**DexVLA: Vision-Language Model with Plug-In Diffusion Expert for General Robot Control**](https://arxiv.org/abs/2502.05855) | arXiv | 2025-02-09 | ![Star](https://img.shields.io/github/stars/juruobenruo/DexVLA?style=social&label=Star) [Github](https://github.com/juruobenruo/DexVLA) |  |
| [RoboDual: **Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | arXiv | 2024-10-10 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/RoboDual?style=social&label=Star) [Github](https://github.com/OpenDriveLab/RoboDual) |
| [DP-VLA: **A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**](https://arxiv.org/abs/2410.15549) | CoRL 2024 | 2024-10-21 | - |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | CoRL 2024 | 2024-09-12 | - |
| [LCB: **From LLMs to Actions: Latent Codes as Bridges in Hierarchical Robot Control**](https://arxiv.org/abs/2405.04798) | IROS 2024 | 2024-05-08 | [Project](https://fredshentu.github.io/LCB_site/) |

### Humanoid Robot
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Helix: A Vision-Language-Action Model for Generalist Humanoid Control**](https://www.figure.ai/news/helix) | - | - | [Porject](https://www.figure.ai/news/helix) |


## ❌ Not a Dual-System VLA
### Robot Manipulation
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**OneTwoVLA: A Unified Vision-Language-Action Model with Adaptive Reasoning**](https://arxiv.org/abs/2505.11917) | arXiv | 2025-05-17 | ![Star](https://img.shields.io/github/stars/Fanqi-Lin/OneTwoVLA?style=social&label=Star) [Github](https://github.com/Fanqi-Lin/OneTwoVLA) | |
| [**NORA: A Small Open-Sourced Generalist Vision Language Action Model for Embodied Tasks**](https://arxiv.org/abs/2504.19854) | arXiv | 2025-04-28 | ![Star](https://img.shields.io/github/stars/declare-lab/nora?style=social&label=Star) [Github](https://github.com/declare-lab/nora) |  |
| [**π<sub>0.5</sub>: a Vision-Language-Action Model with Open-World Generalization**](https://arxiv.org/abs/2504.16054) | arXiv | 2025-04-22 | [Project](https://www.pi.website/blog/pi05) |  |
| [**π<sub>0</sub>: A Vision-Language-Action Flow Model for General Robot Control**](https://arxiv.org/abs/2410.24164) | arXiv | 2024-10-31 | [Project](https://www.physicalintelligence.company/blog/pi0) |  |
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | NeurIPS 2024 | 2024-10-14 | ![Star](https://img.shields.io/github/stars/abliao/PIVOT-R?style=social&label=Star) [Github](http://github.com/abliao/PIVOT-R) |  |
| [**MResT: Multi-Resolution Sensing for Real-Time Control with Vision-Language Models**](https://arxiv.org/abs/2401.14502) | CoRL 2023 | 2024-01-25 | ![Star](https://img.shields.io/github/stars/iamlab-cmu/mrest-multi-resolution-transformer?style=social&label=Star) [Github](https://github.com/iamlab-cmu/mrest-multi-resolution-transformer) |  |

### Humanoid Robot
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**GR00T N1: An Open Foundation Model for Generalist Humanoid Robots**](https://arxiv.org/abs/2503.14734) | arXiv | 2025-03-18 | [Porject](https://developer.nvidia.com/isaac/gr00t) |

