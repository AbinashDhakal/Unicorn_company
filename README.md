# Unicorn Companies Dataset Analysis
## Introduction
The Unicorn Companies dataset provides information about privately held companies with valuations over $1 billion USD as of November 2021. This dataset includes details about each company's country of origin, industry sector, select investors, and valuation.

## Motivation
As a data scientist working for an investment company, the goal is to analyze the dataset to gain insights into the performance of unicorn companies and determine if it's possible to predict whether a company will reach a valuation of over $5 billion based on its characteristics such as country of origin, industry, and investor details.

## Data Exploration
The analysis begins with exploring the dataset to understand its structure and content. It includes information about industries, companies, and funding rounds. Key steps in the analysis include:

Examining the performance of each industry per country.
Calculating measures of central tendency to understand valuation distribution within industries.
Identifying the top 20 most valued companies.
Analyzing the distribution of valuation across industries.
Investigating the top investors in companies with valuations over $5 billion.
## Findings
Industry Performance Across Countries:
By analyzing the performance of each industry per country, it was observed that the USA and China dominate the top 20 industries by average valuation. These two countries have the highest average valuations across multiple industries.

## Valuation Distribution by Industry:
The analysis of valuation distribution within industries revealed that the artificial intelligence industry has the highest average valuation among unicorn companies. However, this industry's valuation distribution is skewed due to an outlier company. When removing the outlier, the industry's average valuation drops significantly.

## Industry Predictability:
By calculating the probability of a company reaching a valuation over $5 billion for each industry per country, it was found that industries like Fintech in the Bahamas and Data Management & Analytics in Belgium had the highest probabilities.

## Top Investors:
The analysis of top investors in companies with valuations over $5 billion revealed the names of investors associated with each company. This insight can provide valuable information for investment decisions.

## Conclusion
The analysis of the Unicorn Companies dataset provides valuable insights into the performance of unicorn companies and their characteristics. While industry and country play significant roles in company valuations, other factors such as investors also influence a company's success. Predicting whether a company will reach a valuation of over $5 billion is challenging, but certain industries and countries show a higher probability of achieving this milestone. The findings from this analysis can guide investment decisions and strategies for the investment company.
