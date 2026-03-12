# Plant Rhizosphere 16S Microbiome Analysis

## Objective
Assess how soil treatment affects bacterial diversity.

## Dataset
NCBI SRA:

## Tools
- QC: FastQC, Cutadapt
- ASV Inference: DADA2
- Analysis: phyloseq
- Workflow: Snakemake
- Reporting: Quarto

## Reproducibility
conda env create -f environment.yml
bash run.sh

## Report
View interactive report:
docs/report.html
