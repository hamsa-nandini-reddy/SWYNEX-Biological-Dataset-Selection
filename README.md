
# SWYNEX – Biological Dataset Selection

## Task 1: Public Biological Dataset Documentation

### 1. Project Overview

This project documents a publicly available biological dataset for potential use in bioinformatics and cancer research. The selected dataset is hosted by the National Center for Biotechnology Information (NCBI) through its Gene Expression Omnibus (GEO) repository.

The purpose of this task is to identify a relevant biological dataset, describe its characteristics, formulate a research question, and evaluate its potential scientific usefulness without performing laboratory experiments.

### 2. Dataset Information

- **Dataset title:** In situ multi-modal characterization of pancreatic cancer reveals tumor cell identity as a defining factor of the surrounding microenvironment
- **GEO accession:** GSE282302
- **Repository:** NCBI Gene Expression Omnibus (GEO)
- **Organism:** Homo sapiens (human)
- **Disease:** Pancreatic ductal adenocarcinoma (PDAC)
- **Data type:** Spatial transcriptomics
- **Number of patients:** 39
- **Number of GEO sample records:** 108
- **Data availability:** Public
- **Official dataset URL:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282302

The GEO record describes spatial transcriptomic profiling of pancreatic cancer specimens using the Visium for FFPE platform.

### 3. Background and Biological Significance

Pancreatic ductal adenocarcinoma is an aggressive cancer characterized by biological heterogeneity and a complex tumor microenvironment. Tumor tissue contains malignant cells alongside non-malignant cells, including fibroblasts and immune cells, as well as extracellular structures that can influence tumor behavior.

Traditional bulk gene-expression measurements average signals across many cells and can obscure differences between distinct cellular populations. Spatial transcriptomics helps researchers examine gene-expression patterns while retaining information about where those patterns occur within tissue.

Studying the spatial relationships between tumor cells and neighboring cells may improve our understanding of tumor organization, cellular interactions, and potential mechanisms associated with tumor progression and treatment resistance.

### 4. Dataset Size and Data Characteristics

The official GEO record lists 39 patients and 108 sample records. The study summary reports approximately 340,000 low-bulk and 530,000 single-cell spatial transcriptomes.

The listed supplementary archive, GSE282302_RAW.tar, is approximately 4.9 GB.

These measurements represent different levels of the dataset and should not be treated as equivalent. The archive size refers to a downloadable supplementary file, while the patient and sample counts describe study records.

The data include spatial gene-expression information that can be investigated to understand tumor-cell identity and the surrounding microenvironment.

### 5. Proposed Research Question

**Does the spatial organization of pancreatic cancer cells and their surrounding microenvironment reveal biological patterns that cannot be explained by cell composition alone?**

This question proposes investigating whether the arrangement and local neighborhoods of cells provide information beyond the relative abundance of different cell types.

It is a proposed research direction and has not been experimentally or computationally validated in this project.

### 6. Research Objectives

1. Identify the dataset's biological context, data type, and available records.
2. Understand the value of spatial transcriptomics in studying tumor heterogeneity.
3. Explore how tumor-cell identity and neighboring cell populations may relate to local biological patterns.
4. Establish a foundation for future computational analysis using public genomic data.

### 7. Potential Bioinformatics Applications

The dataset could support future investigations involving:

- Spatial gene-expression pattern analysis.
- Tumor and microenvironment heterogeneity.
- Cellular neighborhood characterization.
- Comparison of spatial patterns across samples.
- Hypothesis generation about tumor–stroma relationships.
- Comparison of spatial findings with independent datasets, where compatible data are available.

These are potential applications, not results produced by the present documentation task.

### 8. Data Source and Access

The dataset is publicly listed in NCBI's Gene Expression Omnibus.

**Official source:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282302

The study record should be consulted for the sample annotations, experimental design, supplementary files, and data-use details before conducting any further analysis.

No laboratory experiments were performed, and no new biological data were generated for this task.

### 9. Limitations and Considerations

- The dataset concerns a specific cancer type and may not represent all pancreatic cancers or other malignancies.
- Patient and sample counts are different; multiple records may relate to the same patient.
- The study design includes specimens resected following neoadjuvant FOLFIRINOX treatment, which must be considered when interpreting biological patterns.
- Spatial gene-expression measurements do not, by themselves, prove causal interactions between cells.
- Technical effects, tissue quality, sampling differences, and platform-specific limitations may affect comparisons.
- Any proposed biological findings would require appropriate computational validation and, where relevant, independent datasets or experimental confirmation.

### 10. Conclusion

GSE282302 is a relevant public resource for exploring the spatial organization of pancreatic cancer and its tumor microenvironment. Its spatial gene-expression data offer opportunities for future bioinformatics investigations of tumor heterogeneity and cellular neighborhoods.

This task establishes a documented starting point for further computational research. No novel biological discovery or validated predictive model is claimed.

### 11. References

1. NCBI Gene Expression Omnibus. GSE282302: In situ multi-modal characterization of pancreatic cancer reveals tumor cell identity as a defining factor of the surrounding microenvironment.
   https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282302

2. National Cancer Institute. Proteogenomic Characterization of Pancreatic Ductal Adenocarcinoma.
   https://gdc.cancer.gov/about-data/publications/CPTAC-3_2021_1

---

**Prepared for:** SWYNEX Internship – Task 1  
**Topic:** Biological Dataset Selection  
**Field:** Biotechnology and Bioinformatics
