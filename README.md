# Kelvin-Helmholtz Instability with `athena++`

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

Athena++ radiation MHD code modified for Kelvin-Helmholtz Instability (KHI) in a cold stream.

The KHI arises when two distinct fluids meet with opposing flow velocities. A common phenomenom seen on Earth exhibiting KHI is in fluctus cloud
formations that resemble a breaking-wave pattern.

In astrophysical contexts, KHI is ubiquitous. Here I have developed a problem generator using the hydrodynamical fluid simulation code `athena++` to
study KHI in cold streams. The study of KHI arising in cold streams is applicable to accreting cold gas streams in massive halos and Jellyfish galaxy tails in Intracluster medium environments.

Below are Temperature snapshots of 4 simulations with varying cooling and viscosity values.
![](figures/temp_Re.pdf)
