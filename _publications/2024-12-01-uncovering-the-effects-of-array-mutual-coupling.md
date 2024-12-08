---
title: "Uncovering the Effects of Array Mutual Coupling in 21-cm Experiments with the SKA-Low Radio Telescope"
collection: publications
category: preprint
permalink: /publication/uncovering-the-effects-of-array-mutual-coupling
excerpt: ''
date: 2024-12-01
venue: 'Monthly Notices of the Royal Astronomical Society'
paperurl: 'https://arxiv.org/abs/2412.01699'
citation: '<b>O’Hara, O. S.</b>, Gueuning, Q., Acedo, E. D. L., Dulwich, F., Cumner, J., Anstey, D., ... & Liu, Y. (2024). Uncovering the Effects of Array Mutual Coupling in 21-cm Experiments with the SKA-Low Radio Telescope. arXiv preprint arXiv:2412.01699.'
---

We investigate the impact of Mutual Coupling (MC) between antennas on the time-delay power spectrum response of the core of the SKA-Low radio telescope. Using two in-house tools - Fast Array Simulation Tool (FAST) (a fast full-wave electromagnetic solver) and OSKAR (a GPU-accelerated radio telescope simulator) - we simulate station beams and compute visibilities for various array layouts (regular, sunflower, and random). Simulations are conducted in an Epoch of Reionisation subband between 120-150 MHz, with a fine frequency resolution of 100 kHz, enabling the investigation of late delays. Our results show that MC effects significantly increase foreground leakage into longer delays, especially for regular station layouts. For 21-cm science, foreground spill-over into the 21-cm window extends beyond k∥~2 h^−1 Mpc for all station layouts and across all k⊥ modes, completely obscuring the detection window. We find that attempting to remove the foreground contribution from the visibilities using an approximated beam model, based on the average embedded element pattern or interpolating the embedded element patterns from a coarse channel rate of 781 kHz, results in residuals around 1% (∼10^11 mK^2 h^−3 Mpc^3) which is still around 7 orders of magnitude brighter than the expected level of the EoR signal (∼10^4 mK^2 h^−3 Mpc^3). We also find that station beam models with at least 4-5 significant digits in the far-field pattern and high spectral resolution are needed for effective foreground removal. Our research provides critical insights into the role of MC in SKA-Low experiments and highlights the computational challenges of fully integrating array patterns that account for MC effects into processing pipelines.