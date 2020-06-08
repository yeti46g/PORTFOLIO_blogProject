# Write A Medium Blog Post

 - Skills: Data Visualization (matplotlib, seaborn); EDA; Communicating with Shareholders

### Table of Contents

	1. About
	2. Installation
	3. Business Understanding
	4. Data Understanding
	5. Prepare Data
	6. Data Modeling / Analysis
	7. Evaluate the Results

### 1. About

This project is part of Udacity Data Science Nanodegree for students to start building a data science portfolio. The project includes a blog post (posted on Medium in my case) and a github repo. The steps required are :
	
	(1) Pick a dataset.
	(2) Pose at least three questions relatec to business or real-world applications of how the data could be used.
	(3) Create a jupyter notebook to prepare, analyze, model, and visualize data.
	(4) Communicate your business insights by creating a github repo to share code and data with a technical audience, and by creating a blog post to share insights with a non-technical audience.


Here, I picked a [competition dataset from Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) about house price in Ames, Iowa between 2006-2010. Please see the jupyter notebook in this repo for my analyses and data visualizations. Here is also my [blog on Medium](https://medium.com/@ying.geng5/house-price-analysis-of-ames-iowa-2006-2010-266e307f836f).

### 2. Installation

Libraries need : numpy, pandas, matplotlib, and seaborn.

### 3. Business Understanding

The objective is to quickly abtain an understanding of the real-estate market of Ames, Iowa, and come up with an estimate of budget for buying a home in the town. The following three business questions are formulated to guide the analysis.

	(1) How expensive is this town to live in?
	(2) Which are the popular neighborhoods?
	(3) How much should I budget for if I were to buy a house in Ames that fits my preferences during that time period?

### 4. Data Understanding

The data contains 1460 records of home sales and 81 features for these homes in Ames, Iowa over the period of 2006 -2010.

### 5. Prepare Data

After loading the data, we should handle missing values and encode categorical variables if models are created. However, since I plan to answer the three questions with descriptive statistics, I’ll leave the categorical features as is. Also, since the questions asked probably won’t involve most of the features in the dataset, I’ll decide whether and how to impute missing data in each question section.


### 6. Data Modeling /Analysis

Descriptive statistic and data visualizaiotn techniques are employeed to answer the three business questiona. Please see the notebook for details.

### 7. Evaluate the results
Searching for houses can be overwhelming and time-consuming. By asking insightful questions and looking at the data from a data scientist perspective, a home-buyer can quickly narrow down the search results to save their time!


	
