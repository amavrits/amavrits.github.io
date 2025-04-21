---
layout: single
title: "Subsurface Mapping with CPT using Bayesian GPR"
permalink: /projects/subsurface-cpt-gpr/
---

Cone Penetration Testing (CPT) is a widely-used site investigation technique. The CPT provides measurements of the cone resistance and friction (*q<sub>t</sub>* and *f<sub>s</sub>*) respectively along vertical profiles. This project focused on generating a spatial model that maps the *q<sub>t</sub>* and *f<sub>s</sub>* over a 3D subsoil domain, after training on 6 locations where CPTs are available. To this end, the analysis employed two cross-correlated Gaussian Process Regression (GPR) models, one per variable. Using Bayesian statistics, the analysis inferred the parameters per GPR model and their cross-correlation. Ultimately, the analysis set up a predictive model for generating random fields of the subsoil using the derived posterior distributions and conditioned them on the training CPT measurements. The predictions were then compared to an available testing dataset. Comapred to available benchmarks, the approach was proven to be amongst the most effective and achieved the most meaningful description of uncertainty.  

<img src="/assets/baysic.png" alt="baysic" height="300"/>

**Key Points:**
- Bayesian data analysis
- Gaussian Process Regression
- Co-Kriging

[🔗 View Paper](https://ascelibrary.org/doi/abs/10.1061/AJRUA6.RUENG-975)