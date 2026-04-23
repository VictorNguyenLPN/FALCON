# FALCON: Forensic Artifact-guided Localization and Contrastive Reasoning for Generalizable Synthetic Image Detection

**Quang Huy Nguyen and Van Huy Pham**

[![arXiv](https://img.shields.io/badge/arXiv-Coming%20Soon-b31b1b.svg)](https://arxiv.org/) [![IEEE](https://img.shields.io/badge/IEEE-Coming%20Soon-00629b.svg)](https://ieeexplore.ieee.org/) [![Dataset](https://img.shields.io/badge/Kaggle-Dataset-1abfff.svg)](https://www.kaggle.com/datasets/daddychillonkaggle/unirf-112k) 


## Abstract

The rapid advancement of generative models, spanning Generative Adversarial Networks (GANs), Diffusion Models (DMs), Transformers, and Flow Matching (FM), has necessitated the development of forensic detectors capable of generalizing to unseen architectures. While recent frameworks have made strides in generalizability through semantic supervision, they often remain "blind" to low-level technical artifacts and lack spatial interpretability. In this paper, we propose FALCON, an enhanced forensic architecture designed to bridge the gap between semantic understanding and artifact localization. Our approach introduces two key innovations: (1) an optimal Hybrid prompt strategy that aligns visual features with complex forensic artifacts by leveraging diverse labeling spaces, including category-level, descriptive caption, technical-artifact, and joint category-technical labels; and (2) an Attention-based Localization Head that leverages cross-modal weights to generate high-fidelity heatmaps of manipulated regions. To evaluate FALCON, we introduce the UniRF-112K dataset, a comprehensive benchmark comprising 112,000 images from nine state-of-the-art generators. By following a rigorous zero-shot protocol, training exclusively on ProGAN and testing on diverse, unseen architectures including Stable Diffusion, DALL-E 2, Transformers, Flux.1, and StyleGAN3, preliminary evaluations demonstrate that FALCON achieves superior generalizability across multiple domains. The integration of multi-faceted artifact reasoning and localization-aware features significantly enhances robustness against out-of-domain samples, providing both high detection accuracy and critical spatial explainability for digital forensics.

## Dataset

- Name: UniRF-112K
- Scale: 112,000 images collected from 9 state-of-the-art generators
- Access: [Dataset link](https://www.kaggle.com/datasets/daddychillonkaggle/unirf-112k)
- Protocol note: Zero-shot setting (train on ProGAN, test on unseen architectures)

![UniRF-112K Dataset Demo](UniRF-112K.jpg)


## Citation

If you find this work useful, please cite:

```bibtex
@article{nguyen2026falcon,
	title   = {FALCON: Forensic Artifact-guided Localization and Contrastive Reasoning for Generalizable Synthetic Image Detection},
	author  = {Nguyen, Quang Huy and Pham, Van Huy},
	journal = {arXiv preprint arXiv:XXXX.XXXXX},
	year    = {2026}
}
```

## Contact

- Quang Huy Nguyen: nguyenquanghuy.st@tdtu.edu.vn
- Van Huy Pham: huy.phamvan@umt.edu.vn
