---
id:             2024-av-zsl
title:          "Audio-visual Generalized Zero-shot Learning the Easy Way"
authors:        [Shentong, Me]
venue:          European Conference on Computer Vision (ECCV), 2024.
year:           "2024-07"
thumbnail:      https://media1.tenor.com/m/8tbLhifgyEEAAAAC/excited.gif
bibtex:         "@InProceedings{mo24avzsl,<br>&emsp;title={Audio-visual Generalized Zero-shot Learning the Easy Way},<br>&emsp;author={Mo, Shentong and Morgado, Pedro},<br>&emsp;booktitle={European Conference on Computer Vision (ECCV)},<br>&emsp;year={2024}<br>&emsp;}"
links:
    paper:      https://arxiv.org/abs/2407.13095
    bibtex:     assets/publications/2024-av-zsl/ref.txt

layout: project
short_title: Audio-visual Generalized Zero-shot Learning
abstract: "Audio-visual generalized zero-shot learning is a rapidly advancing domain that seeks to understand the intricate relations between audio and visual cues within videos. The overarching goal is to leverage insights from seen classes to identify instances from previously unseen ones. Prior approaches primarily utilized synchronized auto-encoders to reconstruct audio-visual attributes, which were informed by cross-attention transformers and projected text embeddings. However, these methods fell short of effectively capturing the intricate relationship between cross-modal features and class-label embeddings inherent in pre-trained language-aligned embeddings. To circumvent these bottlenecks, we introduce a simple yet effective framework for Audio-Visual Generalized Zero-Shot Learning that aligns audio-visual embeddings with transformed text representations. It utilizes a single supervised text audio-visual contrastive loss to learn an alignment between audio-visual and textual modalities, moving away from the conventional approach of reconstructing cross-modal features and text embeddings. Our key insight is that while class name embeddings are well aligned with language-based audio-visual features, they don't provide sufficient class separation to be useful for zero-shot learning. To address this, our method leverages differential optimization to transform class embeddings into a more discriminative space while preserving the semantic structure of language representations. We conduct extensive experiments on VGGSound-GZSL, UCF-GZSL, and ActivityNet-GZSL benchmarks. Our results demonstrate that our method achieves state-of-the-art performance in audio-visual generalized zero-shot learning."

---