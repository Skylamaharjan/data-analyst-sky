# data-analyst-sky






AWS Portfolio Assignment
Skyla Maharjan (2322663)
University Canada West
BUSI 653: Cloud Computing Technologies (HBD-WINTER-25-05)
Professor Dr. Mahmood Mortazavi Dehkordi
March 26, 2025







Table of Contents:
1.	Exploratory Data Analysis
2.	Descriptive Analysis
3.	Diagnostic Analysis
4.	Data Wrangling
5.	Data Quality Control
6.	Data Security
7.	Data Governance
8.	Data Monitoring






 





Exploratory Data Analysis

Dedicated Fire Protection Systems (DFPS) Water Mains dataset in Amazon S3 The dataset also includes information regarding water mains such as their installation year, diameter and material type, and service area. The study aims to capture patterns and trends with respect to the features of water mains.

Title of the Project: Analyzing DFPS Water Mains Characteristics

Purpose of the project: The main objective of this project is to conduct an exploratory data analysis in DFPS Water Mains dataset to see how the water mains are distributed by diameter, material, date of installation and service area.

Dataset:
•	DFPS Water Mains File
•	Installation Year, Diameter, Material Type, Service Area and Pipe ID are the fields looked into.
•	Highly scalable access and analysis stored in Amazon S3.

Methodology:
Data Ingestion:
•	I put the DFPS dataset on Amazon S3 with their bucket in a structured and organized fashion.
•	AWS Glue Data Catalog is set up to ease query via Amazon Athena.

Data Profiling and Cleaning:
•	I use AWS Glue DataBrew to scratch data for quality, find missing values and anomalies.
•	It was also addressed some format inconsistent and some data types wrongly.

Data Summarization and Visualization:
•	We queried data to generate understanding of water main characteristics using Amazon Athena.
•	I also created visualizations to understand the diameter sizes, installation years, and types of material.

Tools and Technologies:
Amazon S3, AWS Glue DataBrew, Amazon Athena

Deliverables:
•	Structured and cleaned dataset for analysis can be used.
•	Water Mains Characteristics report including pattern and trend of characteristics.
 

Descriptive Analysis

Project Description:
An analysis of the Dedicated Fire Protection Systems (DFPS) Water Mains dataset by Descriptive Analysis to describe key characteristics such as material use, common diameters, installation trends, and a distribution of installation over time.

Project Description: Descriptive Analysis of DFPS Water Mains Installation Data

Objective:
Describe a descriptive statistical analysis of DFPS Water Mains dataset to identify distribution of the materials, and installation years as well as Pipe diameters. Further, this analysis will show trends in time in installation practices.

Dataset:
•	Dedicated Fire Protection Systems (DFPS) Water Mains CSV File
•	Pipe Material, Installation Year, Pipe Diameter and Location are all fields.
•	They store the data on Amazon S3 and process using Amazon Athena.

Methodology:
Data Analysis using SQL Queries:
•	Descriptive statistics were generated using Amazon Athena:
•	Types of pipe material used and their frequency.
•	Common installation years and their frequency.
•	Average and most common pipe diameters.
•	Distribution of installations across different locations.

Visualization of Findings:
•	Some bar charts of the distribution of pipe materials.
•	Graphs for showing the trends on installations over time.
•	Use pie charts to tell what D railroad pipe was used how often.

Summarization of Insights:
•	Listing out the most used pipe materials and diameters.
•	Patterns of procedure over given years.
•	Geographic distribution of installations if applicable.

Tools and Technologies:
Amazon S3, Amazon Athena, Visualization Tools (e.g., Power BI, Matplotlib)

Deliverables:
We produced a Descriptive Analysis Report that includes described findings and visualizations.
 

Diagnostic Analysis

Project Description:
Diagnosis of the Dedicated Fire Protection Systems (DFPS) Water Mains Dataset to understand why certain installations occur at certain periods of time, drop suddenly or spike, and to identify any problems regarding some exit pipe materials or diameters.

Title of the project: Diagnostic Analysis of DFPS Water Mains Installations.

Objective:
The anomalies or patterns in the DFPS Water Mains dataset would be identified in order to detect abnormalities or patterns related to such failures as material or improper installation, or changes in installation practice over time. The purpose of this diagnostic analysis is to understand factors behind the observed unusual patterns and explain any observed trends.

Dataset:
•	Dedicated Fire Protection Systems (DFPS) Water Mains CSV File
•	Pipe Material, Installation Year, Pipe Diameter and Location are all fields to put in.
•	Amazon S3 stores data and its processed with Amazon Athena.

