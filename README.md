# Foundation Model-Based Discovery of Immune Phenotypes in Cancer Transcriptomes

## Overview

This repository demonstrates a baseline transcriptomic representation learning workflow using dimensionality reduction and clustering methods.

---

## Research Objectives

Generate transcriptomic embeddings.
Identify latent biological clusters.
Visualize transcriptomic structure.
Characterize immune-related phenotypes.

## Project Workflow

![Workflow](images/workflow.png)

---
## OR

TCGA/GTEx RNA-seq
        ↓
Preprocessing
        ↓
RNA Foundation Model
        ↓
Embedding Generation
        ↓
Clustering
        ↓
UMAP Visualisation
        ↓
Immune Phenotype Discovery

---
## Technologies Used

- Python
- Scanpy
- scGPT
- PyTorch
- Single-cell RNA-seq
- TCGA
- UMAP
- Transformer Models
- Computational Immunogenomics

---

## Repository Structure

```text
Foundation-Models-for-Cancer-Immunogenomics/
│
├── notebooks/
│   ├── scGPT_Biological_Representation_Learning.ipynb
│   └── TCGA_Immune_Phenotype_Analysis.ipynb
│
└── README.md
```

---

## Workflow

1. Load transcriptomic datasets
2. Perform preprocessing and normalisation
3. Select highly variable genes
4. Generate biological embeddings using scGPT
5. Construct latent cellular representations
6. Visualise embeddings using UMAP
7. Analyse immune-related phenotypes
8. Explore representation learning in cancer biology

---

## Biological Significance

This project demonstrates how transformer-based foundation models can capture biologically meaningful transcriptomic patterns and transfer learned representations across datasets.

The workflow supports emerging applications in:

- Cancer Immunology
- Precision Oncology
- Single-Cell AI
- Computational Biology
- Biomedical Foundation Models

---

## Key Concepts

- Biological Representation Learning
- Foundation Models for Biology
- Transformer-Based Transcriptomics
- Latent Cellular Embeddings
- Zero-Shot Biological Inference
- Computational Immunogenomics

---

## Future Improvements

- Multi-omics integration
- Spatial transcriptomics analysis
- Survival prediction modeling
- Cell-cell interaction analysis
- Foundation model benchmarking
- Clinical response prediction

---

## Workflow

![Workflow](images/workflow.png)

## Results

### UMAP Visualization

![UMAP](images/UMAP_Transcriptomic_Clusters.png)

### Cluster Distribution

![Cluster Distribution](images/Cluster_Distribution.png)

### Top Gene Drivers

![Heatmap](images/Top_Genes_Heatmap.png)


# Results

## Optimal Cluster Number

Silhouette Analysis selected:

K = 9

Best Silhouette Score = 0.171

## Findings

Nine latent transcriptomic phenotypes were identified.

UMAP demonstrated clear separation between biological clusters.

Several clusters exhibited distinct gene expression signatures,
suggesting potential immune-related heterogeneity.
## Author

Heena Afreen

Bioinformatics | Computational Biology | AI in Genomics | Cancer Immunogenomics


