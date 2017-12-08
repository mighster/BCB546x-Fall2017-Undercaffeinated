# Undercaffeinated And Underpaid Pipeline Documentation 

###Background Information

The paper we are developing and deploy a pipeline for is [Characterization of Disease Resistance Loci in the USDA Soybean Germplasm Collection Using Genome-Wide Association Studies](https://doi.org/10.1094/PHYTO-01-16-0042-FI). 

Many different pathogens infect soybean. Pathogens can cause large economic losses for farmers and producers. The goal of this paper was to identify SNPs and candidate genes for disease resistance using the USDA Soybean Germplasm Collection. The authors used publically available phenotype and genotype data to conduct the GWAS.  

The diseases that were analyzed in this study were as follows: Bacterial Pustule, Brown Stem Rot, Diaporthe Stem Canker, Frogeye Leaf Spot, Phytophthora Root and Stem Rot, Pythium, Sudden Death Syndrome, Soybean Rust, Reniform Nematode, Soybean Cyst Nematode, Bean Pod Mottle Virus, Peanut Mottle Virus, and Soybean Mosaic Virus.

The author conducted a GWAS on all of the traits above using a package called GAPIT within R. The GWAS was conducted using mixed linear model. The significant SNPs were then used to look for potential candidate genes using SoyBase. 

This would allow for a comprehensive understanding of disease resistance.  

## Data Workflow Pipeline

###Genotypic marker selection

SoySNP50K iSelect BeadChip markers for 19,652 accessions from both Glycine max and Glycine soja were downloaded from SoyBase (soybase.org).  A subset of these, totaling 15,522 Glycine max accessions that were part of historical USDA germplasm characterization trials with size n > 200, were taken for further analysis. The reasoning for this was a sufficient sample size is need to have the power to detect meaning associations. 

###Missing genotype imputation

A data imputation pipeline using the Java implementation of Beagle 4.1 was used to impute missing data for the 42,080 markers which were aligned to the Williams 82 reference genome (v2).  Markers aligned to scaffolds were removed prior to processing.  Ten burn-in iterations and five phasing iterations were used to impute missing markers, which accounted for 0.6423% of all markers.  A total of 36,335 markers remained after using cutoffs of minor allele frequency greater than or equal to 0.05 and missing data less than or equal to 0.05. Using a higher minor allele frequency (MAF for all accessions allowed for simpler analysis. 

The code for imputation in Beagle 4.1 was as follows:

```
java -Xss50m -Xmx61g -jar beagle.08Jun17.d8b.jar gt=soysnp50k_wm82.a1_41317.vcf.gz out=imputed ne=7777

```

###Phenotypic data selection

Physical and chemical data from USDA reports was compiled from the U.S. National Plant Germplasm System website (http://npgsweb.ars-grin.gov/gringlobal/descriptors.aspx, accessed 10/15/2017).  This file was then supplemented with a file detailing which experiment each measurement originated from using (Http://npgsweb.ars-grin.gov/gringlobal/cropdtail.aspx?type=descriptor&id=51, accessed 10/15/2017).  For the traits examined cohorts with n > 200 unique accessions characterized were kept for further analysis.  In total, 15,522 named accessions and varieties were maintained for analysis.  Genotypes which were included in multiple cohorts for the same trait were only analyzed in one cohort in order to minimize any single genotype’s influence on the results.   

###Genome-wide association analysis

Each cohort was analyzed separately to avoid environment-specific effects, which would be expected for several traits.  Analysis was then also performed for combined panels for each trait.  All significant SNPs were compiled for further analysis, using P < 1e-5. 

Markers which were significant for multiple traits, were significant in multiple cohorts, or were identified during analysis of the combined trials were examined for nearby known or candidate genes.  Candidate genes were identified by examining annotated genes in a nearest-first manner from the most significant marker.   

The GWAS was conducted using Mixed Linear Model (MLM). To run the MLM, R version 3.4.1 and the package GAPIT were used to conduct the analysis. 

### R Notebook

A R notebook contains all of the code to load phenotypic and genotypic data and run analysis GWAS. 

### Results

Manhattan plots were created for each of the traits to show the significant SNPs. Our results are very similar to the authors'. The differences are due to the filtering of markers for a different minor allele frequency, population size, or using the second version of the reference genome. The GWAS analysis agree with the authors discovering the same candidate genes except for two using a MAF of 0.05.

Several novel candidate genes were identified compared to Chang et al's analysis due to additional testing performed in our recreation.  Whereas they only analyzed the traits as a sort of meta-GWAS of all experiments for a given trait, we analysed both the combined (across experiments) as well as the individual tests.

There were some races of diseases we didn't run a GWAS, due to small population size of less than 200 individuals. 


### Genotypic Data Disclaimer

The genotypic data was not added to Github due to the file size. It can be downloaded from: 









