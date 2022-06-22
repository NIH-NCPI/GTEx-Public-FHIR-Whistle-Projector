# GTEx-Public-FHIR-Whistle-Projector
Public GTEx projector for Whistle

This repository contains the whistle projector and supporting data for use with [NCPI Whistler](https://github.com/NIH-NCPI/ncpi-whistler) to ingest into FHIR for use during the [NCPI FHIR Code-a-thon](https://github.com/NIH-NCPI/FHIR-CAT-June22). 

Currently, the focus has been to create the basic study components (ResearchStudy, Group, ResearchSubject), [Patient data](https://storage.googleapis.com/gtex_analysis_v8/annotations/GTEx_Analysis_v8_Annotations_SubjectPhenotypesDS.txt) and a subset of the [sample annotation file](https://storage.googleapis.com/gtex_analysis_v8/annotations/GTEx_Analysis_v8_Annotations_SampleAttributesDS.txt) for Specimen resources as well as the data from the [gene_tpm file](https://storage.googleapis.com/gtex_analysis_v8/rna_seq_data/GTEx_Analysis_2017-06-05_v8_RNASeQCv1.1.9_gene_tpm.gct.gz) 

Terms found inside the harmony file were provided by [Meen](https://github.com/orgs/NIH-NCPI/people/liberaliscomputing) at CHOP along with some filler info from various OBO files found online. 
