# RAD_filtering_vcftools
##Filtering SNPS from ipyrad

This notebook will filter SNPs called from ipyrad (and probably stacks and other RADseq pipelines). The goal of filtering is to reduce individuals with low coverage and missing data and to remove loci that are not biallelic, have too many missing individuals, have very small minor allele frequencies, and lack sufficient sequencing depth. We should can also remove SNPs that are closely linked to other SNPs, this step should be done last in order to ensure that the linked SNP we keep passes our other filtering parameters.

Input files: an unfiltered snp file in vcf format

Output files: a filtered snp file in vcf format

Modules needed: vcftools, gzip


## Step 1. clone this repository:

git clone https://github.com/thalictroides/RAD_filtering_vcftools

## Step 2:  open ddrad_vcftools.ipynb in ondemand

## Step 3:  Set values for your directory and your input file name

## Step 4:  Run the notebook!
This step is a bit more interactive than the last analysis, you should follow allong and may need to make some decisions about changing parameters as you go.

