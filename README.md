# Life Expectancy research project

This is a research project where the company 'Data Analytixs' is trying to get insight on how the world has changing from past 34 years in terms of life expectancy, income, population, child mortality and children born per woman.

In 1900, the average life expectancy of a newborn was 32 years but by 2021 this had more than doubled to 71 years. People are living longer than before.

According to 'Our World in Data' published article, the changes has occured due to the reduction in child mortality which played an important role in this. Not just the life expectancy has increaded in new born child but also in Infants, children, adults, and the elderly people and the death is being delayed.

The shifts, in the result comes from many factors, changes in life style, medicine advances, public health and the living standards. People now a days try to keep themselves more fit, average number of people take help through Gym and yoga, practicing meditation and food habits too. And along with it, the prediction which was there for life expectancy in past has been broken.

"The objective of this project is to is to do research using the dataset of gapminder to find the changes in the world happened in the last few decades in terms of life expectancy, population, child born per women and child mortality."



# Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|country|object|../data/life_expectancy.csv|country names of life expectancy datasets
|1800 - 2023|float64|../data/life_expectancy.csv|The life expectancy details in units
|country|object|../data/population.csv|country names
|1800 - 2023|float64|../data/population.csv|The population of the country(units in thousands and millions)
|country|object|../data/daily_income_per_person.csv|country names
|1800 - 2023|float64|../data/daily_income_per_person.csv|The income of the person(units in thousands and millions) 
|country|object|../data/children_per_women_total_fertility.csv|country names
|1800 - 2023|float64|../data/children_per_women_total_fertility.csv|children born per 1000 women   
|country|object|../data/child_mortality_0_5_year_olds_dying_per_1000_born.csv|country names
|1800 - 2023|float64|../data/child_mortality_0_5_year_olds_dying_per_1000_born.csv|Year column names 
|country|object|../data/countries-continents.csv|country names
|continent|object|../data/countries-continents.csv|continents names 



# Executive Summary

This project addresses the following Data Analysis topics:

- Data Exploration and Preparation

- Data Representation and Transformation

- Data Visualization and Presentation

- Data Exploration and Preparation Learn about data: Are there missing data? Is it categorical? if not, min , max, avg values? if yes, what are the categories? distribution of variables Duplicate entry

### Work I performed in python notebook:
- Imported libraries such as pandas, numpy, seaborn, matplotlib.
- Cleaned data, check for any null values, fix the null values, checked datatype and changed if it wasn't correct.
- Performed exploratory data analysis
- Performed data visualization where I created scatter plot, boxplot, line, histogram.

## Conclusions and Recommendations
For this research work, I choose gapminder datasets for life expectancy, population, income per person, child mortality, children born per woman.


### Findings:
- The contient which has changed most in life expectancy from 1989 to 2023 is: Oceania
- The continent which has changed most in income per person from 1989 to 2023 is: Europe
- The contient which has changed most in population from 1989 to 2023 is: Africa
- The contient which has changed most in fertility from 1989 to 2023 is: Asia
- The continent which has changed most in child mortality from 1989 to 2023 is: Africa


### Resources for research and help with coding
- Our world in data
- Stackoverflow
- W3schools.org
- Previous classworks, lab works and quizzes

