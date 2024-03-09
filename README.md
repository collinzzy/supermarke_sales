# supermarke_sales
Dataset contains supermarket sales and analysis.
Hello Everyone,

Here is My EDA Project based on Super Market Sales Analysis where I analyzed the Data by using Matplotlib and Seaborn.

Dataset
I used Super Market Sales Dataset from Kaggle recorded for 3 Different Cities for 3 Months.

Link to the Dataset : Super Market Sales Dataset

Problem Statement
The objective of this project is to analyze sales data to gain insights into customer purchasing behavior, product performance, and overall trends, of the supermarket business.
Steps involved in the Project
Reading the Data

First I installed all the necessary libraries required for this Project.

Then I imported the Data by reading csv file using read.csv() Method.

Then I dropped the Invoice ID Column because we don't need it in analysis.

After that I listed down all the columns in the Dataset by df.columns Method.

Then I used df.shape Method to look for the rows and columns in the Data.

Then I look for the Info of the Dataset by using df.info() Method.

Cleaning the Data

First I start by describing the Data by using df.describe() Method.

Then I converted Date Column to Pandas Date and Time DataType.

And After that I extracted Year, Month, Day from the Date.

Then I listed down all the unique values of categorical columns.

And Finally I verified the null values in the Dataset by using df.isna().sum()
