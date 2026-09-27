---
permalink: /
title: "AI for Materials Science"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I’m a materials scientist, and my research focuses on using AI to accelerate materials discovery and design, especially for complex metallic alloys such as high-entropy alloys. I use AI not as a black box, but as a way to connect data, physics, and experiments into a coherent design loop for new materials.

## Research Focus

* **Physics-Informed Modeling for Predictive Alloy Design** — My main goal is practical: to predict and optimize key properties—like strength, ductility, or stacking fault energy—when experiments are slow, expensive, or noisy. For that, I build “physics-informed” machine learning workflows: instead of learning only from composition, I encode physically meaningful descriptors and constraints into the models, so the predictions are more robust and easier to interpret.

* **Data-Centric Materials AI** — A big part of my work is also data-centric. I spend a lot of effort curating datasets, checking consistency, and managing uncertainty, because in materials science the data quality often limits the model more than the algorithm itself.

* **Decision-Making: Active Learning and Multi-Objective Optimization** — Finally, I’m interested in decision-making tools: active learning to choose the next best experiments, and multi-objective optimization to balance performance with constraints like cost, sustainability, or compositional robustness.

## Research Themes & Selected Work

### **AI-Guided Functional Materials**
This emerging research line is developed in collaboration with Prof. Zheng Liu (Nanyang Technological University, Singapore) and Prof. Gian-Marco Rignanese (UCLouvain, Belgium), extending my AI-for-materials work toward functional materials for energy and catalysis. We combine curated experimental data, materials descriptors, probabilistic machine learning and active learning to map complex design spaces and guide targeted experiments.
A first outcome of the NTU collaboration is a curated experimental dataset and uncertainty-aware machine-learning framework for the exploration of multinary alloy catalysts for the hydrogen evolution reaction (HER).

