---
id:             2024-latent-mim
title:          "Towards Latent Masked Image Modeling for Self-Supervised Visual Representation Learning"
authors:        [Yibing, Abhinav, Me]
venue:          European Conference on Computer Vision (ECCV), Milan, 2024.
year:           "2024-07"
thumbnail:      https://yibingwei-1.github.io/images/latentMIM.png
bibtex:         "@InProceedings{wei2024lmim,<br>&emsp;title={Towards Latent Masked Image Modeling for Self-Supervised Visual Representation Learning},<br>&emsp;author={Yibing Wei and Abhinav Gupta and Pedro Morgado},<br>&emsp;booktitle={European Conference on Computer Vision (ECCV)},<br>&emsp;year={2024}<br>&emsp;}"
links:
    paper:      https://arxiv.org/abs/2407.15837
    bibtex:     assets/publications/2024-latent-mim/ref.txt
    code:       https://github.com/yibingwei-1/LatentMIM
    website:    https://yibingwei-1.github.io/projects/lmim/lmim.html

layout: project
short_title: Latent Masked Image Modeling
abstract: "Masked Image Modeling (MIM) has emerged as a promising method for deriving visual representations from unlabeled image data by predicting missing pixels from masked portions of images. It excels in region-aware learning and provides strong initializations for various tasks, but struggles to capture high-level semantics without further supervised fine-tuning, likely due to the low-level nature of its pixel reconstruction objective. A promising yet unrealized framework is learning representations through masked reconstruction in latent space, combining the locality of MIM with the high-level targets. However, this approach poses significant training challenges as the reconstruction targets are learned in conjunction with the model, potentially leading to trivial or suboptimal solutions. Our study is among the first to thoroughly analyze and address the challenges of such framework, which we refer to as Latent MIM. Through a series of carefully designed experiments and extensive analysis, we identify the source of these challenges, including representation collapsing for joint online/target optimization, learning objectives, the high region correlation in latent space and decoding conditioning. By sequentially addressing these issues, we demonstrate that latent MIM can indeed learn high-level representations while retaining the benefits of MIM models."
video_embed: https://www.youtube.com/embed/TkZ-eQVErFQ
---