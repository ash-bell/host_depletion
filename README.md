# Assessment of the Effectiveness of Host Depletion Techniques for Profiling Fish Skin Microbiomes and Metagenomic Analysis

Ashley G. Bell<sup>a,b*</sup>, Jo Cable<sup>c</sup>, Ben Temperton<sup>a</sup>, Charles R. Tyler<sup>a,b*</sup>

<sup>a</sup> Faculty of Health and Life Sciences, The University of Exeter, Exeter, Devon EX4 4QD, United Kingdom

<sup>b</sup> Sustainable Aquaculture Futures, The University of Exeter, Exeter, Devon EX4 4QD, United Kingdom

<sup>c</sup> School of Biosciences, Cardiff University, Cardiff CF10 3AX, United Kingdom

<sup>*</sup> Corresponding authors

## Publish manuscript
Link TBC

## EBI Project
PRJEB82663

## Abstract
Microbiomes on fish mucosal surfaces play crucial roles in nutrient absorption, immune priming and defence, and disruptions in these microbial communities can lead to adverse health outcomes, including disease. Studying fish microbiomes relies on sequencing microbiota within mucosal-rich samples, however, nucleic acid extraction from these samples is composed predominantly of host DNA, making subsequent bioinformatic processes difficult. Host depletion techniques address this issue by either selectively degrading host DNA before sequencing or retaining bacterial DNA post-extraction. However, their application on fish mucosal samples has been largely unexplored. Here we assessed the efficacy of various host depletion techniques on fish skin mucosal swabs via either selectively removing CpG-methylated (predominantly eukaryotic) DNA or selectively lysing eukaryotic cells before DNA extraction. Surprisingly, none of the existing methods we assessed effectively reduced host DNA to be practically useful. Furthermore, some methods introduced a bias towards certain bacterial taxa, including the Bacilli class and the Proteobacteria phylum. Our findings illustrate that the currently available host depletion techniques are largely ineffective for reducing host DNA in fish mucosal samples. This poses a major limitation for developing an understanding of the functional composition of fish mucosal microbiomes, as enriching microbiota (and excluding host DNA) is fundamental for cost-effective metagenomic studies and facilitating more accurate analyses of the microbiota metabolome and proteome.

## Importance
Microbial communities on fish mucosal surfaces are vital for immune function and disease resistance. However, sequencing these communities is hindered by the dominance of host DNA in mucosal samples, which can exceed 99% of total nucleic acids. While host depletion techniques are routinely used in human and mammalian systems to enrich microbial DNA, their efficacy on fish samples remains uncharacterised.
In this study, we assessed multiple commercial and published host depletion methods on fish skin microbiomes. None significantly reduced host DNA to levels suitable for high-quality metagenomic sequencing, and some introduced taxonomic bias. We suggest methodological reasons, including differences in fish cell structure and mucus composition compared to mammalian systems, that may explain these shortcomings. Based on our findings, we propose protocol modifications and highlight key areas for improvement. This work identifies critical limitations and offers a foundation for developing optimised host depletion strategies tailored to fish mucosal microbiome research.

### Keywords
fish skin, microbiome, host DNA depletion, metagenomics, metagenome-assembled genomes (MAGs), microbial DNA enrichment, microbial community profiling, Oncorhynchus mykiss

## Preprocessing scripts
Preprocessing was identical to that described in https://github.com/ash-bell/fish_skin_antibiotic_exposure. (See Snakemake file)
