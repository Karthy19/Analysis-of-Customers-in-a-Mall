# Analysis-of-Customers-in-a-Mall


This project aims to analyze customer data from a mall and extract insights to improve customer satisfaction and sales.
This project also helps the owners to segment their customers based on spending score and income.

## Requirements
Python 3.x
Pandas
Numpy
Matplotlib
Seaborn
Sklearn

## Data
The data for this project is a sample of customer information from a mall, including customer demographics and purchasing data. The data is in a CSV file called "customer_data.csv" and includes the following columns:

&#9658; CustomerID: unique ID for each customer

&#9658; Gender: gender of the customer (male/female)

&#9658; Age: age of the customer

&#9658; Annual Income (k$): annual income of the customer

&#9658; Spending Score (1-100): score assigned to the customer based on their spending habits

## KMeans Clustering
In this project, the KMeans Clustering algorithm is used to group customers based on their shopping behavior and demographics.

- First we have collected and preprocessed the data, which could include information such as the customers' age, income, gender, and purchase history.

- Once the data is prepared, the k-means algorithm is applied to group the customers into different segments. 
The number of segments, or clusters, is defined by the elbow method and is represented by the variable k.

- After the clustering is complete, each segment is analyzed to understand the characteristics of the customers in that group. 

This information is then  used by the mall's marketing team to tailor their strategies to the specific needs and preferences of each segment. For example, the mall may offer promotions or discounts to customers in a specific segment, or design their layout to cater to a particular group of customers.

## Usage

Install the required packages 
Run the Jupyter notebook: Mall_Customer_Analysis.ipynb
Follow the instructions in the notebook to analyze the customer data and extract insights.
