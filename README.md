# Olist E-Commerce ETL and Data Analysis Project

## Introduction
In the realm of e-commerce and digital marketing, understanding business trends plays a pivotal role in making informed decisions. The Olist E-Commerce ETL and Data Analysis Project is designed to extract, transform, load (ETL) data from various sources, create a comprehensive data warehouse, and perform in-depth data analysis. By leveraging this project, businesses can gain insights into product sales, customer behavior, satisfaction, and more.

## Problem Definition
The project addresses the need to analyze vast amounts of e-commerce data efficiently. Olist, a Brazilian e-commerce platform, serves as the backdrop for this endeavor. The project aims to:
* Analyze trends in product sales and purchasing behavior
* Evaluate customer satisfaction through reviews
* Examine the relationship between sales and regional population
* Gain insights from marketing funnel data

## Project Goals
* Design and implement a robust ETL pipeline for Olist data
* Create a star schema data warehouse for analysis
* Analyze sales trends, customer behavior, and satisfaction
* Study the impact of regional population on sales
* Extract insights from marketing funnel data

## Data Sources
The project utilizes data from three distinct sources:
* Olist Orders: Kaggle Dataset
* Olist Marketing Funnel: Kaggle Dataset
* Brazilian Population Data: Population Data

## Data Description
The project encompasses data related to orders, sellers, products, reviews, and regional demographics. Datasets include customer information, order details, reviews, seller interactions, and regional population data.

## ETL Pipeline and Data Warehouse
* Data Extraction: Data is collected from various sources.
* Data Transformation: Talend is used for ETL operations, ensuring data quality and consistency.
* Data Loading: A star schema data warehouse is created, with a fact table (sales) and dimension tables (customer, orders, payments, reviews, sellers, location, product, leads, and deals).

## Data Analysis
The project provides in-depth data analysis across several dimensions:
* Sales trends analysis
* Customer behavior analysis
* Customer satisfaction analysis through reviews
* Closed deal analysis
* Impact of regional population on sales

## Queries and Insights
OLAP queries are employed to extract insights from the data warehouse:
* Popular payment types
* Best selling products by category and month
* Average review score for products
* Top contributing states to sales
* Sales analysis by seller and year

## Conclusion
The Olist E-Commerce ETL and Data Analysis Project empowers businesses to harness the power of data for strategic decision-making. By performing thorough ETL processes and in-depth analysis, businesses can optimize their operations, enhance customer satisfaction, and drive growth.
