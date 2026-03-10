---
layout: single
title: "COSMOS2025"
permalink: /cosmos2025/
author_profile: true
toc: true
toc_label: "Contents"
toc_icon: "star"
---

<div class="notice--success" markdown="1">
**COSMOS2025** is the definitive COSMOS-Web galaxy catalog — covering photometry, morphology, photometric redshifts, and physical parameters for over **700,000 galaxies** from JWST, HST, and ground-based data. I led the production of this catalog.
</div>

## What is COSMOS2025?

COSMOS2025 is the official data release of the [COSMOS-Web](https://cosmos.astro.caltech.edu/page/cosmosweb) survey — a 255-hour JWST program covering the COSMOS field, one of the most extensively observed extragalactic survey fields in the sky. The catalog provides a comprehensive multi-wavelength characterization of galaxies across cosmic time, from the local universe out to the epoch of reionization.

The catalog is available at **[cosmos2025.iap.fr](https://cosmos2025.iap.fr)**, hosted at the Institut d'Astrophysique de Paris (IAP).

## Key Facts

| Property | Value |
|---|---|
| **Number of galaxies** | > 700,000 |
| **Survey area** | ~0.54 deg² (NIRCam); ~0.2 deg² (MIRI) |
| **JWST filters** | F115W, F150W, F277W, F444W (NIRCam); F770W (MIRI) |
| **Total photometric bands** | 37 bands from 0.3 to 8 μm |
| **Redshift precision** | σ_MAD = 0.012 at m_F444W < 28 |
| **Redshift range (photo-z)** | 0 < z ≲ 9 |
| **Stellar mass completeness** | ~80% complete at log(M★/M☉) ~ 9 at z ~ 10 |
| **Published in** | *Astronomy & Astrophysics*, Vol. 704, A339 (2025) |

## Data Products

The catalog combines JWST's unprecedented near-infrared depth with an extensive multi-wavelength dataset:

**Photometry** is derived using two complementary techniques: fixed-aperture photometry on space-based bands, and profile-fitting photometry across all 37 bands spanning 0.3–8 μm. This dual approach maximises both precision and completeness.

**Morphology** is characterised for all detected sources using a combination of profile-fitting and machine-learning classification, enabling structural studies of galaxies from the local universe to cosmic dawn.

**Photometric redshifts and physical parameters** — including stellar masses, star formation rates, and non-parametric star formation histories — are derived from spectral energy distribution (SED) fitting. Redshift precision (σ_MAD = 0.012 at m_F444W < 28) represents a factor of ~2 improvement over COSMOS2020 at 26 AB mag.

**Stellar mass completeness** improves by 1 dex in stellar mass compared to COSMOS2020, reaching log(M★/M☉) ~ 7 at z ~ 0.2 and log(M★/M☉) ~ 9 at z ~ 10.

## Why It Matters

COSMOS2025 represents a step-change in our ability to study galaxy formation and evolution across cosmic time. The combination of JWST's infrared sensitivity with the COSMOS field's extensive ancillary data enables:

- Studies of the earliest galaxies at the epoch of reionization (z > 6)
- Precise measurements of the galaxy stellar mass function across a wide redshift baseline
- Accurate characterisation of the galaxy–dark matter halo connection
- Constraints on quenching mechanisms and star formation histories
- A reference catalog for planning future spectroscopic follow-up (e.g. with MOONS, MSE, Roman)

## Paper and Data Access

<div style="margin: 1.5em 0; padding: 1em 1.5em; background: #f8f9fa; border-left: 4px solid #e74c3c; border-radius: 3px;">
  <strong>📄 Paper:</strong> Shuntov et al. (2025) — <em>COSMOS2025: The COSMOS-Web galaxy catalog of photometry, morphology, redshifts, and physical parameters from JWST, HST, and ground-based imaging</em><br>
  <em>A&A</em>, Vol. 704, A339 &nbsp;|&nbsp; <a href="https://doi.org/10.1051/0004-6361/202555799" target="_blank">doi:10.1051/0004-6361/202555799</a> &nbsp;|&nbsp; <a href="https://arxiv.org/abs/2506.03243" target="_blank">arXiv:2506.03243</a>
</div>

<div style="margin: 1.5em 0; padding: 1em 1.5em; background: #f8f9fa; border-left: 4px solid #2980b9; border-radius: 3px;">
  <span style="font-size: 1.2em;">🌐</span> &nbsp;
  <a href="https://cosmos2025.iap.fr" target="_blank" style="font-size: 1.1em; font-weight: 600;">
    cosmos2025.iap.fr
  </a>
  <p style="margin: 0.5em 0 0 0; color: #555;">
    Catalog downloads, documentation, interactive sky viewer, and data release notes.
  </p>
</div>

## My Role

I led the construction of the COSMOS2025 catalog, coordinating the photometric pipeline, SED fitting, and validation across the full 58-person collaboration. This involved:

- Designing and running the multi-band photometric extraction pipeline
- Coordinating photometric redshift and SED fitting across multiple codes
- Leading the validation against spectroscopic samples
- Producing all data products and documentation for the public data release

COSMOS2025 is the successor to [COSMOS2020](https://cosmos.astro.caltech.edu) and will serve as the reference catalog for the COSMOS community for years to come.

---

*For more on my research using this catalog, see the [Publications](/publications/) and [halogal](/halogal/) pages.*
