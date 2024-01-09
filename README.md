# Prediction of Gender Inequality Across the World

## Team Members
- Chaitanya Shekar (cs2046)
- Sangeetha Ramesh (sk2224)
- Weiye Zhu (wz250)
- Yaxin Ye (yy690) 

## Table of Contents
- [Project Description](#project-description)
- [Data and Analysis](#data-and-analysis)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Poster Content Details](#poster-content-details)
- [Report Content Details](#report-content-details)
- [Data Source](#data-source)

## Project Description
Global gender inequality continues to be a prevalent issue, as women frequently experience disparities in career advancement, economic prospects, and educational access. 

This project aims to understand various aspects of gender inequality worldwide, and identify the factors that influence these disparities and their changes over time. By examining these factors, we can identify the causes, track changes, and inform policies for gender equality. Our main focus is on predicting Gender Inequality Index (GII) values using different regression models and comparing their performances based on Root Mean Square Error (RMSE).

## Data and Analysis
The data used in this project comes from various sources and includes different aspects of gender inequality, such as education, employment, and political participation. The data folder contains all the raw data and the clean data used for analysis.

We applied diverse methods to analyze global gender inequality, informing policies and actions for promoting equity. We compared gender disparities worldwide, considering social, economic, and political factors. We used various regression models like Linear Regression, Ridge Regression, LASSO Regression, and Random Forest to predict the GII values.

## Repository Structure
The repository is structured as follows:

- `main` branch: Contains the main version of the project.
- `weiye_zhu`, `Chaitanya`, and `sk224` branches: These branches are used by individual team members to work on their tasks.
- `code` folder: Contains all the code that we used to do the data munging, EDA, and modeling.
- `data` folder: Contains all the raw data and the clean data.
- `img` folder: Contains all the images and plots we used for the poster.
- `poster` folder: Contains our final version poster.
- `report` folder: Contains our final version of the report.
- `.gitignore`: For removal of all the junk files.
- `README.md`: This README file.

## Getting Started
1. Clone this repository to your local machine.
2. Navigate to the `code` folder to find the Python and HTML code used for data munging, EDA, and modeling.
3. To reproduce the analysis, first, install the necessary packages listed in the `requirements.txt` file. Then, run the Python code in the same order as listed in the folder.
4. Access the `data` folder to find the raw and clean data used for analysis.
5. The `img` folder contains all the images and plots used in the poster. You can access the final version of the poster in the `poster` folder.
6. The `report` and `poster` folders store the final versions of the poster and report of the study.

## Poster Content Details
Our poster, titled "Prediction of Gender Inequality Across the World", consists of the following sections:

1. Introduction
2. Analysis & Methods
3. Results
4. Conclusion

For more details on the content of each section, please refer to the [detailed project description provided above](#project-description).


## Report Content Details
The final report of our study consists of the following sections:

1. Introduction
2. Background
3. Methodology
 
    3.1 Data Collection

    3.2 Data Processing

    3.3 Models

        3.3.1 Linear Regression Model

        3.3.2 Ridge Regression Model

        3.3.3 LASSO Regression Model

        3.3.4 Random Forest Model

    3.4 Model Evaluation

    3.5 Limitations

4. Findings
5. Conclusions
6. References

## Data Source
The primary data source for this project is:

UNDP. (2021). Gender Inequality Index data In Human Development Reports. https://hdr.undp.org/sites/default/files/2021-22_HDR/HDR21-22_Statistical_Annex_GII_Table.xlsx

The file contains 2021 gender inequality index values, maternal mortality ratio, adolescent birth rate, the share of seats in parliament, etc. for all the countries in the world.