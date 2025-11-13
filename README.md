# Protein Analysis Demo (R)

A simple R script demonstrating basic protein sequence analysis: amino-acid composition, molecular weight, isoelectric point, hydrophobicity profile, plots, and CSV summary.

## Files
- `protein_analysis_demo.R` — main script
- `protein_summary.csv` — generated summary (after running)
- `hydrophobicity_profile.png` — generated plot
- `aa_composition_barplot.png` — generated plot

## Installation
1. Install R (>= 4.0) and RStudio (recommended).
2. Install required R packages by running the script or manually:

```r
install.packages("Peptides")
install.packages("BiocManager")
BiocManager::install("Biostrings")
