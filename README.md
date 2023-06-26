

This project is related to Hotel Booking having two hotel descriptions i.e. City Hotel and Resort Hotel. This dataset contains a total of rows of 119390 and 32 columns. In this, we divide data manipulation workflow into three category Data Collection, Data cleaning and manipulation, and EDA(Exploratory Data Analysis). As Further moved i.e Data collection first step is to find different columns which are done by coding Head(), tail(), info(), describe(), columns(), and some other methods used for data collection, some of the names of the columns are updated here i.e hotel,is_canceled,lead_time,arrival_date_year,arrival_date_month,arrival_date_week_number,arrival_date_day_of_month,stays_in_weekend_nights.As we further moved we find unique value of each column and generate a list in tabular form and also check the dataset type of each columns’ find some columns not inaccurate data types which correct it later done in Data cleaning part and as well as duplicates data items must be removed as we find duplicates items equal to 87396 which is dropped from dataset later.

Before visualizing any data from the data set we have to do data wrangling. For that, we have checked the null value of all the columns. After checking, when we get a column with more null values, we drop that column by using the 'drop' method. In this way, we have dropped the 'company' column. When we find the minimal number of null values, fill these null values with necessary values as per requirement by using .fillna()

Different charts are used for data visualization so that better insights and Business objective is attained. 

 

