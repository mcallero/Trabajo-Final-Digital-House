# Digital-House Data Science course Final Assignment

MicroRNAs (miRNAs) are a type of non-coding RNAs that act as gene expression regulators. The sequences of many of them are preserved into unrelated organisms, suggesting  that these molecules do participate in essential biological processes. The miRNA expressions are often altered in many types of human cancers and they are critical to carcinogenesis, since they work as tumor suppressor genes or as oncogenes. Recent studies have proved that miRNAs are very associated to cancer progression including the growth of tumors, tumoral differentiation, adhesion, apoptosis, invasion and formation of metastasis.

This project was the final task I had to accomplish to get my Data Scientist Degree. Its main objectives  was to train models for predicting a dependent variable and to evaluate them. 
The data used was downloaded from https://portal.gdc.cancer.gov/  ("Genomic Data Commons Data Portal" - National Cancer Institute) and it enclosed  863 txt files (each one from a different patient) with  miRNAs expression quantification of 1881 genes and a dataset with clinical and pathological features from those patients.

There are two different Jupyter Notebooks presented.
1- CPTAC_csv_grade_tumor, which comprises dataset curation, variables distribution visualization, features engineering, and modeling with the column 'tumor_grade' as the dependent variable.
2- CPTAC_primary_diagnosis, which describes modeling with the column 'primary_diagnosis' as the dependent variable

