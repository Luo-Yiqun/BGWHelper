# Performance Tests


## Overview

This folder contains performance tests for BerkeleyGW on different platforms.
<!-- It is originally for the Perlmutter proposal due 4/29/2025. -->


## Scaling Plots

An anthracene unit cell contains 48 atoms, which is a small size for organic crystals.

Anthracene GPU BGW epsilon strong scaling plot:
![Anthracene GPU BGW epsilon strong scaling plot](./ant_epsilon_Perl_vs_Front_vs_Aur.png)

Anthracene GPU BGW sigma strong scaling plot:
![Anthracene GPU BGW sigma strong scaling plot](./ant_sigma_Perl_vs_Front_vs_Aur.png)

Anthracene GPU BGW kernel strong scaling plot:
![Anthracene GPU BGW kernel strong scaling plot](./ant_kernel_Perl_vs_Front_vs_Aur.png)

Anthracene GPU BGW absorption strong scaling plot:
![Anthracene GPU BGW absorption strong scaling plot](./ant_abs_strong.png)


## Running Time
For the table below, Quantum Espresso (QE) is compiled with CPU version, while BerkeleyGW (BGW) is compiled with GPU version.

| Cluster | Number of Atoms | System | QE Node Hours | BGW Node Hours | Notes |
|---------|-----------------|-----------|---------------|----------------|-------|
| Polaris | 29 | 2D TADF | 8.3 | 297 | 55/856 bands, cutoff 20 Ry |
