# Ecoli-aggregation-RNAseq

This repo hosts all proccesed sequencing data and scripts to generate the figures in the manuscript.

# Contents

## [Data](/Data)
- Figure_2_counts_vst_norm_*.xlsx: normalized counts for ag43 and nanobodies samples used in Figure 2
- *_DEseq_cog.xlsx: differentially expressed genes for UpSet plot Figure 3
- panther_enrich_*.xlsx: output of enriched pathways from Panther (http://www.pantherdb.org/) used in Figures 4,5,6
- [Figure_2_PCA_Metadata.xlsx](Data/Figure_2_PCA_Metadata.xlsx): metadata used to make PCA
- [Figure_S1_Analyze_size_aggregates_MeanOfEachField.xlsx](Data/Figure_S1_Analyze_size_aggregates_MeanOfEachField.xlsx): size of aggregates from microscopy
- [Figure_S2_Amikacin_Resistance.xlsx](Data/Figure_S2_Amikacin_Resistance): CFU counts for antibiotic tolerance assay

## [Figures](/Figures)

Output from scripts as .pdf and .png

## [OutputTables](/OutputTables)

Tables written during scripts

## [Scripts](/Scripts)

All Rmd scripts and html outputs

- [Figure_2.Rmd](/Scripts/Figure_2.Rmd): PCA of normalized transcripts
- [Figure_3.Rmd](/Scripts/Figure_3.Rmd): UpSet plot of DEGs from all comparisons
- [Figure_4_5_6.Rmd](/Scripts/Figure_4_5_6.Rmd): Barplot of enriched pathways, output from PANTHER
- [Figure_S1.Rmd](/Scripts/Figure_S1.Rmd): Raincloud plot of aggregate sizes
- [Figure_S2.Rmd](/Scripts/Figure_S2.Rmd): Boxplots of aggregate tolerance to antibiotic stress
