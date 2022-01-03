# online shoppers intention

# ADE
EDA is The main phase of #datasience  to help look at data before making any assumptions. It can help identify obvious errors, as well as better understand patterns within the data, detect outliers or anomalous events, find interesting relations among the variables.

# Our goal

What are the behaviors of online shoppers according to browsing shopping site ?
what is the main features that have a clear impact to increase revenue from the customers ?
Provide recommendations according to our results

# Data set

I obtain the dataset from UCI Machine Learning Repository that collected in 2018-08-31
dataset contain 18 columns and more than 12000 observations , Data size 12379 x 18

# Preprocessing steps 

1-Data cleaning
2-correlation  between features 
3-Analysis outlires 
4-visualization 

# Data Cleaning 

1-Check on missing values 
2-Remove duplicated rows
3-Check on negative value on duration features 
4-Rename element in Month: 
      df["Month"].replace({"June": "Jun"},inplace=True)
5-Remove unnecessary data 
6-Analysis outliers and removed 

# Correlation between features

![image](https://user-images.githubusercontent.com/78117752/147892851-e5b9c94f-94d8-46c5-a310-7797d2a74ecd.png)

# The target column in our data is revenue 

![image](https://user-images.githubusercontent.com/78117752/147892866-43161817-4d6c-4264-998d-7829943caf98.png)

from the figure above we can see the most data in our data set contains non revenue with 82.8%

# Visuilazation- other column

![image](https://user-images.githubusercontent.com/78117752/147892882-935c4577-88d1-48f3-8801-7c6cd7a358cd.png)

as we can see the most customers used operting system and browser number 2 but this feature cant impact on revenue so, we will deleted

![image](https://user-images.githubusercontent.com/78117752/147892990-6da2ed2e-5a58-408d-b044-b834eac72b48.png)

as we can see the most customers adding revenue in weekday more than weekend

![image](https://user-images.githubusercontent.com/78117752/147893034-3ecca4cb-fd7e-46cb-83c9-2a60a9720709.png)

here the customer adding  revenue in May ,Nov ,Mar more than other months

![image](https://user-images.githubusercontent.com/78117752/147893087-ac597763-f42f-4264-b276-61ea06eef29d.png)

# conclousion

The owner should provide Ads in weekdays more than weekend according to our result
The owner should  care about the customers in regions (5,9 and 8)
The owner should give offers to new visitors to attract them and also in  Feb because its corresponding valentine’s day 
The owner should make web site interface and products show  more attractive to increase positive rating on google and increase revenue 
