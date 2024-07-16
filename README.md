# WebScraping

# Largest US Companies by Revenue Analysis

This project scrapes data from Wikipedia, cleans it, performs classification and regression analysis using machine learning models, and evaluates the results. The main goals are to classify companies based on their revenue and number of employees and to predict their revenue.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Overview](#project-overview)
- [Function Overview](#function-overview)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)

Project Overview
Data Scraping
The data is scraped from the Wikipedia page for the largest US companies by revenue.
Data Preprocessing
Cleaning the data: removing unwanted characters, converting data types.
Feature engineering: creating a 'Rating' column based on revenue thresholds.
Classification Analysis
A Decision Tree classifier is used to classify companies into different rating categories based on revenue.
Regression Analysis
A Linear Regression model is used to predict the revenue of a company based on the number of employees.

