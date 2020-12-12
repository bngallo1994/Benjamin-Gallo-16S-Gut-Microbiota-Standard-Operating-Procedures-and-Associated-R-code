# Benjamin-Gallo-16S-Gut-Microbiota-Standard-Operating-Procedures-and-Associated-R-code
Detailed methods and analysis associated with our upcoming manuscript "Use of next generation sequencing to compare habitat and species level differences in the gut microbiota of an invasive and native freshwater fish species". The paper will be linked when it is accepted. Please feel free to email me (bngallo1994@gmail.com) if you have any questions on any of the methods and/or R - Code. Enjoy!

Weclome to the SOP Repository!

The methods included in this repository are meant to aid researchers with laboratory processing of gut microbiota samples for 16S rRNA sequencing.
Many of these methods are derived from Comeau et. al (2017) and their Microbiome Helper Github (https://github.com/LangilleLab/microbiome_helper/wiki).

Procedures and Proof of concept data analysis are published in (TBD).

Provided below is a quick guide for understanding the contents of this repository. Please contact me if you have any questions.
Enjoy!

Ben


CONTENTS:

Folder: Benjamin-Gallo-16S-Gut-Microbiota-Standard-Operating-Procedures-and-Associated-R-code-master

ALLDATA_Sequence_Read_Archive_Information.docx
  - SRA's of all .FASTQ files associated with the proof-of-concept experiment. Follow the link to download the FASTQ files that correspond with the R Code.
  
Folder: Laboratory_Protocols
20180118_DNA_EXTRACT_PCR_PROTOCOLS.docx
WATER_DNA_EXTRACT_PROTOCOL.docx
ZOOP_DNA_EXTRACT_PROTOCOL.docx

The files correspond to detailed methods for DNA extraction and PCR protocols (e.g. how was got to sequencing).
Please refer to the publication for Next Generation Sequencing prep  for our individual runs.

Folder: Proof of Concept for SOP (Published Data)

Collection Data.xlsx
  - All information kept by the author detailing collection of fishes and their gut microbiota.
Library Prep.xlsx
  -Informatioon loaded onto NGS platform. Information includes sample ID, barcode/primer combinations, and final sample names.
PilotDataFINAL.Rmd
  - RMarkdown file pertaining to all code utilized in the experiment. All files for analysis are located in the "Files Linked with R-Code" Folder in the repository.

Folder: Files Linked with R-Code

This folder is broken into two consitutent folders: "USEARCH_RG" & "USEARCH_RGYBH" corresponding to the analyses completed on Round Goby (RG) and Yellow Bullhead (YBH).
All files are linked to analyses in the PilotDataFINAL_Revised.Rmd file

Folder: USEARCH_scripts

All associated scripts developed for sequencing merging, cleaning/filtering, denoising etc. These are closely based off of the code provided by
Robert Edgar in his youtube video (https://www.youtube.com/watch?v=pOV_tuZqzso). I also include a "primer stripping" script that is necessary if using the V6-V8 primers
from Microbiome Helper. For further information, please refer to the "USEARCH_instructions.docx" file in this folder.



