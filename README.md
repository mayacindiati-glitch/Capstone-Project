# Capstone-Project
Bioinformatics analysis of breast cancer transcriptome using GEO dataset GSE10797 to identify differentially expressed genes and explore Gene Ontology and KEGG pathway enrichment.

# Breast Cancer Transcriptome Analysis (GSE10797)

This capstone project focuses on the bioinformatics analysis of gene expression data related to breast cancer. The analysis aims to identify differentially expressed genes (DEGs) between normal breast stroma and cancer-associated stroma and to understand their biological functions using functional enrichment analysis.

The dataset used in this project is GSE10797, obtained from the Gene Expression Omnibus.

# Objectives

The objectives of this project are:
1. Identify Differentially Expressed Genes (DEGs) between normal stroma and cancer stroma.
2. Explore the biological functions of these genes using Gene Ontology (GO) enrichment analysis.
3. Identify molecular pathways involved in breast cancer progression using KEGG pathway analysis.

# Project Purpose

This project demonstrates how bioinformatics approaches can be used to analyze transcriptomic data and identify molecular mechanisms involved in breast cancer development.

# Tools and Technologies

1. R / RStudio
2. Bioconductor packages
3. GEO2R
4. g:Profiler
5. KEGG Mapper

# Methods

The analysis workflow includes several bioinformatics steps:
1. Dataset exploration from GEO database.

   <img width="924" height="1091" alt="image" src="https://github.com/user-attachments/assets/42adea35-e845-4ed7-b03a-f7db29af2fd0" />

2. Differential gene expression analysis using GEO2R.

   <img width="1874" height="900" alt="image" src="https://github.com/user-attachments/assets/9c1f29fe-f32c-41fa-972a-b10072e1e7f6" />

3. Data visualization using R and Bioconductor including:

   a. Boxplot

   <img width="740" height="443" alt="image" src="https://github.com/user-attachments/assets/c729eabb-3cfe-4e75-a95d-ece759b1a6e3" />

   b. Volcano plot

   <img width="740" height="443" alt="image" src="https://github.com/user-attachments/assets/e484f983-9101-4cb0-8b3d-ac3c1674544d" />

   c. Heatmap

   <img width="667" height="531" alt="image" src="https://github.com/user-attachments/assets/2f708451-f144-49c9-857b-6de8c72836b9" />

4. Functional enrichment analysis using g:Profiler.

   a. up-regulated genes

   <img width="7625" height="6613" alt="gProfiler_hsapiens_2026-03-08_08-57-26" src="https://github.com/user-attachments/assets/38ae9ba8-0adf-4894-b047-0b59013253d3" />

   b. down-regulated genes

   <img width="7625" height="11863" alt="gProfiler_hsapiens_2026-03-08_08-56-17" src="https://github.com/user-attachments/assets/6e8795b7-8ecc-45a6-9ae1-ca0aa7aba60e" />

5. Pathway analysis using KEGG.

   <img width="940" height="896" alt="image" src="https://github.com/user-attachments/assets/a5e44321-9060-46d0-b4b6-e1dda585f2d2" />

   <img width="940" height="559" alt="image" src="https://github.com/user-attachments/assets/53f6f613-0885-425c-b0ad-d67944e08243" />

   <img width="940" height="723" alt="image" src="https://github.com/user-attachments/assets/0fe28a9c-62aa-4e7e-8e7c-e2e4f28a841f" />

   <img width="940" height="689" alt="image" src="https://github.com/user-attachments/assets/977ff3e7-e182-40a0-a716-d9f4079ee870" />

   <img width="940" height="731" alt="image" src="https://github.com/user-attachments/assets/fc5cd483-3f60-466e-9c57-7686e11a7a58" />

   <img width="940" height="697" alt="image" src="https://github.com/user-attachments/assets/7ef1f598-b817-44ae-9fa1-413daf25bdf1" />

# Key Findings

The analysis identified several genes significantly upregulated in breast cancer stroma, including **FN1, POSTN, COL1A2, and COL3A1,** which are associated with extracellular matrix remodeling.

Functional enrichment results suggest that these genes are mainly involved in:
1. Extracellular matrix organization
2. Cell adhesion
3. Cell migration
4. Tumor microenvironment remodeling

KEGG pathway analysis revealed several pathways related to cancer progression, including:
1. ECM-receptor interaction
2. Focal adhesion
3. PI3K-Akt signaling pathway
4. MAPK signaling pathway

<img width="974" height="531" alt="image" src="https://github.com/user-attachments/assets/9cb37d44-276c-4222-9f7b-bfa2418a70e7" />
