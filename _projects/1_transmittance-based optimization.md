---
layout: project-cards
title: Transmittance-based Visibility and Viewpoint Optimization
type: Research
icon: <i class="fa-solid fa-building-columns"></i>
image: assets/images/paperBG.png
---

#### **EuroVis 2024 (Under Review)**

A long-standing challenge in volume visualization is the effective communication of relevant spatial structures that might be hidden due to occlusions. Given a scalar field that indicates the importance of every point in the domain, previous work synthesized volume visualizations by weighted averaging of samples along view rays or by optimizing the extinction through an energy minimization. The contribution of an individual sample to the final pixel color is determined by the so-called transmittance, which, however, has previously not been part of the objective function. In this paper, we propose to measure the visibility of relevant structures directly by incorporating the transmittance into a non-linear energy minimization. For the first time, we not only perform a transmittance-based visibility optimization, we concurrently optimize the camera position to find ideal viewpoints. We derive the partial derivatives for the gradient-based optimization symbolically, which makes the application of automatic differentiation methods unnecessary. The transmittance-based formulation gives a direct visibility measure that is communicated to the user in order to make aware of potentially overlooked relevant structures. Our approach is compatible with any measure of importance and its versatility is demonstrated in multiple data sets.

[Project Page]('')\
[arXiv]('')\
[Code]('')