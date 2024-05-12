# Naloxone in Police Scotland Pilot Evaluation

# Project Overview
This mixed-methods research project evaluates a pilot initiative where Police Scotland officers carry and use intra-nasal naloxone, an emergency antidote for opioid overdoses. This initiative is part of Scotland’s response to increasing drug-related deaths, particularly from opioids like heroin and methadone. The pilot was conducted in three regions—Falkirk, Dundee City, and Glasgow East.

# Context and Background
Scotland faces a severe drug mortality issue, significantly higher than the UK average. The Scottish Government's National Naloxone Programme, started in 2011, aims to distribute naloxone widely to those likely to witness an overdose. Building on this, the pilot project tests the practicality and effectiveness of police officers administering naloxone during their duties.

# Research Objectives and Design
The project aims to understand the implications of naloxone use by police officers, focusing on:

Officers' attitudes toward drug use and users.
Experiences and effectiveness of naloxone training.
Barriers and facilitators affecting naloxone use by police.
Community perspectives on police handling of drug overdoses.
The study involves baseline, post-training, and follow-up questionnaires, along with interviews and focus groups. Data collection extends from March to December 2021, involving approximately 700 police officers.

## Sampling and Recruitment
Officers participating in the pilot are selected from the designated areas, with additional interviews planned with community members affected by opioid use and strategic stakeholders.

## Key Measures
Outcomes focus on changes in police attitudes and knowledge regarding opioid overdoses, assessed using specially designed scales like the Opioid Overdose Knowledge Scale (OOKS) and Opioid Overdose Attitudes Scale (OOAS).

# Data Collection and Analysis
Quantitative data from questionnaires will be analyzed for changes in knowledge and attitudes. Qualitative data from interviews and focus groups will explore deeper insights into the practical aspects and perceptions of naloxone use by officers. Data analysis will be supported by software like IBM SPSS and NVivo.

# Data Handling and Preparation
Loading Data: Data from three time points are loaded from Excel files, cleaned to ensure proper formatting and naming conventions using the janitor package, and empty rows and columns are removed for streamlined analysis.
Packages: A variety of R packages are loaded to handle data transformation (tidyverse, collapse), visualization (ggplot2, ggpubr), and reporting (gtsummary, DataExplorer).

## Exploratory Data Analysis (EDA)
Data Inspection: Initial data exploration includes checking structure and types, using functions like glimpse() and assessing column data types to inform further processing.
Descriptive Analysis: Descriptive statistics are provided for key variables, and summary tables are generated to get an overview of the data at each time point.

## Data Transformation
Recoding Variables: Numerical data such as responses coded as 0 or 1 are transformed into factor variables with more descriptive labels (e.g., "Yes", "No") for clarity in analysis and reporting.
Tidying Data Frames: Columns are arranged and potentially renamed for consistency across data sets, ensuring that comparative analysis can be efficiently executed.
Visualization and Reporting
Generating Tables: Descriptive tables are created to display demographics and survey responses in a structured format using the gtsummary package, which provides a clean and professional look suitable for publication.
Demographic Breakdown: Detailed tables are compiled to illustrate the demographics of participants, including gender, age, rank, and area of service, which help contextualize the findings within the specific population of the study.

## Statistical Analysis
OOKS and OOAS Scales: The Opioid Overdose Knowledge Scale (OOKS) and Opioid Overdose Attitudes Scale (OOAS) are utilized to measure changes in knowledge and attitudes towards opioid overdose management before and after training sessions. Responses are summarized and compared across the three survey waves to assess the impact of the training.

## Additional Elements
Data Management: A data dictionary is suggested to be created, documenting the data cleaning and transformation processes, enhancing the reproducibility of the analysis.
Future Reporting: Plans for further analysis and potential expansion of the datasets are indicated, aiming to deepen the understanding of naloxone use and carriage among police officers.

# Ethics and Dissemination
The study adheres to ethical standards approved by Edinburgh Napier University and will be shared with stakeholders, including a comprehensive report for Police Scotland and possibly policy briefings and academic publications.

# Significance
This evaluation is critical for understanding and potentially expanding the role of police in public health responses to drug overdoses, directly addressing an acute public health crisis in Scotland.






