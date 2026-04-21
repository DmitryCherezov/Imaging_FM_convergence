# Foundation Model Convergence in Medical Imaging

## Overview

This project investigates the convergence properties of foundation models (FMs) in the context of medical imaging, with a particular focus on X-ray data.

The core objective is to understand whether different models — trained on diverse datasets or modalities — learn similar internal representations when exposed to the same underlying physical processes.

---

## Introduction

This work is motivated by two key research questions inspired by prior studies:

1. **Convergence across data sources:**  
   Whether foundation models trained on different datasets, but governed by the same underlying physical principles (e.g., X-ray attenuation), learn convergent representations.  
   This idea is supported by prior work demonstrating that models trained on distinct datasets may align when the underlying signal is physically constrained <a href="#ref1">[1]</a>.

2. **Cross-domain convergence of vision models:**  
   Whether foundation models trained on different types of images (e.g., natural images, radiographs, microscopy) still converge to similar representations despite domain differences.  
   Recent studies suggest that representation spaces of such models may exhibit strong alignment even across domains <a href="#ref2">[2]</a>.

Together, these questions aim to explore the hypothesis that **representation convergence is driven more by shared structure in data (e.g., physics or geometry) than by dataset-specific characteristics**.

---

## Methods

To investigate these hypotheses, the project follows several key steps:

- **Feature Extraction**  
  High-dimensional feature vectors are extracted from multiple foundation models applied to X-ray images.

- **Clustering and Representation Analysis**  
  Unsupervised methods are used to identify structure in the learned representations.

- **Model Comparison**  
  Representations from different models are compared to assess:
  - alignment
  - similarity
  - convergence behavior

- **Performance Association**  
  The relationship between learned representations and downstream diagnostic performance (e.g., AUC) is analyzed.

---

## Repository Structure



## References
<a id="ref1"></a>
1. Edamadaka, S., Yang, S., Li, J. and Gómez-Bombarelli, R., 2025. Universally converging representations of matter across scientific foundation models. arXiv preprint arXiv:2512.03750.


<a id="ref2"></a>
2.  Cherezov, D., Dam, T. and Madabhushi, A., 2025, April. Assessing tuberculosis detection and treatment outcome prediction in x-ray images: a cross-domain foundation model performance analysis. In Medical Imaging 2025: Computer-Aided Diagnosis (Vol. 13407, pp. 650-661). SPIE.

