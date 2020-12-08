# FSC_scripts
Scripts about the 16S analysis of FSC baseline microbial communities

All files starting with DB are the SINTAX-formated database files used for assigning taxonomy

pipeline.txt file provides the general structure of the bioinformatics pipeline

SampleMapping.xlsx file contains the "everything" metadata file

metadataR.txt is a shorter version of the metadata file, used in the R analysis

zASV_Ranalysis_v314.7.Rmd is the R script used to genarate the analysis + some commented out explanations .. and ranting 

zASV_OTUtab-nonchim.txt = the OTU/ASV table produced by VSEARCH denoising after chimera removal
zASV_TAXtab-nonchim.txt = the TAXONOMY asignments for each ASV (Its been cleaned with: cut -f1,3 -d "\t" | sed 's/;*\t/\t/g' )
zASV_SEQfa-nonchim.txt = the fasta file of the nonchimeric ASV sequences

