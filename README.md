# FALCON: Forensic-Aware Language-guided Contrastive Learning for Generalized Synthetic Image Detection

**Quang Huy Nguyen**$^1$, **Van Huy Pham**$^2$

$^1$*Natural Language Processing & Knowledge Discovery Laboratory, Faculty of Information Technology, Ton Duc Thang University, Ho Chi Minh city, Vietnam*  
$^2$*School of Technology, University of Management and Technology, Ho Chi Minh city, Vietnam*


[![arXiv](https://img.shields.io/badge/arXiv-Coming%20Soon-b31b1b.svg)](https://arxiv.org/) [![IEEE](https://img.shields.io/badge/IEEE-Coming%20Soon-00629b.svg)](https://ieeexplore.ieee.org/) [![Click Here](https://img.shields.io/badge/Kaggle-Click%20Here-1abfff.svg)](https://www.kaggle.com/datasets/daddychillonkaggle/unirf-112k) 

---

## News

- **[Sep 9, 2026]** 🎉 Our paper has been accepted to **FITAT 2026** (The 18th International Conference on Frontiers of Information Technology, Applications and Tools), held in Cheongju, South Korea (October 30 - November 2, 2026). 


## Abstract

Recent advances in generative models have significantly improved the realism of synthetic images, making cross-generator synthetic image detection increasingly challenging. Existing forensic detectors often learn generator-specific artifacts and therefore suffer substantial performance degradation when evaluated on unseen architectures. In this paper, we propose **FALCON** (**F**orensic-**A**ware **L**anguage-guided **CON**trastive Learning), a language-guided forensic framework that uses forensic-aware textual supervision to learn transferable visual representations. FALCON aligns image features with textual descriptions of semantic content and forensic traces, and then refines the detector with a hybrid contrastive and classification objective. To evaluate cross-generator robustness, we construct **UniRF-112K**, a benchmark of 112,000 real and synthetic images spanning GANs, diffusion models, transformer-based generation, and flow matching. Under a one-generator training protocol, models are trained on ProGAN and evaluated across diverse held-out generators. Experimental results show that FALCON achieves the highest mean AP of 83.30% among the evaluated methods. The dataset and supplementary resources are publicly available at https://github.com/VictorNguyenLPN/FALCON.

## Dataset

- Name: UniRF-112K
- Scale: 112,000 images collected from 9 state-of-the-art generators
- Source: https://www.kaggle.com/datasets/daddychillonkaggle/unirf-112k
- Protocol note: Zero-shot setting (train on ProGAN, test on unseen architectures)

![UniRF-112K Dataset Demo](UniRF-112K.jpg)


## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{nguyen2026falcon,
  title     = {FALCON: Forensic Artifact-guided Localization and Contrastive Reasoning for Generalizable Synthetic Image Detection},
  author    = {Nguyen, Quang Huy and Pham, Van Huy},
  booktitle = {Proceedings of the 18th International Conference on Frontiers of Information Technology, Applications and Tools (FITAT)},
  year      = {2026}
}
```

## Contact

- Quang Huy Nguyen: nguyenquanghuy.st@tdtu.edu.vn
- Van Huy Pham: huy.phamvan@umt.edu.vn
