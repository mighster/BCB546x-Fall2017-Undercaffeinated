# Documenation of files and file structure for EEOB 546X Final Project 

__Chang, Lipka, Domier, Hartman-2016.md__ - Contains the documentation of the background information about the paper, pipeline 

__Undercaffeinated And Underpaid Final Project - R Notebook.Rmd__ - Contains the R script to load, run, and export the GWAS analysis. 

__Signifcant SNPs GWAS.xlsx__ - Contains all of the signifcant SNPs across all diseases and tests.

__Characterization of Disease Resistance Loci in the USDA Soybean Germplasm Collection using GWAS.pptx__ - Contains a presentation of background of paper used for analysis, workflow, comparison of results, and success and failures of the project. 


All of the disease were abbreviated to simplify the file names during the analysis. Below we have added a list of all of the disease abbreviations. In all of files that contain abbrevations, the naming follows the disease abbreviation followed by the test number from the USDA.  

Below is a list of all of the disease abbreviations:

* BP - Bacterial Pustule
* BSR - Brown Stem Rot
* BSRCode  - Brown Stem Rot Code - Coverted to Numerical
* CHLOROSIS - Iron Deficiency Chlorosis
* CRDR - Charcoal Rot Rating
* CRDS - Charcoal Rot Severity
* PMV - Peanut Mottle Virus
* FE026 - Frogeye Leaf Spot Rating 0-6 
* FE2 - Frogeye Leaf Spot Race 2
* FE32Perc - Frogeye Leaf Spot Percentage - 1/32 inch or larger
* NSC - Northern Stem Canker
* PPR1 - Phytophthora Root and Stem Rot Race 1
* PPR2 - Phytophthora Root and Stem Rot Race 2
* PPR3 - Phytophthora Root and Stem Rot Race 3
* PPR4 - Phytophthora Root and Stem Rot Race 4
* PPR5 - Phytophthora Root and Stem Rot Race 5
* PPR7 - Phytophthora Root and Stem Rot Race 7
* PPR10 - Phytophthora Root and Stem Rot Race 10
* PPR12 - Phytophthora Root and Stem Rot Race 12
* PPR17 - Phytophthora Root and Stem Rot Race 17
* PPR20 - Phytophthora Root and Stem Rot Race 20
* PPR25 - Phytophthora Root and Stem Rot Race 25
* PPR30T - Phytophthora Root and Stem Rot Race 30T
* PYU - Pythium Root Rot
* RUST - Soybean Rust
* SALT - Salt Tolerance
* SCN1 - Soybean Cyst Nematode Race 1
* SCN1FI - Soybean Cyst Nematode Race 1 Female Index
* SCN2 - Soybean Cyst Nematode Race 2
* SCN3 - Soybean Cyst Nematode Race 3
* SCN3FI - Soybean Cyst Nematode Race 3 Female Index
* SCN3Code - Soybean Cyst Nematode Race 3 Code - Converted to Numerical 
* SCN5 - Soybean Cyst Nematode Race 5
* SCN5FI - Soybean Cyst Nematode Race 5 Female Index
* SCN5Code - Soybean Cyst Nematode Race 5 Code - Converted to Numerical
* SCN14 - Soybean Cyst Nematode Race 14 
* SDS - Sudden Death Syndrome
* SMVG1 - Soybean Mosaic Virus Strain G1
* SMVG2 - Soybean Mosaic Virus Strain G2
* SMVG6 - Soybean Mosaic Virus Strain G6
* SMVG7 - Soybean Mosaic Virus Strain G7

## Phenotype Files

The Phenotype Files folder contains all of the files for data analysis. The disease abbreviations for the phenotype files are listed above.  

Below is a list of the __Phenotype__ files:

