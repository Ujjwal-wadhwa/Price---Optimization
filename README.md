# Price---Optimization

## Overview

Setting the right price for avocados as a supplier is a delicate balancing act. Price them too high, and you risk losing customers. Price them too low, and you might not make a profit. With the power of optimization and data science, this project tackles the challenge of avocado pricing and supply.

## Goal

The main objective of this project is to develop a data science pipeline for pricing and distribution of avocados, ultimately maximizing revenue. We aim to strike the perfect balance between setting the optimal price and ensuring a consistent supply of avocados, all while factoring in costs related to wastage and transportation.

## Project Stages

This project is divided into three main stages:

1. **Understanding the Dataset:** In this initial phase, we dive into the dataset to gain insights and infer relationships between various categories, such as sales, price, region, and seasonal trends.

2. **Building a Prediction Model:** Next, we construct a prediction model that forecasts avocado demand based on variables like price, region, year, and seasonality. This step is crucial for making informed pricing decisions.

3. **Optimization:** The final stage involves designing a mathematical optimization model. This model helps us determine the optimal price and supply quantity to maximize net revenue while considering expenses related to wastage and transportation.

## Price Optimization: Parts 1 and 2

This project comprises two parts, each focusing on avocado price optimization:

**Part 1:** In this section, we provide a detailed problem description. The goal is to find the price that maximizes revenue for selling avocados using a quadratic program. We model the relationship between price and demand using linear regression.

**Part 2:** Leveraging Gurobi's open-source package Gurobi Machine Learning, we fit the relationship between price and demand using a Scikit Learn object. This allows us to directly add a constraint to an optimization model, streamlining the price optimization process.

## Repository

You can download the entire repository, by [repository_link](https://github.com/Ujjwal-wadhwa/Price---Optimization/archive/refs/heads/main.zip).

Feel free to explore, contribute, and use this project as a valuable resource for understanding the power of optimization and data science in pricing and supply chain management.
