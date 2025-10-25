---
layout: default
title: "Research"
---

<div align="center">

<h1>Research</h1>
<p><em>Galactic Archaeology • Chemodynamical Simulations • Machine Learning</em></p>

<hr style="width:40%; border:1px solid #444; margin:1.5rem auto;">

</div>

### Overview
My research explores the **formation and evolution of disk galaxies** through the combined lenses of stellar dynamics, chemical evolution, and machine learning.  
I study how stars migrate, mix, and chemically record the dynamical history of the Milky Way.

To do this, I use both **chemodynamical simulations** and **large stellar surveys** to connect theory with observation.  
My long-term goal is to build models that can trace **where stars were born** and **how they evolved** in the context of galactic-scale processes.

---

### Chemodynamical Simulations
I work with the **NEXUS** simulation framework — a hybrid environment that combines:
- **RAMSES**, an **adaptive mesh refinement (AMR)** code for solving the equations of **self-gravitating, magnetized, compressible radiative fluid dynamics**.
- **AGAMA**, an action-based potential solver for dynamical modeling and phase-space analysis.
- Custom analysis pipelines written in **Python** and parallelized with **MPI** for large-scale, multi-snapshot computation.

Using these simulations, I study:
- Angular momentum evolution and **radial migration** in stellar disks.  
- The diffusion of metallicity gradients over time.  
- How non-axisymmetric structures like bars, spirals, and transient perturbations shape the disk’s chemodynamical history.

---

### Machine Learning & Data-Driven Stellar Ages
I also use **machine learning** to infer stellar ages from high-resolution spectroscopic data.  
My current project leverages the **GALAH DR4** survey to train gradient-boosted tree models (**XGBoost**) on ~20,000 turn-off stars with Bayesian isochrone ages.

This work aims to:
- Derive **data-driven age estimators** (“chemical clocks”).  
- Identify which **elemental abundances** carry the strongest age sensitivity.  
- Compare model-derived ages to simulation-based evolutionary histories.

Future directions include incorporating **gyrochronology**, **uncertainty calibration**, and **physics-informed neural networks (PINNs)** for stellar age inference.

---

### Past Work
Before joining OU as PhD student, I worked at **NASA Ames Research Center** as part of the **OSTEM Internship Program**, where I developed acoustic power maps of solar active regions to study subsurface flow structures. 
As an undergraduate student, 
This experience sparked my interest in high-performance computing and large-scale data analysis in astrophysical contexts.

---

### Methods & Tools
- **Simulation Analysis:** `pynbody`, `yt`, `NumPy`, `SciPy`, `h5py`
- **Parallelization & HPC:** `mpi4py`, `OpenMPI`, Slurm job scheduling
- **Machine Learning:** `XGBoost`, `scikit-learn`, `pandas`, `matplotlib`
- **Visualization:** `plotly`, `matplotlib`, `seaborn`, Blender (for 3D renders)

---