* CHLOROSIS.csv
* Fe026.csv
* Fe2.10001.csv
* Fe2.10002.csv
* Fe2.10003.csv
* Fe2.10004.csv
* Fe2.csv
* Fe32perc.csv
* NSC.491493.csv
* NSC.csv
* PRR1.10001.csv
* PRR1.10002.csv
* PRR1.10003.csv
* PRR1.10004.csv
* PRR1.11002.csv
* PRR1.11003.csv
* PRR1.461592.csv
* PRR1.488001.csv
* PRR1.492577.csv
* PRR1.492990.csv
* PRR1.csv
* PRR10.csv
* PRR12.csv
* PRR17.491404.csv
* PRR17.492448.csv
* PRR17.492990.csv
* PRR17.csv
* PRR2.csv
* PRR20.csv
* PRR25.491404.csv
* PRR25.491592.csv
* PRR25.492488.csv
* PRR25.492990.csv
* PRR25.csv
* PRR3.491592.csv
* PRR3.492577.csv
* PRR3.492578.csv
* PRR3.492990.csv
* PRR3.csv
* PRR30T.csv
* PRR4.492758.csv
* PRR4.492990.csv
* PRR4.csv
* PRR5.492990.csv
* PRR5.csv
* PRR7.491404.csv
* PRR7.491592.csv
* PRR7.492448.csv
* PRR7.492990.csv
* PRR7.csv
* PYU.11002.csv
* PYU.11003.csv
* PYU.csv
* RUST.csv
* SCN1.494409.csv
* SCN1.csv
* SCN14.491576.csv
* SCN14.491577.csv
* SCN14.csv
* SCN1FI.494409.csv
* SCN1FI.csv
* SCN2.csv
* SCN2FI.csv
* SCN3.491576.csv
* SCN3.491577.csv
* SCN3.492579.csv
* SCN3.83.csv
* SCN3.csv
* SCN3FI.csv
* SCN3code.83.csv
* SCN3code.csv
* SCN4.492579.csv
* SCN4.83.csv
* SCN4.csv
* SCN5.491576.csv
* SCN5.491577.csv
* SCN5.83.csv
* SCN5.csv
* SCN5FI.csv
* SCN5code.csv
* SDS.493025.csv
* SDS.493026.csv
* SDS.csv
* SMVG1.csv
* SMVG3.csv
* SMVG6.csv
* SMVG7.csv
* bp488001.csv
* bpmvall.csv
* bsr491584.csv
* bsrall.csv
* bsrcode491584.csv
* bsrcode492477.csv
* bsrcodeall.csv
* crdr.csv
* crds.csv
* pmv.csv
* saltreact.csv

## Results

The Results folder contains all of the results from GWAS analysis. The disease abbreviations for the results files are listed above. 

Below is a list of all of this __Results__ files:

