# Project 2: More Data, More Visualizations

For this project, the students will:
* find a data set of their choosing
* get approval from the instructor to use that data set
* upon approval, find another (related) data set
* join the new data set with the original one to create an "enriched" data set
* perform an open-ended Exploratory Data Analysis (EDA) on the enriched data set

Regarding the last bullet, "open-ended" means the student chooses the EDA that is performed. The student should have at least three types of data analysis (e.g., mean, standard deviation) and at least three types of graphs (e.g., historgram, bar graph). The student will explain why those variables were chosen for numerical or graphical analysis. Finally, the student will make note of any unusual values for any variable that is analyzed.
# Project 2: More Data, More Visualizations
For this project, the students will:
* find a data set of their choosing
* get approval from the instructor to use that data set
* upon approval, find another (related) data set
* join the new data set with the original one to create an "enriched" data set
* perform an open-ended Exploratory Data Analysis (EDA) on the enriched data set

Regarding the last bullet, "open-ended" means the student chooses the EDA that is performed. The student should have at least three types of data analysis (e.g., mean, standard deviation) and at least three types of graphs (e.g., historgram, bar graph). The student will explain why those variables were chosen for numerical or graphical analysis. Finally, the student will make note of any unusual values for any variable that is analyzed.
## Start of Project. Group_2_Final.
The Data Set Chosen is an Online Amazon Online Sales Data Set Showing Sales In India by State. The data was Sourced from Kaggle and it is available to the public.
The Data Set was merged with the India Socio-Economic Data Set from India Census 2011.
## Background 
Literacy and Urbanisation Data contained in the India Data Set, can be used to extract and predict online sales. Since the use of devices largely depends on Population Literacy and Internet Availability.
The two datasets are available to the public and they are also published on kaggle. Here are the links; -https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data 
-https://www.kaggle.com/datasets/webaccess/all-census-data?select=elementary_2015_16.csv 
## Problem Statement.
Based on the above background the project intents to answers the question; How does the Population Literacy and Urbanization affects Online Sales.
## Project Objectives.
1. To explore probable business correlations based on the sales data and the Socio economic data.
2. To establish any limitation to the interpretation of the results and their impact on the data
3. To establish dominant trends based on categories such as Gender, State, Months etc. that may be used to     leverage profit.
4. To establish the Correlation and Pattern Discovery for our two Data-sets.
5. To provide Comprehensive, Communication reporting and actionable Recommendations.
## Data.
The Merged Data Set contains the following Columns and their description.
"ORDER ID" - The unique Identifier for each order from Amazon Online Store.
'DATE' - The Date of Purchase.
'STATUS',  - Different Stages of Shipments; Delivered, Cancelled, On Transit etc
'QTY',  - Quantity Purchased.
'AMOUNT', - Total cost for products in India Rupee.
'SHIP-CITY', - Destined Location of the purchased product
'TOTAL_POPULATION', - Total Number of persons per state
'PERCENTAGE_URBAN_POPULATION', - Percentage of the total population in a state living in a City.
'SEX RATIO', - Female Male Distribution.
'OVERALL_LITERACY', - Percentage of the total population that is considered educated.
'FEMALE_LITERACY', - Percentage of the total female population that is considered educated.
'MALE_LITERACY', - Percentage of the total male population that is considered educated.
'DAY', - Day of the week that the items were purchased.
'MONTH', - Month of the year that the items were purchased.
'URBAN_POPULATION',  - Total population in a state living in a City.
'LITERATE_POPULATION', - Total population in a state considered educated.
'LITERATE_POPULATION_MALE', - Total male population in a state considered educated.
'LITERATE_POPULATION_FEMALE' - Total female population in a state considered educated.
## Data Cleaning Process.
Checking Null Values.
Remove Null Values.
Renaming the Columns.
Changing the Data Types.
Removing Outliers.
## EDA Performed.
Checking measures of central tendencies and dispersion. (Mode, Median, Standard Deviation)
We used groupby functions and Pivot Tables. 
Checked Pearson Correlation between Columns
Created new Columns based on existing columns (Urban Population, Literate Population) etc.
## Findings
* Literacy in directly correlated to online sales.
* Urban Populations tends to buy more than rural population.
* High sales were recorded during the weekend (Sunday)
## Way Forward.
* Targeted Advertisement during the weekend, to maximise on the sales.
* Target Customers based on level of Education
* Increase presence in cities to target urban population