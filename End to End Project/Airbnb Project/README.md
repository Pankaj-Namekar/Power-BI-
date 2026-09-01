# Airbnb Project

An end-to-end Power BI case study modeled on Airbnb-style listing and booking data.

## Contents
* Airbnb_BRD.pdf: business requirements document defining the scope and goals of the analysis.
* Airbnb_Data_Dictionary.pdf: field-level definitions for every table in the model.
* Airbnb_PowerBI_Theme.json: a custom Power BI theme file for consistent report styling.
* airbnb Canvas backgound.svg: a custom report canvas background.
* Airbnb_BI_Branding_Guidelines.pptx: branding and style guidelines used across the report.

## Data model (star schema)
* fact_bookings.csv: the fact table of booking transactions.
* dim_date.csv, dim_host.csv, dim_location.csv, dim_property.csv: supporting dimension tables.

## How to use
1. Read Airbnb_BRD.pdf for context on what the report answers.
2. Import the CSVs into Power BI Desktop and build relationships per the data dictionary.
3. Apply Airbnb_PowerBI_Theme.json for consistent styling.

The finished report lives at End to End Project/End to End Project.pbix.
