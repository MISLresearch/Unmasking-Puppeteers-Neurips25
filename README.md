# Unmasking Puppeteers: Leveraging Biometric Leakage to Disarm Impersonation in AI-based Videoconferencing

**Paper Accepted at NeurIPS 2025**

[![Paper](https://img.shields.io/badge/Paper-NeurIPS%202025-blue)](https://arxiv.org/abs/2510.03548)
[![License](https://img.shields.io/badge/License-Custom-red)](LICENSE)

## Abstract

AI-based talking-head videoconferencing systems transmit compact pose-expression embeddings to save bandwidth. However, these systems are vulnerable to **puppeteering attacks** where an attacker hijacks a victim's likeness in real time by sending their movements with the victim's reference image.

We introduce a novel defense that exploits **biometric leakage** inherently present in pose-expression embeddings to detect identity mismatches without accessing RGB video. Our method operates entirely in the latent domain using a pose-conditioned contrastive loss with pose-matched negatives.

## Key Contributions

- **First biometric leakage defense** for puppeteering attacks in low-bandwidth videoconferencing
- **Pose-Conditioned Large-Margin Cosine Loss (PC-LMCL)** with pose-matched negatives
- **Real-time detection** at 75 FPS without RGB reconstruction or user enrollment
- **State-of-the-art performance**: 97.7% AUC (46% error reduction vs. prior work)
- **Strong generalization** to unseen generators and datasets

## Results

| Method | NVIDIA-VC | RAVDESS | CREMA-D | Average |
|--------|-----------|---------|---------|---------|
| Prior Work [10] | 94.5% | 94.7% | 94.4% | 94.5% |
| **Ours** | **97.7%** | **96.8%** | **96.8%** | **97.1%** |

## Code Release

**Full implementation code will be released soon.**

We are preparing the code for public release with documentation and examples. Expected release: [Date TBD]

## Citation

If you use this work in your research, please cite:
```bibtex
@article{vahdati2025unmasking,
  title={Unmasking Puppeteers: Leveraging Biometric Leakage to Disarm Impersonation in AI-based Videoconferencing},
  author={Vahdati, Danial Samadi and Nguyen, Tai Duc and Prashnani, Ekta and Nagano, Koki and Luebke, David and Gallo, Orazio and Stamm, Matthew},
  journal={arXiv preprint arXiv:2510.03548},
  year={2025}
}
```

## ⚖️ License & Citation

### Licensing
This software is licensed under the **PolyForm Noncommercial License 1.0.0**. 
* **Research & Academic Use:** Free and encouraged!
* **Commercial Use:** **Strictly prohibited** without prior written permission.
- 📧 Contact us for licensing inquiries

## Contact

For questions about the paper or code release:
- **Email:** ds3729@drexel.edu
- **Issues:** [Open an issue](https://github.com/MISLresearch/Unmasking-Puppeteers-Neurips25/issues)

---

**Status:** Paper accepted at NeurIPS 2025 | Code release in progress
EOF
