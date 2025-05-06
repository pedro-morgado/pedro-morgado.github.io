---
id:             2025-token-pruning
title:          "Patch Ranking: Token Pruning as Ranking Prediction for Efficient CLIP Inference"
authors:        [ChengEn, Jones, YuHen, Me]
venue:          Winter Conference on Applications of Computer Vision (WACV), Tucson, 2025.
year:           "2025-02"
thumbnail:      assets/publications/2025-token-pruning/banner.png
bibtex:         "@InProceedings{chengen2025pruning,<br>&emsp;title={Patch Ranking: Token Pruning as Ranking Prediction for Efficient CLIP Inference},<br>&emsp;author={Cheng-En Wu and Jinhong Lin and Yu-Hen Yu and Pedro Morgado},<br>&emsp;booktitle={IEEE/CVF Winter Applications in Computer Vision (WACV)},<br>&emsp;year={2025}<br>}"
links:
    bibtex:     assets/publications/2025-token-pruning/ref.txt
    paper:      https://arxiv.org/abs/2409.14607
#    code:       https://github.com/yibingwei-1/LatentMIM
#    website:    https://yibingwei-1.github.io/projects/lmim/lmim.html

layout: project
short_title: Ranking Patches for Efficient CLIP Inference
abstract: "Contrastive image-text pre-trained models such as CLIP have shown remarkable adaptability to downstream tasks. However, they face challenges due to the high computational requirements of the Vision Transformer (ViT) backbone. Current strategies to boost ViT efficiency focus on pruning patch tokens but fall short in addressing the multimodal nature of CLIP and identifying the optimal subset of tokens for maximum performance. To address this, we propose greedy search methods to establish a ``Golden Ranking'' and introduce a lightweight predictor specifically trained to approximate this Ranking. To compensate for any performance degradation resulting from token pruning, we incorporate learnable visual tokens that aid in restoring and potentially enhancing the model's performance. Our work presents a comprehensive and systematic investigation of pruning tokens within the ViT backbone of CLIP models. Through our framework, we successfully reduced 40% of patch tokens in CLIP's ViT while only suffering a minimal average accuracy loss of 0.3% across seven datasets. Our study lays the groundwork for building more computationally efficient multimodal models without sacrificing their performance, addressing a key challenge in the application of advanced vision-language models."
#video_embed: https://www.youtube.com/embed/TkZ-eQVErFQ
---