---
layout: default
title: "Research"
---

<div align="center">
<h1>Research</h1>
<p><em>Secular Evolution • Spiral Structure • Simulation as Experiment</em></p>
<hr style="width:40%; border:1px solid #444; margin:1.5rem auto;">
</div>

### Overview

I study how disk galaxies rearrange themselves over time. Stars do not stay where they form. Over billions of years, non-axisymmetric structures like bars and spiral arms redistribute angular momentum through the disk, moving stars far from their birth radii and reshaping the structure they were born into.

My approach is to build simulations as controlled experiments. Cosmological models capture everything at once, which makes them realistic but makes it hard to attribute an outcome to any single mechanism. Idealized N-body models let me change one thing at a time and ask what that change actually does. The aim is to design simulations that can distinguish between competing analytic predictions rather than simply produce a galaxy and describe it.

<hr style="width:60%; border:1px solid #444; margin:1.5rem auto;">

### Angular Momentum Redistribution in Stellar Disks

My primary project examines how the rate of secular evolution depends on the properties of the disk that drives it. By running families of isolated disk models and varying their structural parameters, I look at whether the resulting migration histories can be understood as the same underlying process running at different speeds, and what sets that rate.

This work uses the NEXUS framework, which couples RAMSES, an adaptive mesh refinement code for self-gravitating radiative hydrodynamics, with AGAMA, an action-based library for potential solving and phase-space analysis. Production runs are carried out on OSCER, with custom analysis pipelines in Python parallelized with MPI for multi-snapshot work.

<hr style="width:60%; border:1px solid #444; margin:1.5rem auto;">

### Kinetic Theory of Stellar Disks

Alongside the simulation work, I am developing the analytic side of the same problem. Kinetic theory describes how a stellar disk evolves under the collective fluctuations it generates itself, and it makes concrete predictions about transport rates and the role of resonances. Simulations are where those predictions get tested, and I am interested in the models needed to test them cleanly.

<hr style="width:60%; border:1px solid #444; margin:1.5rem auto;">

### Chemical Signatures of Migration

Stars carry the chemical composition of the gas they formed from, which makes abundances a record of where a star was born. Migration blurs the relationship between a star's chemistry and its present location, so the chemical structure of a disk is one of the few observational handles on dynamical processes that unfold too slowly to watch. I am interested in what the dynamical results above imply for the abundance patterns we measure in the Milky Way and in external disks.

<hr style="width:60%; border:1px solid #444; margin:1.5rem auto;">

### Data-Driven Methods

I came to astrophysics from data science, and I use machine learning where the problem calls for it. My master's work used gradient-boosted trees trained on GALAH data to infer stellar ages directly from chemical abundances, removing the dependence on evolutionary phase that limits isochrone fitting. Reliable ages matter for the dynamical questions above, since a migration history is only recoverable if stars can be ordered in time.

<hr style="width:60%; border:1px solid #444; margin:1.5rem auto;">

### Earlier Work

As an undergraduate I worked with Dr. Xinyu Dai on microlensing magnification maps for the quasar RX J1131-1231, combining Chandra X-ray data with simulations on OSCER to examine how stellar mass fraction, convergence, and shear affect caustic density, contributing to constraints on extragalactic planet-mass objects. I later interned at NASA Ames through OSTEM, building acoustic power maps of solar active regions to probe subsurface flows. Both were my introduction to computational astrophysics and HPC.

<hr style="width:60%; border:1px solid #444; margin:1.5rem auto;">

### Methods and Tools

- **Simulation:** RAMSES, AGAMA, pynbody, yt
- **HPC:** mpi4py, OpenMPI, Slurm, OSCER
- **Analysis:** NumPy, SciPy, h5py, pandas, matplotlib
- **Machine Learning:** XGBoost, scikit-learn, pytorch
