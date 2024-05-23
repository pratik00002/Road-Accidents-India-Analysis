# Road-Accidents-India-Analysis
1. Introduction

India has the highest number of road fatalities in the world. According to the World Health Organization, India accounted for more than a third of global road accident deaths in 2016. This project aims to perform a detailed statistical data analysis of road accidents in India over the period from 2003 to 2016. By analyzing various datasets, we aim to uncover insights and trends that can inform policies to reduce road accidents and fatalities.
2. Objectives

The primary objectives of this project are:

    To calculate the percentage of road accidents during all the years.
    To find the mean number of accidents per 1 lakh population for each year.
    To identify the states with the highest and least number of accidents.
    To analyze deaths of offenders and victims by gender.
    To calculate the percentage of deaths due to non-wearing of helmets between males and females.
    To analyze the number of accidents happening per state from 2003 to 2016.
    To analyze accidents, injuries, and deaths occurring as per the number of lanes.
    To analyze accidents, injuries, and deaths due to various reasons and vehicle types.
    To analyze accidents occurring during different times of the day.

3. Data Sources

We utilized the following datasets for our analysis:

    roadAccStats13-16.csv: Data on road accidents per lakh population by state and year.
    Details_of_road_accident_deaths_by_situation_state_2014.csv: Data on offender and victim deaths by gender and state.
    Persons_killed_due_to_Non-use_of_Safety_Device_2016.csv: Data on deaths due to non-use of safety devices by gender.
    datafile.xls: Data on total number of accidents from 2003 to 2016 by state.
    laneAccidents.csv: Data on accidents, injuries, and deaths by the number of lanes.
    reasonOfAccident.csv: Data on accidents, injuries, and deaths by various faults/reasons.
    typeOfVehicle.csv: Data on accidents, injuries, and deaths by vehicle type.
    timeOfOccurence.csv: Data on the number of accidents by time of occurrence.

4. Methodology

The analysis was conducted in Python using libraries such as pandas, numpy, matplotlib, and seaborn. The steps included:

    Loading Data: Importing all datasets into the Python environment.
    Data Cleaning: Checking for and handling missing values and inconsistencies.
    Data Analysis: Performing statistical analysis and creating specific variables for each analysis requirement.
    Visualization: Creating graphical representations to better understand the data and the results.

5. Results
5.1 Percentage of Road Accidents During All the Years

The percentage of road accidents for each year was calculated. The results showed fluctuations with certain years having significantly higher or lower percentages.
5.2 Mean Accidents per 1L Population for Each Year

The mean number of accidents per 1 lakh population was computed for each year. The analysis revealed trends and variations in road safety over the years.
5.3 Highest and Least Number of Accident States

We identified the states with the highest and least number of road accidents. This helps in understanding regional disparities in road safety.
5.4 Offenders and Victims Who Died According to Gender

The number of deaths of offenders and victims was analyzed according to gender. The total deaths were also computed to provide an overall perspective.
5.5 Percentage of Deaths Due to Non-wearing of Helmets Between Male and Female

The percentage of deaths due to non-wearing of helmets was calculated for both males and females. This highlighted the importance of helmet usage.
5.6 Number of Accidents Happening per State from 2003 to 2016

The number of accidents in each state from 2003 to 2016 was analyzed to identify trends and patterns over time.
5.7 Number of Accidents, Injuries, Deaths per Lane Type

The analysis covered accidents, injuries, and deaths for different lane types (single, double, three, and four lanes) per 1 lakh population.
5.8 Accidents, Injuries, Deaths Due to Various Reasons and Vehicle Types

We analyzed the data based on different reasons for accidents and types of vehicles involved to identify key risk factors.
5.9 Accidents by Time of Day

The number of accidents during different times of the day (day and night) for the years 2014 and 2016 was analyzed to understand temporal patterns in road safety.
6. Visualizations

We created various plots to visually represent the findings. For example:

    Bar charts showing the percentage of road accidents per year.
    Line graphs depicting mean accidents per 1 lakh population over the years.
    Heatmaps to visualize regional disparities in road safety metrics.

7. Conclusion

This project provided valuable insights into road accidents in India from 2003 to 2016. The analysis highlighted key trends, risk factors, and regional disparities in road safety. These insights can inform policymakers and stakeholders in developing targeted interventions to improve road safety in India.
8. Future Work

Future analysis could include:

    Extending the study to include more recent data.
    Analyzing the impact of road safety interventions and policies implemented over the years.
    Exploring correlations between road accidents and other socio-economic factors.
