---
layout: page
title: Publications
permalink: /publications/
---

### Selected highlights
- **Sparse chaos in neural circuits** (2024, arXiv:2412.21188). Spike onset rapidness shifts networks from dense to sparse chaos, linking single cell biophysics to global dynamics.
- **Gradient Flossing** (NeurIPS 2023). Stabilizes long horizon training by regularizing Lyapunov exponents of the long term Jacobian.
- **SparseProp** (NeurIPS 2023). Event based algorithm that makes million neuron SNN simulation and training practical on a single CPU.
- **Lyapunov spectra of chaotic RNNs** (Phys Rev Research 2023). First full spectra, with extensivity, symmetry, attractor dimension, and a link to Jacobians in backpropagation through time.
- **Input correlations impede suppression of chaos** (PLOS Computational Biology 2022). Why correlations hinder stabilizing balanced networks and learning.

---

## Full list

{% raw %}{% bibliography -f papers -q @*[selected=true]* %}{% endraw %}

{% raw %}{% bibliography -f papers %}{% endraw %}