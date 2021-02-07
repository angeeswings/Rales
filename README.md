# Rales
### This is the repository for storing annotated scripts for the Rales project.

#### 01-Methyl_seq_analysis:
* Scripts for upstream analysis (QC, trimming, alignment, deduplication, methylation calling, extracting on target CpGs, creating R data objects per sample by chromosome).
* Sub-folder: 12-run_bumphunter - Scripts for downstream bumphunter analysis. 

#### 02-RNA_seq_analysis:
* Scripts for upstream analysis (QC, alignment, featureCounts, featureCounts exon level).
* Scripts for downstream analysis (limma and gene set enrichment analysis).

#### 03-Prediction_models:
* Scripts for predicting bedtime/awakening cortisol with DEGs (p<0.005) and CpGs (p<0.01) by pre-specified (p<0.005) DMR criteria.