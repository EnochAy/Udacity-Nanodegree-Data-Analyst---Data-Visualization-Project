<<<<<<< HEAD
=======
# Udacity-Nanodegree-Data-Analyst---Data-Visualization-Project

>>>>>>> 194bb60a4a79b3ba76123033c592a171307647c8
# Communicating Data Findings
# Part I - Prosper Loan Data Exploration and Visualization
## By Ayomide (Enoch) Fadeyi

## Introduction
> Introduce the dataset

## Prosper Loan Data
> Loan Data from Prosper: This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 
Here is the link to the data dictionary to understand the dataset's variables: 
https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

For the purpose of this project, as a result of the large numbers of features in this dataset, 81 in total, 
I will not be able to use all these. I will be focusing on parts of these:

Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), 
EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, 
LoanOriginalAmount, LoanOriginationDate, Recommendations, Investors. 


## Installation
This project uses Python 3 and is designed to be completed through the VS Code using Jupyter Notebooks extension. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks.
The following libraries are expected to be used in this project:

1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn

##  General Research Question guiding my analysis
### What are the main driving factors of outcome of loan?

# Project Motivation
This is the last project in my Data Analyst Udacity Nanodegree program.
I wanted to find out the main driving factors of the outcome of loan using Prosper Loan Data to better understand 
the following:

### Univariate Exploration:
*** Loan status
*** Employment Status
*** Stated Monthly Income
*** Bivariate Exploration:
*** Status and Prosper Rating
*** Credit Start with Listing Category
*** Loan Status and Loan Amount
*** Prosper Rating and Employment Status

### Multivariate Exploration:
*** Rating, Loan Amount and Loan Status
*** Credit category, Credit rating and outcome of Credit
*** Amount, Listing Category Loan and Loan Status Interact



# Project Overview
This project is divided into two parts. This demonstrates the importance and value of data visualization techniques in the data analysis process. In the first part,  I use Python visualization libraries to systematically explore Prosper Loan Data, starting from plots of single variables (Univariates) and building up to plots of two variables (Bivariates), and finally, multiple variables (Multivariates). 
In the second part, I produced a short presentation that illustrates interesting properties, trends, and relationships that I discovered in my analysis. The primary method of conveying is through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.


# Summary of Findings

> ## Conclusions  
> ### Summary
My initial assumptions were strengthened. 

*** Most of the defaulted credits comes from individuals with low Prosper rating

*** The business category tend to have larger amount. This implies that majority of the loans were gotten for business purposes.

*** The employed tend to complete their loans than the unemployed


### What are the main driving factors of outcome of loan?
The main driving factors of outcome of loan from the analysis conducted in the project include the following:
1. Employment
2. Prosper Rating
3. Business Category

### General Steps taken during my data exploration.
1. Question: The first step I took to conduct this project is to pose a general research question. From this one question, several other questions were asked and answered.
2. Analyse: Next, I used different libraries and functions to analyse the data in a bid to proffer answers to the questions posed.
3. Visualize: Then, I moved on to visualizing the data to aid comprehension and understanding of the findings from my analysis.
4. Observation: Lastly, I point out and explain my observations and findings to each of this question.


### More detailed Steps taken during my data exploration.
Step 1.1: Choose your Dataset
Step 1.2: Explore Your Data
Step 2.1: Document your Story
Step 2.2: Create your Slide Deck

NB: I will only include some of the visuals and observations made in part two (explanatory data analysis) 


## Key Insights for Presentation

> *** Those with low prosper rating are found to have highest rates of default in credits. 

  *** The business category tend to have larger amount. This implies that majority of the loans were gotten for business purposes.

  *** The employed tend to complete their loans than the unemployed

  ### Skills
  1. Collaboration with Git and GitHub
  2. Exploratory Data Analysis using Python Packages (Numpy, Pandas, Matplotlib, Seaborn)
  3. Explanatory Data Analysis using Python Packages (Numpy, Pandas, Matplotlib, Seaborn)
  4. Data Visualization using Python Packages (Numpy, Pandas, Matplotlib, Seaborn)
  5. Data Presentation and Communication using Jupyter notebook


## Limitations
1. No Data Dictionary
2. Time constraints


## Further Research
I will like to carry out a further machine learning and predictive analytics based on the interesting relatioinships I discovered in this analysis.


