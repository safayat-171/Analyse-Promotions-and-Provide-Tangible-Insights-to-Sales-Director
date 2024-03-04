# Atliq Mart: Analyse Marketing Promotion and Provide Tangible Insights to Sales Director

## Created By : Safayat Ahmed || Linkedin: http://linkedin.com/in/safayatahmed

## Table of Contents

 - [About Atliq Mart](#about-atliq-mart)
 - [Project Overview](#project-overview)
 - Probelem Statement(#problem-statement)

_   About Atliq Mart
   2. Objective of the project
   3. Probklem Statement
   4. Store Perforamnce Analysis
   5. Promotion Type Analysis
   6. Product and Category Analysis
   7. Recommendation

## About Atliq Mart

Atliq is a retail giant with 50 superstores in the southern region of india. They're currenly running massive promotions during the diwali and sankranti festivals in their stores on their branded products.

## Project Overview


The project is aims to evaluate the festival promotion runned by Atliq Mart and during this time period, it need to analyze various aspects of sales performance around the stores across multiple cities. Through the sales performance matrics, we seek to analyze the performance of stores and get deep into success of two festival promotion, and provide data-driven recommendation to make informed decsions in the next promotions 


## Data Sources

The primary sales summary data used for analyze is 'fact_events_xlxs' file along with dim_campaigns, dim_products, dim_stores files to make relational model.

## Tools

- Execl - Data Cleaning And Ad-Hoc Analysis
- SQL - Data Analysis (MySQL)
- Tableau - Data Visualization

## Ad-hoc Request

### List of products with based price greater than 500 and promo type BOGOF

:cod

SELECT distinct(dim_products.product_name), 
       fact_events.base_price
FROM fact_events
INNER JOIN dim_products
ON fact_events.product_code = dim_products.product_code
where promo_type = 'BOGOF' and base_price > 500

## Store Performance Analysis
## Promotion Type Aanlysis
## Product And Category Analysis
