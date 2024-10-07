---
title: "Pseudospectral Time-Domain Method in EM Simulation"
collection: talks
type: "Talk"
permalink: /talks/pstd_intro
venue: "National Taiwan University"
# date: 2012-03-01
excerpt: "The pseudospectral time-domain (PSTD) method is a numerical technique used in electromagnetic simulations, offering high accuracy with fewer grid points compared to traditional methods like the finite-difference time-domain (FDTD) method."
location: "Taipei, Taiwan"
slidesurl: 'http://jake-w-liu.github.io/files/PSTD_Intro.pdf'
---


The pseudospectral time-domain (PSTD) method is a numerical technique used in electromagnetic simulations, offering high accuracy with fewer grid points compared to traditional methods like the finite-difference time-domain (FDTD) method. PSTD utilizes Fourier transforms to compute spatial derivatives, allowing it to model wave propagation with just two cells per wavelength. This presentation outlines the fundamental principles of PSTD, discusses its implementation challenges, including handling field discontinuities and source conditions, and compares it with FDTD. The advantages of PSTD, such as computational efficiency, are demonstrated alongside its limitations in dealing with complex geometries and high-contrast materials.