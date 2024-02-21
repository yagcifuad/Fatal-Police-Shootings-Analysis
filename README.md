Capstone Project: Fatal Police Shooting in the United States

Project Overview:
Police brutality in the United States has been a national issue since the 20th century. The public safety of U.S. citizens is a typical argument to justify the controversially high number of fatal shootings. As a contractor to the United States Department of Justice, I have been given a case to investigate fatal police shootings throughout the United States of America,I need to provide a list of issues, and propose a plan on how to tackle these issues. 

The department offered some tips:
Public opinion indicates that there's something systematically fishy about the police actions against civilians.
Some states differ from the others, some cities are different from others, and race equality is still an unanswered question.
There's also some talk about huge spendings on police, rumors about mental issues of those getting shot.
Government is all about prioritizing - use the data to list issues with the police activity and propose a plan which issues to tackle first and how.

Author:
Fuad Yagci

Usage:
Ensure that you have the required datasets (database.csv, state_populations.csv, gun_ownership.csv).Then you can run the provided Python script.

Dataset:
database.csv: Contains information about fatal police shootings.
state_populations.csv: Contains population data for each state.
gun_ownership.csv: Contains information about gun ownership rates and related statistics by state.

# Read the datasets
df = pd.read_csv("/database.csv", index_col=0)
df3 = pd.read_csv("/state_populations.csv", sep=';', decimal=',')
df4 = pd.read_csv("/gun_ownership.csv", header=None)

# About Analysis
Functionality:
Data Exploration: Analyzed the structured and content of the datasets.
Data Cleaning: Kept missing values and removed duplicate rows.
Data Visualization: Visualize various aspects of the data using plots and charts.
Statistical Analysis: Performed statistical analysis to understand relationships and patterns.
Exploratory Data Analysis: Explored the data to identify issues and propose solutions.
Correlation Analysis: Analyze correlations between different factors, such as gun ownership and police shooting rates.


Conclusion:
This project aims to provide insights into fatal police shootings in the United States and propose strategies for addressing the identified issues. By analyzing the available datasets and conducting thorough exploratory data analysis, we can contribute valuable information to the United States Department of Justice's efforts to improve public safety and address concerns about police actions.