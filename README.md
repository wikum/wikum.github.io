# Wikum Dinalankara, Ph.D.

Postdoctoral Associate — Department of Pathology and Laboratory Medicine, Weill Cornell Medicine, New York, NY

[wikumdina@gmail.com](mailto:wikumdina@gmail.com) &nbsp;|&nbsp;
[Google Scholar](https://scholar.google.com/citations?user=T2E7-X4AAAAJ) (h-index 15) &nbsp;|&nbsp;
[GitHub](https://github.com/wikum) &nbsp;|&nbsp;
[LinkedIn](https://www.linkedin.com/in/wikumdinalankara/) &nbsp;|&nbsp;
[Download CV](docs/assets/CV_Wikum_Dinalankara.pdf)

---

## About

Computational scientist focused on personalized prediction and outlier detection in high-dimensional biomedical data. My PhD work introduced anti-profile and divergence methods that frame anomaly detection in omics as deviation from a learned baseline — a per-sample, n-of-1 framework directly applicable to personalized biomarker discovery. Subsequent postdoctoral work spans multi-omics oncology pipelines (genomics, transcriptomics), tumor heterogeneity quantification, and machine-learning pipelines for clinical flow cytometry. Strong publication record (h-index 15), open-source software development, and close collaboration with clinicians and wet-lab biologists.

---

## Skills

**Machine Learning & Statistics** — Random Forests, CNNs, SVMs, XGBoost, Bayesian/probabilistic modeling, dimensionality reduction (UMAP, Self-Organizing Maps), batch-effect correction, weakly-supervised classification

**Computational Biology** — Multi-omics integration, single-cell analysis, spatial transcriptomics, flow cytometry data analysis, next-generation sequencing, pathway enrichment (KEGG, Reactome, MSigDB), immune-cell-state inference

**Programming & Infrastructure** — Python (NumPy, pandas, scikit-learn, PyTorch), R/Bioconductor (package author), GCP/Vertex AI, SQL, Linux, Git, LaTeX

---

## Education

**Doctor of Philosophy, Computer Science** — University of Maryland, College Park, MD (2015)
Dissertation: *"Anti-profile methods for anomaly classification and regression"*

**Bachelor of Science (First Class Honours), Computer Science and Engineering** — University of Moratuwa, Sri Lanka (2008)

---

## Work Experience

**Postdoctoral Associate** — Weill Cornell Medicine, Department of Pathology and Laboratory Medicine, New York, NY *(September 2020 – Present)*

- Built ML pipelines on large clinical flow-cytometry datasets for B-cell neoplasm classification (CNNs, random forests, UMAP/SOM); benchmarked accuracy and resource use across approaches (Cytometry Part B, 2024)
- Developed a weakly-supervised algorithm for CLL minimal residual disease detection combining dimensionality reduction with random-forest classification on weakly-labeled flow data; preparing pilot deployment on GCP/Vertex AI
- Multi-omic transcriptomic pipelines for collaborative oncology studies — Pan Prostate Cancer Group (DNA + RNA integration), Hodgkin lymphoma, bladder cancer
- Tumor immune-microenvironment characterization: comparative RNA-seq of tumor-infiltrating versus circulating lymphocytes led to identification of the novel immunosuppressive cytokine Meteorin-like (Immunity, 2024)
- Mesenchymal-state characterization in prostate cancer progression (Nature Communications, 2024)

**Research Fellow** — Johns Hopkins University, Department of Oncology, School of Medicine, Baltimore, MD *(August 2015 – August 2020)*

- Lead developer of the divergence/anti-profile framework: a rank-based, parameter-free outlier-detection method that converts omics profiles into per-sample binary deviations from a learned normal-tissue baseline (PNAS 2018; PLOS ONE 2021)
- Co-led paired DNA–RNA aberration framework for multi-omic representation of tumor diversity across TCGA cancer types (PLOS Computational Biology, 2021)
- Designed an integer-programming approach (Gurobi) to quantify per-cohort heterogeneity by selecting minimal feature sets that explain observed deviation patterns
- Maintained and extended the kTSP R/Bioconductor package (rank-based, parameter-free classifier)

**Doctoral Research Assistant** — University of Maryland, Center for Bioinformatics and Computational Biology, College Park, MD *(May 2011 – July 2015)*

- Development of anomaly-detection methods for disease prognosis and diagnosis; kernel methods for anomaly classification; utilization of cancer heterogeneity as a marker for disease progression

---

## Projects

### Machine Learning for Flow Cytometry Data Analysis

- Comparative analysis of three algorithms (CNNs, random forests, UMAP/Self-Organizing Maps) for multi-class B-cell neoplasm classification with clinical flow cytometry data; benchmarked classification performance and resource usage. [(Repository — Python)](https://github.com/wikum/flowComparison) | [Publication — Cytometry Part B, 2024]

- Novel weakly-supervised algorithm for CLL minimal residual disease detection; dimensionality reduction combined with random forests for presence/quantification prediction on loosely-labeled flow data; pilot deployment in preparation on GCP. [(Repository — Python)](https://github.com/wikum/CLL_MRD) | [In Review — Cytometry Part B]

### Discovery of Novel Targets for Immunotherapy

- RNA-seq comparison of tumor-infiltrating versus paired circulating lymphocytes from patients with renal cell, bladder, prostate cancer, and glioblastoma; by estimating immune-cold and immune-hot samples, discovered the novel immunosuppressive cytokine Meteorin-like in cancer. [(Repository — R)](https://github.com/wikum/TILsAnalysis) | [Publication — Immunity, 2024]

### Digitization of Omics Data (Divergence)

- Development of a rank-based, parameter-free method for high-dimensional omics analysis that encodes each sample as a binary deviation vector relative to a learned normal-tissue baseline; robust anomaly detection applicable across gene expression, methylation, and other omics modalities. [(Repository — R; Bioconductor)](https://github.com/wikum/divergence) | [Publication — PNAS, 2018] | [R Package — PLOS ONE, 2021]

### Transfer Learning of Gene Interactions Between Omics Modalities

- Ongoing project learning patterns of gene–gene interactions associated with chromatin remodeling in different phenotypes, and transferring inferred mechanistic knowledge to make disease-related predictions in more accessible modalities such as gene expression and methylation.

### Paired Abnormality Analysis

- Method for quantifying heterogeneity in high-dimensional sample populations; integer-programming optimization (Gurobi) finds a minimal, parsimonious set of binary abnormalities characterizing a given cancer population. [(Repository — R; requires Gurobi)](https://github.com/wikum/CoveringAnalysis) | [Publication — PLOS Computational Biology, 2021]

---

## Publications

*For a full list see [Google Scholar](https://scholar.google.com/citations?user=T2E7-X4AAAAJ). \* = co-first author.*

**2024**

1. **Dinalankara W.**, Ng D.P., Marchionni L., Simonson P.D. "Comparison of three machine learning algorithms for classification of B-cell neoplasms using clinical flow cytometry data." *Cytometry Part B: Clinical Cytometry*, 2024.

2. Jackson C.M.\*, Pant A.\*, **Dinalankara W.\***, Saleh L.\*, Nitta R., Zhao L., et al. "The cytokine Meteorin-like inhibits anti-tumor CD8+ T cell responses by disrupting mitochondrial function." *Immunity*, 2024.

3. Pakula H., Omar M., Carelli R., Pederzoli F., Fanelli G.N., …, **Dinalankara W.**, …, Marchionni L., Loda M. "Distinct mesenchymal cell states mediate prostate cancer progression." *Nature Communications*, 2024.

**2023**

4. Omar M., **Dinalankara W.**, Mulder L., Coday T., Zanettini C., Luidy-Imada E., Younes L., Geman D., Marchionni L. "Using biological constraints to improve prediction in precision oncology." *iScience*, 2023.

**2021**

5. Luidy-Imada E., Sanchez D.F., **Dinalankara W.**, Vidotto T., Ebot E.M., Tyekucheva S., et al. "Transcriptional landscape of PTEN loss in primary prostate cancer." *BMC Cancer*, 2021.

6. Zanettini C., Omar M., **Dinalankara W.**, Luidy-Imada E., Colantuoni E., Parmigiani G., Marchionni L. "Influenza vaccination and COVID-19 mortality in the USA: an ecological study." *Vaccines*, 2021.

7. Ke Q.\*, **Dinalankara W.\***, Younes L., Marchionni L., Geman D. "Efficient representations of tumor diversity with paired DNA–RNA aberrations." *PLOS Computational Biology*, 2021.

8. **Dinalankara W.**, Ke Q., Geman D., Marchionni L. "An R package for divergence analysis of omics data." *PLOS ONE*, 2021.

**2020**

9. Baloni P., **Dinalankara W.**, Earls J.C., Knijnenburg T.A., Geman D., Marchionni L., Price N.D. "Identifying personalized metabolic signatures in breast cancer." *Metabolites*, 2020.

10. Imada E., Sanchez D.F., Collado-Torres L., Wilks C., Matam T., **Dinalankara W.**, et al. "Recounting the FANTOM Cage Associated Transcriptome." *Genome Research*, 2020.

**2019**

11. Zennami K., Choi S.M., Liao R., Li Y., **Dinalankara W.**, Marchionni L., et al. "PDCD4 Is an Androgen-Repressed Tumor Suppressor that Regulates Prostate Cancer Growth and Castration Resistance." *Molecular Cancer Research*, 2019.

**2018**

12. Ooki A., **Dinalankara W.**, Marchionni L., Tsay J.J., Goparaju C.M., Maleki Z., et al. "Epigenetically regulated PAX6 drives cancer cells toward a stem-like state via GLI-SOX2 signaling axis in lung adenocarcinoma." *Oncogene*, 2018.

13. **Dinalankara W.\***, Ke Q.\*, Xu Y., Ji L., Pagane N., Lien A., Matam T., Ferting E.J., Price N.D., Younes L., Marchionni L., Geman D. "Digitizing Omics Profiles by Divergence from a Baseline." *PNAS*, 2018.

14. Ooki A., Pena M.D.C.R., Marchionni L., **Dinalankara W.**, Begum A., Hahn N.M., et al. "YAP1 and COX2 Coordinately Regulate Urothelial Cancer Stem-like Cells." *Cancer Research*, 2018.

15. Marchionni L., Hayashi M., Guida E., Ooki A., Munari E., Jabboure F.J., **Dinalankara W.**, et al. "MicroRNA expression profiling of Xp11 renal cell carcinoma." *Human Pathology*, 2018.

**2015**

16. **Dinalankara W.** and Corrada-Bravo H. "Gene Expression Signatures Based on Variability can Robustly Predict Tumor Progression and Prognosis." *Cancer Informatics*, 2015.

**2010 – 2008**

17. Shahri H.H., **Dinalankara W.**, Fults S., Wilson S., Perlis D., et al. "The Metacognitive Loop: An Architecture for Building Robust Intelligent Systems." *AAAI Fall Symposium: Commonsense Knowledge*, 2010.

18. **Dinalankara W.**, De-Silva D., Alahakoon D. "Self Learning and its Implications for Machine Understanding." *ICIAfS*, 2008.

**In Review**

- **Dinalankara W.**, Marchionni L., Simonson P.D. "Automated CLL cell population detection using a weakly supervised approach and CLL MRD flow cytometry data." *Cytometry Part B: Clinical Cytometry*.

---

## Service & Recognition

**Peer Review** — Bioinformatics; PLOS Computational Biology; ISMB Proceedings; Journal of Data and Information Quality

**Teaching**
- Teaching Assistant, "Practical Genomics: From Biology to Biostatistics" annual workshop, Center for Computational Genomics, Johns Hopkins University (2015–2017)
- "Statistics and Data Analysis Using R", Johns Hopkins University (2019)

**Awards**
- Travel Award, Association for Pathology Informatics Summit (2023)
- Best Poster, JHU Symposium on Genomics & Bioinformatics

**Memberships**
- American Association for Cancer Research (2016–present)
- Association for Pathology Informatics (2022–2025)
