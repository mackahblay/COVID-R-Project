# COVID-19 Exploratory Data Analysis Report

Melchizedek Ackah-Blay
2024-03-06
Project Overview
Project Description

The COVID-19 Exploratory Data Analysis Report aims to provide a detailed preliminary analysis of COVID-19 patient data to inform the development of a new vaccine, COVIDA, at Sigalo Research. This project involves cleaning, merging, and analyzing datasets containing information on patients quarantined globally, both with and without COVID-19. The goal is to extract meaningful insights about the demographics, comorbidities, and other relevant characteristics of COVID-19 patients.
Objectives

   ## Data Cleaning and Preparation:
   - Import two datasets: coronavirus.xlsx and comorbid.xlsx.
   - Merge the datasets using a common identifier.
   - Recode implausible age values and standardize country names.

   ## Exploratory Data Analysis:
   - Calculate the number of observations and variables.
   - Determine the percentage of female patients.
   - Calculate the median age of COVID-19 patients.
   - Find the mean age and standard deviation of patients who died from COVID-19.
   - Analyze the geographical distribution of COVID-19 patients from China, Italy, and the US.
   - Identify and quantify comorbidities associated with COVID-19 patients.

    Data Visualization:
   - Create a boxplot to visualize the age distribution by COVID-19 status.

## Steps Taken

    Data Cleaning and Preparation:
   - Importing Data: Successfully imported coronavirus.xlsx and comorbid.xlsx into R, resolving initial import errors by suppressing warnings and messages.
   - Merging Datasets: Merged the datasets on the common 'ID' column using an inner join.
   - Recode Values: Reassigned ages 120 or older to NA and standardized country names from 'Mainland China' to 'China'.

    Exploratory Data Analysis:
   -  Number of Observations and Variables: Counted rows and columns in the merged dataset.
   - Percentage of Female Patients: Calculated the percentage of female patients by evaluating the 'Sex' column.
   - Median Age of COVID-19 Patients: Filtered for COVID-19 positive patients and calculated the median age.
   - Mean Age and Standard Deviation of Deceased COVID-19 Patients: Computed the mean age and standard deviation for patients who died from COVID-19.
   - Geographical Distribution: Analyzed the percentage of COVID-19 patients from China, Italy, and the US.
   - Comorbidity Analysis: Grouped data by comorbidity to determine the prevalence of different comorbidities among COVID-19 patients.

    Data Visualization:
   - Boxplot Creation: Created a boxplot to visualize the distribution of age by COVID-19 status, enhancing the plot with color for clarity and aesthetic purposes.
