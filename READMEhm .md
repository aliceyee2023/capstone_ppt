# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Capstone Project-  H&M Personalized Recommender System 

## Introduction

H&M Group is a family of brands and businesses with 53 online markets
and approximately 4,850 stores. Her online store offers shoppers an
extensive selection of products to browse through.

While some customers are good at searching for what they want, others
may prefer not to. Hence, product recommendations become key in
enhancing customer experience.

Simple data, such as garment type and customer age, to text data from
product descriptions, to image data from garment images have been
gathered through the years 2018 to 2021 to study customer transactions.

## Problem Statement

H&M Customers have too many products to browse online. They might not
quickly find what interests them or what they are looking for, and
ultimately, might not make a purchase. To help customers make the right
choices, product recommendations become important.

In this competition, H&M Group invites participants to develop product
recommendations based on data from previous transactions, as well as
from customer and product meta data.

## Datasets

source:<https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/overview>

-   articles.csv : 105542 rows, 25 columns, contains 24 descriptions of
    products in code and name
-   customers.csv : 1371980 rows, 7 columns, contains customers
    information on \'age, postal code, club membership status, fashion
    news frequency\'
-   transactions_train.csv: 31788324 rows, 5 columns, contains
    information on transaction date, customer id, article id , price and
    sales channel

## Data Preprocessing

-   Examine the size of data and null values in data
-   Show how some null values were handled.

## Exploratory Data Analysis (EDA)

-   Share visualizations and insights from the exploratory data
    analysis.
-   Highlight any patterns, correlations, or interesting findings in the
    data.

## Building user-item matrix

-   Selecting features suitable for building user-item matrix
-   forming user-feature dataframe and item-feature dataframe
-   building the user-item matrix

## Challenges

-   Stating some of the difficulties faced while carrying out the
    project

## Conclusion

-   Stating how a Personalized Recommender System can actually help
    online customers improve their online experience and help to improve
    profit for H&M
:::
## References

-  1.	https://www.kaggle.com/code/amangiri/data-snapshot
   2.   https://www.kaggle.com/code/leakotlyar/h-m-personalized-fashion-recommendations
   3.   https://www.kaggle.com/code/multimodel1/content-based-filtering-with-pca