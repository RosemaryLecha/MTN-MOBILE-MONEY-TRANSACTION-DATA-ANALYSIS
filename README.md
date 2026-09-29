
## Project Title
Mobile Money Behavioral User Classification

## Brief Description
This project analyzes anonymized mobile money transactions to classify users into Low, Medium, and High activity segments using a complete data science workflow: collection, cleaning, EDA, modeling, interpretation, reporting, and presentation.

## File Structure Explanation
- `1_Data_Collection/`: anonymized raw dataset, consent form, questionnaire, and data collection report
- `2_Data_Cleaning/`: cleaning notebook, cleaned dataset, and cleaning report
- `3_EDA/`: EDA notebook, EDA report, and saved visualizations
- `4_Modeling/`: modeling notebook, saved best model, model comparison report, and metrics/results
- `5_Report/`: final report PDF and appendices
- `6_Presentation/`: presentation slides PDF (and optional demo note)
- `requirements.txt`: Python dependency list
- `CONTRIBUTIONS.md`: member-by-member contribution breakdown

## How To Run The Code
Run from the `combined` workspace:
- `python3 refresh_q1_q4_all5.py`
- `python3 generate_q5_interpretation.py`
- `python3 generate_final_package.py`

## Dependencies / Requirements
See `requirements.txt` for all libraries used.

## Important Disclosure
The transaction dataset includes 50 real users and 13,426 transaction rows. Real demographic forms are available for 20 users; 30 demographic profiles are generated placeholders and are disclosed in the report.
