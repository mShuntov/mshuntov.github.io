---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD in Astrophysics**, Sorbonne Université / Institut d'Astrophysique de Paris, 2019–2022
  * Thesis: *Magnifying the galaxy-halo connection in the Euclid Deep Fields*
  * Funded by École Doctorale 127 & CNES fellowship
* **Master of Physics – Astrophysics**, Aix-Marseille University, 2017–2019
  * GPA: 16.4/20 — AMIDEX scholarship recipient
* **BSc in Theoretical Physics**, Faculty of Natural Sciences and Mathematics, Skopje, North Macedonia, 2013–2017
  * GPA: 8.67/10

Work Experience
======
* **Postdoctoral Researcher / Assistant Professor**, Dec 2022 – present
  * Cosmic DAWN Center, Niels Bohr Institute, University of Copenhagen
  * Lead developer of photometry and morphology pipeline for the COSMOS-Web JWST survey (JWST, HST, Subaru/HSC, VISTA, CFHT)
  * Running LePHARE SED-fitting on ~5 million galaxies over ~20 deg² in the Euclid Deep Field North (H20/Cosmic Dawn Survey)
  * Developed and maintain Python packages for UV luminosity function and halo occupation distribution modelling ([halogal/uvlf-hod](https://github.com/mShuntov/uvlf-hod)) with MCMC fitting and community documentation
  * Built batch-processing pipelines for 700k+ source catalogs; PSFEx PSF modelling across multiple photometric bands (Euclid, HSC, CFHT, Spitzer)
  * Active member of Euclid, COSMOS-Web, FRESCO, and Cosmic Dawn Survey collaborations
  * Co-investigator on Roman Space Telescope Cycle 1 proposals

* **PhD Researcher**, Sep 2019 – Nov 2022
  * Institut d'Astrophysique de Paris, Sorbonne Université
  * Developed original source extraction and multi-band photometric catalog methodology for wide-field imaging surveys
  * Implemented weak gravitational lensing magnification measurements using two-point cross-correlation functions
  * Built MCMC fitting framework for stellar-to-halo mass relation inference
  * Teaching assistant at Université de Paris: Mathematics, Physics and Data Analysis (64 h)

Technical Skills
======
* **Languages**: Python (expert), C, Fortran, Bash, HTML
* **Data pipelines**: End-to-end galaxy catalog production, astronomical image analysis, source extraction
* **Scientific software**: SExtractor, SourceXtractor++, PSFEx, GalSim, LePHARE, CIGALE, eazy, Bagpipes, SWarp, grizli
* **Statistics & ML**: Bayesian inference, MCMC, covariance estimation, halo occupation distribution modelling, ANN/CNN for photometric redshifts
* **HPC**: Computer clusters, MPI, OpenMP, parallelised large-scale batch processing (700k+ source catalogs)
* **Open source**: Author and maintainer of halogal Python package; public data releases with Python notebook tutorials on GitHub

Open Source & Data Releases
======
* **halogal**: Python package for generating model predictions and fitting observables (UVLF, SMF, SFRD, SMD, 2-point correlation functions, stellar-to-halo mass relation). [github.com/mShuntov/uvlf-hod](https://github.com/mShuntov/uvlf-hod)
* **COSMOS2025 galaxy catalog**: Photometry, morphology, redshifts, and physical parameters from JWST, HST, and ground-based imaging. [cosmos2025.iap.fr](https://cosmos2025.iap.fr/)
* **DAWN JWST Archive – Morphologies**: SourceXtractor++ morphological catalogs for 300,000+ galaxies across all major public JWST surveys. [dawn-cph.github.io/dja](https://dawn-cph.github.io/dja/blog/2024/08/16/morphological-data/)
* **COSMOS-Web SMF**: Stellar mass function measurements with Python notebook tutorials. [github.com/mShuntov/SMF_in_COSMOS-Web_Shuntov2024](https://github.com/mShuntov/SMF_in_COSMOS-Web_Shuntov2024)
* **COSMOS2020 SHMR**: Stellar-to-halo mass measurements from COSMOS2020. [github.com/mShuntov/SHMR_COSMOS2020](https://github.com/mShuntov/SHMR_COSMOS2020)

Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Languages
======
* Macedonian: Native
* English: Fluent (C2)
* French: Fluent (C1)
* Danish: Elementary (A2, actively learning)
