---
layout: project-cards
title: "Electromagnetic Wave Transport with Maxwell's Equations"
type: Research
icon: <i class="fa-solid fa-building-columns"></i>
image: assets/images/mastersBG.png
---

#### **Master's Thesis (graded 1.0)**

Understanding and simulating the general behavior of electromagnetic waves in arbitrary environments is a challenging problem, not only in mathematical or physical terms, but also in algorithmic terms. Mathematical formulations based on physical observations, such as Maxwell’s equations, do exist, but their calculation is a complex and difficult undertaking. At the same time, an understanding of these processes is of paramount importance because the sheer size of the electromagnetic spectrum means that the applications are also diverse. From X-rays in medicine, to visible light in visualization, to radar waves, such as those used in the automotive industry, to name just a few direct fields of application. In addition, many other scenarios such as quantum mechanics or audio wave simulation could benefit from a general algorithmic description for electromagnetic wave behavior. Particularly, wave properties such as diffraction and interference are of high interest. Thus, to gain important insights, a computer simulation of the real world behavior of electromagnetic waves would be of great benefit. By its very nature, it is not easy to build such a simulation since it requires solving a second-order linear partial differential equation, the wave equation. Moreover, many of the defining properties occur only at relatively small scales, which poses numerical problems. There are strategies such as the Finite-Difference Time-Domain Method or the Method of Moments. However, they suffer from limitations regarding domain size or overall accuracy. We present a method based on Monte Carlo integration that attempts to overcome any discretization constraints, showcasing a different approach to the problem. In this thesis, a brief overview of the physical and mathematical basics is given at the beginning. In addition, related work and alternative approaches are discussed. Then, we proceed with the development of the Monte Carlo Waves method to simulate electromagnetic waves. Our method solves the inhomogeneous Helmholtz equation in several subdomains. For this, we must find valid boundary conditions to achieve physically plausible results. After explaining the principle algorithm, an analysis of the results is presented. In order to consolidate the presented approach, it is compared to existing methods. At the end, an outlook is given and possible further developments are discussed.