- S. Gorsse, B. Tang, Y. Tang, M. Ma and Z. Liu,  
  *Curated dataset of multinary alloy HER catalysts for composition-only modelling with Magpie descriptors and GP baselines*,  
  **Scientific Data** (2026).  
  [DOI: 10.1038/s41597-026-07856-2](https://doi.org/10.1038/s41597-026-07856-2)

### **AI-Driven Design of High-Temperature Structural Alloys**
In this line of work, developed in collaboration with Prof. A.-C. Yeh (National Tsing Hua University, Taiwan), we combine physical metallurgy, CALPHAD-based thermodynamics and physics-informed, AI-driven exploration to design and assess high-temperature structural alloys, including HEAs and CCAs, for extreme-environment technologies.

- W.-C. Lin, S. Gorsse, A.-C. Yeh,  
  *Machine-Learning-Assisted Multi-Objective Screening of Hardness and Oxidation Resistance in Refractory High-Entropy Alloys*,  

- W.-C. Lin, S. Gorsse, A.-C. Yeh,  
  *Dataset of oxidation properties of refractory alloys*,  
  **Data in Brief** 68 (2026) 113105.  
  [DOI: 10.1016/j.dib.2026.113105](https://doi.org/10.1016/j.dib.2026.113105)

- S. Gorsse et al.  
  *Advancing refractory high entropy alloy development with AI-predictive models for high temperature oxidation resistance*,  
  **Scripta Materialia** 255 (2025) 116394.  
  [DOI: 10.1016/j.scriptamat.2024.116394](https://doi.org/10.1016/j.scriptamat.2024.116394)

- **PRISM — a reusable physics-informed foundation for refractory-alloy property prediction**, with a manuscript in preparation. The **Physics-Resolved Inference & Stacking Model (PRISM)** decomposes theoretical laws into mechanistic descriptors and combines them with AI to predict high-temperature yield strength and room-temperature ductility in refractory alloys, including HEAs, with a framework designed to extend to additional properties and alloy chemistries.

### **Sustainability-Informed Alloy Design with AI**
Developed in close collaboration with Prof. M. R. Barnett (Deakin University, Australia), this work integrates economic, environmental and societal criteria into AI-guided high-entropy alloy design through quantitative indicators, open datasets and decision frameworks. We also developed an **open-source tool** that evaluates nine sustainability footprints and benchmarks new alloy compositions against HEAs/CCAs and commercial alloys.
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://alloy-sustainability-calculator-sg.streamlit.app/)

- M.R. Barnett and S. Gorsse,  
  *Sustainability of High Entropy Alloys and Do They Have a Place in a Circular Economy?*,  
  **Metallurgical and Materials Transactions A** 56 (2025) 4249.  
  [DOI: 10.1007/s11661-025-07928-9](https://doi.org/10.1007/s11661-025-07928-9)
  
- S. Gorsse, T. Langlois, A.-C. Yeh and M.R. Barnett,  
  *Sustainability indicators in high entropy alloy design: an economic, environmental, and societal database*,  
  **Scientific Data** 12 (2025) 288.  
  [DOI: 10.1038/s41597-025-04568-x](https://doi.org/10.1038/s41597-025-04568-x)
  
- S. Gorsse, T. Langlois, and M.R. Barnett,  
  *Considering sustainability when searching for new high entropy alloys*,  
  **Sustainable Materials and Technologies** 40 (2024) e00938.  
  [DOI: 10.1016/j.susmat.2024.e00938](https://doi.org/10.1016/j.susmat.2024.e00938)

### **High Entropy Alloys & Complex Concentrated Alloys**
In a long-standing collaboration with Dr D. B. Miracle and colleagues at the Air Force Research Laboratory (AFRL, USA), we have mapped the landscape of high-entropy and complex concentrated alloys, quantified their high-temperature performance, built open mechanical-property datasets, and more recently benchmarked HEAs against commercial alloys to identify genuinely unexplored composition spaces for future alloy design.

- D B. Miracle ans S. Gorsse 
  *Commercial Alloy Compositions Through a High-Entropy Lens*,  
  **JMR** (2026)
  
- O. N. Senkov, S. Gorsse, D. B. Miracle, S. I. Rao, T. M. Butler,  
  *Correlations to improve high-temperature strength and room-temperature ductility of refractory complex concentrated alloys*,  
  **Materials & Design** 239 (2024) 112762.  
  [DOI: 10.1016/j.matdes.2024.112762](https://doi.org/10.1016/j.matdes.2024.112762)

- C. K. H. Borg, C. Frey, J. Moh, T. M. Pollock, S. Gorsse, D. B. Miracle,  
  O. N. Senkov, B. Meredig, J. E. Saal,  
  *Expanded dataset of mechanical properties and observed phases of multi-principal element alloys*,  
  **Scientific Data** 7 (2020) 430.  
  [DOI: 10.1038/s41597-020-00768-9](https://doi.org/10.1038/s41597-020-00768-9)

- S. Gorsse, D. B. Miracle, O. N. Senkov,  
  *Mapping the world of complex concentrated alloys*,  
  **Acta Materialia** 135 (2017) 177–187.  
  [DOI:10.1016/j.actamat.2017.06.027](https://doi.org/10.1016/j.actamat.2017.06.027)
  
### **Thermodynamics-Guided Design of HEAs & CCAs**
In collaboration with Prof. Rajarshi Banerjee (University of North Texas, USA), this work combines thermodynamic reasoning, advanced microscopy and alloy processing to design high-entropy and complex concentrated alloys with controlled chemical ordering and tailored properties. The focus is on linking local atomic order, phase transformations and additive-manufacturing pathways to mechanical and functional performance.

- S. Dasari et al.,  
  *Exceptional enhancement of mechanical properties in high-entropy alloys via thermodynamically guided local chemical ordering*,  
  **Proceedings of the National Academy of Sciences** 120 (2023) e2211787120.  
  [DOI: 10.1073/pnas.2211787120](https://doi.org/10.1073/pnas.2211787120)

- S. Dasari et al.,  
  *Tuning the degree of chemical ordering in the solid solution of a complex concentrated alloy and its impact on mechanical properties*,  
  **Acta Materialia** 212 (2021) 116938.  
  [DOI: 10.1016/j.actamat.2021.116938](https://doi.org/10.1016/j.actamat.2021.116938)


## Current Research Programs & Collaborations

- **PEPR DIADEM – ADVANCE** — AI-guided discovery of low-dimensional high-entropy alloys for catalysis.
- **SusMatEner (MSCA Doctoral Network)** — sustainable materials-by-design for renewable-energy applications.
- **IRP PI-AID (CNRS–NTHU–Deakin)** — physics-integrated AI, sustainability-by-design and high-throughput experimentation for alloy design.


## Open Data & Tools


## Academic Positions and International Appointments

I am a professor of materials science at the Institute for Condensed Matter Chemistry of Bordeaux (ICMCB, CNRS) and Bordeaux INP in France, which I joined in 2001. Since September 2025, I have been based in Singapore as an **Adjunct Senior Researcher at Nanyang Technological University (NTU)**, within CINTRA, working on AI-guided design of advanced materials. Since 2020, I have also held an **Honor Chair Professorship** at National Tsing Hua University (Taiwan).

I have built a sustained international research profile, with **120+ peer-reviewed journal publications** and around **50 invited talks** at conferences and universities. I have coordinated or led multiple **EU-funded, national, and industry-partnered projects**, and in 2018 I received the **Constellium Prize of the French Academy of Sciences** for contributions to metallurgy.


