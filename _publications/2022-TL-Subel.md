---
title: "Explaining the physics of transfer learning a data-driven subgrid-scale closure to a different turbulent flow"
collection: publications
permalink: /publication/2022-TL-Subel
excerpt: 'This paper is about finding spectral analysis of convolutional neural network applied to transfer learning.'
date: 2022-06-01
venue: 'PNAS Nexus'
paperurl: ' https://doi.org/10.1093/pnasnexus/pgad015'
citation: 'Adam Subel, <strong>Yifei Guan</strong>, Ashesh Chattopadhyay, and Pedram Hassanzadeh. "Explaining the physics of transfer learning a data-driven subgrid-scale closure to a different turbulent flow." PNAS Nexus (2023).'
---

Transfer learning (TL) is becoming a powerful tool in scientific applications of neural networks (NNs), such as weather/climate prediction and turbulence modeling. TL enables out-of-distribution generalization (e.g., extrapolation in parameters) and effective blending of disparate training sets (e.g., simulations and observations). In TL, selected layers of a NN, already trained for a base system, are re-trained using a small dataset from a target system. For effective TL, we need to know 1) what are the best layers to re-train? and 2) what physics are learned during TL? Here, we present novel analyses and a new framework to address (1)-(2) for a broad range of multi-scale, nonlinear systems. Our approach combines spectral analyses of the systems' data with spectral analyses of convolutional NN's activations and kernels, explaining the inner-workings of TL in terms of the system's nonlinear physics. Using subgrid-scale modeling of several setups of 2D turbulence as test cases, we show that the learned kernels are combinations of low-, band-, and high-pass filters, and that TL learns new filters whose nature is consistent with the spectral differences of base and target systems. We also find the shallowest layers are the best to re-train in these cases, which is against the common wisdom guiding TL in machine learning literature. Our framework identifies the best layer(s) to re-train beforehand, based on physics and NN theory. Together, these analyses explain the physics learned in TL and provide a framework to guide TL for wide-ranging applications in science and engineering, such as climate change modeling.

[Download paper here]( https://doi.org/10.1093/pnasnexus/pgad015)

Recommended citation: Adam Subel, <strong>Yifei Guan</strong>, Ashesh Chattopadhyay, and Pedram Hassanzadeh. "Explaining the physics of transfer learning a data-driven subgrid-scale closure to a different turbulent flow." PNAS Nexus (2023).
