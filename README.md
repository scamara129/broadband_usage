# Broadband Usage Model

Internet accessibility in the United States is greatly important for people to thrive in our society. Many rural communities may not even have internet services available at all, let alone the ability to pay and access those services at high speeds. Broadband allows people to access the internet at much faster speeds than other more outdated methods and is accessible at any time. In this project we will be examining broadband availability and usage by county across the United States, and then predict broadband usage based on county census data using several machine learning techniques. Features used to predict broadband usage include broadband availability, county population, unemployment rate, percent without health insurance, poverty rate, percent receive SNAP, percent without computer, and percent without internet. 

Find the code, descriptions, and analysis in the R-Markdown file.

Find code outputs in the pdf file knit from the R-Markdown file.

### Machine Learning Process
Here is a brief list of all methods used in this project:
- Data Preprocessing
  - Data wrangling and cleaning
  - Splitting training and testing data
  - Impute missing values
  - Center and Scale
- Exploratory Analysis
  - Data Visualizations
- Modeling
  - Simple Linear Regression Model
  - K-Nearest Neighbors Regression
  - Regularized Regression with Elastic Net
  - Principle Component Regression
- Compare Models
  - RMSE values
  - Final Model 

### Data sources

Broadband by county: [https://data.world/amberthomas/broadband-usage-in-us](https://data.world/amberthomas/broadband-usage-in-us)

County census data: [https://www.kaggle.com/datasets/mmattson/us-broadband-availability?resource=download&select=broadband_access.csv](https://www.kaggle.com/datasets/mmattson/us-broadband-availability?resource=download&select=broadband_access.csv)