* GAPIT..CHLOROSIS.GWAS.Results.csv
* GAPIT..Fe026.GWAS.Results.csv
* GAPIT..Fe2.10001.GWAS.Results.csv
* GAPIT..Fe2.10002.GWAS.Results.csv
* GAPIT..Fe2.10003.GWAS.Results.csv
* GAPIT..Fe2.10004.GWAS.Results.csv
* GAPIT..Fe2.GWAS.Results.csv
* GAPIT..Fe32perc.GWAS.Results.csv
* GAPIT..NSC.491493.GWAS.Results.csv
* GAPIT..PRR1.10001.GWAS.Results.csv
* GAPIT..PRR1.10002.GWAS.Results.csv
* GAPIT..PRR1.10003.GWAS.Results.csv
* GAPIT..PRR1.10004.GWAS.Results.csv
* GAPIT..PRR1.11002.GWAS.Results.csv
* GAPIT..PRR1.11003.GWAS.Results.csv
* GAPIT..PRR1.461592.GWAS.Results.csv
* GAPIT..PRR1.488001.GWAS.Results.csv
* GAPIT..PRR1.492577.GWAS.Results.csv
* GAPIT..PRR1.492990.GWAS.Results.csv
* GAPIT..PRR1.GWAS.Results.csv
* GAPIT..PRR10.GWAS.Results.csv
* GAPIT..PRR12.GWAS.Results.csv
* GAPIT..PRR17.491404.GWAS.Results.csv
* GAPIT..PRR17.492448.GWAS.Results.csv
* GAPIT..PRR17.492990.GWAS.Results.csv
* GAPIT..PRR17.GWAS.Results.csv
* GAPIT..PRR2.GWAS.Results.csv
* GAPIT..PRR20.GWAS.Results.csv
* GAPIT..PRR25.491404.GWAS.Results.csv
* GAPIT..PRR25.491592.GWAS.Results.csv
* GAPIT..PRR25.492488.GWAS.Results.csv
* GAPIT..PRR25.492990.GWAS.Results.csv
* GAPIT..PRR25.GWAS.Results.csv
* GAPIT..PRR3.491592.GWAS.Results.csv
* GAPIT..PRR3.492577.GWAS.Results.csv
* GAPIT..PRR3.GWAS.Results.csv
* GAPIT..PRR30T.GWAS.Results.csv
* GAPIT..PRR4.492758.GWAS.Results.csv
* GAPIT..PRR4.492990.GWAS.Results.csv
* GAPIT..PRR4.GWAS.Results.csv
* GAPIT..PRR5.492990.GWAS.Results.csv
* GAPIT..PRR5.GWAS.Results.csv
* GAPIT..PRR7.491404.GWAS.Results.csv
* GAPIT..PRR7.491592.GWAS.Results.csv
* GAPIT..PRR7.492448.GWAS.Results.csv
* GAPIT..PRR7.492990.GWAS.Results.csv
* GAPIT..PRR7.GWAS.Results.csv
* GAPIT..PYU.11002.GWAS.Results.csv
* GAPIT..PYU.11003.GWAS.Results.csv
* GAPIT..PYU.GWAS.Results.csv
* GAPIT..Prr3.492990.GWAS.Results.csv
* GAPIT..RUST.GWAS.Results.csv
* GAPIT..SCN1.494409.GWAS.Results.csv
* GAPIT..SCN1.GWAS.Results.csv
* GAPIT..SCN14.491576.GWAS.Results.csv
* GAPIT..SCN14.491577.GWAS.Results.csv
* GAPIT..SCN14.GWAS.Results.csv
* GAPIT..SCN14code.491576.GWAS.Results.csv
* GAPIT..SCN14code.491577.GWAS.Results.csv
* GAPIT..SCN14code.GWAS.Results.csv
* GAPIT..SCN1FI.494409.GWAS.Results.csv
* GAPIT..SCN1FI.GWAS.Results.csv
* GAPIT..SCN2.GWAS.Results.csv
* GAPIT..SCN2FI.GWAS.Results.csv
* GAPIT..SCN3.491576.GWAS.Results.csv
* GAPIT..SCN3.492579.GWAS.Results.csv
* GAPIT..SCN3.83.GWAS.Results.csv
* GAPIT..SCN3.GWAS.Results.csv
* GAPIT..SCN3FI.GWAS.Results.csv
* GAPIT..SCN3code.491576.GWAS.Results.csv
* GAPIT..SCN3code.492579.GWAS.Results.csv
* GAPIT..SCN3code.83.GWAS.Results.csv
* GAPIT..SCN3code.GWAS.Results.csv
* GAPIT..SCN4.492579.GWAS.Results.csv
* GAPIT..SCN4.83.GWAS.Results.csv
* GAPIT..SCN4.GWAS.Results.csv
* GAPIT..SCN4code.83.GWAS.Results.csv
* GAPIT..SCN4code.GWAS.Results.csv
* GAPIT..SCN5.83.GWAS.Results.csv
* GAPIT..SCN5.GWAS.Results.csv
* GAPIT..SCN5code.83.GWAS.Results.csv
* GAPIT..SCN5code.GWAS.Results.csv
* GAPIT..SDS.493025.GWAS.Results.csv
* GAPIT..SDS.493026.GWAS.Results.csv
* GAPIT..SDS.GWAS.Results.csv
* GAPIT..bp488001.GWAS.Results.csv
* GAPIT..bpmvall.GWAS.Results.csv
* GAPIT..bsr491584.GWAS.Results.csv
* GAPIT..bsrall.GWAS.Results.csv
* GAPIT..bsrcode491584.GWAS.Results.csv
* GAPIT..bsrcode492477.GWAS.Results.csv
* GAPIT..bsrcodeall.GWAS.Results.csv
* GAPIT..crdr.GWAS.Results.csv
* GAPIT..crds.GWAS.Results.csv
* GAPIT..pmv.GWAS.Results.csv
* GAPIT..saltreact.GWAS.Results.csv

