# Serif Health Data Science Take-Home Assignment

Overview

This project focuses on analyzing, cleaning, and integrating healthcare pricing datasets to facilitate better payer-hospital comparisons. 
The main objective is to standardize and merge multiple sources of pricing information while addressing data quality issues.

Data Preprocessing & Cleaning

1. Data Quality Assessment 
	•	Standardized text columns to lowercase to ensure uniformity and avoid duplicate variations
	•	Checked for and removed exact duplicate rows to maintain dataset integrity
	•	Dropped columns with a single unique value, as they do not provide useful information
	•	Removed columns that added no significant value to the analysis, such as filenames

2. Data Standardization
	•	Ensured consistent formatting across datasets
	•	Investigated key identifier columns (e.g., payer names, billing codes, hospital IDs) to align formats

Data Integration and Merging
	•	Identified common columns across datasets (payer names, code types, billing codes, and hospital IDs) to enable accurate merging
	•	Merged datasets while preserving the necessary pricing and hospital-related attributes

Next Steps and Further Improvements

Given more time, potential improvements include:
	•	Implementing Named Entity Recognition (NER) techniques to better match payer names across different datasets
	•	Refine textual descriptions for each code to ensure consistency and remove unnecessary variations.
	•	Refining plan names further for more precise payer-hospital linkages
	•	Enhancing price standardization by incorporating additional hospital and payer-level adjustments
	•	Added external datasets to enrich the analysis

Summary

This project involved a structured approach to cleaning and integrating healthcare pricing datasets to enable effective comparisons. The preprocessing steps ensured data consistency, while the integration strategy focused on meaningful linkages between hospitals and payers. Further refinements could improve matching accuracy and provide deeper insights into pricing structures.
