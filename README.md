# ARTI406 Assignment 1 - LEGO Sets EDA

This repository contains the Exploratory Data Analysis (EDA) for Assignment 1 of the ARTI406 course.

## Dataset Description

The dataset used for this project is the **LEGO Sets Dataset**, which contains product information for LEGO sets sold across 21 countries worldwide.

### Dataset Source
The dataset was sourced from Kaggle:
[LEGO Sets Dataset on Kaggle](https://www.kaggle.com/datasets/mterzolo/lego-sets)

### Dataset Dimensions
* **Number of Rows:** 12,261 (raw) / 10,869 (cleaned)
* **Number of Columns:** 14

### Description of Features (Columns)

| Column Name | Data Type | Description |
|---|---|---|
| **set_name** | String | The name of the LEGO set. |
| **prod_id** | String | Unique product identifier for the set. |
| **ages** | String | Recommended age range for the set (e.g., 6-12, 10+). |
| **piece_count** | Integer | Total number of pieces included in the set. |
| **list_price** | Float | Retail price of the set in USD. |
| **num_reviews** | Float | Number of customer reviews submitted for the set. |
| **play_star_rating** | Float | Customer rating for play experience (1–5 stars). |
| **star_rating** | Float | Overall customer star rating (1–5 stars). |
| **val_star_rating** | Float | Customer rating for value for money (1–5 stars). |
| **review_difficulty** | String | Difficulty level as rated by reviewers (e.g., Easy, Average, Challenging). |
| **theme_name** | String | The LEGO theme the set belongs to (e.g., Star Wars, City, DUPLO). |
| **prod_desc** | String | Short product description. |
| **prod_long_desc** | String | Detailed product description. |
| **country** | String | Country code where the set is sold (e.g., US, GB, DE). |

### Purpose of Using This Dataset
The purpose of using this dataset is to perform an Exploratory Data Analysis (EDA) to understand LEGO's product catalog. Specifically, the analysis aims to:
1. Identify the most popular LEGO themes by number of available sets.
2. Understand the price distribution across the product catalog.
3. Explore the relationship between piece count and price.
4. Analyse customer satisfaction through star ratings and review difficulty.
5. Demonstrate data cleaning skills by handling duplicate rows, missing values, and preparing the data for analysis.
