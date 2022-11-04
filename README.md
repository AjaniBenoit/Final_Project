# Final-Project
## Group 4 Final Project


### Analyzing US Traffic Fatality Data Across 50 States From 2011 to 2020

### Communication Protocol

Group 4 will meet on Monday, Wednseday and Sunday to work on the Project. In addtion to meeting, Group 4 has a dedicated Slack channel that members can post comments, questions or updates.

GitHub will be used to store all project related date and files. Each group member is assigned a primary and back-up role for the duration of the project. 

### Reason why topic was selected 

In initial discussion among the group, members were divided between selecting a topic related vehicular data and public health data. 

While completing our initial search for data, group realized that a vehicular and public health data could be merged into one project. We decided initially to explore DUI vehicular fatalities. 

As the group worked on the project, we made the decision to look at vehicular fatalities in general. Cause of the traffic fatalities such as DUI, speeding could further be refined later in our project. 


### Description of Data source

Raw data comes from National Highway Traffic Safety Administration data tables. Data was downloaded for 50 states. A total of 150 .csv files were downloaded and then combined into 3 .csv files using terminal and the following command "*.csv >combine.csv". The combined .csv files were then cleaned using Excel, duplicate entries were removed from the cleaned files. 

The States Name, Region and Division was pulled from US Census Website and consolidated into .csv file. 

Website: https://cdan.nhtsa.gov/SASStoredProcess/guest

Webiste: https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf

[Performance_measure.csv](https://github.com/pperlinski/Final-Project/blob/main/Performance_measure.csv)

[STSI Combined.csv](https://github.com/pperlinski/Final-Project/blob/main/STSI%20Combined%20.csv)

[Table 1 Combined.csv](https://github.com/pperlinski/Final-Project/blob/main/Table%201%20Combined.csv)

[U.S. Census Bureau Regions and Divisions with State.csv](https://github.com/AjaniBenoit/Final_Project/blob/main/U.S.%20Census%20Bureau%20Regions%20and%20Divisions%20with%20State.csv)


### Questions we hope to answer

1.	Are traffic fatalities increasing or decreasing across all 50 States?
2.	What state has the highest and lowest rate of traffic fatalities?
3.	Are DUI fatalities increasing or decreasing across all 50 States?
4.	Can we predict the number of traffic fatalities for 2021 using Machine learning?

### Exploratory Data Analysis 

Python and Jupyter Notebook were used to complete an exploratory analysis of the Performance_measure.csv file, STSI_Combined.csv file and the Table_1.csv file. 

The Performance_measure.csv file was loaded and read into a data frame. For the initial analysis of the data it was determined that we would only examine Core Outcomes that were Traffic Fatalities. All other outcomes were removed from the database. The mean and standard deviation was calculated for each State from 2011 to 2020. 

The cleaned Performance_measure data frame was read into a .csv file to be used in the Machine learning portion of the project. 

The STSI_Combined.csv file and Table_1 file were both loaded and read into separate data frames. The data frames were then merged. Duplicate columns were dropped.  The mean and standard deviation was calculated for each state as well as for the years between 2016 and 2020.


### Machine learning

The set up is based on creating a machine learning environment that will imitate a model that will perform a statistical algorithms, by inputing data into the machine learning environment to study patterns and make predictions by using mathematical representaion of the input data.

Supervised Learning- bese on labeled data, the data retrieved is clean and prepare for machine learning environment. import of dependencies are placed in the first cell of the machine learning notebook i.e import pandasas pd, from pathlib import pat, import matplotlib.pyplotas plt and from sklearn.linear_model import LinearRegression


We will like to develop a model that predicts trends involving vehicle fatalities across all 50 states. 


### Database

SQL and Postgres will be used to construct the database. The ERD below shows a draft of the database structure. 

![QuickDBD-export(1).png](https://github.com/pperlinski/Final-Project/blob/main/QuickDBD-export%20(1).png)
