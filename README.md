# Airbnb_BOS
This is a script that process the Boston Airbnb Open Data and predict the listing through machine learning models

## Project: Write a Data Science Blog Post

Since the launch of Airbnb in 2008, it has grow into a platform with more than 4 millions of hosts who have hosted more than 800 millions guests globally. Boston as one of the top travel destinations in the US, it welcomes about 22 millions of visitors around the world annually. Here I'm going to use the “Boston Airbnb Open Data” to take a sneak peak into the Airbnb activity in Boston.

The dataset have 3 parts, 'listings' contains all sorts of information about the listing such as location, property type, cancellation policy etc.; 'calender' inclues info like date, price, vailability, etc. the last one, 'reviews', contains information related to reviews.
    
And I'm trying to answer these 3 questions:

	1. Can we build a model to predict the listing price in Boston using the variables (e.g. location, property type, etc.) in the opensource data?
	2. How does geo-location affects the listing price?
	3. How seasonality affect the price of the Airbnb listings in Boston?

Data Understanding

	Load date into dataframe and explore the data

Prepare Data

    Clean the data by remove/fill na, drop irrelavent data, etc. (see Jupyter note book for details)

Data Modeling

    See Jupter note book for details.
Evaluation

    Key findings:
    1. Linear regression model was built to predict the listing price reasonably well
    2. Geo-location have strong impact on the listing price
    3. The listing price shows strong seasonality with Sep. and Oct. as the most expensity month

### The result is presented in a blog post on Medium and the link to the blog posting can be find here:

https://jcguo.medium.com/what-bostons-airbnb-data-tells-us-776658c76fc8

### Runing the script: 

    1. Download data files and jupyter note to a local directory
    2. 2. Run jupyter notebook with in the local directory

#### Software
    Jupyter notebook
#### Langurage
    Python
#### Libraries
    Numpy, Scikit-learn, Matplotlib, Seaborn
#### Files
    data files: listings.csv, calendar.csv, reviews.csv
    script file: airbnb_bos1

