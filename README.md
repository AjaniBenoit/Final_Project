# Final-Project
## Group 4 Final Project


### Selected Topic

Our topic is an analysis of DUI and accident data.

### Communication Protocol

Group 4 will meet on Monday, Wednesday and Sunday to work on the Project. In addtion to meeting, Group 4 has a dedicated Slack channel that members can post comments, questions or updates.

GitHub will be used to store all project related date and files. Each group member is assigned a primary and back-up role for the duration of the project. 

### Reason why topic was selected 

Availibility of data, ease and high potential for interesting graphs and visualizations, finding a common ground topic between CDC health data and consumer automotive data that we were interested in.

### Description of Data source

Raw data comes from National Highway Traffic Safety Administration data tables. Data was downloaded for 50 states. A total of 150 .csv files were downloaded and then combined into 3 .csv files using terminal and the following command "*.csv >combine.csv". The combined .csv files were then cleaned using Excel, duplicate entries were removed from the cleaned files. 

[Performance_measure.csv](https://github.com/pperlinski/Final-Project/blob/main/Performance_measure.csv)

[STSI Combined.csv](https://github.com/pperlinski/Final-Project/blob/main/STSI%20Combined%20.csv)

[Table 1 Combined.csv](https://github.com/pperlinski/Final-Project/blob/main/Table%201%20Combined.csv)


### Questions we hope to answer

1. What state has the highest rate of DUI fatalities?
2. Are DUI fatalities increasing or decreasing? 
3. What states has the highest and lowest frequency of DUI fatalities?
4. Do DUI fatalities account for the majority of vehicle fatalities? 

### Machine learning

The set up is based on creating a machine learning environment that will imitate a model that will perform a statistical algorithms, by inputing data into the machine learning environment to study patterns and make predictions by using mathematical representaion of the input data.

Supervised Learning- bese on labeled data, the data retrieved is clean and prepare for machine learning environment. import of dependencies are placed in the first cell of the machine learning notebook i.e import pandasas pd, from pathlib import pat, import matplotlib.pyplotas plt and from sklearn.linear_model import LinearRegression


We will like to develop a model that predicts trends involving vehicle fatalities across all 50 states. 

### Database

SQL and Postgres will be used to construct the database. The ERD below shows a draft of the database structure. 

![QuickDBD-export(1).png](https://github.com/pperlinski/Final-Project/blob/main/QuickDBD-export%20(1).png)
