
# MODELS 2021 Replication Package

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5128416.svg)](https://doi.org/10.5281/zenodo.5128416)

Replication package for the paper _Collaborative Model-Driven Software Engineering: A Systematic Update_.

The full dataset including raw data, mining scripts, and analysis scripts produced during the study are available below.

### Data & analysis scripts

This replication package is structured as follows:
* `/corpus` - Corpus: papers, and ID mappings (for traceability).
  * `01_Corpus_full.xlsx` - Full corpus: the list of the 886 papers identified through the systematic search and screened during the study. The data contains the inclusion/exclusion criteria of the papers, including the criterion an exclusion was based on.
  * `02_Primary_studies_included.xlsx` - The list of 54 papers included in our study. Information about the snowballing round the paper was found included.
  * `03_Clusters.xlsx` - The list of 29 clusters.
  * `04_Primary_studies_clustered_with_PID.xlsx` - The list of 29 clusters with the eventual ID used in the paper.
  * `05_Corpus-final.pdf` - An integrated overview of the 54 included papers shown in the 29 clusters.
  * `README.MD` - Information about the ID mappings.
* `/data` - Data.
   * `analysis.csv` - Clean data in a processable form.
   * `analysis-09052021-clean.xlsx` - Clean data.
   * `analysis-years.csv` - Clean data for the publication year analysis in a processable form.
   * `analysis-years.xlsx` - Clean data for the publication year analysis.
* `/analysis` - Analysis scripts.
   * `/descriptive` - Descriptive statistics (.R script and the resulting .PDF report).
   * `/horizontal` - Horizontal statistics (.R script and the resulting .PDF report).
   * `/publishers` - Publisher data (.R script and the resulting .txt output).
   * `/significance` - Significance analysis of the 2012/2013 publication ouput increase (.R script and the resulting .txt output).
   * `/venues` - Venues analysis (.R script and the resulting .txt output).
   * `/year_stacked` - Number and type of publications by year on a stacked bar chart (.R script and the resulting .PDF report).
* `/results.zip` - Data+Analysis in one .zip file.
* `ClassificationSchemaChanges.pdf` - Classification schema changes.
* `DataExtractionForm-FINAL.xlsx` - Extracted data spreadsheet.

### Protocol

This work follows the protocol of the original study with minor adaptations clearly described in the paper.

### Original study
* [Protocol and replication package](http://people.disim.univaq.it/mirco.franzago/collaborativeMDSE)
* [Publication](https://ieeexplore.ieee.org/document/8047991/)

