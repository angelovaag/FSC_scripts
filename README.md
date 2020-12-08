This repo presents with scripts, code and materials used in the creation of publication titled:
#### Inter- and intra-annual bacterioplankton community patterns in a deepwater sub-Arctic region: persistent high background abundance of putative oil degraders

Angelina G. Angelova1, Barbara Berx2, Eileen Bresnan2, Samantha B. Joye3, Andrew Free4, Tony Gutierrez1

1School of Engineering and Physical Sciences, Heriot-Watt University, Edinburgh EH14 4AS, UK
2Marine Scotland Science, Aberdeen, AB11 9DB, UK
3Department of Marine Sciences, University of Georgia, Athens, Georgia, USA
4School of Biological Sciences, University of Edinburgh, Edinburgh EH9 3FF, UK


##### FSC_scripts
Scripts about the 16S analysis of FSC baseline microbial communities

All files starting with DB are the SINTAX-formated database files used for assigning taxonomy. 
DB_ncbi16S.fasta was primarily used for the FSC baseline analysis. The rest are supplemental.

pipeline.txt file provides the general structure of the bioinformatics pipeline

SampleMapping.xlsx file contains the "everything" metadata file

metadataR.txt is a shorter version of the metadata file, used in the R analysis

zASV_Ranalysis_v314.7.Rmd is the R script used to genarate the analysis + some commented out explanations .. and ranting 

zASV_OTUtab-nonchim.txt = the OTU/ASV table produced by VSEARCH denoising after chimera removal
zASV_TAXtab-nonchim.txt = the TAXONOMY asignments for each ASV (Its been cleaned with: cut -f1,3 -d "\t" | sed 's/;*\t/\t/g' )
zASV_SEQfa-nonchim.txt = the fasta file of the nonchimeric ASV sequences

