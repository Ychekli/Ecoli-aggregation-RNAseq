# Ecoli-aggregation-RNAseq

This repo hosts all proccesed sequencing data and scripts to generate the figures in the manuscript.

# Contents

## [Data](/Data)
- panther_enrich_*.xlsx: output of enriched pathways from Panther (http://www.pantherdb.org/)
- [Figure_2_PCA_Metadata.xlsx](Data/Figure_2_PCA_Metadata.xlsx): metadata used to make PCA
- Figure_2_counts_vst_norm_*.xlsx: normalized counts for ag43 and nanobodies samples
- Figure_S1.xlsx: CFU counts for antibiotic tolerance assay
- *_DEseq_cog.xlsx: 
- [Figure_S2_Analyze_size_aggregates_MeanOfEachField.xlsx](Data/Figure_S2_Analyze_size_aggregates_MeanOfEachField.xlsx): size of aggregates from microscopy


## [Figures](/Figures)

Output from scripts

## [OutputTables](/OutputTables)

Tables written during scripts

## [Scripts](/Scripts)

All Rmd scripts and html outputs

- [Figure_2.Rmd](/Scripts/Figure_2.Rmd): PCA of normalized transcripts
- [Figure_3.Rmd](/Scripts/Figure_3.Rmd): UpSet plot of DEGs from all comparisons
- [Figure_4_5_6.Rmd](/Scripts/Figure_4_5_6.Rmd): Barplot of enriched pathways, output from PANTHER
- [Figure_S1.Rmd](/Scripts/Figure_S1.Rmd): Boxplot of aggregate tolerance to antibiotic stress
- [Figure_S2.Rmd](/Scripts/Figure_S2.Rmd): Raincloud plot of aggregate sizes
