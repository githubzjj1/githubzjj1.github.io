---
title: "CGTGait: Collaborative Graph and Transformer for Gait Emotion Recognition"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: ''
date: 2024-02-17
venue: 'IEEE International Joint Conference on Biometrics (IJCB)'
paperurl: 'https://arxiv.org/abs/2509.16623'
citation: '
@article{zhou2025cgtgait,
  title={CGTGait: Collaborative Graph and Transformer for Gait Emotion Recognition},
  author={Zhou, Junjie and Xiong, Haijun and Lu, Junhao and Lin, Ziyu and Feng, Bin},
  journal={arXiv preprint arXiv:2509.16623},
  year={2025}
}
'
---

Skeleton-based gait emotion recognition has received significant attention due to its wide-ranging applications. However, existing methods primarily focus on extracting spatial and local temporal motion information, failing to capture long-range temporal representations. In this paper, we propose \textbf{CGTGait}, a novel framework that collaboratively integrates graph convolution and transformers to extract discriminative spatiotemporal features for gait emotion recognition. Specifically, CGTGait consists of multiple CGT blocks, where each block employs graph convolution to capture frame-level spatial topology and the transformer to model global temporal dependencies. Additionally, we introduce a Bidirectional Cross-Stream Fusion (BCSF) module to effectively aggregate posture and motion spatiotemporal features, facilitating the exchange of complementary information between the two streams. We evaluate our method on two widely used datasets, Emotion-Gait and ELMD, demonstrating that our CGTGait achieves state-of-the-art or at least competitive performance while reducing computational complexity by approximately \textbf{82.2\%} (only requiring 0.34G FLOPs) during testing.
