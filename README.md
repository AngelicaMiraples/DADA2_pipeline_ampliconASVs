# DADA2_pipeline_ampliconASVs

This pipeline is adapted from Dr. Benjamin Callahan to process 16S rRNA reads
This pipeline will processes raw pair-end reads --> run through quality control --> filtering and trimming --> sorting by ASVs --> merge pair-end reads --> remove chimeras -->  assign microbial taxonomy (silva v138) --> explore diversity and relative abundance

You will need: Sequences in FASTAq format (forward and reverse)
Core packages required: DADA2, ggplot2, phyloseq, Biostrings (see Rmd file)

Useful links:
Callahan et al., 2016 https://doi.org/10.1038/nmeth.3869 
Dr. Benji Github page https://github.com/benjjneb/dada2
