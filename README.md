# CA-Mamba: Curvature-Aware Adaptive State Space Modeling for Autoregressive Mesh Generation

Official implementation of the paper:

"CA-Mamba: Curvature-Aware Adaptive State Space Modeling for Autoregressive Mesh Generation"

## Overview

We propose a curvature-aware state space modeling framework for autoregressive triangular mesh generation with linear-time complexity. The framework explicitly conditions state transitions on geometric curvature and integrates geometry-aware adaptive decoding to improve geometric validity.

## 📌 Open-Source Roadmap

We are committed to releasing a complete and reproducible implementation of **CA-Mamba**.
Due to the complexity of the framework and ongoing paper review, we adopt a **phased open-source strategy**:

- [x] Project repository initialization
- [x] Core curvature computation and geometric statistics module
- [x] Geometry-Aware Adaptive Decoding (GAAD) implementation
- [ ] Full CA-Mamba model training pipeline
- [ ] Pre-trained models for ShapeNet categories
- [ ] End-to-end training and evaluation scripts
- [ ] Detailed documentation and usage examples

The remaining components will be progressively released upon paper acceptance.
