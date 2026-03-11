# Alvin Chirchir

**PhD Researcher · AI for Semiconductor Manufacturing · Swansea University**

I work on automated defect detection in Silicon Carbide (SiC) epitaxial wafers, using self-supervised learning and active learning to build inspection systems that don't require thousands of labelled examples to work. My research is done in collaboration with [KLA](https://www.kla.com/) and [VISHAY Technologies](https://www.vishay.com/), using real production data from a working fab environment.

---

## Research

**Self-Supervised Deep Active Learning for SiC Defect Detection**

SiC is the material behind modern power electronics — EV inverters, fast chargers, high-voltage switching devices. As manufacturing scales up, so does the pressure on yield. Defects like micropipes, stacking faults, carrot defects, and surface contamination can silently degrade device performance or cause failure, and catching them at the wafer stage is critical.

The inspection bottleneck is labelled data. Defects are rare by nature — some classes have fewer than 10 confirmed examples in an entire production run. Most approaches either rely on fragile classical image processing or assume you have thousands of clean labelled examples. My work addresses this directly:

- **Self-supervised pretraining** — ResNet-18 trained with SimCLR on unlabelled wafer imagery, learning visual structure before any labels are introduced
- **Clustering-guided active learning** — the model flags the most informative unlabelled samples each round, maximising accuracy gain per annotation hour
- **Generative augmentation** — synthesising physically realistic training examples for critically underrepresented defect classes
- **Real-world evaluation** — all experiments run on SIMOSFET device images from VISHAY's manufacturing environment, not benchmarks

> Targeting submission to **ICSCRM 2026** (International Conference on Silicon Carbide and Related Materials)

---

## Projects

| Project | Description | Stack |
|---|---|---|
| [SiC Defect Detection](#) | Self-supervised active learning pipeline for wafer inspection | PyTorch · SimCLR |
| [resnet-cifar100](https://github.com/alvinchirchir/resnet-image-classification-cifar100) | ResNet CNN classification on CIFAR-100 | PyTorch |
| [pca-hog-svm-cifar100](https://github.com/alvinchirchir/pca-hog-svm-image-classification-cifar100) | Classical ML image classification baseline | sklearn · Jupyter |
| [face_net](https://github.com/alvinchirchir/face_net) | Face verification library | Python |
| [Tibu](https://github.com/alvinchirchir/Tibu) | Nature-inspired AI disease diagnosis assistant | MATLAB |

---

## Stack

```
Deep Learning     PyTorch · ResNet · SimCLR · Generative Models
Computer Vision   OpenCV · Albumentations
Active Learning   Clustering · Uncertainty Sampling · Core-Set
Backend           Python · Go · TypeScript · Node.js
```

---

## Background

Before the PhD, I worked in backend engineering ;building APIs, database layers, and system architecture across fintech and SaaS products. I still write a lot of code and treat research infrastructure with the same standards as production software.

---

**Industry Partners:** KLA · VISHAY Technologies  
**Institution:** Swansea University, College of Engineering  
🐦 [@chirchir_alvin](https://twitter.com/chirchir_alvin) · Swansea, UK
