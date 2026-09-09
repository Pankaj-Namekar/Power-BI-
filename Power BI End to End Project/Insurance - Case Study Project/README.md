# Insurance - Case Study Project

An end-to-end Power BI case study built for a Customer Insights Analyst assignment, analyzing customer, policy, and claims data for Allianz, a global insurance company.

## Contents
- `Case Study Assignment - Customer Insights Analyst.docx`: the original assignment brief defining the business background, dataset, tasks, and evaluation criteria.
- `Case Study Report - Pankaj Namekar.pdf`: an annotated walkthrough of the finished report pages (KPI Summary, Customer, Claims) with a UI/navigation guide.
- `Allianz Branding Theme.json`: a custom Power BI theme file (Allianz brand colors and fonts) used to style the report.
- `Policy Insurance Analysis.pbix`: the finished Power BI report.

## Dataset
- `Case_Study_Policy_Data.csv`: 10,000 fictional customer policy records with `CustomerID`, `Age`, `Gender`, `PolicyType`, `PolicyStartDate`, `PolicyEndDate`, `PremiumAmount`, `ClaimsMade`, `CustomerSatisfactionScore`, and `Region`.

## Report pages
1. **KPI Summary** - premium received, customer growth, CSAT score, and claims made, each with a trend sparkline, sliceable by year, region, and policy type.
2. **Customer** - demographic breakdown (age, gender), premium & customer trends by year, and CSAT by gender / policy claim status.
3. **Claims** - claims by year, region, policy type, and age group, plus claims volume vs. average CSAT by policy type.

## Key insights
- Across 10,000 customers, Allianz collected $8.7M in premiums, with Motor policies generating the most claims (9,706), followed by Home (7,659) and Auto (6,106).
- 81% of customers have made at least one claim, yet average CSAT stays close between claimed (5.46) and not-claimed (5.59) customers, and across genders (5.44-5.68) - suggesting satisfaction is driven more by overall service experience than by claim outcome.
- Claims volume peaked in 2022 (5,017) before declining, and premium/customer counts have also trended down since 2021 - worth investigating further as a retention risk.

## How to use
1. Read `Case Study Assignment - Customer Insights Analyst.docx` for the business background and requested analysis.
2. Clean and import `Case_Study_Policy_Data.csv` into Power BI Desktop (handle missing `Age` / `PolicyEndDate` values).
3. Apply `Allianz Branding Theme.json` as a custom report theme (View > Themes > Browse for themes).
4. Open `Policy Insurance Analysis.pbix` to explore the finished report, or refer to `Case Study Report - Pankaj Namekar.pdf` for a static walkthrough.
