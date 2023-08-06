---
layout: page
title: Bachelor's Thesis
description: Generating Structured Thermal Noise for Quantum Dynamical Systems
img: assets/img/Noise.PNG
importance: 4
category: Academic
---

Bachelor's thesis project at Jacobs University Bremen under the supervision of Prof. Ulrich Kleinekathöfer and Yannick Holtkamp. The thesis can be viewed in detail <a href="/assets/pdf/Thesis_final_submission.pdf">here</a>.

### Abstract:


To understand some of the most fundamental processes responsible for life on Earth, such as photosynthesis, quantum dynamical descriptions are of utmost importance. This analysis can be performed by studying the so-called open systems through a vari- ation of the mean-field Ehrenfest Dynamics methods, known as Numerical Integration of Schr ̈odinger equation (NISE). A key ingredient for the calculations using NISE is the time-dependent site energies. Such fluctuations can be obtained from Molecular Dynamics (MD) simulations. However, these methods are usually computationally expensive, and do not provide the desired accuracy. An alternative approach is the generation of structured noise following the bath spectral density. This has been done previously for systems described by simple spectral functions.

In this thesis I implement an enveloping algorithm capable of generating noise with any arbitrary spectral density. Several tests are performed to verify the validity, scope and limitations of the algorithm. After finding the parameters necessary to repli- cate more complex spectral shapes, this noise is used in the calculation of population dynamics for a collection of test systems. These simulations provide insight on the parameter regimes and specific considerations for the implementation of the noise in these calculations, and yield useful information in the performance of NISE under the new frameworks.