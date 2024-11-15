# Biomarker-identification

**Understanding the Gut Response in IBS by Analyzing mRNA Expression Profiles**

**Overview**

This project investigates the gut response in IBS patients by analyzing mRNA expression profiles. The goal is to identify biomarkers for diagnostics or therapeutics by examining gene expression data linked to gut dysfunction, inflammation, and microbiome interactions.

**Tools Used**

Google Sheets: Organizing gene expression data.

Gene Expression Omnibus (GEO) Datasets: Sourcing IBS-related mRNA expression profiles.

DAVID Bioinformatics Resources: Functional annotation of identified genes.

ENSEMBL Symbol Converter: Mapping gene IDs to symbols.

Tableau: Visualization of gene expression trends and interactions.

PubMed: Literature review of genes linked to IBS pathophysiology.

ClinicalTrials.gov: Exploring trials targeting identified biomarkers.


**Data Collection**

Dataset Selection: Retrieve IBS-related datasets from the GEO database.

Patient Samples: Compare mRNA profiles of IBS patients (e.g., IBS-C, IBS-D) with healthy controls.


**Data Preparation & Analysis**

Data Download & Cleaning:
Import GEO datasets in .txt format.
Filter out blank or zero expression values.

Grouping Samples:
Separate average gene expression for IBS subtypes (e.g., IBS-C, IBS-D) and healthy controls.

Fold Change Calculation:
Calculate fold change (e.g., diseased vs. healthy).
Retain genes with fold change ≥ 2 for further analysis.

Statistical Analysis:
Perform T-tests to identify significant genes (p-value ≤ 0.05).

Gene Annotation:
Use DAVID to identify pathways associated with gut inflammation, motility, or microbiota-host interactions.


Data Visualization

Import to Tableau:
Visualize filtered data with bar graphs or heatmaps.

Configure Charts:
Include fold change, p-value, and average expression for IBS subtypes and controls.
Use colors to highlight genes with significant changes.

**Insights and Application**
The analysis highlights differentially expressed genes linked to IBS, helping to pinpoint biomarkers for non-invasive diagnostics or personalized therapies. Further exploration can assess gene roles in inflammation or gut barrier dysfunction, aiding in therapeutic advancements.

