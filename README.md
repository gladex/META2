# META2: Intercellular DNA METhylation Annotation & Analysis

**About META2**

META2 (DNA METhylation Annotator & Analyzer), aims to detect differential status of cross-cell DNA methylation, annotate the detected loci and perform downstream analysis. It contains multiple functions to run a series of operations on DNA methylation analysis and cross cell interrogation. Currently only RRBS (Reduced Representation Bisulfite Sequencing) can be directly run through the whole analysis procedure, but the package functions are be used to analyse the other datasets with the permitted input formats.

META2 contains several statistical analysis and integrative visulization functions. Part of those functions are listed as below,

1. **fun_findDMC**: the function aims to identify the differentially methylated CpG loci (DMC), together filter out the statistically significant DMCs;
2. **fun_plotMethLoci**: the function is designed to plot the differentially methylated loci (based on differential methylated level between control vs treatment). The function can plot the dot or line style for the methylated loci across the whole genome (ch1 ~ chr22, chrX and chrY);
3. **fun_combineDMC**: the function aims to combine the isolated DMCs into a complete DMC cluster with a predefined length, then those clusters can further become differential methylated region (DMR) candidates;
4. **fun_findDMR**: the function is to filter differentially methylated loci and combine those isolated loci into region with its length specified, and finally output the identified differential methylated region (DMR) candidates. This function is an integration of fun_findDMC and fun_combineDMC;
5. **fun_intplotDMR**: the function is to generate the integrative diagram for the identified differential methylated region (DMR) candidate, which contains reference sequence information within the interested DMR.

Any question or suggestion, please direct to bh.tang@outlook.com

Last updated: 09/16/2016
