# Project 2: Detecting Population Structure from Genetic Data

## Background and Introduction

The primary goal of this project is to apply unsupervised learning algorithms to detect the population structure within the samples using their DNA information. In this case, each sample is represented by 2,540 genetic markers (more precisely, SNPs). Although each marker may have very limited power in clustering, the combination of **all** the markers can potentially improved the performance dramatically. This is also the essential idea of big data. 


## Data Downloading

Download the compressed genotype file ```hgdp.processed.dat.gz```, run the following command to unzip the file (if necessary)

```
gzip -d hgdp.processed.dat.gz
```
The genotype file is in plain text format. It contains genotype information of 927 individuals. Each row represents a single individual with the following simple format

```
Individual_ID  genotype_SNP1  genoype_SNP2 ... genotype_SNP2540
```
The genotypes are coded as the combination of two nucleotides, it is up to you to transform the genotypes into the dosage coding.

## Specific Aims



