# Evan_V3: Hybrid Deep Learning Framework for Alzheimer’s Disease Classification Using MRI

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/PyTorch-DeepLearning-red.svg">
  <img src="https://img.shields.io/badge/Medical-Imaging-green.svg">
  <img src="https://img.shields.io/badge/MRI-Alzheimer-orange.svg">
  <img src="https://img.shields.io/badge/Status-Research-purple.svg">
</p>

---

## Overview

Evan_V3 is a comprehensive hybrid deep learning framework developed for automated Alzheimer’s disease staging using brain MRI images. The framework integrates heterogeneous learning paradigms, including convolutional neural networks (CNNs), Transformer-based architectures, and detection-adapted backbones, enabling robust feature extraction and high-precision classification across multiple dementia stages.

The proposed system was designed to address the limitations of single-model architectures by leveraging complementary representational capabilities from diverse deep learning families. Extensive experimentation, cross-validation, benchmarking, and statistical evaluation were conducted to ensure robustness, generalization capability, and clinical relevance.

---

## Key Features

- Hybrid multi-paradigm deep learning architecture
- MRI-based Alzheimer’s disease staging
- CNN + Transformer + Detection-based learning integration
- 5-fold cross-validation evaluation
- Extensive benchmarking and statistical analysis
- Explainable AI visualization support (Grad-CAM)
- t-SNE feature space visualization
- Data augmentation and preprocessing pipeline
- Weighted hybrid prediction strategy
- High-performance multi-class classification framework

---

## Supported Alzheimer’s Classes

The framework supports four-stage Alzheimer’s disease classification:

| Class | Description |
|---|---|
| Non Demented | Cognitively normal subjects |
| Very Mild Dementia | Early-stage cognitive impairment |
| Mild Dementia | Mild Alzheimer’s progression |
| Moderate Dementia | Advanced cognitive deterioration |

---

# Evan_V3 Architecture

The proposed Evan_V3 framework integrates three distinct deep learning paradigms:

## CNN Backbones
- EfficientNetV2-S
- ResNet50
- DenseNet121
- ConvNeXt-Tiny

## Transformer Backbones
- ViT-B/16
- Swin-Tiny
- DeiT-S
- MLP-Mixer

## Detection-Based Backbones
- CSPDarkNet-53
- HRNet-W32
- FPN-ResNet50
- DETR-Cls

These architectures collectively contribute to robust spatial, contextual, and multi-scale feature learning.

---

## Dataset

The study utilizes the publicly available OASIS MRI dataset.

### Dataset Source
https://www.kaggle.com/datasets/ninadaithal/imagesoasis

---

## Experimental Pipeline

The complete workflow consists of:

1. MRI Data Collection
2. Data Partitioning
3. Image Preprocessing
4. Data Augmentation
5. Deep Feature Extraction
6. Hybrid Model Learning
7. Cross-Validation
8. Performance Evaluation
9. Alzheimer’s Disease Prediction

---

## Evaluation Metrics

Performance was evaluated using multiple statistical and medical AI metrics:

- Accuracy
- Balanced Accuracy
- Precision
- Recall
- Weighted F1-Score
- Macro F1-Score
- Matthews Correlation Coefficient (MCC)
- Cohen’s Kappa
- ROC-AUC
- PR-AUC
- Brier Score
- Expected Calibration Error (ECE)
- G-Mean

---

## Installation

Clone the repository:

```bash
git clone https://github.com/evanmahmud/Alzheimer-s-Cross-Validation.git
cd Alzheimer-s-Cross-Validation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Requirements

Main dependencies include:

```text
Python >= 3.10
PyTorch
Torchvision
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
OpenCV
tqdm
timm
albumentations
```

---

## Running the Framework

Launch the notebook:

```bash
jupyter notebook
```

Open:

```text
evan-v3-alzheimer.ipynb
```

Execute all cells sequentially.

---

## Cross-Validation

The framework supports:

- Hold-out validation
- Stratified splitting
- 5-fold cross-validation
- Statistical robustness analysis

---

## Visualization Support

The repository includes:

- Grad-CAM visualizations
- t-SNE feature embeddings
- Accuracy/loss curves
- Benchmarking plots
- EDA visualizations
- Confusion matrices

---

## Benchmarking

Extensive comparisons were conducted among:

- CNN architectures
- Vision Transformers
- Detection-based backbones
- Hybrid Evan_V3 framework

The benchmarking includes:
- Accuracy vs. latency
- Parameter efficiency
- Inference throughput
- Computational complexity

---

## Research Contributions

- Introduction of a novel hybrid Alzheimer’s classification framework
- Integration of CNN, Transformer, and detection paradigms
- Exploration of detection-adapted backbones for MRI classification
- Comprehensive statistical validation and benchmarking
- Improved robustness against severe class imbalance
- Enhanced minority-class sensitivity

---

## Reproducibility

All experiments were conducted with fixed random seeds to ensure reproducibility.

---

## Citation

If you use this work in your research, please cite:

```bibtex
@article{evanv3_alzheimer,
  title={Evan_V3: A Multi-Paradigm Hybrid Deep Learning Framework for Alzheimer's Disease from Brain MRI — with Rigorous Cross-Validation and Statistical Benchmarking},
  author={Md Mahmudul Hoque, Mahmudul Hasan, Rakib Al Akand},
  journal={Under Review},
  year={2026}
}
```

---

## Code Availability

GitHub Repository:

https://github.com/evanmahmud/Alzheimer-s-Cross-Validation

---

## Future Work

Future extensions may include:

- Multi-modal MRI integration
- Federated medical learning
- Clinical deployment optimization
- Explainable Transformer attention analysis
- Lightweight edge deployment
- Longitudinal disease progression modeling

---

## License

This project is intended for research and academic purposes.

---

## Author

**Md Mahmudul Hoque**  
Data Science Researcher  
Machine Learning | Computer Vision | Medical Imaging | Deep Learning

---

## Acknowledgements

The authors acknowledge the publicly available OASIS dataset and the open-source deep learning community for enabling reproducible medical AI research.

---
