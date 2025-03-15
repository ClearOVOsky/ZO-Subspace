# ZO-Subspace
Zeroth-order optimizer used in deep networks. We apply an Evolution Strategy (ES) algorithm called CMA-ES to approximate gradients, which are calculated by the Backpropagation (BP) algorithm to update the model parameters in subspace.
---
## Introduction
In this section, we introduce our project where we achieve model parameter updates in subspace using zero-order optimization. Many related papers propose a hypothesis that neural network models can be updated in a tiny space with dimensions much lower than the full space, and the accuracy can reach similar levels in fewer epochs. Based on the current state of research, we delve deeper, hoping to apply zero-order optimization in subspace to the direction of domain adaptation. We aim for zero-order optimization in subspace to achieve domain adaptation with results comparable to traditional domain adaptation algorithms such as the test-time entropy algorithm.

