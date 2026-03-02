# Fase3D: Efficient Encoder-Free Fourier-based 3D Large Multimodal Model

[![arXiv](https://img.shields.io/badge/arXiv-2602.23153-b31b1b.svg)](https://arxiv.org/abs/2602.23153)
[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://your-website-url.github.io)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

This is the official code and website repository for the paper **"Efficient Encoder-Free Fourier-based 3D Large Multimodal Model"** (CVPR 2026).



## 📢 News
* **[Feb 2026]** Fase3D has been accepted to **CVPR 2026**! 🎉
* **[Feb 2026]** The [preprint](https://arxiv.org/abs/2602.23153) is now available on arXiv.
* **[Upcoming]** Training code, evaluation scripts, and pre-trained model weights will be released here soon.

## 🚀 Overview

Large Multimodal Models (LMMs) that process 3D data typically rely on heavy, pre-trained visual encoders. **Fase3D** is the first efficient encoder-free Fourier-based 3D scene LMM. 

By combining structured superpoints, space-filling curve serialization, and the Fast Fourier Transform (FFT), Fase3D effectively tokenizes unordered 3D data and completely bypasses traditional 3D encoders. Coupled with Fourier-augmented LoRA adapters, our model injects global frequency-aware interactions directly into the LLM with negligible computational cost, achieving state-of-the-art performance in 3D Scene QA and understanding.

## 💻 Code & Models (Coming Soon)

Instructions for environment setup, training, and inference will be provided in this section upon the official code release.

```bash
# Placeholder for future installation commands
git clone [https://github.com/YOUR_ORG/Fase3D.git](https://github.com/YOUR_ORG/Fase3D.git)
cd Fase3D
pip install -r requirements.txt
```


```bash
@inproceedings{mei2026fase3d,
  title={Efficient Encoder-Free Fourier-based 3D Large Multimodal Model},
  author={Mei, Guofeng and Lin, Wei and Riz, Luigi and Wu, Yujiao and Wang, Yiming and Poiesi, Fabio},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```