## Manhattan Plots

The Manhattan Plots folder contains all of the Mahattan plots from GWAS analysis. The disease abbreviations for the files are listed above. 

Here is a list of the __Mahattan Plots__:

* GAPIT..CHLOROSIS.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe026.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe2.10001.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe2.10002.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe2.10003.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe2.10004.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe2.Manhattan.Plot.Genomewise.pdf
* GAPIT..Fe32perc.Manhattan.Plot.Genomewise.pdf
* GAPIT..NSC.491493.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.10001.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.10002.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.10003.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.10004.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.11002.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.11003.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.461592.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.488001.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.492577.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR1.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR10.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR12.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR17.491404.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR17.492448.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR17.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR17.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR2.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR20.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR25.491404.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR25.491592.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR25.492488.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR25.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR25.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR3.491592.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR3.492577.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR3.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR30T.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR4.492758.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR4.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR4.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR5.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR5.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR7.491404.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR7.491592.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR7.492448.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR7.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..PRR7.Manhattan.Plot.Genomewise.pdf
* GAPIT..PYU.11002.Manhattan.Plot.Genomewise.pdf
* GAPIT..PYU.11003.Manhattan.Plot.Genomewise.pdf
* GAPIT..PYU.Manhattan.Plot.Genomewise.pdf
* GAPIT..Prr3.492990.Manhattan.Plot.Genomewise.pdf
* GAPIT..RUST.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN1.494409.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN1.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN14.491576.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN14.491577.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN14.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN14code.491576.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN14code.491577.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN14code.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN1FI.494409.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN1FI.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN2.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN2FI.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3.491576.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3.492579.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3.83.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3FI.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3code.491576.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3code.492579.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3code.83.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN3code.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN4.492579.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN4.83.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN4.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN4code.83.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN4code.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN5.83.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN5.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN5code.83.Manhattan.Plot.Genomewise.pdf
* GAPIT..SCN5code.Manhattan.Plot.Genomewise.pdf
* GAPIT..SDS.493025.Manhattan.Plot.Genomewise.pdf
* GAPIT..SDS.493026.Manhattan.Plot.Genomewise.pdf
* GAPIT..SDS.Manhattan.Plot.Genomewise.pdf
* GAPIT..bp488001.Manhattan.Plot.Genomewise.pdf
* GAPIT..bpmvall.Manhattan.Plot.Genomewise.pdf
* GAPIT..bsr491584.Manhattan.Plot.Genomewise.pdf
* GAPIT..bsrall.Manhattan.Plot.Genomewise.pdf
* GAPIT..bsrcode491584.Manhattan.Plot.Genomewise.pdf
* GAPIT..bsrcode492477.Manhattan.Plot.Genomewise.pdf
* GAPIT..bsrcodeall.Manhattan.Plot.Genomewise.pdf
* GAPIT..crdr.Manhattan.Plot.Genomewise.pdf
* GAPIT..crds.Manhattan.Plot.Genomewise.pdf
* GAPIT..pmv.Manhattan.Plot.Genomewise.pdf
* GAPIT..saltreact.Manhattan.Plot.Genomewise.pdf





 



