# Comparative Transcriptomic Analysis Identifies Distinct Biological Pathways Underlying Cerebral Malaria and Severe Malarial Anemia

## Project Overview

This capstone project investigates transcriptomic differences between Cerebral Malaria (CM) and Severe Malarial Anemia (SMA) using the public GEO dataset GSE117613.

## Objectives

- Identify differentially expressed genes (DEGs)
- Perform GO enrichment analysis
- Perform KEGG pathway analysis
- Interpret biological mechanisms underlying severe malaria

## Dataset

- GEO Accession: GSE117613
- Platform: Illumina HumanHT-12 V4.0
- Samples:
  - 17 Cerebral Malaria
  - 17 Severe Malarial Anemia

## Bioinformatics Workflow

Data preprocessing
↓

Quality assessment

↓

Differential expression analysis (limma)

↓

GO enrichment

↓

KEGG pathway analysis

↓

Biological interpretation

## Main Results

- 967 significant DEGs
- Autophagy
- Mitophagy
- Erythrocyte homeostasis
- mTOR signaling
- FoxO signaling
- Ferroptosis

## Repository Structure

Capstone-BRSP/
│
├── README.md
├── script.R
│
├── figures/
│   ├── Boxplot.png
│   ├── DensityPlot.png
│   ├── UMAP.png
│   ├── VolcanoPlot.png
│   ├── Heatmap.png
│   ├── GO_BP.png
│   ├── GO_CC.png
│   ├── GO_MF.png
│   └── KEGG.png
│
├── results/
│   ├── DEG_CM_vs_SMA.csv
│   ├── DEG_CM_vs_SMA_ALL.csv
│   ├── GO_BP_CM_vs_SMA.csv
│   ├── GO_CC_CM_vs_SMA.csv
│   ├── GO_MF_CM_vs_SMA.csv
│   └── KEGG_CM_vs_SMA.csv
│
└── report/
    └── Capstone_Report.pdf

## Author

Kiky Martha Ariesaka