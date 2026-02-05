---
layout: archive
title: "My Research Work"
permalink: /Research/
author_profile: true
---

*  <b> <span style="color:navy;"> Quantifying Normality: Convergence Rate to Gaussian Limit for Stochastic Approximation and Unadjusted OU Algorithm </b> <br>
<b> SU Haque </b>, Z. Wang, Z. Zhang, ST Maguluri, Submitted <br>
<b> Overview: </b> In this work, we establish explicit non-asymptotic bounds on the Wasserstein distance between the distribution of the rescaled iterate at time k and the asymptotic Gaussian limit for various choices of step-sizes including constant and polynomially decaying. We obtain these sharp rates by first studying the convergence rate of the discrete Ornstein–Uhlenbeck (O-U) process driven by general noise, whose stationary distribution is identical to the limiting Gaussian distribution of the rescaled SA iterates. The analysis involves adapting Stein’s method for Gaussian approximation to handle the matrix weighted sum of i.i.d. random variables. Then, the desired finite-time bounds for SA are obtained by characterizing the error dynamics between the rescaled SA iterate and the discrete time O-U process and combining it with the convergence rate of the latter process.

*  <b> <span style="color:navy;"> Fine-Tuning Diffusion Models via Intermediate Distribution Shaping </b> <br>
G. G. Anil, <b> SU Haque </b>, N. Kannen, D. Nagaraj, K. Shanmugan, S. Shakottai, [arXiv version](https://arxiv.org/abs/2510.02692), Accepted in ICLR 2026 <br>
<b> Overview: </b> Diffusion models are widely used for generative tasks across domains. In many settings, it is often desirable to fine-tune the output data distribution using reward functions to align with downstream applications. In this context, we unify variants of Rejection sAmpling based Fine-Tuning (RAFT) as GRAFT, and show that this implicitly performs KL regularized reward maximization with reshaped rewards. Building on this, we introduce P-GRAFT to shape distributions at intermediate noise levels, which we justify through a bias-variance tradeoff. We also propose an inverse noise correction for flow models that functions without explicit rewards. We emiprically validate the superior performance of P-GRAFT over policy gradient methods on text-to-image, molecule generation and layout generation benchmarks and demonstrate significant improvements in image quality for unconditional generation task using inverse noise correction.

*  <b> <span style="color:navy;"> Finite-time Bounds for Two-Time-Scale Stochastic Approximation with Arbitrary Norm Contractions and Markovian Noise </b> <br>
S Chandak, <b> SU Haque </b>, N Bambos, "'', [arxiv version](https://arxiv.org/pdf/2503.18391), [64th IEEE CDC](https://ieeexplore.ieee.org/document/11312393). <br>
<b> Overview: </b>

* <b> SU Haque </b>, ST Maguluri, "Stochastic Approximation with Unbounded Markovian Noise: A General-Purpose Theorem", [arxiv version](https://arxiv.org/abs/2410.21704), [AISTATS 2025](https://proceedings.mlr.press/v258/haque25a.html). <br>
* S Zhang, Z Zhang, Z Chen, <b> SU Haque </b>, ST Maguluri, "A non-asymptotic theory of seminorm Lyapunov stability: From deterministic to stochastic iterative algorithms'', [arxiv version](https://arxiv.org/pdf/2502.14208),  Submitted <br>
* <b> SU Haque </b>, S Khodadadian, ST Maguluri, "Tight Finite Time Bounds of Two-Time-Scale Linear Stochastic Approximation with Markovian Noise", [arxiv version](https://arxiv.org/abs/2401.00364), (Submitted). <br>
* <b> SU Haque </b>, A Rajwade, KS Gurumoorthy, "Joint Probability Estimation Using Tensor Decomposition and Dictionaries", [EUSIPCO 2022](https://eurasip.org/Proceedings/Eusipco/Eusipco2022/pdfs/0002226.pdf).   <br>
* S Sharma, A Girish, N P Rakhashia, V M Gadre, <b> SU Haque </b>, A Ansari, R B Pachori, P Radhakrishna, P Sahay, "Theoretical Analysis of an Inverse Radon Transform Based Multicomponent Micro-Doppler Parameter Estimation Algorithm", [2022 National Conference on Communications (NCC)](https://ieeexplore.ieee.org/abstract/document/9806802).  <br>
* <b> SU Haque </b>, S Chandak, F Chiariotti, D Gündüz, P Popovski, "Learning to Speak on Behalf of a Group: Medium Access Control for Sending a Shared Message", [IEEE Communications Letters, 2022](https://ieeexplore.ieee.org/abstract/document/9792282).  <br>

* <b>Learning to Speak on Behalf of a Group: Medium Access Control for Sending a Shared Message </b> <br>
The project involved developing an algorithm for multiple agents to learn Medium Access Control (MAC) protocol to communicate through a set of collision channels. Our problem required agents to share information without collision at least once at any instant, which is different from the conventional average throughput maximization. We modeled our problem by posing it as a Multi-Armed Bandit for each agent where it learned successfully which channels to access when it became active. By simulating over multiple cases, we showed the superiority of our learning-based solution over heuristic approaches that utilize the knowledge of the distribution according to which observer agents are chosen. We theoretically proved the NP-hardness of the problem and also showed that it is sufficient to search for the optimal solution only in the space of deterministic actions. We have submitted our work as a conference paper at IEEE WCNC 2022. For more information please refer to my [CV](http://shaan3130.github.io/files/CV.pdf).

* <b>Micro-Doppler Effects in RADAR </b> <br>
I was involved in this research during my sophomore year. In real life, we have sources like helicopters that have vibrating surface (due to engine) and rotating blades. These motions induce a sinusoidally varying frequency in the RADAR signal along with the body Doppler. If we can estimate these frequencies we can even tell the frequency of vibration of the engine and the angular speed of the blades. Our task is, given a signal, we need to estimate the values of the micro-doppler and body-doppler frequencies. For more information please refer to my [CV](http://shaan3130.github.io/files/CV.pdf).
