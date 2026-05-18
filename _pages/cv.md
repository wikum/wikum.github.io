---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)](/files/CV_Wikum_Dinalankara.pdf){: .btn .btn--info}

Education
======
* **Ph.D., Computer Science** — University of Maryland, College Park (2015)
  * Dissertation: *"Anti-profile methods for anomaly classification and regression"*
* **B.Sc. (First Class Honours), Computer Science and Engineering** — University of Moratuwa, Sri Lanka (2008)

Work Experience
======
* **Postdoctoral Associate** — Weill Cornell Medicine, Dept. of Pathology and Laboratory Medicine, New York, NY *(Sep 2020 – Present)*
  * ML pipelines for B-cell neoplasm classification from clinical flow cytometry data (CNNs, random forests, UMAP/SOM)
  * Weakly-supervised CLL minimal residual disease detection; pilot deployment on GCP/Vertex AI
  * Tumor immune-microenvironment characterization: identified novel immunosuppressive cytokine Meteorin-like (*Immunity*, 2024)
  * Multi-omic transcriptomic pipelines for prostate cancer, Hodgkin lymphoma, and bladder cancer collaborations

* **Research Fellow** — Johns Hopkins University, Dept. of Oncology, School of Medicine, Baltimore, MD *(Aug 2015 – Aug 2020)*
  * Lead developer of the divergence/anti-profile framework (*PNAS* 2018; *PLOS ONE* 2021)
  * Co-led paired DNA–RNA aberration framework for tumor diversity across TCGA (*PLOS Computational Biology* 2021)
  * Integer-programming approach (Gurobi) for cancer heterogeneity quantification

* **Doctoral Research Assistant** — University of Maryland, Center for Bioinformatics and Computational Biology *(May 2011 – Jul 2015)*
  * Anomaly-detection methods for disease prognosis/diagnosis; kernel methods for anomaly classification

* **Doctoral Research Assistant** — University of Maryland, Maryland Metacognition Lab *(Sep 2009 – Apr 2011)*
  * Reinforcement learning-based meta-cognitive loop simulator for robust intelligent systems

Skills
======
* **Machine Learning & Statistics** — Random Forests, CNNs, SVMs, XGBoost, UMAP, Self-Organizing Maps, Bayesian modeling, weakly-supervised classification
* **Computational Biology** — Multi-omics integration, single-cell analysis, spatial transcriptomics, flow cytometry, NGS, pathway enrichment (KEGG, Reactome, MSigDB), immune-cell-state inference
* **Programming & Infrastructure** — Python (NumPy, pandas, scikit-learn, PyTorch), R/Bioconductor (package author), GCP/Vertex AI, SQL, Linux, Git, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service & Recognition
======
* **Peer review** — *Bioinformatics*; *PLOS Computational Biology*; *ISMB Proceedings*; *Journal of Data and Information Quality*
* **Teaching** — "Statistics and Data Analysis Using R" (JHU, 2019); "Practical Genomics: Biology to Biostatistics" (JHU, 2015–2017)
* **Awards** — Travel Award, Association for Pathology Informatics Summit (2023); Best Poster, JHU Symposium on Genomics & Bioinformatics
* **Memberships** — American Association for Cancer Research (2016–present); Association for Pathology Informatics (2022–2025)
