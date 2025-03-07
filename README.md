# Serif Health Data Science Take-Home Assignment

Overview

This project focuses on analyzing, cleaning, and integrating healthcare pricing datasets to facilitate better payer-hospital comparisons. <br>
The main objective is to standardize and merge multiple sources of pricing information while addressing data quality issues.

**Data Preprocessing & Cleaning**

1. Data Quality Assessment <br>
	•	Standardized text columns to lowercase to ensure uniformity and avoid duplicate variations<br>
	•	Checked for and removed exact duplicate rows to maintain dataset integrity<br>
	•	Dropped columns with a single unique value, as they do not provide useful information<br>
	•	Removed columns that added no significant value to the analysis, such as filenames<br>

2. Data Standardization
	•	Ensured consistent formatting across datasets<br>
	•	Investigated key identifier columns (e.g., payer names, billing codes, hospital IDs) to align formats<br>

**Data Integration and Merging**<br>
	•	Identified common columns across datasets (payer names, code types, billing codes, and hospital IDs) to enable accurate merging<br>
	•	Merged datasets while preserving the necessary pricing and hospital-related attributes<br>

**Next Steps and Further Improvements**<br>
Given more time, potential improvements include:<br>
	•	Implementing Named Entity Recognition (NER) techniques to better match payer names across different datasets<br>
	•	Refine textual descriptions for each code to ensure consistency and remove unnecessary variations<br>
	•	Refining plan names further for more precise payer-hospital linkages<br>
	•	Enhancing price standardization by incorporating additional hospital and payer-level adjustments<br>
	•	Added external datasets to enrich the analysis<br>

Summary

This project involved a structured approach to cleaning and integrating healthcare pricing datasets to enable effective comparisons. The preprocessing steps ensured data consistency, while the integration strategy focused on meaningful linkages between hospitals and payers. Further refinements could improve matching accuracy and provide deeper insights into pricing structures.
