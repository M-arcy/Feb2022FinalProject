# Feb2022FinalProject
Predicting Housing Prices - Final Project

In February 2021, Zillow announced a new home-buying arm of its business using artificial intelligence to make purchases of homes to modestly renovate and resell at a profit. The iBuying plan lasted just 9 months before the company announced it was closing down the venture. During the fourth quarter, Zillow lost an average of about $25,000 on every home it sold, before interest expense, the company said. They posted a loss of $528 million last year, laid off a quarter of their workforce, and were stuck trying to move some 7,000 homes after volatile changes in the market knocked the machine learning algorithm off its price-predicting axis.
 The company has announced to shareholders it is targeting revenue of $5 billion by 2025. Will it rejoin the machine learning push to predict future housing prices? What are some things they can have do differently? 

This is a final project for the Entity Academy/Woz U Data Science course. 

Predicting housing prices is critical to be able to purchase houses at scale to renovate and resell. It can be risky involving machine learning predictions in making expensive decisions in a market that changed as quickly as it did last summer when Covid made its appearance. It can be difficult to predict months out with a market that is hard to quantify in terms of what buyers are looking for, and what they're willing to pay. 

1. Kaggle Dataset 
This dataset is available from Kaggle and contains 79 columns (independent variables) that indicate characteristics of the 1,460 houses. It contains one response variable: Sale Price. Housing dataset contains homes sold between 2006-2010 in Ames, Iowa.

The original data can be found at the following link: 

https://www.kaggle.com/marcopale/housing


2. Data Cleaning and Exploratory Data Analysis
    - Mitigated missing values and data types. LotFrontage null values received an average of all frontage values; other columns were dropped. 
    -Summary statistics, graphs and check for normal distribution, if needed.
    - Label encoding. One-hot encoding was not appropriate for this dataset; it increased the dimensionality of the dataset and was computationally expensive. While one-hot encoding would have worked perfectly for the Alley column, creating a binary 0 or 1 column denoting the presence or absence of an alley behind each house, it didn't further my purposes in this application.  

3. Data Analysis in R

4. Data Visualization using Python
    - bar graphs, scatter plots, histogram, correlation plot, heat map
    - save to png for use in slide deck presentation.


5. Splitting into training and testing sets. Assessing K Nearest Neighbors, Random Forest, Stepwise regression.

6. Check performance of the model. 

Presentation
Presented February 21, 2022 via Zoom to students, faculty and prospective employers.

View the project presentation video on VIMEO. Instructor critique begins at 35:17.

https://vimeo.com/680143023
