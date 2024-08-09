# Project Expense Dashboard

This repository contains a Power BI dashboard for monitoring project expenses. The dashboard allows project managers to see the expenses linked to all ongoing projects and monitor whether planned and actual disbursements match.

## Files

- **TestCase Project file_01.pbix**: Power BI report file
- **Copy of TestCase_Project2023.xlsx**: Data file containing project and disbursement details

## Features

1. **Dashboard View Restriction**:
   - The dashboard owner can see all data, but project managers can only see their projects.

2. **Project Mapping**:
   - Links `ProjectCode` in Salesforce to `ProjectID` in EXACT using the `ProjectMapping` sheet.

3. **Flag Unmapped Projects**:
   - Identifies and flags any projects that do not have a corresponding mapping.

4. **Measure Disbursement Discrepancies**:
   - Calculates and highlights projects where actual disbursements differ from planned disbursements.

5. **Total Planned Disbursements**:
   - Measures total planned disbursements for a selected period and identifies ledgers with the highest amounts.

 #  Conclusion
 
![Abhi_Main](https://github.com/user-attachments/assets/ad4130da-7454-4d26-ab58-e2ad8974295d)

The Project Expense Dashboard is a powerful tool for project managers to monitor and compare planned versus actual disbursements across ongoing projects. With features like restricted data views, unmapped project identification, and discrepancy detection, the dashboard ensures effective financial oversight. This repository centralizes all relevant files and documentation, making it easy for your team to access and collaborate on enhancing project expense tracking.

# Note: 
This report was completed within the client’s timeline of 1 day, successfully meeting all requirements and receiving positive feedback from the client.
