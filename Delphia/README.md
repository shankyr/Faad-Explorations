# Delphia Time Series X Forecasting Assignment
Your task is to build a ML model to daily forecast Quarterly Sales Growth YoY 
for various companies better than the consensus estimates.

*Requirements*
- Dataset: forecasting_dataset.csv
- Codebook: forecasting_codebook.json

*Target Variable*
- 'sales_growth_yoy': Quarterly Sales Growth YoY
  (current quarter sales / sales of the same quarter 1 year ago)

## Instructions
- Download all the files related to the assignment.
- You are allowed to use Python and/or R for this assignment.
- You are only allowed to use data provided in order to derive features.
- Define or use an existing evaluation metric that accounts for *direction* and *magnitude*.
- Evaluate the consensus estimates performance on the chosen evaluation metric.
- Build a ML model that makes daily predictions for the relevant period for each 'date' in the dataset.
- Build a baseline to evaluate your forecast of Quarterly Sales Growth YoY (other than the consensus estimate).
- Evaluate, compare, and report the performance of your model to the baseline and the consensus.

## Deliverables
- Any piece of code written that is required to reproduce the results.
- Any outputs (notebooks, graphs, or tables) generated during the assignment.
- A csv file containing the model's daily forecasts for each 'date', 'company_id'.
- Include any other documents, reports, or comments that you judge helpful to the reader.

## Notes
- Observations are indexed by 'date' and 'company_id'.
- Be careful with look-ahead bias when engineering features or cross-validating.
- Any variable in the dataset or subsequent transformations can be used in the model.

## Confidentiality
This assignment, the data provided, and all accompanying documentation disclosed by Delphia 
to the candidate hereunder shall not be distributed or disclosed in any way or used for any 
purpose other than this assignment.
