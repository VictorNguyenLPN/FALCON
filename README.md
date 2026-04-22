# FALCON: Forensic Artifact-guided Localization and Contrastive Reasoning for Generalizable Synthetic Image Detection

**Quang Huy Nguyen and Van Huy Pham**

[![arXiv](https://img.shields.io/badge/arXiv-Coming%20Soon-b31b1b.svg)](https://arxiv.org/) [![IEEE](https://img.shields.io/badge/IEEE-Coming%20Soon-00629b.svg)](https://ieeexplore.ieee.org/)


## Abstract

The rapid advancement of generative models, spanning Generative Adversarial Networks (GANs), Diffusion Models (DMs), Transformers, and Flow Matching (FM), has necessitated the development of forensic detectors capable of generalizing to unseen architectures. While recent language-guided frameworks like LASTED improve generalizability through semantic supervision, they often remain "blind" to low-level technical artifacts and lack spatial interpretability. In this paper, we propose FALCON, an enhanced forensic architecture designed to bridge the gap between semantic understanding and artifact localization. Our approach introduces two key innovations: (1) an optimal Hybrid prompt strategy-selected through an extensive evaluation of semantic, technical-expert, and hierarchical labeling spaces-to align visual features with complex forensic artifacts; and (2) an Attention-based Localization Head that leverages cross-modal weights to generate high-fidelity heatmaps of manipulated regions. To evaluate FALCON, we introduce the UniRF-112K dataset, a comprehensive benchmark comprising 112,000 images from nine state-of-the-art generators. Following a zero-shot protocol of training exclusively on ProGAN and testing on unseen architectures-including Stable Diffusion, DALL-E 2, Transformers, Flux.1 and StyleGAN3-preliminary results on our benchmark demonstrate that FALCON achieves a mean Average Precision (mAP) of 0.98, outperforming the re-implemented LASTED baseline by 0.12 under identical experimental conditions. The integration of artifact-guided reasoning and localization-aware features significantly enhances robustness against out-of-domain samples, providing both superior detection accuracy and critical spatial explainability for digital forensics.


## Dataset

- Name: UniRF-112K
- Scale: 112,000 images collected from 9 state-of-the-art generators
- Access: [Dataset link (coming soon)](https://example.com/unirf-110k)
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