Methodology:
Comparative Analysis:
•	Comparison of installation counts across various spans of time to reveal if there are large increases in the installation counts or if these numbers have dwindled to levels of insignificance.
•	Determine how installation years affect cross referencing materials used so that shifts in material preferences can be detected.

Correlation Analysis:
•	Determine whether there may be an association between some pipe material and a higher or lower installation rate.
•	Deciding whether the rates of installation vary depending on pipe diameters or have changed over time.

Anomaly Detection:
•	Identify outliers installation counts that significantly differ from expected patterns.
•	Looking to see if certain times consume, or refrain from consuming, specific materials or diameters.

Root Cause Analysis:
•	It identifies problems in terms of installation practices, material choices or site specific factors and thus may inform potential causes of anomalies.
•	Comparing the findings with statistical comparison and historical data trends.

Tools and Technologies:
Amazon S3, Amazon Athena, AWS Glue DataBrew, Power BI visualization tools, Matplotlib
Deliverables:
•	Identified Anomalies, explained by way of Diagnostic Analysis Report.
•	Abnormal trends with their associated causes that can be displayed visually.

 

Data Wrangling
Project Description:
Data Wrangling on the Dedicated Fire Protection Systems (DFPS) Water Mains Dataset to clean, transform and organize the data to structure the data so as to allow for meaningful and non manipulated structured analysis.

Title of the Project: Data Wrangling for DFPS Water Mains Data Analysis

Objective:
Preparing the DFPS Water Mains dataset to be cleaned, transformed, and standardized from all sorts of inconsistencies, missing values, and incorrect format. The idea is to prepare the data so that you can put it for further analysis using Amazon Athena and others.

Dataset:
•	Dedicated Fire Protection Systems (DFPS) Water Mains CSV File
•	Pipe Material, Installation Year, Pipe Diameter and Location are the fields.
•	The data is in Amazon S3 and is processed using AWS Glue DataBrew.


Methodology:
Data Ingestion:
•	Then the data was uploaded to Amazon S3 for storing in a reliable and scalable manner.
•	Amazon Athena had been configured to easily access AWS Glue Data Catalog.

Data Profiling:
•	The dataset quality was determined using AWS Glue DataBrew.
•	Checking for inputs on columns and identifying values missing, wrong data types and inconsistencies.
•	Error detection of entries with incorrect delimiters and incorrect column formats.

Data Cleaning:
•	It applied transformations through AWS Glue DataBrew, such as:
•	Removing missing or irrelevant entries.
•	Standardizing column names and formats.
•	Addressing data type inconsistencies
•	Removing duplicates, then correcting the typos.



Data Transformation:
•	Consistency of pipe material and diameter labels.
•	Turning date type iinformation into the same format.
•	If data is required to be aggregated to increase readability.

Data Consolidation:
•	s3://processed-dataset is stored back to Amazon S3 for further analysis with Amazon Athena.
•	Structured the naming convention and ensured data integrity through the metadata management.

Tools and Technologies:
Amazon S3, AWS Glue DataBrew, Amazon Athena

Deliverables:
Transformed and Cleaned Dataset ready for Analyzing.
Same process as the data wrangling report.
 




Data Quality Control

Project Description:
Data Quality Control measures for the Dedicated Fire Protection Systems (DFPS) Water Mains Dataset to implement accuracy, consistency, completeness, and reliability of data over the analysis process.

The project title: Data Quality Control for DFPS Water Mains Data

Objective:
In order to profile, cleanse and validate the data set to create robust data quality standards within profiling, cleansing, validating, and monitoring the data set to ensure that the data used is accurate and reliable.

Dataset:
•	Dedicated Fire Protection Systems (DFPS) Water Mains CSV File
•	The fields are Pipes Material, Installation Year, Pipe Diameter and Location.
•	Amazon S3 is used to store data and AWS Glue DataBrew is used to process.


Methodology:

Data Profiling:
•	Assessed data completeness, validity and uniqueness and were conducted using AWS Glue DataBrew.
•	Removed identified values because they’re missing, duplicates, inconsistent formats and data type mismatches.

Data Cleansing:
•	Applied transformations via AWS Glue DataBrew:
•	Removal of duplicates.
•	Fixing of text values to a standard (e.g., normalize material names).
•	Imputation or exclusion of missing values where necessary.
•	Correcting incorrect data types.

Data Validation:
•	Valdied the data for integrity.
•	The installation years were ensured that they fall in a reasonable range.
•	Confirmed the pipe diameters and involved materials were correct according to standard values.

