COVID-19 Vaccination Data Analysis and Visualization
Description
This repository contains code for the analysis and visualization of COVID-19 vaccination data from around the world. The dataset used for this analysis is sourced from Kaggle, specifically from https://www.kaggle.com/gpreda/covid-world-vaccination-progress. The dataset provides information about the vaccination progress in various countries, including details like the total number of vaccinations administered, the number of people vaccinated, the number of people fully vaccinated, and more.

Key Components
Initialization: The code initializes by importing necessary libraries, including Pandas for data manipulation, Matplotlib for data visualization, and Google Colab for working with files. It also mounts Google Drive to access the dataset.

Data Loading: The dataset, named 'country_vaccinations.csv,' is loaded into a Pandas DataFrame named vaccinations_df.

Data Preprocessing: The code performs several preprocessing steps, including:

Splitting the date into separate year, month, and day columns.
Converting date columns to the datetime format.
Handling missing values by filling NaNs with zeros.
Data Description: The code provides information about the dataset, such as its source, size, and the date range of data.

Column Descriptions: Detailed descriptions of each column in the dataset are provided, including data type, categories for categorical columns, and the count of missing values for each column.

Data Analysis and Visualization: The code conducts various data analysis and visualization tasks, including:

Summarizing key statistics of the dataset.
Displaying the most commonly used vaccines.
Visualizing the dynamics of daily vaccinations.
Showing the top countries with the highest number of fully vaccinated individuals.
Analyzing the relationship between variables, such as people fully vaccinated vs. people vaccinated, and daily vaccinations per million vs. daily vaccinations.
Examining the number of daily vaccine doses administered per million people for specific countries.
Identifying countries with the highest percentages of fully vaccinated populations.
Conducting monthly vaccination analysis for specific countries, like Indonesia.
Conclusions
The code and analysis in this repository provide valuable insights into COVID-19 vaccination data. Some key findings and takeaways include:

The repository includes thorough data preprocessing steps to prepare the dataset for analysis.
Important statistics and visualizations, such as dynamics of daily vaccinations and top countries with fully vaccinated individuals, are presented.
Relationships between various vaccination-related variables are explored through scatter plots.
The code demonstrates the ability to conduct country-specific analysis, such as examining vaccination trends on a monthly basis for specific countries.
This repository serves as a useful resource for anyone interested in understanding and visualizing COVID-19 vaccination data on a global scale.# GDSCITB_PROJECT
