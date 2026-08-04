## Input data

The report requires a single CSV file named `data.csv`

## Required variables

Your dataset must contain the following variables.

`id_child`	Unique participant identifier	example, C001

`block`	Block name	example, Block1

`district`	District name	example, DistrictA

`bll_child`	Measured blood lead level (µg/dL). Leave blank (NA) for BDL and >65 results.	

`bll_child_cat`	Blood lead result category	

Additional variables (e.g., age, sex) may be included but are not used in this report.

## Blood lead result categories

For summary statistics, the report substitutes:

2.3 µg/dL for BDL results (bll_child_cat = 2)
65 µg/dL for results >65 µg/dL (bll_child_cat = 3)

## Running the code in RStudio 
Step 1: Open the project folder in RStudio.

Step 2: Open bll_survey_status.Rmd.

Step 3: Click Knit button on the top of the file 

The report will be generated as `bll_survey_status.docx` and saved in the project folder.

For any questions, contact mkushwaha.consultant@vitalstrategies.org

Public github link: https://github.com/meenakshi-kushwaha/2025_mh_lead_surv_status