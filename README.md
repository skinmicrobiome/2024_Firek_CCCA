# Firek_CCCA_2024

R codes to generate Figure 1A-1C, Figure 2, and eFigure 2. The scripts requires the following files:
* bracken_genus.biom - A biom file generated from the Kraken/Bracken metagenomics classification pipeline. It contains the taxonomic abundance data at the genus level for the analysed samples.
* data_files/all_ccca_data.csv - Contains metadata information for samples analyzed in the study, with each row representing a sample and columns providing various attributes such as subject ID, CCCA severity scale, group ID, sampling site, library ID, and sequencing metrics (e.g., total reads, trimmed reads, human/non-human reads, and unclassified reads percentages).

Figure1.Rmd
* Figure 1A displays a stacked bar plot showing the relative abundance of different taxa across sample sites and cohorts.
* Figure 1B displays a PCoA plot for the vertex scalp site, colored by cohort.
* Figure 1C displays a PCoA plot for the occipital scalp site, colored by cohort.

Figure2.Rmd
* Figure 2A displays boxplots of relative abundances of Corynebacterium for the vertex scalp site, grouped by cohort.
* Figure 2B was generated using the Interactive Tree of Life (iTOL) tool (https://itol.embl.de/) and the dataset file data_files/dataset_heatmap_template.txt.

eFigure2.Rmd
* eFigure 2 displays boxplots of relative abundances of Lawsonella for the vertex scalp site, grouped by cohort.
