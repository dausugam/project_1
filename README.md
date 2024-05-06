# Data Analytics Boot Camp - Project 1, Group 2

## Overview

Welcome to the Data Analytics Boot Camp Project 1 repository, created by Group 2. Within these repositories, we have analysed the Drug Consumption of illegal substances and its relationship with different demographic information.

The analysis was conducted by:
- Daniel Usuga
- Lisa Shimano
- Rock David Adeline
- Tammy Powell

## Data Source

The Database contains records for 1,885 respondents (rows). For each respondent 12 attributes are known:
- Demographic Information: age, gender, education, country, and ethnicity.
- Personality Traits Information: five factor model, impulsiveness, and sensation seeking

Furthermore, each participant was questioned in the use of 18 different legal and illegal drugs. or each drug they must select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day.

The initial database was downloaded from kaggle.com at:

https://www.kaggle.com/datasets/mexwell/drug-consumption-classification

## Analysis Objective

Our overarching aim in this analysis is to discern and delineate any differentials in drug consumption behaviours across diverse demographic information.

## Data Analysis Structure

### Data Cleaning

And initial procedure for data cleaning was conducted (see file data_cleaning.ipynb) to transform the raw data according to the necessities of the analysis and a new cleaned data was created (data/drug_consuption_clean.csv).

### Drug Consumption Analysis

#### By Country

The proportion of drug usage per country and geographical location is analysed and presented using API HVplots (see file david_drugs_analysis.ipynb).

#### By Gender

A statistical analysis is presented to understand if there is any significative difference in Drug Consumption patterns between Men and Women (see file analysis_by_gender.ipynb).

#### By Age Group

A graphical analysis using matplotlib is presented to understand if the consumption of drugs reduces as people grew older for different types of illegal substances (see fiel Age_Group_Analysis.ipynb). 