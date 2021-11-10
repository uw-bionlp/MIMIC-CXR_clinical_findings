# MIMIC-CXR_clinical_findings

This repo contains over 1 million medical problem findings and 31 K lesion findings extracted from 
227,835 chest X-ray reports in the [MIMIC-CXR database](https://physionet.org/content/mimic-cxr/2.0.0/).

The schema in the annotation guideline document provides details of the two clinical findings (Medical Problem and Lesion).
 
 - <em>Medical problem</em>  contains (Problem, Anatomy, Assertion).
 
 - <em>Lesion</em> contains (Description, Anatomy, Size, Size Trend, Count, Characteristic, Assertion).
 
The extracted findings are in [BRAT's standoff format](https://brat.nlplab.org/standoff.html). 
 
The directory structure of the extracted data is identical to the MIMIC-CXR data, so that it can be easily integrated.  Only the extractions are included in this repo. The original X-ray reports and images will needed to acquired from MIMIC-CXR with proper data usage agreement.