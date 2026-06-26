# RNA-Seq Cancer vs Normal Differential Expression Analysis using DESeq2

## Project Overview

This project demonstrates a complete RNA-seq differential gene expression analysis workflow using **R** and **DESeq2**. The objective is to identify genes that are differentially expressed between **cancer** and **normal** tissue samples using publicly available gene expression data.

The analysis includes data loading, preprocessing, normalization, differential expression analysis, and visualization of results.

---

## Objectives

- Load publicly available gene expression data
- Perform differential gene expression analysis using DESeq2
- Compare cancer and normal samples
- Visualize results using PCA, heatmap, and volcano plot
- Export differential expression results for downstream analysis

---

## Dataset

- **Source:** NCBI Gene Expression Omnibus (GEO)
- **Dataset ID:** GSE10072
- **Study:** Lung Cancer vs Normal Lung Tissue

> Note: This project is intended for learning bioinformatics workflows using publicly available data.

---

## Tools and Packages

- R
- Bioconductor
- DESeq2
- GEOquery
- ggplot2
- pheatmap

---

## Analysis Workflow

1. Install and load required Bioconductor packages
2. Download RNA-seq dataset from GEO
3. Extract expression matrix and sample metadata
4. Define cancer and normal sample groups
5. Create DESeq2 dataset
6. Normalize count data
7. Perform differential expression analysis
8. Generate PCA plot
9. Generate heatmap
10. Generate volcano plot
11. Export differential expression results

---

## Project Structure

```
RNASeq-Cancer-DESeq2-Project/
│
├── scripts/
│   └── rna_seq_analysis.R
│
├── results/
│   ├── deseq2_results.csv
│   ├── volcano_plot.png
│   ├── pca_plot.png
│   └── heatmap.png
│
├── README.md
└── requirements.txt
```

---

## Results

The project produces:

- Differentially expressed genes
- PCA plot showing sample clustering
- Heatmap of gene expression
- Volcano plot highlighting significant genes
- CSV file containing DESeq2 statistical results

---

## Skills Demonstrated

- RNA-seq data analysis
- Differential gene expression analysis
- Bioinformatics workflow development
- Data preprocessing and normalization
- Statistical analysis using DESeq2
- Data visualization in R
- Reproducible research with GitHub

---

## Future Improvements

- Gene Ontology (GO) enrichment analysis
- KEGG pathway analysis
- Functional annotation of significant genes
- Interactive visualizations
- Analysis of additional cancer datasets

---

## Author

**Mehwish**

MPhil Biotechnology | Bioinformatics | Computational Drug Design

GitHub: https://github.com/Mehwish55

---

## License

This project is intended for educational and portfolio purposes using publicly available research data.
