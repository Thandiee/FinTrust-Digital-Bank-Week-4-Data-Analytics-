# FinTrust-Digital-Bank-Week-4-Data-Analytics-

# FinTrust Week 4 Final Data Analytics Submission

## What is included
- `sql/FinTrust_Week4_Final_SQL.sql`: final SQL review queries.
- `final_analysis/FinTrust_Week4_Final_Validation_Workbook.xlsx`: KPI definitions, validation, recommendations and test log.
- `powerbi/FinTrust_Week4_Final_PowerBI_Build_Guide.md`: dashboard pages, measures and validation checklist.
- `final_documentation/FinTrust_Week4_Final_Project_Report.pdf`: final report.
- `final_presentation/FinTrust_Week4_Final_Presentation.pptx`: presentation deck.
- `final_presentation/FinTrust_Week4_5to10_Minute_Presentation_Script.docx`: speaking script.
- Week 3 SQL, notebook, visuals, workbook and source data are preserved in this package.

## Key validated results
- Customers: 33
- Transactions: 33
- Total transaction value: NGN 959,180.43
- Mean transaction value: NGN 29,066.07
- Median transaction value: NGN 6,702.14
- Customer ID match rate: 3.0% (1/33)
- IQR outlier count: 5; value share: 71.4%

## Critical limitations
1. The CSV files are structured transcriptions of visible records from supplied PDF exports, not original raw system extracts.
2. Only 1/33 transaction Customer_IDs match the visible customer export; customer-level transaction conclusions are not reliable until the key mapping is corrected.
3. The visible transaction export does not include `Transaction_Status` or `Risk_Review_Flag`.
4. The visible transaction timestamps cover only 2026-01-01 00:00:00 to 2026-01-01 05:45:00; trend analysis is exploratory.
5. The native Power BI `.pbix` is not included. Build it in Power BI Desktop using the guide, save as `FinTrust_Week4_Final_Dashboard.pbix`, reopen it, validate measures/filters/relationships and capture screenshots before submission.
6. Do not claim actual cross-track integration without real artifacts and evidence.

## Final steps for the user
1. Open the final report and validation workbook.
2. Build/test the native Power BI file in Power BI Desktop.
3. Run the SQL in a compatible SQL engine after loading the CSVs as tables (some percentile/date syntax varies by engine).
4. Rerun the notebook in the target environment if required and retain the outputs.
5. Update GitHub, add final evidence/screenshots, and record the 5–10 minute presentation.
6. Publish the final LinkedIn and X posts, tag AnalystLab Africa / @analystlabafric, and include #AnalystLabAfrica.

## Responsible-use note
FinTrust and the data are synthetic educational materials. No output in this project should be represented as production banking analysis or actual fraud detection.
