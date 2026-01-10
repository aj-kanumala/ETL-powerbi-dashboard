# powerbi-reporting-dashboard
A sample PowerBI dashboard created with real world insurance data

## Objective
This project presents an approach for analyzing a raw dataset to generate valuable insights for key business functions using a python ETL pipelines and Microsft PowerBI dashboard. *This landed me an internship offer at an US based organisation focused in Health Care.*

## Challenge
Prior to conducting any analysis, it is essential to thoroughly examine and process the data. Preprocessing and cleaning a raw dataset in Python involves several crucial steps to ensure that the data is well-structured, consistent, and prepared for analysis or modeling.

## Extract

### Import the raw data
- Importing the raw data from excel sheet into python a DataFrame.
- Removing duplicate and empty rows and columns from the dataset.
- Remove the first row and set the appropriate row as column headers.

## Transform

### Data Cleaning
- Replace any spaces in column names with '_' for convenience.
- Remove unwanted rows which has the values of column headers.
- Check for missing values.
- Replace any invalid values and convert data types of necessary fields to numeric from string.
- Dealing with columns with string values such as labelling, removing spaces etc.

## Load

Exporting the cleaned dataset into excel file which is stored on local machine within the same folder. (This approach is recommended for the client as the personal details of the patients never leaves their internal systems, adhering to compliance standards like HIPAA.)

After this step, the cleaned/pre-processed excel file can be imported into PowerBI Desktop app.

`Microsoft PowerBI` is a business intelligence tool that helps users analyze and visualize data to make informed decisions. It is prominently used for Data Visualizations, AI insights, creating Dashboards and Collaboration.

The excel file can be loaded into PowerBI in two ways:
1. Manually upload the excel sheet into the application and update the dashboards.
This method is simple and easy to use but involves manual intervention.
2. Configure the PowerBI application to directly pull the excel file from a one-drive shared folder and update the dashboards in real time.
This method requires a one-time configuration which is a bit complex.

