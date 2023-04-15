# *E. coli* aggregation RNAseq with native and synthetic adhesins

This repo hosts all proccesed sequencing data and scripts to generate the figures in the manuscript. The raw sequencing data for this study have been deposited in the European
Nucleotide Archive (ENA) at EMBL-EBI under accession number E-MTAB-11396.

### To cite this work:
Chekli, Y., Stevick, R. J., Kornobis, E., Briolat, V., Ghigo, J. M., & Beloin, C. (2023). Escherichia coli aggregates mediated by native or synthetic adhesins exhibit both core and adhesin-specific transcriptional responses. *Microbiology Spectrum*, e00690-23.


#### This repository has been archived on Zenodo. Access or cite the most recent release:  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7595094.svg)](https://doi.org/10.5281/zenodo.7595094)


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
