# Influenza Staffing Plan
**Purpose and Context:** The United States has an influenza season where more people than usual suffer from the flu. This analysis aims to assist a medical staffing agency in planning for influenza season by examining historical trends to proactively address staffing needs across the U.S. 

### Tableau Storyboard
You can visit my [Tableau Storyboard](https://public.tableau.com/app/profile/nirav.bariya/viz/Exercise2_9_17110453323300/InfluenzaStory?publish=yes) to understand the analysis in brief highlighting the key aspects:
You can also checkout the [video presentation](https://www.youtube.com/watch?v=bJ7_mNFz3k4) that I have created. This will give you the most important insights in an easy way. 

### Project Goals:
- Classify states based on vulnerable population.
- Determine influenza season.
- Determine which states requires most staff.

## Tools and Techniques
For conducting this analysis I have used **Excel** as my main tool and for presenting the results of the analysis to our stakeholders I have used **Tableau Public**.
Following are some of the skills and methodologies that have gone into the making of this project:
* Data Profiling
* Data Cleaning
* Data Transformation
* Data Integration using Vlookup
* Hypothesis Testing
* Forecasting
* Story Telling with Tableau

## Datasets
The following data sets covering influenza in the United States will be used during the project:
1. [Influenza Deaths by Geography](https://coach-courses-us.s3.amazonaws.com/public/courses/da_program/CDC_Influenza_Deaths_edited.xlsx)
2. [Population Data by Geography, Time, Age, and Gender](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/Census_Population_transformed_202101.csv)

The influenza deaths dataset comes from Center for Desease Control(CDC) and population data is from US Census Bureau. 
### Census Data
The dataset is likely representative of the population due to various data collection methods. However, some county population data is missing for certain years, which limits aggregation and yearly state-wise comparisons. Additionally, the annual data collection process creates a gap between survey and publication, potentially introducing errors. Manual data entry could also cause inaccuracies. Nonetheless, since the data is from a government agency, it is likely to have minimal errors and is the best available source for this analysis.
### CDC Influenza Deaths Data
Puerto Rico data is missing, so we can't accurately describe flu-related deaths there. Some data is suppressed for privacy, meaning not all influenza deaths are included. The analysis results will only apply to 2018, as the data spans 2009-2017, and may not be relevant for the current year. Despite these limitations, this is the most accurate dataset available for our analysis.
### Preprocessing Data:
The first step of finding a solution for the staffing agency to meet the staffing need of the country was to understand and clean the data. I took these steps to understand the data and preprocess the data to make sure it’s ready for the analysis that is to come.

1. Prepared Project Management Plan
2. Performed Data Quality Checks
3. Created Data Profiles for Raw Data
4. Checked for errors and consistency in the data
5. Addressed missing values and duplicated rows
6. Creating summary statistics for cleaned data

### Challenges Encountered:
* All the deaths for less than 5 years age group were suppressed due to privacy concerns.
* For age group 15-24 and 5-14, 99% of the deaths were suppressed.Deaths were suppressed wherever the count was less than 10.
* I did not impute deaths as most of the data was suppressed.

## Summarizing and Analyzing Data 
I started with exploring the number of deaths that had taken place in recent years to understand the severity of the problem. Moreover, doing so helped me capture the recent trend of influenza.
<p align = "center">
  <img width="45%" alt="image" src="https://github.com/user-attachments/assets/ed9d255c-de3e-4fbf-a40c-f35fa28b6011">
</p>

<p align="center">
  <img alt="Light" src="https://github.com/user-attachments/assets/d19ce87d-2b67-4c25-91b8-c6644947b6e1" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Dark" src="https://github.com/user-attachments/assets/a1cbc7ea-2f0e-445f-982e-a4b96c4e8e45" width="45%">
</p>

* The impact of influenza on people having age over 65 years is clearly much more severe than other people as 91.30% deaths were recorded in this age group between 2009-2017.
<p align="center">
<img width="672" alt="image" src="https://github.com/user-attachments/assets/87d8d047-b15b-4ee6-bc9b-247334e867d7">
</p>

* I categorized the states in three categories, high risk, medium risk, low risk, based on deaths in 65 years and above age group and mortality rate of states.
* California, New York will belong to high-risk category.
* Texas, Pennsylvania, Florida, Illinois, and Ohio will belong to medium risk category.

For more thorough analysis, I urge you to visit Tableau Dashboard. It will also help you clarify any questions you may have.

