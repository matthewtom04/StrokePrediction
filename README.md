# StrokePrediction

# Introduction
The increased use of digital information and electronic health records (EHRs) is creating 'Big Data' to the healthcare industry. Along with the development of technologies such as machine learning and big data techniques, health care industries are utilizing predictive modeling with electronic health records (EHR) to drive personalized medicine and improve healthcare quality. For my final project, I wanted to explore the idea of extracting free text data from physician notes of a EHR to help identify those patients suspected of having life-threatening disease. In particular, I wanted to predict if an individual is at risk of a stroke based on their social, medical, and family history in order to prevent strokes.

# Problem Statement
To make a classification model to predict risk of strokes.

# Data
Data was extracted from the MIMIC-III (Medical Information Mart for Intesive Care), a large, single-center database comprising information related to patients to critical care units at a large tertiary care hospital, is used. The MIMIC-III database includes 26 tables but for my analysis, I focused on 3 tables. (1) NOTEEVENTS- Nursing and Physician Notes. (2) Diagnoses_ICD (Hospital assigned diagnoses, coded using the International Statistical Classification of Disease and Related Health Problems. (3) D_Diagnoses_ICD( ICD-9 Codes related to diagnoses tables).