Data Monitoring:
•	All this was implemented within AWS Glue DataBrew.
•	You ensure continuous quality monitoring with scheduled regular profiling tasks.

Documentation:
•	Each step in the data cleaning and validation was recorded for transparency.
•	Kept the processed datasets in version history for the future reference.

Tools and Technologies:
Amazon S3, AWS Glue DataBrew, Amazon Athena

Deliverables:
It is Data Quality Control Report containing found problems and resolutions.
 




Data Governance

Project Description:
Ensuring the effective implementation of a Data Governance framework for the Dedicated Fire Protection Systems (DFPS) Water Mains Dataset that is responsible for the accessibility, data consistency, and data organization.

Title: Data Governance for DFPS Water Mains Data

Objective:
The need to set up a structured data governance system that will ensure that the data gets catalogued in a proper way, accessible by authorised users and consistent in its management throughout the lifecycle of the data.

Dataset:
•	Dedicated Fire Protection Systems (DFPS) Water Mains CSV File
•	These fields namely include Pipe Material, Installation Year, Pipe Diameter, and Location.
•	Data in Amazon S3 is stored and registered via AWS Glue Data Catalog.

Methodology:
•	Metadata Management:
•	AWS Glue Data Catalog is configured to create one centralized metadata repository.
•	It defined the table and column names with descriptive names to help data usability.
•	Ensured metadata consistency for seamless querying through Amazon Athena.

Access Control Management:
•	IAM Policies were implemented to define the datasets for role based access.
•	Restricted data access to authorized users and services only.
•	Roles, which can be applied such as Data Analyst, Data Engineer and Administrator for enforced permissions.

Data Consistency:
•	Fostered the process of standardised dataset, table and column naming.
•	Enforced versioning to maintain the dataset’s historic integrity and alter the dataset.

Data Discovery:
•	This enabled the datasets to be indexed using AWS Glue Data Catalog for efficient discovery of related data.
•	It ensured that data sets can be searched and queried easily by authorized users.

Documentation:
•	The metadata structure and access controls were kept maintained in comprehensive documentation.
•	Brought the policies and procedures applied for data governance into the record.

Tools and Technologies:
Amazon S3, AWS Glue Data Catalog, IAM Policies

Deliverables:
Metadata structure, access management and consistency processes to be outlined in Governance Documentation.

 





Data Security

Project Description:
The purpose of this is to implement Data Security measures for the Dedicated Fire Protection Systems (DFPS) Water Mains dataset such that this dataset is protected from unauthorized access, tampering, or loss at all points of this lifecycle.

The title of the project: Data Security for DFPS Water Mains Dataset

Objective:
The purpose of handling DFPS Water Mains dataset by encrypting, controlling and monitoring access should be established and made flexible to comply with the DFPS standard.

Dataset:
•	Dedicated Fire Protection Systems (DFPS) Water Mains CSV File
•	The set of fields include Pipe Material, Installation Year, Pipe Diameter, and Location.
•	AWS Glue Data Catalog validates this with those tables in Amazon S3.


Methodology:

Data Encryption:
•	When implementing KMS to protect data at rest in Amazon S3, you can store the key in a hardware security module through an instance of AWS KMS in the region.
•	It enabled automatic encryption on data storage in Server Side Encryption (SSE).
•	I configured bucket policies that required encryption when uploading.

Access Control:
•	Restrict access to the dataset with the defined IAM Policies.
•	Different user groups were configured role based access controls.
•	I have written and applied S3 Bucket Policies and ACLs (Access Control Lists) to determine how data can be accessed.

Data Integrity:
•	Preserving historical copies of datasets was done by applying versioning to Amazon S3 buckets.
•	Added AWS CloudTrail implementation to log the access and modifications.


Monitoring and Alerts:
•	Also got data access and performance metrics fed to Amazon CloudWatch.
•	Bounded the access attempts with CloudWatch Alarms to detect them and then notify us about it.
•	To send notifications on the finding of anomalies used used Amazon SNS (Simple Notification Service).

Documentation and Compliance:
•	Keept a record of all security policies and procedures.
•	Ensured adherence to data security best practices as per AWS guidelines.

Tools and Technologies:
Amazon S3, AWS KMS, IAM Policies, AWS CloudTrail, Amazon CloudWatch, Amazon SNS

Deliverables:
Finally, a Data Security Report documenting all security measures that were set.


 
 




 
AWS Course Completion Badge: https://www.credly.com/badges/18fd1b6b-e74f-497b-b913-8d169f2c8753/public_url


