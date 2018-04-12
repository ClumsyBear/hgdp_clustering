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

### 1. Identify the population structure 

Use any unsupervised learning algorithm of your choice to identify the hidden cluster structure in the data. For this analysis, use only 900 samples and exclude the 27 samples that are listed in ```clustering.blacklist``` file. Provide the visualization of the cluster structure.

### 2. Determine the number of clusters (K)

Justify your choice of  number of clusters (K) and assign the 900 individuals into the corresponding clusters. Note that K should be no smaller than 3 and no greater than 10. 


### 3. Assign the 27 individuals into the inferred clusters

Use your method of choice to assign the 27 blacklisted individuals for clustering back into the inferred clusters.




