# Influenza Staffing Analysis
## Project Summary
This project involves an in-depth analysis of population data, influenza deaths data, and influenza visits data for a medical staffing agency to plan for the upcoming influenza season. The objective of the analysis is to generate a staffing plan for the distribution of temporary medical staff to hospitals and clinics across all US states in preparation for the upcoming influenza season. The analysis also aims to inform the timing for the distribution of medical staff and determine which states require more staff than others. The analysis was conducted in Excel and visualizations were generated in Tableau. The insights derived from the visualizations will help the medical staffing agency to allocate the appropriate amount of temporary medical staff to each state at the appropriate times of the year which will ensure that there are adequate medical staff available to treat the increased number of patients during the influenza season.
## Key Goals
- Provide information to support a staffing plan, detailing what data can help inform the timing and spatial distribution of medical personnel throughout the United States.
- Determine whether influenza occurs seasonally or throughout the entire year. If seasonal, does it start and end at the same time (month) in every state?
- Prioritize states with large vulnerable populations. Consider categorizing each state as low-, medium-, or high-need based on its vulnerable population count.
- Assess data limitations that may prevent you from conducting your desired analyses.
## Data
Datasets used for this project:
- [Influenza deaths by geography from CDC](https://coach-courses-us.s3.amazonaws.com/public/courses/da_program/CDC_Influenza_Deaths_edited.xlsx)
- [Population data by geography, time, age, and gender by US Census Bureau](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/Census_Population_transformed_202101.csv)
- [Influenza visits data from CDC (Fluview)](https://images.careerfoundry.com/public/courses/data-immersion/A1-A2_Influenza_Project/CDC_Influenza_Visits.xlsx)
### Influenza Deaths by Geography Dataset
This dataset includes the number of deaths due to influenza by age group for every month of each year from 2009-2017 for each US state. Some of the death counts are suppressed for privacy reasons, and due to this, some influenza deaths data is missing. This dataset is from the Center for Disease Control (CDC) and the data was collected through the US government's vital statistics program.
### Population Data by Geography, Time, Age, and Gender Dataset
This dataset includes the numbers for total population, male total population, female total population and populations of each age group (groups of 5 years) in each county in the United States from 2009-2017. Some counties are missing data for one or more years. This dataset is from the US Census Bureau and the data was collected through the census.
### Influenza Visits Dataset
This dataset includes weekly amounts for the total number of patients that were seen by healthcare providers, the number of providers that saw the patients, and the percentage of visits. This dataset includes data for each state from 2010-2019. Some data is missing for the Commonwealth of the Northern Mariana Islands, Puerto Rico, and the Virgin Islands and for weeks 36-39 and 53 of the year. This dataset is from the Center for Disease Control's Fluview and the data was collected through surveys.
## Tools Used
- Microsoft Excel: To clean and analyze data.
- Tableau Public: To generate visualizations.
## Techniques
The following techniques were used in this project:
- Data profiling
- Data cleaning
- Data quality checks
- Data transformation
- Data integration
- Descriptive statistics
- Statistical hypothesis testing
- Storytelling with Tableau
## Analyzing Data
First, I looked at the total deaths due to influenza by year in the USA from 2009-2017 to see how many additional patients medical staff would be needed for.

![image](https://github.com/user-attachments/assets/8f1b00e3-0923-4a07-9f67-f3b67b5cd244)

I divided the deaths due to influenza by age group, and found that the greatest number of deaths occur in the 65-85+ years age group. This age group is the most vulnerable age group.

![image](https://github.com/user-attachments/assets/9ec1a13f-e5cf-4aed-9f04-6bcdf4159731)
![image](https://github.com/user-attachments/assets/7b4e17f6-163b-481d-867b-9ec541d954b4)

I hypothesized that states with higher populations of people ages 65-85+ would have higher numbers of deaths due to influenza. I used statistical hypothesis testing to test my hypothesis, and this showed that my hypothesis was correct. There is a strong relationship and strong positive correlation between the 65-85+ years population and the total deaths due to influenza.

![image](https://github.com/user-attachments/assets/b05fc2b6-0781-4d9a-92ef-a2b78ae9d2bc)

For each US state, I looked at the population of people ages 65-85+ and influenza death numbers to identify which states will require more medical staff to treat influenza patients. The states with the largest populations of people ages 65-85+ and most influenza deaths are California, New York, Texas, Pennsylvania, and Florida.

![image](https://github.com/user-attachments/assets/b0c307c6-bac0-41d2-8430-5fd06bda6851)

To determine whether influenza occurs seasonally or throughout the year, I analyzed the influenza deaths in each state by month of the year. This led to the discovery that influenza occurs seasonally and results in the most hospitalizations and deaths in January-April and December. The seasonality of influenza is the same every year.

![image](https://github.com/user-attachments/assets/29fc2f2c-1e03-4b5e-888a-cd547d1e7e7e)
![image](https://github.com/user-attachments/assets/7f027767-1909-440e-9c40-c518a6bb48ac)
![image](https://github.com/user-attachments/assets/c32f466a-a9df-423c-9395-75c44b0720ea)
![image](https://github.com/user-attachments/assets/da2d0c6d-150f-4b63-81e0-ceb6985b825f)
## Results and Recommendations
- The most vulnerable age group is 65-85+ years.
- States with larger populations of people in the 65-85+ age group have higher mortality numbers due to influenza.
- The states with the largest 65-85+ years populations and highest influenza mortality numbers are California, New York, Texas, Pennsylvania, and Florida.
- Influenza is seasonal and the most deaths occur in January-April and December.
- The medical staffing agency should allocate more medical staff to California, New York, Texas, Pennsylvania, and Florida than the other states as these states are of higher priority than the others.
- The medical staffing agency should send their staff to each state before December 1st and the staff should remain there until the end of April.
## Visualizations
View visualizations generated for this project here: [Visualizations on Tableau Public](https://public.tableau.com/app/profile/priya.agrawal4103/viz/Book9_17333702165620/InfluenzaStaffingRequirements)
## Contact
If you would like more details about the project, or if you have any questions, please feel free to contact me through [LinkedIn](https://www.linkedin.com/in/priya-agrawal-0929) or [email](mailto:priya.agrawal0929@gmail.com).
