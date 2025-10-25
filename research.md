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
I study how stars migrate, mix, and chemically record the dynamical history of the Milky Way — a field known as **galactic archaeology**.

To do this, I use both **hydrodynamical simulations** and **large stellar surveys** to connect theory with observation.  
My long-term goal is to build models that can trace **where stars were born** and **how they evolved** in the context of galactic-scale processes.

---

### Chemodynamical Simulations
I work with the **NEXUS** simulation framework — a hybrid environment that combines:
- **RAMSES**, a grid-based adaptive mesh refinement (AMR) code for solving gravitational and hydrodynamical equations.
- **AGAMA**, an action-based potential solver for dynamical modeling.
- Custom analysis pipelines written in **Python** and parallelized with **MPI** for large-scale, multi-node computation.

Using these simulations, I study:
- Angular momentum evolution and **radial migration** in stellar disks.  
- The diffusion of metallicity gradients over time.  
- How galactic structure (spirals, bars) imprints itself on stellar abundance distributions.

---

### Machine Learning & Data-Driven Stellar Ages
I also use **machine learning** to infer stellar ages from high-resolution spectroscopic data.  
My current project leverages the **GALAH DR4** survey to train gradient-boosted tree models (**XGBoost**) on ~20,000 turn-off stars with Bayesian isochrone ages.

This work aims to:
- Derive **data-driven age estimators** (“chemical clocks”).  
- Explore which **elemental abundances** carry the most predictive power.  
- Compare model-derived ages to simulation-based evolutionary tracks.

Future directions include integrating **gyrochronology constraints**, **uncertainty quantification**, and **physics-informed neural networks** (PINNs) for stellar age inference.

---

### Past Work
Before joining OU, I worked at **NASA Ames Research Center** as part of the **OSTEM Internship Program**, where I developed acoustic power maps of solar active regions to study subsurface flow structures.  
This experience sparked my interest in high-performance computing and large-scale data analysis in astrophysical contexts.

---

### Methods & Tools
- **Simulation Analysis:** `pynbody`, `yt`, `NumPy`, `SciPy`, `h5py`
- **Parallelization & HPC:** `mpi4py`, `OpenMPI`, Slurm job scheduling
- **Machine Learning:** `XGBoost`, `scikit-learn`, `pandas`, `matplotlib`
- **Visualization:** `plotly`, `seaborn`, `matplotlib`, Blender (for 3D renders)

---

<div align="center" style="margin-top:2rem;">
<a href="/projects" style="margin:0 10px; padding:6px 14px; border:1px solid #a989ff; border-radius:6px; color:#a989ff; text-decoration:none; font-weight:600;">View Computational Projects →</a>
</div>
