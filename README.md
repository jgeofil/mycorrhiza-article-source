# Mycorrhiza: genotype assignment using phylogenetic networks
Jeremy Georges-Filteau,  Richard C Hamelin,  Mathieu Blanchette
Bioinformatics, Volume 36, Issue 1, 1 January 2020, Pages 212–220, https://doi.org/10.1093/bioinformatics/btz476
Published: 14 June 2019

## Abstract
Motivation
The genotype assignment problem consists of predicting, from the genotype of an individual, which of a known set of populations it originated from. The problem arises in a variety of contexts, including wildlife forensics, invasive species detection and biodiversity monitoring. Existing approaches perform well under ideal conditions but are sensitive to a variety of common violations of the assumptions they rely on.

## Results
In this article, we introduce Mycorrhiza, a machine learning approach for the genotype assignment problem. Our algorithm makes use of phylogenetic networks to engineer features that encode the evolutionary relationships among samples. Those features are then used as input to a Random Forests classifier. The classification accuracy was assessed on multiple published empirical SNP, microsatellite or consensus sequence datasets with wide ranges of size, geographical distribution and population structure and on simulated datasets. It compared favorably against widely used assessment tests or mixture analysis methods such as STRUCTURE and Admixture, and against another machine-learning based approach using principal component analysis for dimensionality reduction. Mycorrhiza yields particularly significant gains on datasets with a large average fixation index (FST) or deviation from the Hardy-Weinberg equilibrium. Moreover, the phylogenetic network approach estimates mixture proportions with good accuracy.

## Availability and implementation
Mycorrhiza is released as an easy to use open-source python package at https://github.com/jgeofil/mycorrhiza.

## Supplementary information
Supplementary data are available at Bioinformatics online.

© The Author(s) 2019. Published by Oxford University Press. All rights reserved.
