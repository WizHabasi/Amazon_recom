# Amazon Product Recommendation System

This project implements a product recommendation system for e-commerce businesses using collaborative filtering techniques. The system is designed in three parts to cater to different business contexts.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Recommendation System Parts](#recommendation-system-parts)
  - [Part I: Popularity-Based](#part-i-product-popularity-based-system)
  - [Part II: Model-Based Collaborative Filtering](#part-ii-model-based-collaborative-filtering)
  - [Part III: Cold Start Problem](#part-iii-cold-start-problem)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

A well-developed recommendation system helps businesses improve shopper experience, leading to better customer acquisition and retention. The system is designed based on the journey of a new customer from their first visit to repeat purchases.

## Dataset

The dataset used is the [Amazon Product Reviews dataset](https://www.kaggle.com/skillsmuggler/amazon-ratings) containing:
- User IDs
- Product IDs
- Ratings
- Timestamps

## Recommendation System Parts

### Part I: Product Popularity-Based System
- Targets new customers
- Recommends most popular products sold on the platform
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
git clone https://github.com/WizHabasi/Amazon_recom.git
