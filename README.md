# Wikum Dinalankara, Ph.D.
Postdoctoral Associate, Weill Cornell Medical College

#### Machine Learning | Omics | Computational Biology 

## Education
Computer Science, Ph.D.
University of Maryland, College Park

## Work Experience
Postdoctoral Associate, Department of Pathology and Laboratory Medicine, Weill Cornell Medicine, New York, NY

Research Fellow, Johns Hopkins School of Medicine, Baltimore, MD

## Projects
### Machine learning for flowcytometry data analysis
•	Comparative analysis of three available algorithms for multi-class disease type prediction with flow cytometry data; the methods compared use convolutional neural networks, random forests, and multiple dimensionality reduction tools (UMAP, Self-Organizing Maps). These methods were obtained from existing code or implemented, and benchmarked in terms of classification performance and resource usage. [(Repository | Python)](https://github.com/wikum/flowComparison)

•	Design and implementation of a novel algorithm for residual disease prediction with loosely labeled flow cytometry data; the algorithm uses dimensionality reduction in conjunction with a random forests to predict the presence of remaining disease and perform quantification (regression). The method is currently being prepared for a pilot clinical test deployment using google cloud platform (GCP). [(Repository | Python)](<https://github.com/wikum/CLL_MRD>)

### Discovery of novel targets for immunotherapy
•	In this project, we examined gene expression data from RNA sequencing experiments that compared tumor infiltrating lymphocytes with paired circulating lymphocytes from patients with renal cell, bladder cancer, prostate cancer, and glioblastoma. By estimating putative immune-cold and immune-hot samples, we were able to discover a novel immunosuppressive cytokine in cancer. [(Repository | R)](https://github.com/wikum/TILsAnalysis)

### Transfer learning of gene interactions between omics modalities
•	This is an ongoing project in which we are attempting to learn patterns of gene-gene interactions associated with chromatin re-modeling in different phenotypes and transfer this inferred mechanistic knowledge to make disease related predictions in more easily available modalities such as gene expression and methylation.

### Digitization of omics data
•	Development of a novel method for high dimensional omics data analysis (such as gene expression or methylation); our method, termed ‘divergence’ attempts to produce a boundary around a given baseline cohort, with respect to which the anomaly status of a novel sample can be indicated as a binary variable. The method works in rank space and is robust in its applicability as an anomaly detection method. [(Repository | R - Bioconductor)](https://github.com/wikum/divergence)

### Paired abnormality analysis
•	Design of a method for quantifying heterogeneity in different sample populations of high dimensional data. Abnormalities in samples are represented in a binary form which can then be assessed with integer programming optimization (implemented through Gurobi) to find a minimal set that provides a parsimonious representative set of abnormalities that characterize a given population; applied to assess heterogeneity in different cancer populations. [(Repository | R; requires Gurobi for optimization)](https://github.com/wikum/CoveringAnalysis)


For a full list of publications, see [Google Scholar: Wikum Dinalankara](https://scholar.google.com/citations?user=T2E7-X4AAAAJ)

