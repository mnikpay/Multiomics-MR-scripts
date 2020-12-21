# SNP-based multiomics scripts
These are the scripts to do a SNP-based multiomics data analysis. Together, they can be used to combine different sets of omics data for molecular (Biomarker → Biomarker) and clinical (Biomarker → Phenotype) insight.

To do these analyses, first convert your GWAS summary data to the GSMR and the SMR formats:

GSMR manual: http://cnsgenomics.com/software/gcta/#Mendelianrandomisation

SMR manual: https://cnsgenomics.com/software/smr/#DataManagement

Then use the co-localization, and the 2-sample MR scripts to find biomarkers that are causally associated with a phenotyope within genomic regions that are consistently associated to both biomarker (e.g. a molecular probe) and phenotype (trait/biomarker).

Link to the QTL data (input files):

https://filr.ottawaheart.ca/ssf/s/readFile/share/1438/6705413317368203034/publicLink/QTL_data.zip

As for your bfile, you can use the genotype data from the 1000G:

https://www.cog-genomics.org/plink/2.0/resources#1kg_phase3

If you need any further information, please feel free to contact me (majid.nikpay@gmail.com).
