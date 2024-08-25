---
layout: page
title: Research
permalink: /projects/
description: My research interests keep on constantly evolving and I let them be. On a broad sense, I try to understand properties and functions of materials, if possible in the most realistic sense. Following are some of the areas I am currely interested in and playing around
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

## Probablistic Machine Learning
Machine learning (ML) has emerged as a handy tool to make inferences from data, aiding decision-making processes. On the contrary to other areas, it is not straightforward to build generalizable ML workflows in disciplines such as materials science where due to the inherently interpolative nature, ML Models are prone to fail when deployed outside the domain of the training data. Since we are always interested in identifying/understanding materials with promising properties (and hence likely to be far from the training data distribution), the ML models should be able to signal about less-confident regions in materials space. By utilizing probabliy distributions to represent the unknowns, more accurate and informative ML pipelines could be built which can be employed for adaptive learning and knowledge generation. My studies in this direction involve both Bayesian and non-Bayesian approaches for uncertainty quantification, multi-modal learning and design of experiments.

## Explainable Artificial Intelligence
In an ideal world, any AI system should be self-explinable, i.e., humans should be able to understand its interpretations. For instance, while a right prdiction of a material which is super hard (e.g.,high bulk modulus) is interesting, which fundamental properties of this material caused such a behaviour is more important for a model's universal adapatability. For achieving this, developing AI methods which incorporate the domain knowledge and thus acheive explainability is desirable. By using methods such as symbolic regression and physics-informed modelling, I try to discover the mathematical equations governing a phenomena demonstrated by a material. I am particularly interestd in material genomics, where the functions and properties of materials are attempted to be explained from the fundamental physico-chemical parameters.

## Devlopment of Computational Workflows
Evaluation of material properties often involve multiple steps and often pose intricacies specific to that material. Hence when multiple materials with diverse properties are to be estimated, efficient computaional workflows need to be developed which can seamlessly automates and parellize many of these tasks. These workflows could be mission-driven (e.g.,building a database of a material category) or AI-guided (e.g., building a database of best thermal conductors starting from a few). I am interested in developing high-throughput frameworks which effectively integrates first principles simulations, AI models and high-throughput frameworks for efficient, reproducible materials simulations.

## Complex Material Simulations
For many important applications such as energy-storage or conversion, many of the potentially useful materials are complex in composition or (electronic)structure. Example categories are transition metal oxides (strong electron correlation), nanoclusters (quantum confinement) or solid-liquid interfaces (amorphous nature). Typical first principles based approaches are inadequate in accurately estimating the properties of such systems. By using tools such as beyond-DFT electronic structure methods, *ab initio* thermodynamics, cluster expansion and machine-learning interatomic potentials, I attempt to simulate such materials and evaluate their properties. Also I am interested in understanding the effect of real-time conditions such as pressure/temperature effects, interface charesteristics and defects.
