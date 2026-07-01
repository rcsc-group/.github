# Radu Cimpeanu Scientific Computing Group

### 💧 Applied Mathematics · Multi-scale · Multi-physics · Computational Fluid Dynamics

[![Warwick Mathematics Institute](https://img.shields.io/badge/Warwick_Mathematics_Institute-University_of_Warwick-6A0DAD?style=flat-square&logo=academia&logoColor=white)](https://warwick.ac.uk/fac/sci/maths)
[![Personal Website](https://img.shields.io/badge/Personal_Website-raducimpeanu.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://www.raducimpeanu.com)
[![Primary Language](https://img.shields.io/badge/Language-Basilisk_C-00599C?style=flat-square&logo=c&logoColor=white)](http://basilisk.fr)
[![License](https://img.shields.io/badge/License-MIT%20%7C%20GPL--3.0-brightgreen?style=flat-square)](https://github.com/rcsc-group)

---

## 🔬 About the Group

We are a computational applied mathematics research group based at the **[Warwick Mathematics Institute](https://warwick.ac.uk/fac/sci/maths)** in the United Kingdom. We focus on *interfaces*, with our work sitting at the intersection of analytical and computational methods, combining **reduced-order modelling**, **asymptotic analysis**, **stability theory** and **direct numerical simulation**, targeting technologically relevant problems across fluid mechanics (involving, you guessed it, *interfaces* arising in physical systems involving droplet, bubble or liquid film dynamics), computational acoustics, and beyond (with quite a few industrial mathematics projects and examples of knowledge exchange). Making physical insight and results arising from complex simulation workflows readily deployable and usable in cross-disciplinary contexts is an important mission of ours.

---

## 🎯 Research Themes

<table>
  <tr>
    <td align="center" width="25%">💧<br><b>Drop impact</b><br><sub>Bouncing · Coalescence · Splashing · Multi-fluid systems</sub></td>
    <td align="center" width="25%">⚡<br><b>Multi-physics flow control</b><br><sub>Electrohydrodynamics · Falling films · Feedback control · Bioreactors</sub></td>
    <td align="center" width="25%">🔊<br><b>Computational acoustics</b><br><sub>Perfectly matched layers · Helmholtz equation · Focused ultrasound</sub></td>
    <td align="center" width="25%">🏭<br><b>Industrial mathematics</b><br><sub>Aircraft anti-icing · Vacuum pumps · Pesticide sprays · Port logistics</sub></td>
  </tr>
</table>

---

## 🛠️ Technical Stack

![Basilisk C](https://img.shields.io/badge/Basilisk_C-DNS_&_VOF-00599C?style=flat-square&logo=c)
![MATLAB](https://img.shields.io/badge/MATLAB-Modelling_&_Postprocessing-0076A8?style=flat-square)
![Python](https://img.shields.io/badge/Python-Analysis_&_Visualisation-3776AB?style=flat-square&logo=python&logoColor=white)
![MPI](https://img.shields.io/badge/MPI-Parallel_HPC-FF6600?style=flat-square)
![ParaView](https://img.shields.io/badge/ParaView-Scientific_Visualisation-4B6EAF?style=flat-square)

**Simulation framework:** [Basilisk C](http://basilisk.fr) — adaptive mesh refinement, volume-of-fluid interface tracking, MPI parallelisation  
**Modelling toolchains:** MATLAB (reduced-order models, asymptotic analysis), Python (post-processing, data workflows)  
**HPC:** Warwick Scientific Computing Research Technology Platform; external allocations at national facilities

---

## 🚀 Featured Repositories

| Repository | Description | Tech | DOI |
|---|---|---|---|
| 💧 [BouncingDroplets](https://github.com/rcsc-group/BouncingDroplets) | DNS of inertio-capillary drop rebound off liquid pools | Basilisk C | [JFM 2023](https://doi.org/10.1017/jfm.2023.88) |
| 💧 [BouncingDropletsMovingPool3D](https://github.com/rcsc-group/BouncingDropletsMovingPool3D) | 3D drop impact in the bouncing regime onto moving pools | Basilisk C | [JFM 2026](https://doi.org/10.1017/jfm.2026.11232) |
| 💧 [SplashingDropletsMovingPool3D](https://github.com/rcsc-group/SplashingDropletsMovingPool3D) | 3D drop impact in the splashing regime | Basilisk C | [JFM 2026](https://doi.org/10.1017/jfm.2026.11586) |
| 💧 [DropImpactViscousPool](https://github.com/rcsc-group/DropImpactViscousPool) | Impact of drops onto pools of a different liquid | Basilisk C | [JCIS 2023](https://doi.org/10.1016/j.jcis.2023.03.040) |
| ⚡ [FallingFilmControlLQR2D](https://github.com/rcsc-group/FallingFilmControlLQR2D) | LQR feedback control of 2D falling liquid films | Basilisk C | [SIAP 2024](https://doi.org/10.1137/23M1548475) |
| 🧫 [BioReactor](https://github.com/rcsc-group/BioReactor) | Rocking wave bioreactor — cultivated meat application | Basilisk C | [IJMF 2025](https://doi.org/10.1016/j.ijmultiphaseflow.2025.105375) |
| 📐 [BouncingDropletsLiquid2D](https://github.com/rcsc-group/BouncingDropletsLiquid2D) | Reduced-dimensional model for 2D drop rebound | MATLAB | [Proc. R. Soc. A 2025](https://doi.org/10.1098/rspa.2024.0956) |

---

## 📚 Recent Publications

1. **Sykes, Alventosa, Castrejon-Pita, Cimpeanu, Harris, Castrejon-Pita** — *Fast droplet impact onto slowly moving deep pools*, J. Fluid Mech. **1037**, A11 (2026). [doi:10.1017/jfm.2026.11586](https://doi.org/10.1017/jfm.2026.11586)
2. **Harris, Alventosa, Sand, Silver, Mohammadi, Sykes, Castrejon-Pita, Cimpeanu** — *Bouncing to coalescence transition for droplet impact onto moving liquid pools*, J. Fluid Mech. **1030**, A16 (2026). [doi:10.1017/jfm.2026.11232](https://doi.org/10.1017/jfm.2026.11232)
3. **Holroyd, Cimpeanu, Gomes** — *Nonlinear estimators for the observation and stabilization of falling liquid films*, Proc. R. Soc. A **481**, 2327 (2025). [doi:10.1098/rspa.2025.0539](https://doi.org/10.1098/rspa.2025.0539)
4. **Gabbard, Agüero, Cimpeanu, Kuehr, Silver, Barotta, Galeano-Rios, Harris** — *Drop rebound at low Weber number*, J. Fluid Mech. **1019**, A25 (2025). [doi:10.1017/jfm.2025.10589](https://doi.org/10.1017/jfm.2025.10589)
5. **Kim, Harris, Cimpeanu** — *Computational modeling of fluid motion in a rocking bioreactor*, Int. J. Multiphase Flow **193**, 105375 (2025). [doi:10.1016/j.ijmultiphaseflow.2025.105375](https://doi.org/10.1016/j.ijmultiphaseflow.2025.105375)

→ **[Full publication list](https://www.raducimpeanu.com/funding-and-output/publications)**

---

## 🤝 Collaborator Network

We work closely with several fantastic experimental and theoretical groups, currently having strong collaborative links with:

| Group | Institution | Shared Focus |
|---|---|---|
| [Harris Lab](https://github.com/harrislab-brown) | Brown University | Drop impact · Bouncing dynamics · Bioreactors |
| [Oxford Fluids Lab](https://github.com/OxfordFluidsLab) | University of Oxford | High-speed impact · Splashing · Coalescence |

---

## 🌟 Sustainable Software Engineering Commitment

For quite a few years we have done our best to release accessible implementations (source code, tutorial, examples) alongside any publications and outputs from the group. We will strive to do so in the future as well. Have a look around and do not hesitate to get in touch with us at conferences, workshops or just by reaching out if you have interesting ideas to extend this space.

---

## 💡 Get Involved

- 🎓 **Prospective PhD/postdoc students:** See [open opportunities](https://www.raducimpeanu.com/supervision) or reach out directly
- 🤝 **Research collaborations:** We welcome contacts from experimental, theoretical, and industrial partners
- 💻 **Code issues / questions:** Just get in touch, either by opening an issue or letting us know. We're pretty friendly!
- 📧 **Contact:** [Radu.Cimpeanu [at] warwick.ac.uk](mailto:Radu.Cimpeanu@warwick.ac.uk) · [LinkedIn](https://www.linkedin.com/in/raducimpeanu/)

