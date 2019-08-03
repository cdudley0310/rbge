# Phylogeny of the Angiosperms of Brazil

This repository contains the data and analysis I performed as part of the [*Nordeste* project](https://gtr.ukri.org/projects?ref=NE%2FN01247X%2F1) while volunteering at the Royal Botanic Garden Edinburgh.

# Important Data in this Repository

## Data

* nordeste.csv –– species data, including data on lifeform, phytogeographic domain, which administrative state it is found, and more
* phylogeny.rmd –– RMD script for semi-automated phylogeny building (also see phylogeny.pdf and phylogeny.html)
* phylo_stats.rmd –– RMD script of basic summary statistics regarding the phylogeny created using the methods detailed in phylogeny.rmd (also see phylo_stats.pdf and phylo_stats.html)
* alignment_table.csv –– CSV containing data on the sequences used in the supermatrix
* missing.csv –– CSV containing the species for which no useable sequences were found for the genes of interest
* RBGE.Rproj –– project environment for both phylogeny.rmd and phylo_stats.rmd

## Results

* alignments/combined_alignment/final_combined_alignment –– supermatrix alignment used for building the final tree
* trees/combined_tree.tree –– tree file containing the final phylogeny
