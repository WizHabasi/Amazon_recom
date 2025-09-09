# Amazon Product Recommendation System

This project implements a product recommendation system for e-commerce businesses using collaborative filtering techniques. The system is designed in three parts to cater to different business contexts..

## Project Overview

A well-developed recommendation system helps businesses improve the shopper experience, leading to better customer acquisition and retention. The system is designed based on the journey of a new customer from their first visit to repeat purchases.

## Dataset

- User IDs
- Product IDs
- Ratings
- Timestamps
## Project Folder Structure
```
.
├── Amazon_Recom.ipynb
├── product_descriptions.csv
└── ratings_Beauty.csv

0 directories, 3 files
```

## Recommendation System Parts

### Part I: Product Popularity-Based System
- Targets new customers
- Recommends the most popular products sold on the platform
- Uses simple counting of product ratings to determine popularity

**Analysis:**
- The analysis shows products arranged in descending order of popularity
- For example, product ID #B001MA0QY2 has over 7000 sales

### Part II: Model-Based Collaborative Filtering
- Recommends items based on purchase history and similarity of ratings
- Uses Singular Value Decomposition (SVD) for dimensionality reduction
- Creates a utility matrix of user-item preferences

### Part III: Cold Start Problem
- Addresses the challenge when a business is setting up its e-commerce website without any product ratings
- (Implementation details would go here)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/WizHabasi/reco.git
