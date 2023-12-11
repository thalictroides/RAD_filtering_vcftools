# RAD_filtering_vcftools
##Filtering SNPS from ipyrad

This notebook will filter SNPs called from ipyrad (and probably stacks and other RADseq pipelines). The goal of filtering is to reduce individuals with low coverage and missing data and to remove loci that are not biallelic, have too many missing individuals, have very small minor allele frequencies, and lack sufficient sequencing depth. We should can also remove SNPs that are closely linked to other SNPs, this step should be done last in order to ensure that the linked SNP we keep passes our other filtering parameters.

Input files: an unfiltered snp file in vcf format

Output files: a filtered snp file in vcf format

Modules needed: vcftools, gzip
