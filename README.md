# Base resolution maps reveal the importance of 5-hydroxymethylcytosine in a human glioblastoma

This repository contains a description of the bioinformatics methods associated to the [manuscript](http://www.nature.com/articles/s41525-017-0007-6?WT.feed_name=subjects_molecular-biology).

Summary details about the analyses are given in the following files:

- [DNA sequencing](dnaseq_processing.md "dnaseq_processing.md"): alignment, variation and tumour purity
- [Bisulfite sequencing](bsseq_processing.md "bsseq_processing.md"): processing and alignment, methylation counting and 5mC/5hmC levels
- [RNA sequencing](rnaseq_processing.md "rnaseq_processing.md"): transcript alignment, quantification and levels

The scripts written during the development of the project are available in [20150501_methylation_brain/](20150501_methylation_brain/).

A bayesian approach to estimate 5mC/5hmC is available in [20160727_bayes_fisher_sim](20160727_bayes_fisher_sim/).

An exploration of the levels of 5mC/5hmC in gene bodies ia available in [20170425_genebody_5hmC](20170425_genebody_5hmC/).
