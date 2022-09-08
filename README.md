# Bertelsmann/Arvato Segmentation Project

## Link for the story with Medium 
The following is the link for the story being published with Medium. 

https://medium.com/@fgarcia2/capstone-project-create-a-customer-segmentation-report-for-arvato-financial-services-423f1e54fa92

## Context 
In this project, demographics data for customers of a mail-order sales company in Germany is analyzed, comparing it against demographics information for the general population.

## Content 
There are four data files associated with this project:

Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. 
The datatypes are mainly numerical, but there are 6 columns containing object datatypes. Additionally, both rows and columns appear to have a fair number of NaNs, which will have to be dealt with in the data preparation section. 
Finally, a couple of Excel files were provided that contain further information about the encoding of the data in the columns and what each category represents.

## Installation 
This project requires Python 3.x and the following Python libraries installed:

NumPy Pandas matplotlib seaborn sklearn

Python Jupyter notebook has been used and is recommended for coding.

## Project Motivation 
From a business perspective, these were the primary objectives of this project 

Customer segmentation; i.e., identifying the parts of the population that best describe the core customer base of the company.
Marketing campaign targets, i.e., use a model to predict which individuals are most likely to convert into becoming customers for the company.

## File descriptions 

Jupyter Notebook (Arvato Project Workbook.ipynb). Also supported by AZdias, customers and DIAS Attribute Values 2017 data files. 

## Results 

Overall, the project concludes that there are differences between the clusters that represent the general population of Germany and those in the company customers group. This becomes an important indicator to determine which features to look for to select potential customers for this company. 

Another main result was that utilizing the training data it was possible to train a model to perform classification, and predict which individuals were most likely to become customers for the company. The model provided good results.  


