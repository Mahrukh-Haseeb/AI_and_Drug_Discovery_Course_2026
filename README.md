# Assignment 2: QSAR Data Curation Using ChEMBL

## Target
Androgen Receptor (CHEMBL1871)

## Bioactivity Records
- Raw IC50 records: 4425
- Preprocessed records: 4178

## Workflow Description
1. Mount Google Drive to save and load datasets.
2. Install and import required libraries (pandas, chembl_webresource_client).
3. Search ChEMBL for Androgen Receptor target and select CHEMBL1871.
4. Retrieve IC50 bioactivity data from ChEMBL.
5. Save raw data to CSV on Google Drive.
6. Filter rows with valid IC50 values.
7. Assign bioactivity classes: active (≤1000 nM), intermediate, inactive (≥10000 nM).
8. Extract relevant columns: molecule_chembl_id, canonical_smiles, standard_value, bioactivity_class.
9. Remove compounds without valid SMILES.
10. Save preprocessed bioactivity data to CSV and copy to Google Drive.
