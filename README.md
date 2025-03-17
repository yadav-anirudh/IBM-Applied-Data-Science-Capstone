# Final Graded Assignment for "Applied Data Science Capstone" Course

This is a Github repository for submitting the assignment of the course: Applied Data Science Capstone.  

## Project Background
SpaceX has transformed the commercial space industry by offering Falcon 9 rocket launches at $62 million, significantly lower than competitors' $165 million launches. This cost reduction is due to their innovative reuse of the first stage, which can be landed and reused to further lower costs. As a data scientist at a startup competing with SpaceX, this project aims to build a machine learning pipeline using publicly available data to predict the success of the first stage landing. By forecasting landing outcomes, we can estimate launch costs and determine competitive pricing strategies.

## Questions to be answered 
1. How do variables such as payload mass, launch site, number of flights, and orbits influence the likelihood of a successful landing?
2. Which model provides the most reliable results for estimating the likelihood of a successful landing based on the given dataset?

## Methodology
  ### 1. Data collection methodology
  - Data was collected in 2 ways: SpaceX API and Web Scraping

  ### 2. Performed data wrangling
  - Handling missing values
  -Applying One-Hot Encoding to preprocess the categorical data for binary classification

  ### 3. Performed exploratory data analysis (EDA) using visualization and SQL
  ### 4. Performed interactive visual analytics using Folium and Plotly Dash
  ### 5. Performed predictive analysis using classification models
  - Data was split into training and test sets
  - Multiple models were built, trained on training data and evaluated on test data

